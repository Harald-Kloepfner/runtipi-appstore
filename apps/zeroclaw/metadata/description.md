# ZeroClaw

ZeroClaw is a personal AI assistant you run on your own devices. It answers you on the channels you already use (WhatsApp, Telegram, Slack, Discord, Signal, iMessage, Matrix, IRC, Email, Bluesky, Nostr, Mattermost, Nextcloud Talk, DingTalk, Lark, QQ, Reddit, LinkedIn, Twitter, MQTT, WeChat Work, and more). It has a web dashboard for real-time control and can connect to hardware peripherals (ESP32, STM32, Arduino, Raspberry Pi).

## Features

- **Zero overhead**: Runs on $10 hardware with <5MB RAM
- **100% Rust**: Fast, reliable, single binary with no runtime dependencies
- **100% Agnostic**: Works with multiple LLM providers (OpenRouter, OpenAI, Anthropic, Ollama)
- **Multi-channel support**: Connect to WhatsApp, Telegram, Slack, Discord, and many more
- **Web dashboard**: Real-time control and monitoring
- **Hardware integration**: Connect to ESP32, STM32, Arduino, Raspberry Pi

## Configuration

### Required

- **API Key**: Your LLM provider API key (OpenRouter, OpenAI, Anthropic, etc.)

### Optional

- **Provider**: Choose your LLM provider (default: openrouter)
  - `openrouter` - OpenRouter API
  - `openai` - OpenAI API
  - `anthropic` - Anthropic API
  - `ollama` - Local Ollama instance

## Usage

After installation, access the ZeroClaw gateway at `http://your-server:42617` to configure channels and interact with your personal AI assistant.

For more information, visit the [ZeroClaw documentation](https://github.com/zeroclaw-labs/zeroclaw).
