# 更新日志 (Changelog)

[English Version](./CHANGELOG.md)

## [0.1.1] - 2026-01-29

### 新增
- 新增 `ignoreOtherMentions` 配置项。当 `requireMention` 为 false 时，允许机器人忽略那些明确 @ 了其他人的消息。这使得机器人既可以参与普通聊天，又能在其他人被点名时不插嘴。
- 改进提及（Mention）检测逻辑。现在会检查 `openclaw.json` 中配置的机器人 `name`，避免群组中多个机器人同时响应不属于自己的 @ 消息。

## [0.1.0] - 2024-05-20

### 新增
- Feishu/Lark 渠道插件初始发布。
- 支持 WebSocket 和 HTTP 事件模式。
- 支持多账户配置。
- 基础消息功能（文本、媒体、回应、置顶/取消置顶）。
