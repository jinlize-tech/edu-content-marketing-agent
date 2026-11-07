# G5/G9 产品修改记录

- 产品编号：$(@{number=14; product_id=JLZ-EDU-AG-002; chinese_name=内容营销运营; english_name=Content Marketing Agent; repository_name=edu-content-marketing-agent; repository_url=https://github.com/jinlize-tech/edu-content-marketing-agent; product_type=Agent; category_code=01; category=01 招生营销中心; description=内容定位、选题、文案、发布规划和营销效果分析。; target_users=System.Object[]; core_input=机构定位、课程矩阵、目标客群、渠道现状、内容资产和历史表现; main_output=内容定位、栏目矩阵、选题库、渠道分工、发布节奏、素材清单和复盘指标; product_risk=内容同质化、夸大宣传或虚构历史效果; dedup_label=需要明确差异化; dedup_note=与通用内容运营助手相比限定教培招生与家长沟通；不执行发布、投放或账号操作。; development_status=Planned / 待研发; license=Apache-2.0; spec_version=1.0.0; workbuddy_status=PLANNED_FOR_WORKBUDDY}.product_id)
- 产品名称：内容营销运营
- 基线：EDUCATION_BASELINE_V1.0.0
- 基线提交：$BaselineCommit
- 原版本：1.0.0
- 新版本：1.0.1

## 本次修改

1. 强化产品专属执行流程、输入核对和输出验收规则。
2. 新增 scripts/validate_input.js，实际检查必填字段、冲突、未确认数据和敏感信息。
3. 新增正常、缺失、冲突、敏感信息和非法JSON场景输入。
4. 测试升级为 T1–T7 分层并保存逐项检查结果。
5. 安装包加入 Apache-2.0 LICENSE 和 THIRD_PARTY_NOTICES.md。
6. 安装包升级为 1.0.1，加入许可证、第三方声明和输入校验脚本，保留 1.0.0 ZIP。
7. 按本产品冻结规格补充专属处理规则、输入到成果的核对矩阵和去重边界。

## 产品专属增强

- 核心任务：内容定位、选题、文案、发布规划和营销效果分析。
- 主要风险：内容同质化、夸大宣传或虚构历史效果
- 去重边界：与通用内容运营助手相比限定教培招生与家长沟通；不执行发布、投放或账号操作。

- 先锁定招生目标、课程、时间窗口、目标客群和可得预算，再讨论创意与渠道。
- 把假设线索量、转化率和单价分别列示，不以单一历史数据外推全部结果。
- 逐项检查渠道费用、人员投入、活动固定成本和单人可变成本，防止重复计费。
- 对宣传承诺、价格、名额、效果和第三方素材做合规与真实性复核。

## 运行边界

- 本地模型行为：NOT_RUNTIME_VERIFIED
- WorkBuddy平台验证：WORKBUDDY_VALIDATION_NOT_IN_SCOPE
- 本轮不执行上传、安装、审核或正式发布。
