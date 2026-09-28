---
name: service-to-productization-ladder
description: |
  把已经有人付费的人工或半自动服务，按交付记录逐步沉淀成模板、Skill、虚拟产品或 Agent。适用于“服务如何产品化”“该不该做 SaaS”；不用于尚未验证需求的点子。Triggers: productize service, 服务产品化, 虚拟产品, SaaS, Agent。
metadata:
  source: "24 条 Bilibili AI 搞钱视频证据包：视频 12、15、16、21"
  tags: "service, productization, workflow"
---
# 先服务后产品的产品化阶梯

## R — 原文（Reading）
> 虚拟产品应来自已经熟悉、可重复交付的服务，而不是先批量做泛提示词包。
>
> — 视频 16 验证摘要，BV1PouX67Esu

## I — 方法论骨架（Interpretation）
产品不是凭空设计出来的功能集合，而是重复服务中稳定下来的部分。先手工或半自动交付明确结果，逐单记录输入、步骤、失败、验收与修改；再把重复且风险低的部分封装成检查表、模板或 Skill；当输入输出稳定且自助使用可成功时，才做数字商品；只有需要持续状态、权限、审批和恢复时，才升级为 Agent 或软件。每一阶都必须保留人工兜底，并由真实交付证明值得进入下一阶。

## A1 — 资料中的应用（Past Application）
- **知识视频 Skill**：先拆研究、来源筛选、写作和人工修改步骤，再固化为可重复流程。
- **海外接单与虚拟产品**：先靠服务获得订单和反馈，再把高频交付做成可重复销售资产；自动接单市场被放到最后。

## A2 — 触发场景（Future Trigger）
1. 用户已有重复服务，返工多，想做模板或 Skill。
2. 用户考虑把接单业务升级成数字商品、SaaS 或 Agent。
3. 用户问哪些步骤该自动化、哪些应保留人工。

语言信号："怎么产品化"、"把服务做成 Skill"、"要不要做 SaaS"、"productize my service"、"turn workflow into product"。

与相邻 Skill 的区分：本 Skill 决定产品化顺序；`delivery-feedback-data-loop` 规定要积累什么交付数据；`agent-delivery-scope` 判断最终是否需要完整 Agent。

## E — 可执行步骤（Execution）
1. **画出现状**：收集至少一批真实交付，列输入、动作、判断、输出、验收、返工和人工审批。
   - 完成标准：能区分固定步骤与每单变化步骤。
2. **封装稳定残余**：先做内部清单/模板，再做可复用 Skill；仅封装重复、可验收、低风险部分。
   - 完成标准：另一名执行者能用它完成同等质量的样例交付。
3. **逐阶升级**：有重复购买和低返工后做数字商品；有持续状态与系统责任后才做软件/Agent。
   - 判停条件：若客户仍频繁改变输入、结果或验收标准，停留在服务层继续学习。

## B — 边界（Boundary）
- 没有真实订单时先用 `existing-market-manual-validation`，不要直接产品化。
- 高责任专业判断不能因重复出现就完全自动化。
- 失败模式：批量制作泛提示词包；把内部脚本包装成客户可自助产品；先建设市场再验证交易。
- 盲点：少量高客单定制服务可能永远不值得软件化，利润而非技术完整度决定阶梯终点。

## 相关 Skills
- depends-on: `existing-market-manual-validation`, `bounded-deliverable-offer`
- contrasts-with: `agent-delivery-scope`
- composes-with: `delivery-feedback-data-loop`, `service-product-content-flywheel`

## 审计信息
- 验证通过：V1 ✓ / V2 ✓ / V3 ✓
- 测试通过率：100%（6/6，独立盲测）
- 来源单元：v03
- 蒸馏时间：2026-08-24
