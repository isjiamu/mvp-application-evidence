# Role-specific teaching templates · 岗位教学模板摘录

These excerpts demonstrate course and case design. They are teaching prompts, not verified learner outputs, deployed assistants or measured business results.

以下摘录展示课程与案例设计，属于教学 Prompt，不代表已核验的学员成果、已部署助手或实际业务成效。

**Source / 来源：** 自然萃AI提效培训专属提示词模板库.md，文档署名“甲木 | 2026.03.30”。原文包含编号 1–35 的场景模板。仅公开以下 3 个场景的目标、约束、步骤与输出格式；角色设定、内部背景和个体问卷原话未收入。

**Editorial note / 编辑说明：** The selected prompt sections are reproduced as teaching-material excerpts. Human review of facts, calculations, product representation and inferred causes is still required; no runtime evaluation of these templates is claimed here.

所选 Prompt 段落按教学材料摘录保留。事实、统计口径、产品外观及原因推断仍需人工核对；本页不声称对模板进行了实际运行评测。


## 场景 14：用户评论智能分析

```text
## Goals:
- 对一批用户评论进行智能分类、情感分析和洞察提炼
- 输出分析报告，包含：各维度好评率 / 差评率统计、TOP5 好评关键词、TOP5 差评问题、可复用的卖点表述、改进建议

## Constraints:
1. 分类维度固定为：口感体验、配料安全、包装设计、物流服务、性价比、复购意愿
2. 情感标注三级：正面 ✅ / 中性 ⚪ / 负面 ❌
3. 负面评论必须深挖具体问题点，不能只标「差评」
4. 正面评论必须提炼可复用于营销的原话金句
5. 输出格式为表格，方便导入飞书多维表格

## Workflows:
1. 接收用户评论数据（建议 30 条以上效果最佳）
2. 逐条进行分类和情感标注
3. 统计各维度的好评率和差评率
4. 提炼 TOP5 好评关键词和 TOP5 差评问题
5. 从好评中提炼可直接用于营销的「用户原话金句」（5-10 条）
6. 从差评中提炼改进建议
7. 输出完整分析报告
```


## 场景 32：AI 生图约束与审图 Prompt（设计岗位）

```text
## Goals:
- 根据自然萃品牌视觉规范，生成一套 AI 生图的标准化约束提示词体系
- 包含：风格约束词库、材质约束词库、元素约束词库、负面排除词库
- 附上 AI 生图审核检查清单（10 项检查点）

## Constraints:
1. 约束词库必须对应自然萃的品牌调性：清新自然、干净纯粹、有品质感
2. 风格约束覆盖：色调（暖调为主）、材质（天然质感）、光影（柔和通透）、构图（简洁留白）
3. 负面排除词库必须包含：人工感、塑料感、过饱和、低质量、怪异比例等
4. 审图检查清单需覆盖：品牌色系一致性、产品比例准确性、文字可读性、合规性等

## Workflows:
1. 梳理自然萃品牌视觉规范的核心要素
2. 为风格、材质、元素三个维度分别建立约束词库
3. 建立负面排除词库
4. 设计 10 项 AI 生图审核检查清单
5. 输出一份可直接使用的「自然萃 AI 生图规范手册」
```


## 场景 34：指标口径说明 Prompt（数据与分析岗位）

```text
## Goals:
- 生成一份自然萃电商运营的「核心指标口径说明手册」
- 覆盖 30+ 常用指标，每个指标包含：定义、计算公式、数据来源、注意事项、各平台差异说明
- 按业务模块分类（流量、转化、客单、售后、投放、达人）

## Constraints:
1. 定义必须清晰无歧义
2. 公式必须写出具体的分子分母
3. 不同平台的口径差异必须标注
4. 标注常见的误用场景（如「把加购率当转化率用」）

## Workflows:
1. 确认需要覆盖的指标范围和业务模块
2. 逐个指标编写口径说明
3. 标注各平台的口径差异
4. 附上常见误用案例和正确用法
5. 输出指标口径手册
```

## Demonstration-data boundary / 演示数据说明

The associated source casebook, 自然萃_三大场景实战案例集.md, explicitly describes its people and brand data as fictional training demonstrations. Its example outputs and before/after efficiency estimates are therefore not reported here as customer achievements or observed learner results.

配套《自然萃_三大场景实战案例集.md》明确说明人物和品牌数据为虚构演示。其示例输出、耗时对比和提效估算不作为客户实际成果或已观察到的学员效果。
