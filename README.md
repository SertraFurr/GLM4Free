# GLM4Free

A Python-only client for Z.AI (GLM) that allows you to interact with the LLM for free, requests only.

## Features

- **Python Only**: No Node.js, Selenium, or heavy dependencies.
- **Stream Support**: Real-time streaming of AI responses.
- **Thinking Mode**: Toggle "Thinking" process.
- **Web Search**: Toggle capability to search the web.
- **CLI & API**: Use it as a library or a command-line tool.

## Installation

```bash
pip install GLM4Free
```

## 🎯 Usage

## 📖 As a Library

```python
from GLM4Free.client import ZChat

# Initialize
bot = ZChat()
bot.initialize()

# Chat
print("AI: ", end="")
bot.chat("Hello! Who are you?")

# Enable Web Search
bot.use_web_search = True
bot.chat("What is the latest Python version?")
```

## 👥 CLI

You can run the chat interface directly from your terminal:

```bash
glm4free
```

## 🔧 Commands

Inside the CLI, you can use:
- `/search`: Toggle Web Search
- `/thinking`: Toggle Thinking Mode
- `/new`: Start a new conversation
- `/history`: View conversation history
- `/exit`: Quit

## 🚨Disclaimer

This is an unofficial client for educational purposes. It is not affiliated with Z.AI. Use responsibly.

## 🤝 Contributing

We welcome contributions! We are still missing upload functionality, feel free to pull request !

## 📄 License

This project is licensed under the MIT License.

## 💖 Support

If you find this project helpful:

- ⭐ Star this repository
- 🐛 Report issues
- 💡 Suggest new features
- 🤝 Contribute code

Enhanced using AI.
