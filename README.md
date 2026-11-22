# Laoban 发布页

Laoban 是一个人指挥一支 AI 团队做项目的 Mac 桌面应用：角色由你定义，在真终端里运行 Claude Code / Codex，角色之间自己派活、交验收，你只管拍板和验收。

这个仓库只放安装包和版本说明，用于下载和应用内的「检查更新」。

## 下载

到 [最新版本](https://github.com/qd-wl/Laoban-releases/releases/latest) 下载 `Laoban-<版本>-arm64.dmg`（Apple 芯片的 Mac），打开后把 Laoban 拖进「应用程序」。

内测版没有苹果签名。第一次打开如果被拦：

- macOS 13、14：在「应用程序」里右键 Laoban → 打开，弹窗里再点「打开」。
- macOS 15 及以后：先双击一次（会被拦），再到「系统设置 → 隐私与安全性」，页面下方点「仍要打开」。
- 如果提示「已损坏，无法打开」，在终端运行一次：`xattr -dr com.apple.quarantine /Applications/Laoban.app`

## 更新

Laoban 启动时会检查这里有没有新版本，有就在窗口顶部提示，点「下载并安装」即可（只读公开的发布页，不上传任何数据；可在「设置」里关掉）。每个安装包都附有 `.sha256` 校验文件。

## 内测说明

下载或使用 Laoban，即表示你同意以下条款：

- **免费内测**：Laoban 目前是免费的内测版，仅供个人试用和评估。
- **版权**：版权归作者所有，保留所有权利。未经许可，不得再分发、出售，或修改后再发布。
- **不提供担保**：软件按现状提供。作者不对使用过程中的数据丢失、AI 引擎额度消耗或其他损失负责。
- **请在信任的项目里使用**：角色在你的电脑上运行 Claude Code / Codex，会读写你授权的目录、执行命令。重要数据请自己备份。
- **隐私**：Laoban 是纯本地应用，项目数据只存在你的电脑上。除了检查更新（只读本页，可在设置里关掉），不联网，也不收集任何使用数据。AI 引擎怎么处理你的数据，以 Anthropic / OpenAI 各自的条款为准。
- **随时变化**：内测版可能随时更新、调整或停止提供。

**Beta terms (English):** Laoban is a free beta for personal evaluation only. All rights reserved; do not redistribute, sell, or publish modified copies without permission. Provided as is, without warranty; the author is not liable for data loss, AI quota usage, or other damages. Roles run Claude Code / Codex on your machine with access to the folders you grant — use it only on projects you trust and keep backups. Laoban is local-only and collects no usage data; apart from the optional update check, it does not go online. The beta may change or end at any time. By downloading or using Laoban you agree to these terms.

## 联系

问题反馈：185609073@qq.com
