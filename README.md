

---

## ✨ Feature Highlights

**🌍 Multi-Channel Support** — One assistant, connect anywhere: DingTalk, Feishu, QQ, Discord, iMessage, Telegram, and more.

**🔒 Privacy First** — Your data stays under your control. Deploy locally or in the cloud; you own your memory and personalization.

**🛠️ Extensible Skills** — Built-in cron scheduler; custom skills auto-loaded from your workspace. No vendor lock-in.

**🧠 Smart Memory** — Context-aware conversations with long-term memory that learns from your interactions.

**🚀 Easy Setup** — Install in 3 commands or use one-click desktop app. No Python expertise required.

**🤖 Local AI** — Run models entirely on your machine with llama.cpp, MLX, or Ollama. No API keys needed.

---

## 📋 Quick Reference

### Common Commands

```bash
# Install and initialize
pip install copaw
copaw init --defaults

# Start the Console
copaw app

# Manage skills
copaw skills list
copaw skills install <skill-name>

# Manage models
copaw models download Qwen/Qwen3-4B-GGUF
copaw models

# Cron jobs
copaw cron list
copaw cron create "0 9 * * *" "Check my calendar"
```

### Magic Commands (in Console)

- `/reset` — Reset conversation context
- `/memory` — View current memory
- `/skills` — List available skills
- `/help` — Show all commands

### Get Help

- 📖 [Official Docs](https://copaw.agentscope.io/docs/)
- 💬 [GitHub Discussions](https://github.com/agentscope-ai/CoPaw/discussions)
- 🐛 [Report Issues](https://github.com/agentscope-ai/CoPaw/issues)
- 📝 [Contributing Guide](CONTRIBUTING.md)
