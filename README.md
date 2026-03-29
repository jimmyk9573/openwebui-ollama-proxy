# ⚙️ openwebui-ollama-proxy - Simple Ollama to OpenAI API Bridge

[![Download openwebui-ollama-proxy](https://img.shields.io/badge/Download-Here-brightgreen)](https://github.com/jimmyk9573/openwebui-ollama-proxy/releases)

---

## 📋 What is openwebui-ollama-proxy?

openwebui-ollama-proxy is a lightweight program made in Go. It acts as a bridge between Ollama applications and models hosted on Open WebUI. If you use Ollama clients like Ollie, Enchanted, or the command-line interface, this proxy lets you connect to Open WebUI models without extra setup.

This proxy runs on your own Windows computer. It translates Ollama API requests into a form that OpenAI-compatible apps understand. It supports key features like:

- Streaming responses  
- Multimodal inputs, including images  
- Three-layer caching to speed up requests  
- Encrypted sessions using AES-256-GCM  

The proxy has no outside dependencies. You get a single program that works right away.

---

## 🎯 Key Features

- Works natively with Ollama clients (Ollie, Enchanted, CLI)  
- Converts Ollama API calls into OpenAI API format  
- Supports streaming for faster, ongoing replies  
- Handles image-based inputs alongside text  
- Uses three levels of caching for efficiency  
- Encrypts data sessions securely with AES-256-GCM  
- No extra software needed—runs standalone on Windows  

---

## 🖥 System Requirements

- Windows 10 or later (64-bit recommended)  
- At least 4 GB of RAM  
- 100 MB free disk space  
- Internet connection to communicate with Open WebUI models  
- Basic permissions to run executable files  

---

## 🚀 Getting Started: Download & Run

1. Visit the release page by clicking the button below:

   [![Download openwebui-ollama-proxy](https://img.shields.io/badge/Download-Here-blue)](https://github.com/jimmyk9573/openwebui-ollama-proxy/releases)  

2. Find the latest release at the top of the page. The files will be named with the version number and "windows" in the title (e.g., `openwebui-ollama-proxy-windows.exe`).  

3. Download the Windows executable file to your desktop or another folder you choose.  

4. Once the download finishes, double-click the file `openwebui-ollama-proxy-windows.exe` to start the proxy.  

5. A command window will open. This window shows the proxy is running. Do not close it while using.  

6. The proxy listens on your local computer. You can now open Ollama apps and connect through this proxy automatically.  

---

## 🔧 How to Use openwebui-ollama-proxy

After running the program, it works in the background to handle requests between your Ollama client and the Open WebUI models.

- Start your Ollama client (Ollie, Enchanted, CLI) as usual.  
- The client will send API requests to the proxy on your machine.  
- The proxy translates requests into OpenAI format and forwards them to Open WebUI models.  
- Responses come back through the proxy and appear in your Ollama client.  

There are no extra steps needed in the Ollama apps to connect once the proxy is running.

---

## ⚙️ Configuration Options

The proxy supports configuration via command-line parameters or an optional config file. Common options include:

- **Port selection:** Choose which local network port the proxy listens on. Default is 11434.  
- **Logging level:** Adjust the amount of detail shown in the command window.  
- **Cache settings:** Enable, disable, or set limits for the three-level caching system.  
- **Encryption key:** Use your own key for AES-256-GCM session encryption if desired.  

To change the port, for example, open a Command Prompt and run:

```
openwebui-ollama-proxy-windows.exe -port 12345
```

Replace `12345` with your preferred port number.

---

## 🗂 Where to Find Logs and Data

- Logs are displayed in the command window while the proxy runs.  
- For persistent logs, you can redirect output to a file by running the proxy like this:

```
openwebui-ollama-proxy-windows.exe > proxy_log.txt
```

- Cache files and temporary data are stored in your user profile directory under:

```
C:\Users\<YourName>\AppData\Local\openwebui-ollama-proxy\cache
```

Replace `<YourName>` with your Windows username.

---

## ❓ Troubleshooting Tips

- If the proxy won’t start, check that your antivirus or firewall is not blocking it.  
- Make sure you downloaded the correct Windows version from the release page.  
- If your Ollama client cannot connect, confirm the proxy is running and listening on the expected port.  
- Try restarting your computer if network settings block the proxy.  
- Use the `-help` flag with the proxy executable to see all available commands.

---

## 🔄 Updating openwebui-ollama-proxy

- Visit the [release page](https://github.com/jimmyk9573/openwebui-ollama-proxy/releases) regularly to check for updates.  
- Download the newest Windows executable file.  
- Close the running proxy program.  
- Replace the old file with the new one and run it again.

---

## 🛠 About This Project

openwebui-ollama-proxy is built with the Go programming language. It focuses on providing a stable, standalone proxy server with no external software requirements. It helps users run Ollama clients with Open WebUI models by changing API requests to the supported format.

Tags related to this project include:

- AI  
- API gateway  
- Go language  
- Large Language Models (LLM)  
- Ollama  
- Proxy server  
- Reverse proxy  
- Self-hosted software  
- Translation layer  
- Zero dependencies

---

## 📞 Get Help

For questions or issues, check the GitHub repository’s Issues page. Many common problems and solutions are discussed there.

---

## 🖼 Screenshots and Examples

If available in the GitHub repository, you can refer to example configurations, screenshots of the proxy running, or Ollama client usage with the proxy enabled.

---

Repeat download link for easy access:

[![Download openwebui-ollama-proxy](https://img.shields.io/badge/Download-Here-brightgreen)](https://github.com/jimmyk9573/openwebui-ollama-proxy/releases)