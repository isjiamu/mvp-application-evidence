# Skills and simulated CRM MCP · 岗位 Skills 与模拟 CRM MCP

## Teaching design / 教学设计

Role-specific exercises connect input materials, business rules, tool steps, output formats and human checks. The retained raw-materials inventory covers customer service, QC, curriculum/document work, course consultants, marketing and administration/compliance. Reference implementations support learners when they need help.

岗位实操将输入材料、业务规则、工具步骤、输出格式和人工核对连接起来。原物料目录覆盖客服、质检、教研文档、课程顾问、市场和行政合规，并准备参考实现用于学习辅导。

| Example / 示例 | Teaching objective / 教学目标 |
| --- | --- |
| Reply improvement / 客服话术优化 | Find missing context or knowledge; propose replies and review risks / 识别背景与知识缺口，提出回复并复核 |
| Chat auditing / 聊天质检 | Check explicit criteria and return evidence-linked findings / 按明确标准检查，并返回可定位依据 |
| Course-document structuring / 课程文档结构化 | Extract fields without inventing missing information / 抽取字段，缺失信息不编造 |
| Learning communication / 学习汇报 | Combine learner-data fields, communication templates and human review / 连接学员数据字段、沟通模板与人工检查 |
| Content, HR and administration / 内容、人事与行政 | Decompose tasks and use role-specific outputs and checking steps / 拆解任务，设定岗位输出与核验步骤 |

## Simulated MCP interface / 模拟 MCP 接口

The retained CRM MCP README explicitly calls this a fake-data teaching demonstration. The server loads local JSON files; its preparation does not establish a connection to the real CRM. Eleven tool declarations were verified by static inspection of the retained server source.

原 CRM MCP README 明确注明为 fake 数据教学演示，服务读取本地 JSON；材料准备不能证明已接入真实 CRM。本次静态核对 server.py 得到 11 个工具声明。

| Tool / 工具 | Purpose / 用途 |
| --- | --- |
| `get_student_info` | Learner profile / 学员档案 |
| `get_recent_lessons` | Recent lessons / 近期课程 |
| `get_textbook_progress` | Textbook progress / 教材进度 |
| `get_homework_completion` | Homework completion / 练习完成情况 |
| `get_attendance_trend` | Attendance trends / 上课趋势 |
| `get_last_communication` | Previous communication / 既往沟通 |
| `get_classroom_analysis` | Lesson analysis / 单课分析 |
| `get_recent_classroom_summary` | Recent analysis summary / 近期分析汇总 |
| `get_consultant_info` | Consultant information / 顾问信息 |
| `list_students_by_consultant` | Learners assigned to a consultant / 顾问名下学员 |
| `get_full_student_profile` | Combined profile / 汇总画像 |

The teaching flow is: request the needed data through tools, organize the returned fields, apply a role-specific Skill, and have a human check the draft against business criteria. This demonstrates how interfaces and knowledge can support repeatable agent tasks.

教学流程为：工具获取所需数据，组织返回字段，应用岗位 Skill，再按业务标准人工核对草稿，展示接口、知识与可复用 Agent 步骤的连接方式。

No real learner identifiers, sample profiles, recordings, private files, API credentials or internal URLs are included. No MCP runtime or live CRM test was run for this publication, and no performance result is claimed. Adapting a demo to production would require integration, access control, data handling and validation appropriate to the actual system.

本页不包含学员标识、样例画像、录音、私有原件、密钥或内部 URL。本次发布未运行 MCP 或真实 CRM 测试，不声称性能结果；真实接入仍需按系统完成集成、权限、数据处理与验证。

## Source locators / 来源定位

- 0512-workshop-demo/crm-mcp/README.md — simulation note and tool list / 模拟说明与工具清单。
- 0512-workshop-demo/crm-mcp/server.py — local JSON loader and tool declarations / 本地数据读取与工具声明。
- skills-demo/raw-materials/README.md — role-group input materials / 岗位分组输入物料。
- 0512-workshop-demo/reference-skills/README.md — reference learning packages / 岗位参考实现。

Microsoft Foundry relevance concerns MCP tool design, context organization and evaluation methods. No direct Microsoft Foundry use or deployment is asserted for this collaboration.

与 Microsoft Foundry 的关联指 MCP 工具设计、上下文组织及评估方法，不声称本合作直接使用或部署了 Foundry。
