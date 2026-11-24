# Shellport

原生 macOS SSH 客户端：直接使用 `~/.ssh`，支持跳板机、自动 attach tmux，小巧省电。

## 功能

- **直接用你的 ~/.ssh**：读取 config、私钥和 known_hosts，只读不写
- **跳板机**：多级 ProxyJump，可从已有主机中选择跳板
- **自动 attach tmux**：断线重连回到原来的工作现场
- **断线不丢屏**：保留终端内容，按回车重连
- **主机分组**：可折叠，把主机拖进分组即可
- **原生终端**：Powerline 字形、浅色 / 深色主题、导入「终端」App 的描述文件
- **私钥写入 iCloud 钥匙串**，在你的设备间同步

界面支持简体中文、English、日本語、Tiếng Việt。

## 下载与安装

系统要求：macOS 27 及以上，Apple Silicon。

1. 下载 [Shellport.dmg](https://github.com/leadead/Shellport-Releases/releases/latest/download/Shellport.dmg)（[所有版本](https://github.com/leadead/Shellport-Releases/releases)）
2. 打开后，在弹出的窗口中把 Shellport 拖到「Applications」
3. 打开 Shellport，左栏会列出 `~/.ssh/config` 中的主机

安装包已通过 Apple 公证。

## 更新

App 会自动检查更新，也可以在菜单「Shellport → 检查更新…」中手动检查。

## 隐私

Shellport 不采集、不上传任何数据，只连接你指定的主机。密码与私钥只存放在钥匙串和内存中。

## 关于本仓库

本仓库只用于发布安装包，Release 页面的 Source code 压缩包里也只有这份说明。Shellport 不开源：官方版本可免费下载使用，不得再分发或修改。
