# 隐私说明 / Privacy

## 本地记录

语航读取用户选择的本机 Codex 日志、目录和状态信息，并在独立应用目录保存设置、索引和统计。为匹配当前用户，适配器会在本机读取账号身份信息；不把身份凭证发送给更新服务或公开反馈入口。监测不修改 Codex 对话、配置或已读状态，也不恢复原对话。

语航没有自建用户账号、遥测或营销后台。首次统计会读取必要本地记录；不要向公众提交这些原始材料。

## 可选 AI

AI 默认关闭。用户配置并启用后，分析所需的对话材料会发送到用户选择的 API 服务。材料可能含对话内容，因此开启前应检查服务地址、隐私条款与预算。API 凭证使用本机钥匙串的语航独立服务保存，不随旧版导入迁移。第三方服务的保存、计费与处理政策由该服务负责。

## 更新

启用更新检查时，程序连接 GitHub Pages 更新源及 GitHub Releases 下载服务。服务会收到正常网络请求信息，例如 IP 地址。语航不把对话正文、账号 token 或统计库加入更新请求；Sparkle 系统概况上报不启用。当前版本已启用更新检查入口；公开更新源尚未发布，检查可能暂时失败。是否允许自动检查由首次提示征询，自动安装关闭。

## 用户主动反馈

反馈由用户主动提交。只填写系统、App/Codex 版本、可复现步骤及脱敏截图。当前没有经过验收的一键诊断导出，暂不提供“导出后必然安全”的保证。不要上传原始日志、数据库、auth.json、Cookie、API Key 或完整文件路径。

## English

ContextCruise processes selected local Codex records and stores its settings and derived statistics locally. Account identity is read locally to match the current user, not transmitted to the update service. Monitoring does not edit Codex conversations, configuration, read state, or resume a conversation.

There is no ContextCruise account, telemetry, or marketing backend. Optional AI is off by default. If configured and enabled, analysis material, potentially including conversation content, is sent to the selected API provider. Credentials are stored in a dedicated local Keychain service and are not imported from older versions.

Enabled update checks contact GitHub Pages and GitHub Releases. These services receive ordinary request metadata such as IP addresses. Conversation text, credentials, and statistics databases are not added to update requests; Sparkle system-profile reporting is disabled. Bug reports are submitted by the user. Do not attach raw private records or credentials.
