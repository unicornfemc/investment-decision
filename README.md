# Investment Decision Skill / 投资决策分析 Skill

[English](#english) | [中文](#中文)

---

## English

> Structured investment analysis framework for making better investment decisions.

### Overview

Investment Decision Skill provides a systematic framework for analyzing investment opportunities. It enforces a **six-section analysis template** that ensures every investment decision is well-documented and reproducible.

### Why This Skill?

Investment decisions are often made impulsively or based on incomplete analysis. This skill addresses common pitfalls:

- ❌ Buying without checking the balance sheet
- ❌ Chasing momentum, emotional trading
- ❌ Forgetting why you bought, unable to review
- ❌ Over-concentrating in single positions
- ❌ Relying on a single valuation metric (PE only)
- ❌ Ignoring red flags in financial statements

### Six Essential Sections / 六大必填节

| # | Section | Description |
|---|---------|-------------|
| 1 | **业务理解 / Business Understanding** | What does the company do? How does it make money? |
| 2 | **护城河 / Moat** | Why can it sustain profits? What's the competitive advantage? |
| 3 | **财务健康 / Financial Health** | Is the balance sheet healthy? |
| 4 | **估值判断 / Valuation** | Is it expensive or cheap now? |
| 5 | **风险评估 / Risk Assessment** | What are the fatal risks? |
| 6 | **交易计划 / Trading Plan** | How much to buy? When to sell? |

### Quick Start

```
分析贵州茅台 / Analyze Moutai (600519)
```

The skill will output a complete analysis report following the six-section template.

### Installation / 安装

```bash
# Clone the repository
git clone https://github.com/unicornfemc/investment-decision.git
cd investment-decision
```

### File Structure

```
investment-decision/
├── SKILL.md              # Main skill definition
├── references/          # Reference materials
│   └── reference.md    # Detailed methodology
└── test-prompts.json   # Test cases
```

### Trigger Words / 触发词

- 分析 / analysis
- 股票分析 / stock analysis
- 投资分析 / investment analysis
- 估值 / valuation
- 值得买吗 / worth buying?
- 复盘 / review

---

## 中文

> 结构化的投资分析框架，帮助做出更好的投资决策。

### 概述

投资决策分析 Skill 提供了一套系统化的投资机会分析框架。它强制使用**六大必填节分析模板**，确保每一次投资决策都有完整的文档记录并且可复盘。

### 为什么需要这个 Skill？

投资决策常常是冲动做出的，或者基于不完整的分析。这个 Skill 解决了常见的陷阱：

- ❌ 没看负债表就买入
- ❌ 追涨杀跌，情绪化决策
- ❌ 忘记当时为什么买，无法复盘
- ❌ 重仓单押，无仓位管理
- ❌ 依赖单一估值指标（只用 PE）
- ❌ 忽视财报中的异常信号

### 核心功能

1. **六大必填节** - 每次分析必须包含业务理解、护城河、财务健康、估值判断、风险评估、交易计划
2. **数据驱动** - 调用东方财富MxData API获取实时财务数据
3. **风险量化** - 概率×影响矩阵评估风险
4. **交易计划** - 明确的买入区间、仓位配置、止盈止损条件

### 使用示例

```
分析贵州茅台 / Analyze Moutai (600519)
```

Skill 将输出完整的六大必填节分析报告。

### 数据来源

- 东方财富MxData API（实时行情+财务数据）
-references/reference.md（估值方法论、财务指标解读）

### License

MIT License

---

*Created with 女娲·Skill造人术 / Built with Nuwa Skill Creator*