# negotiation-skill

> 🇺🇸 [English README](./README.md)

**5층 분석 아키텍처 기반 협상 설계·시뮬·복기 엔진. Fisher&Ury, Chris Voss, 게임이론, 문화 프레임워크를 단일 구조적 프로토콜로 통합.**

## 사전 요구

- **Claude Cowork 또는 Claude Code** 환경

## 목표

협상 결과의 80%는 준비의 질이 결정한다. 이 스킬은 5층 분석 아키텍처로 그 준비를 구조화한다: 이해관계 매핑(Fisher&Ury) → 구조 분석(BATNA/ZOPA/3-D Setup) → 심리 프로파일링(앵커링, 반응적 평가절하, 손실회피) → 관계 역학(문화 차원, Shadow Negotiation) → 실행 설계(조건부 계약, 로그롤링, PSS).

## 사용 시점 & 방법

협상, BATNA, 텀시트, 딜 준비 언급 시 자동 발동. 3모드: **설계**(사전 전략), **돌파**(교착 해소), **복기**(사후 분석). "이번 텀시트 협상 어떻게 준비하지", "협상이 막혔어" 등으로 호출.

## 사용 사례

| 상황 | 프롬프트 | 동작 |
|---|---|---|
| 텀시트 협상 준비 | `"이번 텀시트 협상 준비해줘"` | 5층 스크리닝 → BATNA/ZOPA 매핑 → 상대방 심리 프로파일 → 3시나리오 시뮬레이션 → 액션 플랜 |
| 교착 상태 돌파 | `"협상이 막혔어"` | 교착 진단 매트릭스(5층×5패턴) → 정확한 근본 원인 식별 → 타겟 돌파 전술 |
| 파트너십 조건 설계 | `"파트너십 조건 조율 전략 짜줘"` | 이해관계 매핑 → 로그롤링 기회 → 문화 차원 점검 → 프로세스 설계 |

## 주요 기능

- **5층 분석 아키텍처** — L1 이해관계(Fisher&Ury) → L2 구조(BATNA/ZOPA/3-D) → L3 심리(앵커링, 반응적 평가절하, 보유효과) → L4 관계(문화, 권력, Shadow) → L5 실행(프로세스 설계, 조건부 계약)
- **심리 프로파일 스크리닝** — 상대방 지배적 메커니즘 식별: 앵커링 취약성, 반응적 평가절하, 손실회피, 공정성 규범 민감도
- **게임이론 렌즈** — 필수 체크: 반복 게임?, 정보 비대칭?, commitment device 기회?
- **교착 진단 매트릭스** — 5층×5패턴 = 25셀 정밀 진단으로 돌파 포인트 특정
- **문화 협상** — Hofstede 6차원 + Erin Meyer Culture Map 8척도
- **허브+스포크 아키텍처** — 경량 허브 + 6개 전문지식 reference 파일

## 연동 스킬

- **[person-profiler](https://github.com/jasonnamii/person-profiler)** — 상대방 프로파일링 → L1 이해관계·L4 관계 입력
- **[human-skill](https://github.com/jasonnamii/human-skill)** — 행동심리 메커니즘 → L3 심리 층 강화
- **[startup-investment](https://github.com/jasonnamii/startup-investment)** — 텀시트 구조·밸류에이션 → 투자 협상
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — 전략적 맥락 → 이해관계 프레이밍

## 설치

```bash
git clone https://github.com/jasonnamii/negotiation-skill.git ~/.claude/skills/negotiation-skill
```

## 업데이트

```bash
cd ~/.claude/skills/negotiation-skill && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용 가능합니다.

## Cowork Skills

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT License — 자유롭게 사용, 수정, 공유 가능합니다.
