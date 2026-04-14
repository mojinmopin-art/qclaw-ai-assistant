# QClaw - AI Chat Assistant / 微信AI助手

[![Official Site](https://img.shields.io/badge/Official_Site-qq--claw.org-brightgreen)](https://qq-claw.org)
[![Version](https://img.shields.io/badge/Version-2026.4-blue)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

QClaw is an AI-powered chat assistant designed for Chinese social platforms. It provides smart reply suggestions, message translation, and content generation directly within your chat interface.

## Features

- **Smart Reply**: AI-generated contextual reply suggestions based on conversation history
- **Real-time Translation**: Translate incoming messages instantly (supports 15+ languages)
- **Content Generation**: Draft messages, announcements, and formatted text with AI
- **Group Chat Summary**: Summarize unread messages in busy group chats
- **Voice-to-Text Enhancement**: Improve accuracy of voice message transcriptions

## Supported Platforms

| Platform | Version | Status |
|----------|---------|--------|
| WeChat (Desktop) | 3.9+ | ✅ Full support |
| QQ (Desktop) | 9.7+ | ✅ Full support |
| WeChat (Web) | Latest | ✅ Via browser extension |
| Telegram | Desktop 4.0+ | ⚠️ Beta |

## Installation

### Desktop Application
1. Visit [qq-claw.org](https://qq-claw.org) to download the installer
2. Run the installer and follow setup wizard
3. Launch QClaw — it will detect installed chat apps automatically

### Browser Extension (for WeChat Web)
1. Install from [qq-claw.org](https://qq-claw.org)
2. Open web.wechat.qq.com
3. QClaw sidebar appears automatically

## Use Cases

### Customer Service Automation
- Auto-generate professional replies to common customer inquiries
- Maintain consistent tone across team members
- Multi-language support for international customers

### Group Chat Management
- Summarize 100+ unread messages into key points
- Highlight messages that mention you or require action
- Auto-categorize messages by topic

### Personal Productivity
- Draft quick replies when you're busy
- Translate foreign language messages without leaving the chat
- Format messages with proper structure and emojis

## Technical Details

```
Chat Message Stream
    ↓
Message Parser (extracts text, context, sender info)
    ↓
Intent Classification (question / request / casual / urgent)
    ↓
AI Response Generation (context-aware, tone-matched)
    ↓
User Review → Send or Edit
```

Design principles:
- **Non-intrusive**: QClaw suggests, never sends automatically
- **Privacy-first**: Messages are processed locally; AI calls use anonymized context
- **Low latency**: Reply suggestions appear within 500ms
- **Customizable tone**: Formal, casual, friendly, or professional presets

## Known Issues

### QClaw not detecting WeChat
Make sure WeChat is updated to version 3.9+. Older versions use a different message protocol that QClaw cannot hook into.

### Slow suggestions in large group chats
Groups with 500+ members generate high message volume. Enable "Focus Mode" in QClaw settings to only process messages that mention you or contain keywords.

### Translation accuracy for slang
AI translation works best with standard text. For internet slang and memes, accuracy varies. We're continuously improving the slang dictionary.

For more help, visit the [troubleshooting page](https://qq-claw.org).

## Contributing

We welcome feedback and bug reports via [Issues](../../issues).

## License

MIT License - see [LICENSE](LICENSE) for details.

---
*Download, setup guide, and feature updates at [qq-claw.org](https://qq-claw.org)*
