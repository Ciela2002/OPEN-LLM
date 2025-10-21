================================================================================
  OLLM v1.0.0 - Open LLM Chat Client
  Lightning-Fast AI Chat for Windows
================================================================================

Thank you for downloading OLLM!

OLLM is a blazingly fast, lightweight desktop chat client for Large Language 
Models, built entirely in Rust. Designed to be intuitive and easy to use, 


================================================================================
  WHY OLLM?
================================================================================

✨ LIGHTNING FAST
   Built with Rust for maximum performance and minimal resource usage.
   Start chatting in seconds, not minutes.

🎯 SUPER INTUITIVE
   Clean, modern interface that just works. No complicated setup,
   no confusing menus. Just open and chat.

💬 MULTIPLE CONVERSATIONS
   Manage unlimited chat sessions. Switch between conversations,
   rename them, or start fresh anytime.

📝 CODE-FRIENDLY
   Automatic code block detection with syntax highlighting and
   one-click copy. Perfect for developers.

🌐 UNIVERSAL COMPATIBILITY
   Works with OpenAI, OpenRouter, local models, and any
   OpenAI-compatible API. Your choice, your control.

🔒 PRIVACY FIRST
   All data stored locally on your computer. No cloud sync,
   no tracking, no telemetry. Your conversations stay yours.

================================================================================
  INSTALLATION
================================================================================

OPTION 1: INSTALLER (Recommended)
  1. Run OLLM-1.0.0-Setup.exe
  2. Follow the installation wizard
  3. Launch OLLM from Start Menu or Desktop shortcut

OPTION 2: PORTABLE
  1. Extract OLLM-1.0.0-Windows-Portable.zip
  2. Run llmite.exe
  3. No installation required!

================================================================================
  QUICK START GUIDE
================================================================================

STEP 1: CONFIGURE YOUR API
  1. Open OLLM
  2. Go to Settings tab (⚙️)
  3. Enter your API endpoint (e.g., https://api.openai.com/v1)
  4. Enter your API key
  5. Click "🔄 Load Available Models"

STEP 2: SELECT A MODEL
  1. Choose a model from the dropdown list
  2. Or enable "Use custom model ID" for specific models

STEP 3: START CHATTING!
  1. Go to Chat tab (💬)
  2. Type your message
  3. Press Enter or click "📤 Send"
  4. Enjoy lightning-fast responses!

================================================================================
  KEY FEATURES
================================================================================

💬 CHAT INTERFACE
   • Multiple chat sessions with history
   • Create, rename, and delete conversations
   • Auto-scroll to latest messages
   • Search through chat history
   • All conversations saved locally

📝 CODE RENDERING
   • Automatic code block detection
   • Syntax highlighting for all languages
   • One-click copy to clipboard
   • Horizontal scroll for long lines
   • Dark theme optimized for code

⚙️ ADVANCED SETTINGS
   • Temperature control (0.0 - 2.0)
   • Max tokens adjustment (1 - 8192)
   • Custom model IDs
   • Multiple API provider support
   • Persistent configuration

🌐 LOCAL PROXY SERVER
   • Start a local OpenAI-compatible API server
   • Use OLLM as a proxy for other applications
   • Default: http://127.0.0.1:8080
   • Perfect for integrating with other tools

🎨 USER INTERFACE
   • Modern dark theme
   • Minimalist design
   • Collapsible sidebar
   • Responsive layout
   • Keyboard shortcuts (Enter to send, Shift+Enter for new line)

================================================================================
  SYSTEM REQUIREMENTS
================================================================================

Operating System: Windows 10/11 (64-bit)
RAM: 100 MB minimum
Disk Space: 10 MB
Internet: Required for API calls
Other: API key from your LLM provider

================================================================================
  SUPPORTED PROVIDERS
================================================================================

✓ OpenAI (GPT-4, GPT-3.5, etc.)
✓ OpenRouter (Access to 100+ models)
✓ Anthropic Claude (via OpenRouter)
✓ Google Gemini (via OpenRouter)
✓ Local models (Ollama, LM Studio, etc.)
✓ Any OpenAI-compatible API

================================================================================
  CONFIGURATION FILES
================================================================================

All your data is stored locally at:
  %APPDATA%\llmite\

Files:
  • config.json - Your API settings and preferences
  • chat_history.json - All your conversations

To backup your data, simply copy this folder!
To reset OLLM, delete this folder and restart.

================================================================================
  KEYBOARD SHORTCUTS
================================================================================

Chat:
  Enter           - Send message
  Shift + Enter   - New line in message
  Ctrl + L        - Clear current chat

Navigation:
  Ctrl + 1        - Go to Chat tab
  Ctrl + 2        - Go to Settings tab

================================================================================
  USING THE PROXY SERVER
================================================================================

OLLM includes a built-in proxy server that makes your configured LLM
accessible to other applications:

1. Go to Settings → Local Proxy Server
2. Set host (default: 127.0.0.1) and port (default: 8080)
3. Click "▶ Start Server"
4. Use http://127.0.0.1:8080/v1 in other apps

Available Endpoints:
  • GET  /health - Health check
  • GET  /v1/models - List available models
  • POST /v1/chat/completions - Chat completions

Perfect for:
  • Using OLLM with VS Code extensions
  • Integrating with custom scripts
  • Testing API calls locally
  • Centralizing API key management

================================================================================
  TROUBLESHOOTING
================================================================================

Q: OLLM won't start
A: Make sure you have Windows 10/11 64-bit. Try running as administrator.

Q: Can't connect to API
A: Check your internet connection and verify your API key is correct.

Q: Models won't load
A: Ensure your API endpoint is correct and your API key has proper permissions.

Q: Chat history disappeared
A: Check %APPDATA%\llmite\ folder. Your data might be there.

Q: High memory usage
A: Close unused chat sessions. Each session stores full conversation history.

Q: Code blocks not rendering
A: Make sure the AI response includes proper markdown code blocks (```).

================================================================================
  GETTING HELP
================================================================================

GitHub: https://github.com/Ciela2002/OLLM
Issues: https://github.com/Ciela2002/OLLM/issues
Email: nanaciel2002@proton.me

Found a bug? Have a feature request? Open an issue on GitHub!

================================================================================
  LICENSE & CREDITS
================================================================================

OLLM is open-source software licensed under the MIT License.
Copyright (c) 2025 Ciela2002

Built with:
  • Rust - Systems programming language
  • egui - Immediate mode GUI framework
  • tokio - Async runtime
  • reqwest - HTTP client
  • warp - Web server framework

Special thanks to the Rust community and all open-source contributors!

================================================================================
  VERSION HISTORY
================================================================================

v1.0.0 (2025-10-21) - Initial Release
  • Multiple chat sessions with history
  • Code block rendering with syntax highlighting
  • Local proxy server
  • Persistent settings
  • Dark theme UI
  • Temperature and token controls

================================================================================

Thank you for using OLLM! 🚀

If you find OLLM useful, please consider:
  ⭐ Starring the project on GitHub
  🐛 Reporting bugs and issues
  💡 Suggesting new features
  🤝 Contributing to the project

Happy chatting!

================================================================================

