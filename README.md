<div align="center">
  <h1>📡 Awesome Agent Communication</h1>
  <p>A curated list of tools, platforms, and SDKs for connecting AI agents to the world — phone calls, SMS, messaging apps, and beyond.</p>

  [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
</div>

---

> **50+ tools across 7 categories.** Everything you need to give your AI agent a voice, a phone number, or a presence on messaging platforms.

---

## Contents

- [Telephony & Voice APIs](#-telephony--voice-apis) — Phone numbers, voice calls, SMS
- [Voice Agent Platforms](#-voice-agent-platforms) — Turnkey voice AI infrastructure
- [Messaging Platforms](#-messaging-platforms) — WhatsApp, Telegram, Discord, Slack
- [Multi-Channel Agent Hubs](#-multi-channel-agent-hubs) — One agent, every platform
- [Open-Source Voice & Audio](#-open-source-voice--audio) — STT, TTS, conversation
- [Protocols & Standards](#-protocols--standards) — MCP, A2A, agent-to-agent
- [Learning Resources](#-learning-resources)

---

## 📞 Telephony & Voice APIs

*Give your AI agent a real phone number. Programmable voice, SMS, and calling infrastructure.*

| Tool | Description | Pricing |
|------|-------------|---------|
| [AgentLine](https://agentline.cloud) | Open-source telephony API purpose-built for AI agents. Phone numbers, voice calls, SMS, MCP server, LangChain integration, skill-based install. Works with OpenClaw, Hermes, Claude Code, and any LLM. | $2/number, $0.10/min |
| [Twilio](https://twilio.com) | General-purpose cloud communications platform. Voice, SMS, video, WhatsApp API. Requires managing WebSocket streams for AI integration. | Pay-as-you-go |
| [SignalWire](https://signalwire.com) | Twilio-compatible API with open-source core. AI agent support via SWAIG and Relay. | Pay-as-you-go |
| [Vonage](https://vonage.com) | Voice, SMS, video APIs. Nexmo heritage. AI studio for building conversational agents. | Pay-as-you-go |
| [Telnyx](https://telnyx.com) | Carrier-grade voice and SMS. AI call control, real-time transcription APIs. | Pay-as-you-go |
| [Plivo](https://plivo.com) | Cloud API platform for voice and SMS. Simple pricing, global coverage. | Pay-as-you-go |

## 🎙 Voice Agent Platforms

*Turnkey infrastructure for building voice-enabled AI agents. Sub-300ms latency, natural conversation.*

| Platform | Description | Pricing |
|----------|-------------|---------|
| [Vapi](https://vapi.ai) | Developer-first voice AI. Low-latency, model-agnostic. Handles STT, TTS, and conversation flow. | Usage-based |
| [Bland AI](https://bland.ai) | Outbound call automation platform. CRM integration, SOC2/HIPAA compliant. | Usage-based |
| [Retell AI](https://retellai.com) | Human-like voice agents. Multi-language, telephony integration built-in. | Usage-based |
| [ElevenLabs](https://elevenlabs.io) | Industry benchmark for voice AI. Conv AI 2.0 — RAG, multimodal, batch calling. 75ms latency. HIPAA. | Free / $5+/mo |
| [Synthflow](https://synthflow.ai) | No-code voice agents for SMBs. Pre-built templates, easy deployment. | From $29/mo |
| [Voiceflow](https://voiceflow.com) | No-code voice and chat builder. Drag-and-drop conversation design. | Free / $50+/mo |
| [PolyAI](https://poly.ai) | Enterprise voice agents. Natural multi-turn conversation. Hospitality and retail focus. | Enterprise |
| [HeyGen](https://heygen.com) | AI avatars with voice. Real-time interactive streaming. | From $24/mo |
| [Deepgram](https://deepgram.com) | STT and TTS APIs. Sub-300ms latency. Nova-3 model for real-time. | Usage-based |
| [AssemblyAI](https://assemblyai.com) | STT with diarization, sentiment analysis, entity detection, summarization. | Usage-based |

## 💬 Messaging Platforms

*Connect your AI agent to messaging apps where users already are.*

| Platform | Description | Pricing |
|----------|-------------|---------|

| [API-Supp](https://api-supp.com) | WhatsApp REST API and OAuth MCP for existing numbers via QR (unofficial bridge, not Meta's Cloud API). Multi-number cloud MCP for text and chat context; separate local MCP adds files, voice notes, media downloads; signed webhooks. | Paid, $7.50/number/month |
| [WhatsApp Cloud API](https://developers.facebook.com/docs/whatsapp/cloud-api) | Meta's official API. Send/receive messages, templates, media. Free tier available. | Free / Pay-per-conversation |
| [Telegram Bot API](https://core.telegram.org/bots/api) | Free, feature-rich bot API. Inline queries, keyboards, payments, webhooks. | Free |
| [Discord API](https://discord.com/developers/docs/intro) | Bot and webhook APIs. Slash commands, message components, voice channels. | Free |
| [Slack API](https://api.slack.com) | Bot users, slash commands, interactive messages. Block Kit for rich UIs. | Free |
| [Signal](https://signal.org) | End-to-end encrypted messaging. Signal-CLI for automation. | Free |
| [Facebook Messenger](https://developers.facebook.com/docs/messenger-platform) | Bot API for Messenger. Templates, quick replies, persistent menus. | Free |
| [iMessage (Messages API)](https://developer.apple.com/messages/) | Apple Messages for Business. Rich links, interactive messages. | Apple Developer |
| [Matrix](https://matrix.org) | Open federated protocol. Bridges to other platforms. Element clients. | Free (self-hosted) |

## 🌐 Multi-Channel Agent Hubs

*One agent, every platform. Deploy once, reach users everywhere.*

| Platform | Description | Pricing |
|----------|-------------|---------|
| [OpenClaw](https://github.com/openclaw/openclaw) | Self-hosted agent runtime across WhatsApp, Telegram, Slack, Discord, Signal. 5,700+ community skills. 188k GitHub stars. | Free (OSS) |
| [Hermes Agent](https://github.com/nousresearch/hermes-agent) | Nous Research's agent with native WhatsApp, Telegram, and webhook connectivity. Persistent memory, skills system, cron scheduler. | Free (OSS) |
| [Meta AI](https://meta.ai) | Llama-powered AI built into WhatsApp, Messenger, and Instagram. Native platform integration. | Free |
| [Coze](https://coze.com) | ByteDance's agent builder. Deploy to Telegram, Discord, Slack, web widgets. Visual workflow builder. | Free / Paid |
| [Botpress](https://botpress.com) | Open-source conversational AI platform. Deploy to WhatsApp, Telegram, Messenger, web. Visual flow builder. | Free / Cloud |
| [Rasa](https://github.com/RasaHQ/rasa) | OSS conversational AI framework. NLU-based. Deploy anywhere. Enterprise CALM add-on for generative. | Free (OSS) |

## 🔊 Open-Source Voice & Audio

*Build your own voice pipeline. STT, TTS, conversation orchestration.*

| Tool | Description |
|------|-------------|
| [LiveKit Agents](https://github.com/livekit/agents) | OSS framework for real-time voice/video AI agents. Python and TypeScript. |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | OSS framework for voice and multimodal conversational AI. Python. |
| [Vocode](https://github.com/vocodedev/vocode-python) | OSS library for building voice-based LLM agents. Handles STT → LLM → TTS pipeline. |
| [Whisper](https://github.com/openai/whisper) | OpenAI's open-source speech recognition. Multilingual, robust. |
| [Coqui TTS](https://github.com/coqui-ai/TTS) | Open-source text-to-speech. 100+ languages, voice cloning. |
| [Piper](https://github.com/rhasspy/piper) | Fast, local neural TTS. Runs on Raspberry Pi. 100+ voices. |
| [Faster Whisper](https://github.com/SYSTRAN/faster-whisper) | CTranslate2-based Whisper. 4x faster, lower memory. |
| [OpenVoice](https://github.com/myshell-ai/OpenVoice) | Instant voice cloning. Granular control over tone, emotion, accent. |

## 📋 Protocols & Standards

*Standards for agent communication and interoperability.*

| Standard | Description |
|----------|-------------|
| [MCP (Model Context Protocol)](https://modelcontextprotocol.io) | Anthropic's open protocol for AI-tool integration. Server/client architecture. |
| [A2A (Agent-to-Agent)](https://github.com/google/A2A) | Google's open protocol for agent-to-agent communication and task delegation. |
| [Agent Protocol](https://github.com/AI-Engineer-Foundation/agent-protocol) | Standard API interface for AI agents. Interoperability across frameworks. |
| [AGNTCY](https://github.com/agntcy) | Cisco-led open-source project for agentic workflow orchestration. |
| [WhatsApp Cloud API](https://developers.facebook.com/docs/whatsapp/cloud-api) | De facto messaging standard. Used by most multi-channel AI platforms. |

## 📚 Learning Resources

- [AgentLine Blog](https://agentline.cloud/blogs) — Tutorials on giving AI agents phone numbers
- [OpenClaw Documentation](https://docs.openclaw.ai) — Multi-platform agent deployment
- [Hermes Agent Docs](https://hermes-agent.nousresearch.com/docs) — WhatsApp/Telegram connectivity
- [Vapi Documentation](https://docs.vapi.ai) — Voice AI development guides
- [ElevenLabs Docs](https://elevenlabs.io/docs) — Conversational AI guides
- [Telegram Bot API Docs](https://core.telegram.org/bots/api) — Build bots for Telegram
- [WhatsApp Cloud API Docs](https://developers.facebook.com/docs/whatsapp/cloud-api) — Official Meta docs
- [Discord Developer Portal](https://discord.com/developers/docs) — Build Discord bots

---

## Contributing

Contributions welcome! Please see the [contribution guidelines](CONTRIBUTING.md).

Add tools by submitting a PR — keep entries alphabetical within each category. Include the tool name, link, brief description, and pricing model.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this work.
