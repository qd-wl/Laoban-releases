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

## 联系

问题反馈：185609073@qq.com
