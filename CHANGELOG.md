# Changelog

[中文版本](./CHANGELOG_zh-CN.md)


## [0.1.1] - 2026-01-29

### Added
- Added `ignoreOtherMentions` configuration option to allow bots to ignore messages where other users are explicitly mentioned, even when `requireMention` is false. This enables bots to participate in general conversations without interrupting when someone else is addressed.
- Improved mention detection logic to respect the bot's configured `name` in `openclaw.json`, preventing multiple bots in the same group from responding to mentions not intended for them.

## [0.1.0] - 2024-05-20

### Added
- Initial release of the Feishu/Lark channel plugin.
- Support for WebSocket and HTTP event modes.
- Support for multi-account configuration.
- Basic messaging capabilities (text, media, reactions, pin/unpin).
