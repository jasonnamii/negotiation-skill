# negotiation-skill

> 🇰🇷 [한국어 README](./README.ko.md)

**A 5-layer negotiation analysis engine covering interests, structure, psychology, relationships, and execution — integrating Fisher & Ury, Chris Voss, game theory, and cross-cultural frameworks into a single structured protocol.**

## Prerequisites

- **Claude Cowork or Claude Code** environment

## Goal

Negotiation outcomes are 80% determined by preparation quality. This skill structures that preparation through a 5-layer analysis architecture: from interest mapping (Fisher & Ury) through structural analysis (BATNA/ZOPA/3-D setup), psychological profiling (anchoring, reactive devaluation, loss aversion), relationship dynamics (cultural dimensions, shadow negotiation), to execution design (contingent contracts, logrolling, post-settlement settlement).

## When & How to Use

Triggers when you mention negotiation, BATNA, term sheets, or deal preparation. Three modes: **Design** (pre-negotiation strategy), **Breakthrough** (deadlock resolution), and **Debrief** (post-negotiation analysis). Say "이번 텀시트 협상 어떻게 준비하지" or "협상이 막혔어".

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Term sheet negotiation prep | `"이번 텀시트 협상 준비해줘"` | 5-layer screening → BATNA/ZOPA mapping → psychological profile of counterpart → 3-scenario simulation → action plan |
| Deadlock resolution | `"협상이 막혔어"` | Deadlock diagnosis matrix (5 layers × 5 patterns) → precise root cause identification → targeted breakthrough tactic |
| Partnership deal design | `"파트너십 조건 조율 전략 짜줘"` | Interest mapping → logrolling opportunities → cultural dimension check → process design (single-text, contingent contracts) |

## Key Features

- **5-Layer Analysis Architecture** — L1 Interest (Fisher&Ury) → L2 Structure (BATNA/ZOPA/3-D) → L3 Psychology (anchoring, reactive devaluation, endowment) → L4 Relationship (culture, power, shadow) → L5 Execution (process design, contingent contracts)
- **Psychological Profile Screening** — Identifies dominant mechanism in counterpart: anchoring susceptibility, reactive devaluation, loss aversion, fairness norm sensitivity
- **Game Theory Lens** — Mandatory check: repeated game?, information asymmetry?, commitment device opportunity?
- **Deadlock Diagnosis Matrix** — 5 layers × 5 patterns = 25-cell precise diagnosis for breakthrough
- **Cross-Cultural Negotiation** — Hofstede 6 dimensions + Erin Meyer Culture Map 8 scales
- **Hub+Spoke Architecture** — Lean hub with 6 deep reference files

## Works With

- **[person-profiler](https://github.com/jasonnamii/person-profiler)** — Counterpart profiling feeds into L1 interest and L4 relationship layers
- **[human-skill](https://github.com/jasonnamii/human-skill)** — Behavioral psychology mechanisms for L3 psychology layer
- **[startup-investment](https://github.com/jasonnamii/startup-investment)** — Term sheet structure and valuation for investment negotiations
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — Strategic context for interest framing

## Installation

```bash
git clone https://github.com/jasonnamii/negotiation-skill.git ~/.claude/skills/negotiation-skill
```

## Update

```bash
cd ~/.claude/skills/negotiation-skill && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
