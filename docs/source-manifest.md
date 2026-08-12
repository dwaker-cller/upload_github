# 资料来源与处理说明

本仓库以《实习生工作手册》为主线，并使用下列资料进行交叉校对。按仓库所有者的明确要求，9 份原始 PDF 原样归档于 `docs/pdfs/`，2 份原始 PPTX 原样归档于 `docs/presentations/`；它们可能包含测试信息、内部地址、业务截图和未公开需求，因此仓库必须保持 Private。CSV、Base、ZIP 和 DOC/DOCX 不入库。

| 资料 | 用途 | 入库处理 |
| --- | --- | --- |
| `实习生工作手册.pdf` | 工作主线、成果清单与 Demo 对应关系 | 原样归档于 `docs/pdfs/` |
| `Meet Influencer V1.0 产品需求文档 (1).pdf` | 产品角色、主流程与业务规则 | 原样归档于 `docs/pdfs/` |
| `Influencer V1.0 上线范围与业务验收标准.pdf` | 上线范围、主流程与异常流验收 | 原样归档于 `docs/pdfs/` |
| `7月第三周基础优化需求.pdf` | 页面与基础体验优化对照 | 原样归档于 `docs/pdfs/` |
| `6.29验收问题（达人端） (1).pdf` | 达人端问题与回归参考 | 原样归档于 `docs/pdfs/` |
| `MeetInfluencer V1.0 英文文案需求文档 (1).pdf` | 英文术语、状态和提示文案检查 | 原样归档于 `docs/pdfs/` |
| `MeetInfluencer_社媒账号认证与数据同步需求文档.pdf` | 社媒认证、授权、审核和同步范围 | 原样归档于 `docs/pdfs/` |
| `Nox聚星网红营销云-2026版.pdf` | 2026 年网红营销云资料 | 原样归档于 `docs/pdfs/` |
| `游戏达人营销自动化系统搭建方案.pdf` | 游戏达人营销自动化方案资料 | 原样归档于 `docs/pdfs/` |
| `MeetInfluence_2026_战略规划.pptx` | 2026 年战略规划资料 | 原样归档于 `docs/presentations/` |
| `从付费买玩家到自转化-YoudaoAds-游戏KOC孵化.pptx` | 游戏 KOC 孵化方案资料 | 原样归档于 `docs/presentations/` |
| `前端页面问题清单 - 任务跟进看板.csv` | 问题跟踪字段与回归参考 | 不提交原始行数据 |
| `🛠️ Meet influencer需求收集与管理.base` | 需求池、状态与实施参考 | 不提交飞书 Base 快照 |
| 飞书 Wiki Demo | 与本地 Demo 的成果归档关系 | 不提交私有 Wiki 地址或访问凭据 |

## Demo 选择

- 新手引导采用手册中点名的 `MeetInfluencer_New_User_Guide_Demo_CN.html`。
- 社媒认证采用手册中点名的 v2 原型；旧版和重复 ZIP 不提交。
- 两个文件均重命名为各自目录下的 `index.html`，便于本地静态服务器访问。

## 脱敏与安全检查

- 移除测试环境邮箱和内部运营邮箱，统一替换为 `example.com` 示例地址。
- 不包含密码、令牌、API Key、Cookie、私钥或 GitHub 凭据。
- 不包含外部脚本、外部样式、`fetch`、XHR、WebSocket 或表单提交。
- 外部社媒 URL 只作为模拟地址或手动链接，不会被页面自动请求。
- 原始 PDF 与 PPTX 仅按仓库所有者明确指定的文件原样归档；CSV、Base、ZIP 和 DOC/DOCX 由 `.gitignore` 阻止误提交。

如需继续加入 PDF 以外的原始资料，仍应先取得资料所有者授权，并复核仓库的 Private 状态与访问成员。
