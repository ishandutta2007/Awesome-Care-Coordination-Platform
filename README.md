# Awesome-Care-Coordination-Platform

# 顶级护理协调平台生态系统



**精选 SaaS 产品与开源 GitHub 项目列表**

*聚焦跨机构转诊、闭环沟通、社区健康工作与人口健康管理*

**最后更新：2026 年 9 月**



本仓库追踪 **护理协调** 领域的知名 **SaaS 平台** 与 **开源项目**。这些工具帮助医疗机构、支付方和社区组织跨护理场所协调患者护理，实现闭环转诊、共享护理计划和跨机构数据交换。



**示例** 包括 Innovaccer、Unite Us、Findhelp、Arcadia、Aidin、WellSky、CarePort Health、Lightbeam Health、Bamboo Health（PatientPing）、ZeOmega 和 HealthEC（该领域的领先者）。



**开源重点**：护理协调的开源生态在 **人口健康管理和社区护理协调层面成熟**。**SPICE**（Medtronic LABS）是数字公共产品认证的平台，已在撒哈拉以南非洲 6 个国家部署，筛查了 50 万患者 。**Community Health Toolkit (CHT)** 支持 15 个国家约 40,000 名社区卫生工作者，完成了超过 8500 万次护理活动 。**AHRQ eCare Plan** 提供了基于 SMART-on-FHIR 的共享护理计划应用，包含患者端和临床端两个应用 。**ORCA** 提供了荷兰护理协调的参考实现，实现了 FHIR 工作流 Task 和共享护理计划 。



欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。



## 目录



- [SaaS/托管平台](#saas托管平台)

- [开源 GitHub 项目](#开源github项目)

- [如何贡献](#如何贡献)

- [免责声明](#免责声明)



## SaaS/托管平台



- **[Innovaccer](https://innovaccer.com/)**

  医疗数据平台和护理协调解决方案。整合支付方和提供方数据，支持人口健康管理、风险分层和护理差距闭合。



- **[Unite Us](https://uniteus.com/)**

  社区护理协调平台，连接医疗提供方和社区组织。支持社会需求筛查、闭环转诊和结果追踪。



- **[Findhelp](https://findhelp.org/)**

  社会护理网络和转诊平台。连接患者与食品援助、住房、交通等社区资源，支持闭环转诊。



- **[Arcadia](https://arcadia.io/)**

  医疗数据分析和人口健康管理平台。提供风险分层、护理差距识别和提供方绩效分析。



- **[Aidin](https://aidin.com/)**

  护理过渡管理平台。支持从医院到急性后期护理的转诊和协调。



- **[WellSky](https://wellsky.com/)**

  护理协调和急性后期护理技术平台。涵盖家庭健康、临终关怀、康复和社区护理。



- **[CarePort Health](https://careporthealth.com/)**

  WellSky 旗下的护理协调平台。连接医院、急性后期护理提供方和支付方，支持实时患者转诊和护理过渡。



- **[Lightbeam Health](https://lightbeamhealth.com/)**

  人口健康管理平台。提供风险分层、护理协调和患者参与工具。



- **[Bamboo Health (PatientPing)](https://bamboohealth.com/)**

  护理协调和患者事件通知平台。通过实时患者事件通知（入院、出院、转院）支持跨提供方的护理协调。



- **[ZeOmega](https://zeomega.com/)**

  人口健康管理和护理协调平台。为支付方和提供方提供护理管理、利用管理和风险调整工具。



## 开源 GitHub 项目



### 社区护理协调平台



- **[SPICE (Medtronic LABS)](https://github.com/Medtronic-LABS)**

  **最成熟的开源社区护理协调平台，数字公共产品认证。** 专门为卫生系统和社区设计，聚焦社区和初级护理层面的数据驱动护理 。**核心功能**：社区卫生工作者筛查和风险分层；**闭环转诊和反向转诊**，将社区护理与设施服务双向链接；基于临床算法的纵向患者管理；设施层面的医疗审查、处方和检查；SMS 患者提醒；基于 WHO Hearts 算法的定制治疗计划 。**部署规模**：已在 6 个国家部署，筛查 50 万患者，转诊 146,646 患者， enrolling 222,000 患者，改善超过 130,000 患者的生活 。**FHIR 兼容**，支持与 DHIS2 等国家报告系统互操作。**BSD-3-Clause 许可** 。



- **[Community Health Toolkit (CHT)](https://github.com/medic/cht-core)**

  **支持社区卫生工作者的最广泛部署开源平台，数字公共产品。** 包含开源框架和应用集合，帮助合作伙伴为护理团队设计和部署数字工具 。**支持约 40,000 名社区卫生工作者**，在 15 个非洲和亚洲国家运行 。**功能模块**：消息传递、任务和日程管理、决策支持工作流、纵向个人档案和分析。支持**离线优先**运行，可通过 SMS（功能手机）、Android 应用、平板和计算机访问 。**合规**：手动可配置为符合 HL7 FHIR 标准 。**规模**：卫生工作者已完成超过 **8500 万次护理活动**。六个国家（肯尼亚、马里、尼泊尔、尼日尔、乌干达和桑给巴尔）已选择 CHT 作为国家社区平台 。**AGPL-3.0 许可**。



### 共享护理计划与转诊



- **[AHRQ eCare Plan](https://github.com/AHRQ-eCare-Plan)**

  **美国医疗保健研究与质量局 (AHRQ) 和 NIDDK 开发的开源共享护理计划应用。** 包含两个 SMART-on-FHIR 应用 ：**MyCarePlanner**（患者端）——患者和护理者设定目标、完成问卷、与护理团队分享优先事项；**eCarePlanner**（临床端）——聚合多个 EHR 供应商的数据，呈现目标、社会需求和护理团队信息。**基于 FHIR 和 USCDI 标准**，支持 Epic、VistA 和其他 EHR 的互操作性 。**试点结果**：90% 目标编写成功，67% 护理者表示使工作更轻松，63% 表示改善了护理协调 。**开源**。



- **[ORCA (Santeon)](https://github.com/SanteonNL/orca)**

  **开源护理计划参考实现，实现 Shared Care Planning 规范。** 支持通过 FHIR 工作流 Task 在护理组织间发起和处理任务 。**功能**：护理专业人员填写问卷的 UI；护理组织 EHR 访问护理计划服务 FHIR API 的代理；处理认证、本地化和数据聚合 。**架构**：每个 ORCA 实例作为 SCP 节点，可与使用不同 EHR 系统的其他节点通信 。适用于荷兰医疗体系，可适配其他地区。**开源**。



- **[careplan-service (REAN Foundation)](https://github.com/REAN-Foundation/careplan-service)**

  **护理计划管理服务，支持创作、调度、注册和任务分发。** 以 **TypeScript** 编写 。为护理计划的全生命周期提供 API：创建护理计划、安排任务、注册参与者、向参与者分发任务。可作为自定义护理协调系统的基础组件。**开源**。



### FHIR 基础设施与互操作



- **[Microsoft FHIR Server](https://github.com/microsoft/fhir-server)**

  **微软开源的 FHIR 服务器，Azure Health Data Services FHIR 服务的基础。** 支持 FHIR R4 规范，提供完整的 RESTful API 。可作为护理协调平台的底层数据存储和互操作层。**开源**。



- **[Microsoft FHIR-Converter](https://github.com/microsoft/FHIR-Converter)**

  **将传统医疗数据格式转换为 FHIR 的数据转换工具。** 支持 CLI 和 `$convert-data` 端点 。帮助将遗留系统数据迁移到 FHIR 兼容的护理协调平台。**开源**。



- **[TPT Healthcare NZ](https://github.com/tpt-solutions/tpt-healthcare-nz)**

  **新西兰开源医疗平台，FHIR R5 REST API，支持 NHI/HPI/ACC/NES/PHARMAC 集成。** Go 后端，React 前端，多租户，审计追踪，同意管理 。**功能**：FHIR R5 资源存储（PostgreSQL JSONB）；患者查找、从业者验证、PHO 注册、ACC 索赔；SNOMED CT、LOINC、ICD-10-AM 术语加载；FHIR R5 订阅（rest-hook、WebSocket、email）；同意管理（HIPC Rule 10/11）；AES-256-GCM 字段加密；OpenTelemetry 追踪 。**合规**：Privacy Act 2020 和 HIPC 2020。**开源**。



### 临床沟通与团队协作



- **[Matrix for Healthcare Communication (Nuts Foundation)](https://github.com/nuts-foundation/toepassing-instante-communicatie)**

  **基于 Matrix.org 的医疗即时通讯和护理团队协作规范。** 使用联邦通信协议实现护理组织间的安全消息传递 。**核心设计**：**Matrix Space = 护理团队**；**Matrix Room = 对话**；权限级别（100=护理团队负责人，50=医疗从业者，25=相关人员，10=客户）；与医疗身份提供者集成；通过 mCSD 发现从业者 。**用例**：网络管理、新对话、消息管理、跨平台集成、多组织协作 。**CC BY-SA 4.0 许可**。



### 其他强开源选项



- **社区护理协调**：**SPICE**（数字公共产品，6 国部署）、**CHT**（40,000 CHW，15 国）。

- **共享护理计划**：**AHRQ eCare Plan**（SMART-on-FHIR，患者+临床双应用）、**ORCA**（FHIR 工作流 Task）。

- **FHIR 基础设施**：**Microsoft FHIR Server**、**FHIR-Converter**、**TPT Healthcare NZ** 。

- **临床沟通**：**Matrix for Healthcare**（联邦通信，护理团队空间）。



**构建自定义系统的框架**：结合 **Microsoft FHIR Server** 或 **TPT Healthcare NZ** 作为 FHIR 数据存储和互操作层，**AHRQ eCare Plan** 或 **ORCA** 作为共享护理计划引擎，**SPICE** 或 **CHT** 作为社区护理协调前端，**Matrix for Healthcare** 作为临床沟通层。添加 **PostgreSQL** 用于持久化，**Docker** 用于部署。



## 如何贡献



1. Fork 仓库。

2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。

3. 包含：名称、链接、1–2 句描述，以及是 SaaS 还是开源。

4. 提交 PR 并附简短说明。



如果你觉得这个仓库有用，请点星！



## 免责声明



- 这是一个 **社区精选** 列表——并非详尽无遗，也不构成认可。

- 护理协调平台处理敏感患者健康数据；确保符合 HIPAA、GDPR 和适用的医疗数据保护法规。

- **开源现实**：护理协调的开源生态在 **社区护理协调**（SPICE、CHT）和 **FHIR 互操作**（Microsoft FHIR Server、TPT Healthcare NZ）层面 **成熟且生产可用**。**AHRQ eCare Plan** 提供了经过验证的共享护理计划应用 。**ORCA** 提供了可适配的护理计划参考实现 。然而，**企业级人口健康管理**（Innovaccer、Arcadia、Lightbeam）和 **社会护理网络**（Unite Us、Findhelp）的商业平台在风险分层算法、社会服务资源库和支付方集成方面具有显著优势，开源方案需要大量集成和定制开发才能匹配。



---



**为护理协调员、人口健康管理者、社区健康组织和医疗 IT 团队打造。**

让护理协调更开放、透明、以患者为中心。
