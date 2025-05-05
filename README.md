[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/txbm-mcp-local-dev-badge.png)](https://mseep.ai/app/txbm-mcp-local-dev)

# 🚀 MCP Local Dev

Let AI handle your local development environments while you focus on building amazing things!

<div align="center">
  <video src="https://github.com/user-attachments/assets/cec79cde-0881-4773-a289-49bb86f14449" width="1920" />
</div>


## ✨ What's This?

A local development environment manager that lets LLMs configure and manage dev environments for you. Built for AI assistants to handle environment setup, dependency management, and testing automatically.

## 🏃 Quick Start

1. Install Claude Desktop from the [MCP quickstart guide](https://modelcontextprotocol.io/quickstart/user)
2. Add the following to your Claude Desktop config:

```json
{
  "servers": {
     "local_dev": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/txbm/mcp-local-dev@main",
        "mcp-local-dev"
      ]
    }
  }
}
```

3. Point Claude at any GitHub repository and ask it to set up a dev environment!
<img width="636" alt="Screenshot 2025-01-06 at 10 06 14 PM" src="https://github.com/user-attachments/assets/c137d1d8-a61a-4a8d-9633-b89b61524cae" />

4. Have it run the tests and report coverage!
<img width="622" alt="Screenshot 2025-01-06 at 10 06 52 PM" src="https://github.com/user-attachments/assets/e9db66d2-0e86-417c-af75-97e46f274b3e" />

5. Have a discussion, poke around or clean it up if you're done!
<img width="648" alt="Screenshot 2025-01-06 at 10 07 24 PM" src="https://github.com/user-attachments/assets/0d6118a0-f00e-49d3-90e9-c7ec2d654247" />

## 🎯 Core Features

### Test Runners
- 🧪 pytest with coverage reporting
- ⚡️ Vitest with V8 coverage
- 🃏 Jest with detailed coverage metrics
- 🔬 unittest with coverage support

### Runtime Support 
- 🐍 Python with UV package management
- 📦 Node.js with NPM
- ⚡️ Bun runtime and package manager

### Environment Management
- 🏗️ Automatic runtime detection
- 📦 Smart package manager selection
- 🔒 Sandboxed environments
- 🧹 Automatic cleanup
- 🔄 GitHub repository support
- 📂 Local project support

### Developer Experience
- 🎯 Zero configuration needed
- 📊 Structured JSON logging
- 🔍 Detailed test coverage metrics
- 🛡️ Isolated environments per project


## 💫 Under the Hood

- **MCP Server Spec**: Full compliance with comprehensive test coverage
- **Path Isolation**: Each environment is neatly contained
- **System Integration**: Uses your installed runtimes (Python, Node.js, Bun)
- **Package Management**: Automatically selects fastest available package manager for each runtime
- **Network Access**: Full connectivity for package management
- **Process Handling**: Native system processes for maximum speed

## 🌟 Behind the Scenes

Development involved rigorous testing across multiple models:
- 🏆 Claude 3.5 Sonnet: Crushed it
- 💪 DeepSeek V3: Strong performer
- 👎 O1: Not great, Bob

## 🚀 Key Takeaways

This project demonstrates the incredible potential of AI-assisted development:
- 🏃‍♂️ Lightning fast prototyping
- 🎯 That last 15% is still where the real work happens
- 📚 Great example of real-world AI development patterns

## 💭 A Note on AI & Development

As someone who's spent years in software development, what's exciting about this project isn't just automation - it's the shift in how we interact with development environments. The value isn't in replacing human developers, but in reducing cognitive overhead. When AI handles environment setup and maintenance, developers can focus more on architecture and design decisions.

This project demonstrates that AI isn't just about generating code - it's about managing complexity. By handling the mechanical aspects of development environment setup, we free up mental bandwidth for the creative and architectural challenges that truly need human insight.

## 🙏 Big Thanks To

- [UV](https://github.com/astral-sh/uv) - Speed demon Python package installer
- [Aider](https://github.com/paul-gauthier/aider) - Your AI pair programming buddy
- [Anthropic](https://www.anthropic.com) - For Claude's assistance in development
- [Helix Editor](https://helix-editor.com/) - Modal editing at its finest

## 📄 License

MIT
