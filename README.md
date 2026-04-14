# Soros-Skill | 索罗斯思维Skill

[English](#english) · [中文](#中文)

---

## English

A collection of AI skills built on George Soros's investment framework.

Activates George Soros's complete investment thinking system — reflexivity theory, boom-bust cycle analysis, super-cycle trading, and macro speculation strategies.

## Trigger

Automatically activates when you:

- Analyze macro trends, market turning points, or geopolitical events
- Evaluate credit cycles, currency pegs, or 泡沫/崩盘 timing
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

## 中文

基于乔治·索罗斯投资框架构建的 AI Skill 集合。

全面激活索罗斯的投资思维体系——反身性理论、繁荣-萧条周期分析、超周期交易策略及宏观投机框架。

## 触发条件

以下场景会自动激活：

- 分析宏观趋势、市场拐点或地缘政治事件
- 评估信用周期、货币挂钩或泡沫/崩盘时机
- 讨论反身性、反身性理论或繁荣-萧条动态
- 分析市场叙事与现实的偏离
- 讨论方向性宏观交易或趋势终结
- 即使未提及"索罗斯"，当话题涉及共识vs现实分析或叙事驱动市场走势时也会主动触发

## 快速开始

克隆仓库并复制 `skills/soros` 文件夹到你的项目：

```bash
git clone https://github.com/unicornfemc/Soros-Skill.git /tmp/soros-skill
cp -r /tmp/soros-skill/skills/soros your-project/.claude/skills/soros
```

Skill 必须放在项目根目录的 `.claude/skills/soros/SKILL.md`：

```
your-project/
└── .claude/
    └── skills/
        └── soros/ ← 此文件夹
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

Claude Code 会自动发现 `.claude/skills/<name>/SKILL.md` 路径下的 skills，无需注册。

## 参考文件

| 文件 | 内容 |
|------|------|
| `01-reflexivity-theory.md` | 核心反身性理论、认知功能vs参与功能、反馈循环 |
| `02-decision-framework.md` | 五步决策框架、BISES测试、论点确认 |
| `03-super-cycle-analysis.md` | 超周期识别、趋势终结、晚期周期动态 |
| `04-credit-bubble-dynamics.md` | 信用周期、杠杆动态、去杠杆触发因素 |
| `05-currency-fixed-income.md` | 货币挂钩机制、ERM机制、固定收益套利 |
| `06-historical-cases.md` | 1992年ERM危机、1987年崩盘、互联网泡沫、亚洲金融危机 |
| `07-bias-equilibrium.md` | 偏见类型、开放社会投资、知识的易错性 |
| `08-risk-management.md` | 仓位规模、止损纪律、回撤管理 |

## 核心框架

### 反身性理论

与有效市场假说不同，索罗斯认为**市场价格并不反映现实——它们积极塑造现实**。这创造了反身性反馈循环，可以将趋势放大到远超基本面合理性的程度。

### 关键概念

- **认知功能**：预期影响基本面
- **参与功能**：基本面影响价格
- **BISES测试**：国际收支、通胀、经济状态、退出机制
- **超周期**：反身性能够持续多年的趋势

### 决策框架

1. 识别主导偏见
2. 定位反身性反馈循环
3. 应用 BISES 测试
4. 识别超周期
5. 确定仓位规模并制定退出策略

## 输出格式

所有分析遵循结构化模板：

- **结论**：做多/做空/离场/等待确认 + 理由
- **反身性评估**：偏见、错误程度、反馈循环、反身性水平
- **BISES测试结果**：国际收支、通胀、经济状态、退出机制
- **超周期评估**：阶段、持续时间、崩溃点
- **关键假设**：3-5个核心假设
- **仓位架构**：入场、规模、止损、退出触发器
- **风险情景**：早期错误、晚期错误、最大损失
- **索罗斯类比**：历史类似交易
- **监控指标**：每日检查、终结信号

---

*此 Skill 由 [女娲·Skill造人术](https://github.com/alchaincyf/nuwa-skill) 创建。*