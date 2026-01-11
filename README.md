# MCP Based AI Agent with Memory (Groq + LangChain)

This repository contains an **AI conversational agent** built using **MCP (Model Context Protocol)** with built-in **conversation memory**, powered by **Groq LLMs** via **LangChain**. The agent supports interactive chat, persistent context, and browser-based MCP tools through a configurable MCP client.

---

## 🚀 Features

- 🔗 MCPAgent & MCPClient integration  
- 🧠 Conversation memory (context-aware responses)  
- ⚡ Groq LLM (`gemma2-9b-it`) for fast inference  
- 🌐 MCP tool support via JSON configuration  
- 🧹 Commands to clear memory or exit chat  
- 🔐 Secure API key handling using environment variables  

---

## 🛠️ Tech Stack

- Python 3.9+
- LangChain
- Groq
- MCP (`mcp_use`)
- asyncio
- python-dotenv

---

## 📂 Project Structure

```
.
├── main.py
├── browser_mcp.json
├── .env
└── README.md
```

---

## 🔑 Environment Setup

Create a `.env` file in the root directory:

```
GROQ_API_KEY=your_groq_api_key_here
```

⚠️ Do not commit your `.env` file to GitHub.

---

## 📦 Installation

```
pip install langchain langchain-groq python-dotenv mcp-use
```

---

## ▶️ How to Run

```
python main.py
```

---

## 💬 Chat Commands

- `exit` / `quit` → End the conversation  
- `clear` → Clear conversation memory  

---

## 🧠 Memory Support

Conversation memory is enabled using:

```
memory_enabled=True
```

This allows the agent to remember previous interactions automatically.

---

## ⚙️ MCP Configuration

The MCP client loads tools from:

```
browser_mcp.json
```

Customize this file to add or modify MCP tools.

---

## 📌 Use Cases

- Context-aware AI assistants  
- MCP tool-based agents  
- Browser-augmented chatbots  
- AI research & experimentation  

---

## 👨‍💻 Author

**Abul Kalam Azad**  
### Data Science and AI Developer LinkedIn: https://www.linkedin.com/in/azad2181/

---

⭐ If you like this project, give it a star on GitHub.

