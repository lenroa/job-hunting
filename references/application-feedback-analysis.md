# Application Feedback Analysis

## Input To Request

When the user wants objective analysis from投递情况, ask for a compact table or pasted notes with as many fields as available:

- Company/industry:
- Role title:
- JD keywords:
- Channel: Boss/Zhipin, LinkedIn, referral, email, other
- Greeting angle used:
- Outcome: no reply, HR replied, resume requested/sent, interview, rejected, offer, unknown
- Timeline:
- HR/interviewer feedback:
- User's notes: why interested, perceived fit, concerns

If the user has many records, ask for 10-30 representative applications first: roles with replies, interview invites, and clear no-response cases.

## Analysis Method

Compare outcomes by:

- Domain: AI, SaaS, enterprise service, catering/hotel digitization, industrial internet, smart hardware, consumer, growth, data, platform, operations.
- Role seniority: junior/mid/senior/lead, product manager vs product operations vs AI product manager.
- Match angle: AI cost reduction, B-side workflow digitization, delivery efficiency, customer success, data metrics, team/project management.
- JD requirements: SQL/data analysis, AI/LLM, commercialization, technical depth, user growth, industry knowledge, cross-functional ownership.
- Message quality: whether the greeting led with the strongest relevant evidence and made a low-friction ask.

Treat signals cautiously:

- One rejection is weak evidence.
- Repeated no-response in the same role type is a market signal.
- Interviews but no offers often mean the resume passed screening but interview story, depth, case ability, or role expectations need work.
- HR asking for a resume is stronger than read/no-reply, but weaker than interview invitations.
- Referral success may indicate network/channel strength rather than resume strength.

## Hidden Experience Mining

Use repeated JD gaps and successful-response patterns to ask targeted questions, such as:

- "多个高匹配 JD 都提到 SQL/数据看板。你在 AI 项目仪表盘里是否做过指标口径设计、数据字段定义、取数规则、自动化表格配置？有没有和研发或业务一起定义数据结构？"
- "如果 AI 产品岗位反复要求模型评估/效果评估，你是否做过生成结果的验收标准、人工抽检规则、通过率/直通率口径、错误类型归因？"
- "如果 SaaS 岗位看重客户成功/商业化，你是否参与过续费、客单价、客户分层、标杆客户案例、销售打法沉淀？"
- "如果平台型产品看重权限/流程配置，你在客户管理系统、订单模板配置、标签库/图片组库里是否设计过角色权限、配置规则、审核流或异常处理？"
- "如果管理岗或项目负责人岗位响应好，你是否有预算、排期、OKR、人员绩效、跨部门冲突解决、资源协调的具体例子？"

Add confirmed answers to `references/user-profile.md` under a clear section such as `## Additional Confirmed Experiences`. Mark facts, outcomes, and limits explicitly.

## Resume Inclusion Criteria

Recommend adding an experience to the resume only if it meets most of these:

- It matches repeated JD demand or a role type with better response.
- The user can explain the work in interview with concrete context, decisions, tradeoffs, and results.
- It has evidence: metric, artifact, stakeholder, launch, process change, customer impact, cost/revenue impact, or adoption.
- It strengthens the target positioning rather than making the resume look scattered.
- It can be worded truthfully without inflating ownership.

Do not recommend adding:

- Buzzwords learned only superficially.
- One-off tasks that cannot survive interview probing.
- Experiences that dilute the main AI + B-side/SaaS + efficiency story.
- Claims that require confidential details the user cannot discuss.

## Market-Based Advice Standard

When giving market advice:

- Be specific about the role segment, such as "AI SaaS product manager" rather than "PM market".
- Prefer evidence from current JD patterns, application outcomes, interview feedback, and credible public sources when available.
- Cite public sources if using external market data.
- Say when the sample is too small.
- Separate "market appears to reward" from "your current evidence proves".

## Output Pattern

```text
投递反馈结论：
- 有效市场信号：
- 可能的隐藏优势：
- 明确短板/风险：
- 样本不足，暂不能判断：

建议挖掘的问题：
1.
2.
3.

建议进入素材库：
- 已确认：
- 待确认：

建议进入简历：
- 建议加：
- 暂不建议加：

下一步投递策略：
- 更值得投：
- 谨慎投：
- 需要先补能力再投：
```
