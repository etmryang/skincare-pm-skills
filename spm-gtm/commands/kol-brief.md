---
description: 生成达人投放 brief 与选号建议（基于 kol-brief 技能）
argument-hint: [产品+投放目标，如"新品精华上市期，预算 30 万，小红书为主"]
---

使用 kol-brief 技能处理：$ARGUMENTS

要求：
1. 按预算与目标给出层级组合建议（素人/尾部/腰部/头部配比及理由）
2. 输出一页内容 brief（必讲点 ≤3、自由度声明、必带项）
3. 生成禁语清单：调用 claim-compliance 的红线规则，结合该产品宣称生成具体禁句
4. 附选号硬指标 checklist 与效果评估口径（分层 KPI，直播用结算 GMV）
