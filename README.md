# SOP 智能体资产拆解

将 SOP 或工作清单，通过逐项访谈拆解成 **工作方法、参考资料、系统与权限需求**，并标记 **🟢 AI 提效机会** 和 **🔴 待解决项**。

## 使用

将本目录放入 `~/.codex/skills/sop-to-agent-assets`，在支持 Skills 的会话中输入：

> 使用 $sop-to-agent-assets，帮我把这份 SOP 拆成智能体可复用资产。

也可自然描述同类需求。仅润色或摘要 SOP 不触发完整拆解。

流程：读取资料 → 确认全部任务边界 → 补齐实际流程 → 三类资产拆解 → 标记 AI 机会与缺口 → 用户确认 → 收集反馈并改进。

访谈方法借鉴 [RobMitt/grill-me-skill](https://github.com/RobMitt/grill-me-skill)，无需额外安装。每次交付后主动收集反馈，通用改进记录在 [CHANGELOG.md](CHANGELOG.md)。
