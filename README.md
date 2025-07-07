# 🤖 AI Setup Agent: Full Stack AI Environment Bootstrapper for Linux

> 🎯 **Mission:** Automate. Standardize. Accelerate.  
> 🚀 **Result:** Full AI dev stack setup in minutes — not hours.

---

## 🧠 Overview

We're building a **CLI-based AI Setup Agent** that streamlines and standardizes the installation of tools, extensions, and AI service logins for Full Stack AI developers on **Linux-based systems**.

This agent is crafted to work like an intelligent assistant — walking you through a complete dev setup with minimal input and zero frustration.

---

## ✨ Why This Matters

- ⚡ **Faster onboarding** → From hours of manual setup to <10 mins
- 🧪 **Eliminates inconsistency** → All devs, same environment
- 🛠️ **No more guesswork** → Auto-install + validate everything
- 🧘 **Beginner-friendly** → Clean UX and decision flow
- 🧱 **Modular and extensible** → Built to grow with our stack

---

## 🔧 Tools It Installs & Validates

### 🖥️ Editors (Choose One)
- [Cursor](https://www.cursor.sh) (preferred for AI workflows)
- [VS Code](https://code.visualstudio.com)

### 🧩 CLI Utilities
- GitHub CLI (`gh`) with authentication

### 🤖 AI Coding Extensions
- GitHub Copilot  
- Gemini Code Assist  
- Rocode  
- Kilocode  
- Cline  
- Augment  
- Claude Code  
- Gemini CLI

### 🔐 AI Service Logins
- [Claude.ai](https://claude.ai)  
- [Grok](https://grok.x.ai)  
- [ChatGPT](https://chat.openai.com)  
- [Gemini](https://gemini.google.com)  
- [NotebookLM](https://notebooklm.google)

---

## 🧪 Features

| Feature                     | Description                                    |
|-----------------------------|------------------------------------------------|
| 🔍 Preflight Check          | Detects OS, RAM, CPU, disk, tools              |
| 🧭 Interactive CLI Agent    | Intelligent prompt-based flow                  |
| ⚙️ Auto Installer           | Installs editors, CLI tools, extensions        |
| 🔐 Secure Logins            | Prompts browser auth for AI services           |
| ✅ Environment Validator    | Verifies installs and logins                   |
| 📜 Setup Summary Report     | Generates a post-install success log           |

---

## 🌐 Distro Compatibility

| Linux Distro | Status          |
|--------------|-----------------|
| Ubuntu       | ✅ Full Support  |
| Debian       | ✅ Full Support  |
| Fedora       | 🔄 In Progress   |
| Arch Linux   | 🔄 In Progress   |
| WSL (Ubuntu) | ✅ Supported     |

---

## 📁 File Structure (Planned)
/agent/ ├── main.py # 👋 CLI entrypoint and flow control ├── preflight.py # 🔍 OS/system checks and detection ├── installer.py # ⚙️ Installs tools and editors ├── extensions.py # 🧩 Installs AI coding extensions ├── logins.py # 🔐 Triggers browser logins for services ├── validator.py # ✅ Validates setup post-install ├── report.py # 📜 Generates setup summary


---

## 🚀 Example Usage

```bash
python3 agent/main.py
➡️ The agent will:

🕵️‍♂️ Detect your Linux distro & specs
🎨 Offer choice of editor (Cursor / VS Code)
⚙️ Install necessary packages & extensions
🔐 Guide login to all AI services
🧪 Validate the entire environment
🖨️ Print a beautiful report ✅
✨ Visual Flow (Simulated Animation with Markdown)
sequenceDiagram
    participant User
    participant Agent
    User->>Agent: Run CLI
    Agent->>User: Detect system 🕵️
    Agent->>User: Choose editor 🎨
    Agent->>User: Install tools & extensions ⚙️
    Agent->>User: Browser login prompts 🔐
    Agent->>User: Validate everything ✅
    Agent->>User: Print report 📜
    ℹ️ Ready to accelerate your AI dev journey? Run the agent and get building!
