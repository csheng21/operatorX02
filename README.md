<div align="center">
  <h1>⚡ Operator X02 ⚡</h1>
  <p><strong>Code Your Vision. Build Your Dream.</strong></p>
  <p>An open-source, 100% local AI IDE with boundless memory and multi-agent intelligence.</p>

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Windows Support](https://img.shields.io/badge/Windows-10%2F11-blue)](https://github.com/csheng21/operatorX02/releases)
  [![Beta Release](https://img.shields.io/badge/Beta-v1.0.0-orange)](https://github.com/csheng21/operatorX02/releases/tag/v1.0.0-beta)
  [![Downloads](https://img.shields.io/github/downloads/csheng21/operatorX02/total)](https://github.com/csheng21/operatorX02/releases)

  <h3>
    <a href="https://www.operatorx02.com/">Website</a> •
    <a href="https://github.com/csheng21/operatorX02/releases/tag/v1.0.0-beta">Download Beta</a> •
    <a href="#-key-features">Features</a> •
    <a href="#-quick-start">Quick Start</a> •
    <a href="#-roadmap">Roadmap</a>
  </h3>
</div>

---

## 🎯 The Problem

Other AI coding tools forget your project after one session. You constantly have to re-explain your architecture, past decisions, and code patterns. Your data goes to the cloud, and customization is limited.

## ✨ The Solution: Operator X02

An AI-native IDE where the assistant **truly remembers**. It's the first development environment built with:

*   **🧠 Boundless Memory**: Ask "What did we fix last week?" and the AI recalls the exact conversation, code, and commit—all stored **locally**.
*   **🤖 Multi-Agent Team**: Assign roles: Architect, Developer, Reviewer. They collaborate autonomously to plan, code, and review.
*   **🔒 100% Local & Private**: No account, no telemetry, no cloud. Your code never leaves your machine.
*   **🔄 VCS Aware**: Deep integration with Git & SVN. The AI understands your version control state.
*   **📚 Multi-File Autonomous Coding**: AI modifies multiple files at once with a clear visual diff.
*   **🔌 Built for Embedded Dev**: Native support for Arduino, ESP32, STM32 with one-click compile and serial monitor.

## 🖼️ Preview

> *"Yesterday we fixed the JWT token expiry bug in auth.ts..."* — AI recalls context from a previous session automatically.

*(Consider adding a GIF or screenshot here showing the multi-agent panel or the memory recall demo)*

## ⚡ Key Features

| Feature | Description |
| :--- | :--- |
| **Boundless Memory** | Unlimited, local project history. AI gets smarter with every session. |
| **Multi-Agent Roles** | 8 specialized roles (Architect, Developer, Reviewer, Debugger, etc.). |
| **Provider Calibration** | Fine-tune which AI model handles which task. |
| **8 Quick Actions** | Select code → Click ⚡ → Explain, Optimize, Refactor, Test, Document, and more. |
| **VCS Integration** | Native Git & SVN awareness. Ask "what changed?" and get real diffs. |
| **Project Analysis** | One-click understanding of your entire codebase structure. |
| **Embedded Support** | Arduino, ESP32, STM32. Compile and monitor from within the IDE. |
| **MISRA C Ready** | Support for safety-critical development workflows. |
| **Full Customization** | Open source (MIT). Fork it, modify prompts, change the UI—everything is yours. |

## 📥 Quick Start (Windows Beta)

Getting started takes **less than 2 minutes**:

### 🚀 **One-Click Install**

1. **⬇️ Download** the installer from our **[Releases page](https://github.com/csheng21/operatorX02/releases/tag/v1.0.0-beta)** (`.msi` or `.exe` file)
2. **🖱️ Double-click** the downloaded file
3. **✅ Follow** the installation wizard (just click "Next" a few times)
4. **🎉 Launch** Operator X02 from your Start Menu or Desktop shortcut

That's it. You're ready to go.

### ⚙️ **Configure AI** — Choose Your Path

| Path | What It Means | Setup Time |
| :--- | :--- | :--- |
| **🟢 Default (Zero Setup)** | X02 comes with **built-in Operator X02 API** — just start coding. No keys required. | **0 seconds** |
| **🔑 Bring Your Own Keys** | Use your existing accounts: OpenAI, Anthropic, Gemini, DeepSeek, Groq, and more. | ~60 seconds |
| **🖥️ 100% Local & Offline** | Connect to **Ollama** for complete offline mode. Air-gap ready. | ~2 minutes |

**Most users can just click "Next" and start coding immediately.** The built-in API means you don't need to configure anything.

### 💾 **Important: Memory Storage**

> **By default, Operator X02 uses temporary storage** — your chat history and AI memory will be cleared if you reset the IDE.

To keep your memory forever:
- Go to **IDE Settings → Storage**
- Enable **"Permanent Local Storage"**
- Choose a folder on your PC to store all project memories

Once enabled, your AI will remember everything **forever** — across sessions, restarts, and even computer reboots.

### ✅ System Requirements

- Windows 10 or 11 (64-bit)
- WebView2 Runtime (usually pre-installed on modern Windows)

## 🗺️ Roadmap

- **February 15, 2026**: Public Beta v1.0.0 (Windows `.msi`/`.exe`) - **YOU ARE HERE** 🎉
- **March 15, 2026**: Full Source Code Release (MIT License) & production-ready build
- **Q2 2026**: macOS & Linux support
- **Q3 2026**: Plugin ecosystem & community templates

## 🤝 How to Contribute

We're just getting started! While the full source code is coming March 15, you can still help:

| Area | How to Help |
| :--- | :--- |
| **🐛 Report Bugs** | Found an issue? Open a [GitHub Issue](https://github.com/csheng21/operatorX02/issues). |
| **💡 Suggest Features** | Have an idea? Share it in [Discussions](https://github.com/csheng21/operatorX02/discussions). |
| **📢 Spread the Word** | Star the repo, share on Twitter, or write a blog post. |
| **🎨 Design Feedback** | Love or hate the UI? We'd love to hear your thoughts. |
| **📝 Documentation** | Help us improve guides and examples. |

## ❓ Frequently Asked Questions

**Q: Is this really free?**  
A: Yes! Operator X02 is and will always be free. It's open-source under the MIT license. The built-in Operator X02 API is also free during beta.

**Q: Where is my data stored?**  
A: **Entirely on your local machine**. No cloud, no telemetry, no tracking. Even when using the built-in API, your code and conversations stay local—only anonymized prompts are sent.

**Q: Will my AI memory persist after I close the IDE?**  
A: **By default, memory is temporary** and will clear if you reset the IDE. To enable **permanent memory**, go to IDE Settings → Storage and select "Permanent Local Storage." Choose a folder on your PC, and your AI will remember everything forever.

**Q: Do I need to create an account?**  
A: **No.** Zero. Zilch. No sign-up, no email, no login. Just install and code.

**Q: Can I use it 100% offline?**  
A: Absolutely. Connect to Ollama for a completely offline, air-gapped experience.

**Q: When will macOS/Linux versions be available?**  
A: Planned for Q2 2026, after the March 15 full source release.

**Q: The beta is only an `.exe`/`.msi`. Where is the source code?**  
A: To ensure a stable first release, we're focusing on the Windows build first. The **full source code for this version will be published on March 15, 2026**.

**Q: What if I hit rate limits on the built-in API?**  
A: The built-in Operator X02 API is designed for generous personal use during beta. For heavy usage, we recommend adding your own API keys.

## 📄 License

MIT License. Use it, modify it, make it yours.


---

<div align="center">
  <p>Built with ❤️ by <a href="https://github.com/csheng21">HengCS</a> and the community.</p>
  <p>
    <a href="https://www.operatorx02.com/">Official Website</a> •
    <a href="https://github.com/csheng21/operatorX02/releases">Downloads</a> •
    <a href="https://github.com/csheng21/operatorX02/issues">Issues</a> •
    <a href="https://github.com/csheng21/operatorX02/discussions">Discussions</a>
  </p>
  <p>⭐ Star us on GitHub — it helps others discover the project! ⭐</p>
</div>
