# Skincare PM Skills 🧴

护肤品/美妆产品经理的 AI 技能市场。对标 [phuryn/pm-skills](https://github.com/phuryn/pm-skills) 的结构，内容完全重写为**中国市场护肤品 PM** 的真实工作流：消费者洞察 → 产品开发 → 法规合规 → 上市渠道 → 增长数据 → 品牌战略。

> 通用 AI 给你文字，这套技能给你**行业结构**：每个技能都内置了护肤品行业的判断标准、模板和踩坑清单。

📖 **第一次用？先看 [零基础上手指南](使用指南.md)** ——概念、安装、怎么输入、真实例子，5 分钟上手。

## 六大插件（28 技能 · 10 命令）

| 插件 | 技能 | 命令 |
|---|---|---|
| **spm-insight** 消费者洞察 | 肤质用户画像 · 消费者访谈 · 社媒聆听 · 概念测试 · 护肤场景 JTBD | `/persona` `/interview-guide` |
| **spm-development** 产品开发 | 产品概念书 · 成分卖点转化 · 打样评审 · 包材 brief · COGS 成本测算 · 肤感感官评估 | `/product-brief` `/ingredient-story` |
| **spm-regulatory** 法规合规 | 备案/注册速查 · 功效宣称合规 · 标签审核 · 功效测试规划 | `/claim-check` `/label-review` |
| **spm-gtm** 上市与渠道 | 上市计划 · 定价与价盘 · 渠道策略 · 达人投放 brief · 大促规划 | `/launch-plan` `/kol-brief` |
| **spm-growth** 增长与数据 | 电商漏斗分析 · 复购分析 · 评论挖掘 · 素材 A/B 测试 | `/review-analysis` |
| **spm-strategy** 品牌战略 | 品牌定位 · 产品线规划 · 竞品拆解 · 市场规模测算 | `/competitor-teardown` |

## 安装

### Claude Code（本地路径安装）

```bash
claude plugin marketplace add "D:/Program Files/skincare-pm-skills"
```

然后按需安装插件：

```bash
claude plugin install spm-development@skincare-pm-skills
```

（把 `spm-development` 换成上表中任意插件名；全装也可以。）

### 推送到 GitHub 后

```bash
claude plugin marketplace add <你的用户名>/skincare-pm-skills
```

## 典型工作流串联

- **新品从 0 到 1**：`/persona` → jtbd-beauty → `/product-brief` → formula-review → `/claim-check` → `/launch-plan`
- **卖点开发**：social-listening（找原声）→ `/ingredient-story`（转化卖点）→ `/claim-check`（合规过滤）→ content-ab-test（投放验证）
- **上市后运营**：ecommerce-funnel（诊断转化）→ `/review-analysis`（口碑体检）→ repurchase-analysis（复购健康度）

## 重要声明

- **法规内容仅供 PM 做项目规划参考**。备案、宣称、标签的正式决策请以国家药监局（NMPA）现行法规、地方局执行口径和贵司法规/法务岗审核为准。
- 涉及成本区间、周期、行业比率的数字为行业常见量级参考，用于沙盘推演，实际以供应商报价与实测为准。

## 设计理念

参考了消费品行业的经典方法论（JTBD、Cohort 分析、感官评价体系）并结合中国美妆电商生态（小红书/抖音种草、天猫承接、大促节奏、备案制度）落地。每个技能遵循统一结构：**何时使用 → 框架/步骤 → 输出模板 → 注意事项（踩坑清单）**。

MIT License
