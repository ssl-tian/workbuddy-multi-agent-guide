# WorkBuddy 多 Agent 协同实操指南

> **零代码、零基础、零 API Key** — 精神科医生教你用自然语言搭建多 Agent 协同系统

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 这是什么

一个面向**完全零编程基础**用户的多 Agent 协同系统搭建指南。作者是广州医科大学附属脑科医院的精神科医生，用自然语言（不需要写一行代码）在 WorkBuddy 平台上搭建了一个 4-Agent 审稿协同系统。

## 快速开始

1. 打开 [WorkBuddy](https://www.codebuddy.cn)
2. 阅读 [`multi-agent-guide-for-beginners.md`](./multi-agent-guide-for-beginners.md)（六步上手）
3. 复制 `reviewer_prompts.yaml` 模板，改成你的领域
4. 复制 `pipeline_state.yaml` 模板，填入你的项目信息
5. 在 WorkBuddy 里说：**「帮我创建一个 Team」**

## 仓库内容

```
workbuddy-multi-agent-guide/
├── README.md                           # 你在看
├── multi-agent-guide-for-beginners.md  # 六步实操指南（主体）
├── reviewer_prompts.yaml               # 审稿人 Prompt 模板
├── pipeline_state.yaml                 # 项目状态管理模板
└── examples/                           # 案例（建设中）
    └── aud-mdd-review/                 # AUD-MDD 共病研究案例
└── psychiatry-daily-automation/   # 精神科规培每日自动化
```

## 案例

- 📚 精神科规培每日自动化 — 真实运行的 20 天 prompt 案例 → [](./examples/psychiatry-daily-automation/)

## 适用场景

即使你的领域不是医学研究，这套方法论也适用：

- 📝 内容创作：写手 + 编辑 + 合规审查
- 📊 数据分析：数据工程师 + 分析师 + 可视化
- 🎓 学术写作：方案设计 + 撰写 + 审校 + 投稿
- 💼 商业决策：市场分析 + 竞品分析 + 风险评估

## 作者

**Song (@ssl-tian)** — 精神科住院医。用 WorkBuddy 从零搭建了多 Agent 审稿流水线。

## 许可

MIT License — 随便用、随便改、随便分发。
