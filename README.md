# 🤖 AI Coding Agent

An intelligent AI-powered coding assistant built using Python and Large Language Models (LLMs) to automate software development tasks. The agent supports tool calling, project analysis, file management, shell execution, memory management, and interactive conversations for efficient coding workflows.

---

## 🚀 Features

### 🧠 Core Functionality

* Interactive and single-run execution modes
* Streaming AI responses for real-time interaction
* Multi-turn conversational support with tool calling
* Configurable LLM model selection and temperature settings

### 🛠️ Built-in Tools

* 📄 File Operations – Read, write, edit, and manage files
* 📁 Directory Operations – List directories and search files using glob patterns
* 🔍 Text Search – Pattern matching using grep
* 💻 Shell Execution – Execute terminal commands securely
* 🌐 Web Access – Search and retrieve web content
* 🧠 Memory Management – Store and retrieve contextual information
* ✅ Todo Manager – Create and manage task lists

### 📚 Context Management

* Automatic context compression near token limits
* Tool output pruning for efficient context handling
* Token usage tracking and optimization

### 🔒 Safety & Approval System

* Multiple approval modes:

  * On Request
  * Auto
  * Never
  * YOLO
* Dangerous command detection and prevention
* Secure path validation
* User confirmation for file modifications and critical operations

### 💾 Session Management

* Save and resume conversations
* Create and restore checkpoints
* Persistent session storage

### 🔌 MCP (Model Context Protocol) Integration

* Connect to external MCP servers
* Use tools provided by MCP servers
* Supports both stdio and HTTP/SSE transports

### 🤝 Subagents

* Specialized AI subagents for dedicated tasks
* Built-in agents:

  * Codebase Investigator
  * Code Reviewer
* Customizable subagent configurations with independent tool access

### 🔄 Loop Detection

* Detects repetitive execution patterns
* Prevents infinite execution loops

### 🪝 Hooks System

* Execute scripts before and after agent execution
* Execute scripts before and after tool calls
* Error handling hooks
* Support for custom automation scripts

### ⚙️ Configuration

* Configurable working directory
* Tool allowlisting
* Custom developer and user instructions
* Shell environment policies
* MCP server configuration

### 💻 User Interface

* Interactive terminal-based interface
* Real-time visualization of tool calls
* Built-in commands:

  * `/help`
  * `/config`
  * `/tools`
  * `/mcp`
  * `/stats`
  * `/save`
  * `/resume`
  * `/checkpoint`
  * `/restore`

---

## 🛠️ Tech Stack

* **Language:** Python
* **AI:** Large Language Models (LLMs)
* **CLI Framework:** Terminal Interface
* **Protocol:** Model Context Protocol (MCP)
* **Tools:** Shell, File System, Web Search, Memory Management

---

## 📂 Project Structure

```text
ai-coding-agent/
├── agent/
├── tools/
├── memory/
├── session/
├── mcp/
├── subagents/
├── hooks/
├── config/
├── cli/
└── README.md
```

---

## 🎯 Key Capabilities

* AI-assisted software development
* Intelligent code generation
* Project understanding and navigation
* File editing and management
* Automated shell command execution
* Context-aware conversations
* Modular tool integration
* Extensible architecture for custom tools and agents

---

## 🔮 Future Enhancements

* Voice-enabled coding assistant
* Web-based user interface
* Multi-agent collaboration
* Retrieval-Augmented Generation (RAG)
* IDE integration (VS Code Extension)
* Docker deployment
* Cloud-hosted API support



