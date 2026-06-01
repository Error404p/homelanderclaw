# Build Your Own OpenClaw

Connect your messaging apps to an AI agent that can chat, use tools, remember conversations, and run tasks autonomously — built from scratch.

## Features

* 🤖 AI Agent Gateway - Connects WhatsApp, Telegram, Discord, Slack and more to an LLM
* 🧠 Persistent Memory - Remembers context across conversations
* 🛠️ Tool Use - Agent can browse the web, manage files, write and run code
* 🔌 Model Agnostic - Works with OpenAI, Anthropic, or local Ollama models
* 🌐 Multi-platform - One gateway, multiple chat channels simultaneously

## Tech Stack

* Node.js 22+
* TypeScript
* OpenAI / Anthropic / Ollama

## Getting Started

1. Clone the repository

```
git clone https://github.com/your-username/build-your-own-openclaw.git
cd build-your-own-openclaw
```

2. Install dependencies

```
npm install
```

3. Set up environment variables

```
cp .env.example .env
```

Edit `.env` and add your API key:

```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```

4. Run the development server

```
npm run dev
```

## Project Structure

```
├── agents/     # Agent configuration and templates
├── gateway/    # Server connecting chat platforms to the agent
├── skills/     # Tools the agent can use (browser, file, search)
├── memory/     # Conversation persistence layer
└── cli/        # Command-line interface
```

## License

MIT
