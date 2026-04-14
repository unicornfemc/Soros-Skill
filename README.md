# Soros-Skill

A collection of AI skills built on George Soros's investment framework.

Activates George Soros's complete investment thinking system — reflexivity theory, boom-bust cycle analysis, super-cycle trading, and macro speculation strategies.

## Trigger

Automatically activates when you:

- Analyze macro trends, market turning points, or geopolitical events
- Evaluate credit cycles, currency pegs, or泡沫/崩盘 timing
- Discuss reflexivity, reflexivity theory, or boom-bust dynamics
- Analyze market narrative vs reality divergences
- Discuss directional macro trades or trend termination
- Even if you don't mention "Soros," proactively trigger when the topic involves consensus vs. reality analysis or narrative-driven market moves

## Quick Start

Clone this repo and copy the `skills/soros` folder into your project:

```bash
git clone https://github.com/unicornfemc/Soros-Skill.git /tmp/soros-skill
cp -r /tmp/soros-skill/skills/soros your-project/.claude/skills/soros
```

The skill must be placed at `.claude/skills/soros/SKILL.md` relative to your project root:

```
your-project/
└── .claude/
    └── skills/
        └── soros/ ← this folder
            ├── SKILL.md
            └── references/
                ├── 01-reflexivity-theory.md
                ├── 02-decision-framework.md
                ├── 03-super-cycle-analysis.md
                ├── 04-credit-bubble-dynamics.md
                ├── 05-currency-fixed-income.md
                ├── 06-historical-cases.md
                ├── 07-bias-equilibrium.md
                └── 08-risk-management.md
```

Claude Code auto-discovers skills placed under `.claude/skills/<name>/SKILL.md` — no registration required.

## Reference Files

| File | Content |
|------|---------|
| `01-reflexivity-theory.md` | Core reflexivity theory, cognitive vs participation function, feedback loops |
| `02-decision-framework.md` | 5-step decision framework, BISES test, thesis confirmation |
| `03-super-cycle-analysis.md` | Super-cycle identification, trend termination, late-cycle dynamics |
| `04-credit-bubble-dynamics.md` | Credit cycles, leverage dynamics, deleveraging triggers |
| `05-currency-fixed-income.md` | Currency peg mechanics, ERM dynamics, fixed income arbitrage |
| `06-historical-cases.md` | 1992 ERM crisis, 1987 crash, dot-com bubble, Asian financial crisis |
| `07-bias-equilibrium.md` | Bias types, open society investing, fallibility of knowledge |
| `08-risk-management.md` | Position sizing, stop-loss discipline, drawdown management |

## Core Framework

### Reflexivity Theory

Unlike efficient market hypothesis, Soros argues that **market prices do NOT reflect reality — they actively shape reality**. This creates reflexive feedback loops that can amplify trends far beyond fundamental justifications.

### Key Concepts

- **Cognitive Function**: Expectations affect fundamentals
- **Participation Function**: Fundamentals affect prices
- **BISES Test**: Balance of payments, Inflation, State of economy, Exit mechanism
- **Super-Cycle**: Multi-year trends where reflexivity sustains

### Decision Framework

1. Identify prevailing bias
2. Locate reflexive feedback loop
3. Apply BISES test
4. Identify super-cycle
5. Size position & define exit strategy

## Output Format

All analysis follows a structured template:

- **Conclusion**: Long/Short/Out/Await Confirmation + rationale
- **Reflexivity Assessment**: Bias, falsehood level, feedback loop, reflexivity level
- **BISES Test Results**: Balance of payments, inflation, economy state, exit mechanism
- **Super-Cycle Assessment**: Phase, duration, breaking point
- **Key Assumptions**: 3-5 core assumptions
- **Position Architecture**: Entry, size, stop-loss, exit trigger
- **Risk Scenarios**: Early wrong, late wrong, max loss
- **Soros Parallel**: Historical analogous trade
- **Monitoring Indicators**: Daily checks, termination signals

---

*This skill was created using [女娲·Skill造人术](https://github.com/alchaincyf/nuwa-skill).*