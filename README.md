# ToolChest 安装包仓库

Windows x64 便携软件安装包与加密文件仓库。本仓库仅用于公开发行和程序更新，不包含开发源码。

## 下载与使用

1. 在 [正式发行版](https://github.com/ljy7727/toolchest-releases/releases/latest) 下载 `ToolChest-portable.zip` 并解压。
2. 双击 `ToolChest.exe`，系统需要 Microsoft WebView2 Runtime。
3. 换机器时复制整个便携目录，包含运行后生成的 `ToolChestData`。
4. 已有版本升级只替换 EXE，保留原有 `ToolChestData`，不要把旧数据删掉。
5. 设置中的发行仓库填写 `ljy7727/toolchest-releases`，检查和下载更新无需令牌。旧版本首次迁移可手动填写此地址，或下载本版替换 EXE。

## 功能

- 保存完整安装包、文件夹和下载链接，支持下载队列及链接检测。
- 自定义分类、分区及主题，支持仓库完整备份和恢复。
- 私密空间独立加密文件、文件名和目录结构；导入保留外部原件。
- 设置可选择自动检查与空闲时安装软件更新，自动安装默认关闭。

私密空间恢复凭据由你自行备份。忘记密码需要本库有效恢复凭据；没有万能密码。外部打开或导出会产生明文，第三方软件可能留缓存。

每个正式版本提供固定 ZIP 与 SHA256 文件。下载后可用 `Get-FileHash` 核对完整性。GitHub 页面自动生成的 Source code ZIP 仅包含本仓库公开说明，并不是软件源码或可运行安装包。

软件许可证与上游归属包含在便携包的 `LICENSE` 和 `THIRD_PARTY_NOTICES.md` 中。用户安装包、数据库、私密文件及凭据不上传至本仓库。
