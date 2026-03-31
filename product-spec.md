Width Risk & Compliance Database

一、核心定位

对标：Dow Jones Risk & Compliance，覆盖其最薄弱的亚洲市场。
公司主体：新加坡注册，面向亚洲全区域客户。
品牌名：Width Risk & Compliance Database
Skill 名：width-risk-compliance-database
一句话：亚洲版道琼斯风险合规数据库。

域名：
主域名：width.info
备用/API 域名：info.width.com

定位逻辑：
道琼斯 = 欧美数据权威，亚洲覆盖薄弱，起步价数千美元/月，面向金融机构
Width = 亚洲数据权威，中文/东南亚独家数据，免费可用，面向所有人
用户看到 Width 第一反应：这是亚洲的道琼斯



二、产品形态（只做这四个）





三、核心产品设计：结果页 + 分享卡片

信息分层逻辑

免费用户看到的是结论，完整信息通过 URL 链接访问。

第一层（免费，所有人可见）

第二层（点击链接后，网页完整信息）

分享卡片设计（Twitter/X Card）

当用户分享链接到 Twitter 时，自动展示 Open Graph 卡片：

卡片设计原则：
不显示敏感详情，只显示风险结论
有 Width 品牌标识，让卡片在 Twitter 上传播时持续带来品牌曝光
永久链接，卡片分享出去后始终可访问



四、数据库覆盖范围

对标道琼斯，重点补足亚洲


优先覆盖的亚洲司法管辖区

中国大陆 · 香港 · 台湾 · 新加坡 · 马来西亚 · 泰国 · 越南 · 印尼 · 菲律宾 · 日本 · 韩国



五、Skill 设计（width-risk-compliance-database）


SKILL.md 核心内容



六、Telegram Bot 交互设计

基本流程





七、Twitter/X Bot 设计

触发方式

用户在 Twitter 上提及 @width_risk 并附上查询对象：

Bot 自动回复带卡片的推文：

主动内容策略

每次大型被盗事件/制裁新闻发生后，官方账号主动发布：



八、Key 与访问机制

UUID Key 自动分配

所有 API 请求自动获得匿名 UUID Key
无需注册，无需邮箱，直接使用
Skill / Bot / 网页端共用同一套 Key 体系

额度设计


个人用户永久免费。



九、KPI 目标


分享卡片曝光量是额外追踪的品牌指标：每一次用户把 width.info 的链接分享到 Twitter，都是一次品牌曝光，这是 Width 区别于竞品的独特增长飞轮。



十、推广计划

Phase 1：冷启动（week 1）

产品上线
width.info 网页端上线，搜索框 + 分享卡片功能完整
Telegram Bot 上线，支持姓名/地址/公司查询
GitHub 开源，README 第一行：
"Asia's Risk & Compliance Database · 亚洲风险合规数据库"

种子内容
Twitter/X 官号：每天发 1 条亚洲制裁/风险人物追踪，附 width.info 卡片
每次新制裁名单发布（OFAC/UN/MAS）：第一时间发布"Width 已收录"
Telegram 加入亚洲合规/反诈圈子，提供免费查询服务

GitHub 冷启动
提交 Show HN："Show HN: Asia's open risk & compliance database"
提 PR 进入 awesome-mcp / awesome-compliance 列表

Phase 2：破圈（week 2–6）

热点借势
每次亚洲重大金融犯罪事件：Width 官号第一时间发追踪卡片
每次 OFAC/UN 制裁亚洲实体：发布"Width 数据库已更新"
定位：亚洲合规信息的第一手来源

合作导流
接触亚洲 Crypto 媒体（CoinDesk Asia、The Block Asia）：提供独家数据
与 6551、BlockBeat 等数据 Skill 互相推荐
联系新加坡 MAS 认可的合规社区，申请作为推荐工具

Skill 生态
Claude Plugin Store 上线
Composio / Toolhouse 上架
LangChain / n8n 示例模板发布

Phase 3：规模化（week 7–12）

企业销售
主动接触新加坡、香港的 Fintech 公司合规团队
产品定位：道琼斯的低成本亚洲替代方案
合同谈判：年费 Enterprise 方案

数据扩展
扩充东南亚本地数据（泰国、越南、印尼）
与亚洲本地数据提供商合作采购授权数据
发布年度《亚洲风险合规报告》，媒体背书



十一、竞争定位


一句话竞争策略：道琼斯是合规团队的工具，Width 是所有人的工具。道琼斯看欧美，Width 看亚洲。



十二、合规说明

公司主体：新加坡注册，不在大陆设立任何实体
数据来源：官方制裁名单、公开监管公告、公开法院记录
个人数据：仅处理公开信息，提供异议申请渠道（dispute@width.info）
免责声明：数据仅供参考，不构成法律意见，用户自行承担决策责任
不主动向大陆用户推广，用户自行访问



最后更新：2026 年 3 月 · Width Risk & Compliance Database · Singapore







| 产品 | 说明 | 优先级 |
| --- | --- | --- |
| 网页端 width.info | 结果页 + 分享卡片 | P0 |
| Skill（width-risk-compliance-database） | Claude/GPT/MCP 接入 | P0 |
| Telegram Bot | 发名字/地址 → 返回结果 + 链接 | P0 |
| Twitter/X Bot | @width_risk 触发查询，自动回复卡片 | P1 |


| Plain Text ⚠️ 赵某某 出现在制裁名单中  来源：OFAC SDN List 更新时间：2024-03-01 风险等级：高风险  查看完整信息 → width.info/entity/abc123 |
| --- |


| Plain Text Width Risk Profile · 赵某某  基本信息 姓名：赵某某 别名：Zhao XX / 赵 XX 国籍：中国 出生年份：1978  命中记录（3条） · OFAC SDN List（美国财政部制裁）2023-11-15 · UN Security Council List（联合国安理会）2023-12-01 · MAS Investor Alert List（新加坡金管局）2024-01-10  风险分类 制裁 · 金融犯罪  数据来源 官方制裁名单 · 公开法院记录 · 监管公告  报告生成时间：2026-03-25 14:32 UTC+8 永久链接：width.info/entity/abc123  分享此报告 [Twitter] [复制链接] [下载 PDF] |
| --- |


| Plain Text ┌─────────────────────────────────────┐ │  Width Risk & Compliance Database   │ │                                     │ │  ⚠️ 高风险实体                       │ │  赵某某                              │ │  命中 3 项制裁名单                   │ │  OFAC · UN · MAS                    │ │                                     │ │  width.info/entity/abc123           │ └─────────────────────────────────────┘ |
| --- |


| 数据类型 | 道琼斯覆盖 | Width 目标覆盖 |
| --- | --- | --- |
| 全球制裁名单 | 强（欧美为主） | 全覆盖 + 亚洲补充 |
| PEP 政治敏感人物 | 强（欧美为主） | 亚洲重点：中、日、韩、东南亚 |
| 亚洲法院判决 | 弱 | 重点建设 |
| 中文负面媒体 | 弱 | 独家优势 |
| 东南亚本地数据 | 弱 | 独家优势 |
| 加密货币风险地址 | 无 | 独家优势（链上数据） |


| Plain Text Width Risk & Compliance Database  用途 检查个人、企业、钱包地址是否出现在制裁名单、PEP 名单、 犯罪记录或负面媒体中。专注亚洲数据，覆盖 11 个司法管辖区。  调用方式 screen [name/address] [country_code]  返回格式 {   "entity": "赵某某",   "risk_level": "HIGH",   "hits": [     { "list": "OFAC SDN", "date": "2023-11-15" },     { "list": "UN Security Council", "date": "2023-12-01" }   ],   "profile_url": "https://width.info/entity/abc123",   "summary": "该实体出现在 2 项国际制裁名单中，风险等级高。" }  安装 复制到 .claude/skills/ 或通过 MCP 接入： npx width-risk-compliance-database |
| --- |


| Plain Text 用户：赵某某  Bot： ⚠️ 发现风险记录  赵某某 命中 2 项制裁名单 · OFAC SDN List · UN Security Council List  完整报告： width.info/entity/abc123  分享到 Twitter ↗ |
| --- |


| Plain Text 用户：0x1234abcd...（钱包地址）  Bot： 🚨 高风险地址  该地址关联已知诈骗集群 最后活动：2 小时前 资金已转入 Binance 充值地址  完整报告： width.info/address/0x1234 |
| --- |


| Plain Text 用户：Alibaba Group  Bot： ✅ 未发现风险记录  阿里巴巴集团 未出现在任何制裁或 高风险名单中。  完整报告（含详细尽调信息）： width.info/entity/xyz789 |
| --- |


| Plain Text @width_risk 帮我查一下 赵某某 |
| --- |


| Plain Text @用户名  Width Risk Check ·赵某某  ⚠️ 高风险：命中 OFAC 制裁名单 详情 → width.info/entity/abc123 |
| --- |


| Plain Text 【Width 追踪】  本次 Bybit 黑客事件涉及地址 已收录至 Width 数据库  0x1234... → 风险等级：极高 关联：Lazarus Group（朝鲜黑客）  完整报告 → width.info/address/0x1234 |
| --- |


| 层级 | 额度 | 升级方式 |
| --- | --- | --- |
| 游客 | 100 次/日 | 自动分配，无需操作 |
| 认证用户 | 500 次/日 | 绑定邮箱或手机号 |
| 反馈用户 | 1,000 次/日 | 提交一次使用反馈 |
| Enterprise | 无限 + 私有部署 | 联系 Singapore 商务团队 |


| 指标 | 12 个月目标 |
| --- | --- |
| GitHub Stars | 10,000 |
| 累计装机量（Key 激活数） | 50,000 |
| 日活 DAU | 2,000 |
| 分享卡片曝光量 | 500,000 |


| 维度 | Dow Jones R&C | Width |
| --- | --- | --- |
| 总部 | 美国纽约 | 新加坡 |
| 亚洲数据 | 弱 | 核心优势 |
| 中文数据 | 有限 | 深度覆盖 |
| 链上数据 | 无 | 独家覆盖 |
| 定价 | 数千美元/月起 | 免费 + Enterprise 定制 |
| 目标客户 | 大型金融机构 | 所有人 + 机构 |
| 产品门槛 | 需要合规团队操作 | 普通人直接用 |
| 分享能力 | 无 | 卡片分享，社交传播 |
