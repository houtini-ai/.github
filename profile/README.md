# Houtini

<div align="center">
  <img src="https://raw.githubusercontent.com/houtini-ai/.github/refs/heads/main/houtini-logo.jpg" alt="Houtini Logo" height="240">
  
  <h3>Your AI's Local Superpower</h3>
  <p>Transform your development workflow with unlimited local AI processing</p>
  
  <p><a href="https://github.com/houtini-ai/lm/blob/main/docs/user-guide-md.md">
    <img src="https://img.shields.io/badge/🚀_Get_Started-0066FF?style=for-the-badge" alt="Get Started">
  </a>
  <a href="https://github.com/houtini-ai/lm">
    <img src="https://img.shields.io/badge/📦_@houtini/lm-00CC88?style=for-the-badge" alt="Main Package">
  </a>
  <a href="https://github.com/houtini-ai/lm/blob/main/docs/user-guide-md.md">
    <img src="https://img.shields.io/badge/📚_Documentation-4A90E2?style=for-the-badge" alt="Documentation">
  </a></p>
<hr>
<p><a href="https://github.com/houtini-ai/lm/blob/main/docs/analysis-functions-md.md">
  <img src="https://img.shields.io/badge/🔍_Analysis_Functions-9B59B6?style=for-the-badge" alt="Analysis Functions">
</a>
<a href="https://github.com/houtini-ai/lm/blob/main/docs/generation-functions-md.md">
  <img src="https://img.shields.io/badge/⚡_Code_Generation-E74C3C?style=for-the-badge" alt="Code Generation">
</a>
<a href="https://github.com/houtini-ai/lm/blob/main/docs/custom-functions-md.md">
  <img src="https://img.shields.io/badge/🎯_Custom_Prompting-F39C12?style=for-the-badge" alt="Custom Prompting">
</a></p>
</div>

<br>

<div align="center">
  <a href="https://github.com/houtini-ai/lm/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/houtini-ai/lm" alt="License">
  </a>
  <a href="https://github.com/houtini-ai/lm/stargazers">
    <img src="https://img.shields.io/github/stars/houtini-ai/lm?style=social" alt="GitHub Stars">
  </a>
  <a href="https://www.npmjs.com/package/@houtini/lm">
    <img src="https://img.shields.io/npm/dt/@houtini/lm" alt="NPM Downloads">
  </a>
</div>

---

## Why Houtini?

**Building with Claude?** Stop that pesky thread length hard stop in Claude Desktop threads and offload routine tasks to your local LLM on LM Studio to assist with API call efficiency routine tasks. Houtini handles code analysis, generation, and documentation locally so you can focus on architecture and creative problem-solving. Houtini-LM is a revolution for coders, vibe coders and anyone with a GPU who is curious about building the things they never thought they could. Using our custom expert prompt library (we're adding to it daily!), you can create scaffolding, WordPress plugins, Themes, games and an awful lot more - check out our documentation and user guides to see how powerful this LM Studio MCP actually is!"

## Our Core Ecosystem

### Main Package
<a href="https://github.com/houtini-ai/lm">
  <img align="right" src="https://github-readme-stats.vercel.app/api/pin/?username=houtini-ai&repo=lm&theme=light" />
</a>

**[@houtini/lm](https://github.com/houtini-ai/lm)** - Local LLM MCP Server  
Growing list of expert functions for code analysis, generation, and documentation. Unlimited processing without API costs.

<br clear="right"/>

### Documentation
<a href="https://github.com/houtini-ai/examples">
  <img align="right" src="https://github-readme-stats.vercel.app/api/pin/?username=houtini-ai&repo=examples&theme=light" />
</a>

<br clear="right"/>

### Website & Community
<a href="https://houtini.ai">
  <img align="right" src="https://github-readme-stats.vercel.app/api/pin/?username=houtini-ai&repo=website&theme=light" />
</a>

<br clear="right"/>

## Quick Start

```bash
# Install the MCP server
npm install -g @houtini/lm

# Add to Claude Desktop
{
  "mcpServers": {
    "houtini-lm": {
      "command": "npx",
      "args": ["@houtini/lm"],
      "env": {
        "LM_STUDIO_URL": "ws://127.0.0.1:1234",
        "LLM_MCP_ALLOWED_DIRS": "C:/dev"
      }
    }
  }
}

# Start building unlimited
local-llm:health_check
```

## Core Functions

| Category | Functions | Purpose |
|----------|-----------|---------|
| **Analysis** | 17+ functions | Code quality, security audits, project structure |
| **Generation** | 8+ functions | Tests, documentation, WordPress plugins |
| **Creative** | 3+ functions | Games, CSS art, interactive experiences |
| **System** | 5+ functions | Health checks, diagnostics, cache management |

## Community & Support

<div align="center">
  <a href="https://github.com/houtini-ai/lm/discussions">
    <img src="https://img.shields.io/badge/GitHub_Discussions-181717?style=for-the-badge&logo=github&logoColor=white" alt="Discussions">
  </a>
  <a href="https://github.com/houtini-ai/lm/issues">
    <img src="https://img.shields.io/badge/Report_Issues-FF6B35?style=for-the-badge&logo=github&logoColor=white" alt="Issues">
  </a>
  <a href="https://github.com/houtini-ai/lm/blob/main/docs/user-guide-md.md">
    <img src="https://img.shields.io/badge/Website-0066FF?style=for-the-badge&logoColor=white" alt="Documentation">
  </a>
</div>

<br>

- **[X/Twitter](https://x.com/houtini_lm)** - Follow for updates and news
- **[LinkedIn](https://www.linkedin.com/company/houtini/)** - Connect with our team
- **[Email Support](mailto:hello@houtini.ai)** - Direct support and enquiries
- **[GitHub Discussions](https://github.com/houtini-ai/lm/discussions)** - Share workflows and get help
- **[Issue Tracker](https://github.com/houtini-ai/lm/issues)** - Report bugs and request features
- **[Documentation](https://houtini.ai/docs-index.html)** - Complete guides and function reference
- **[About](https://houtini.ai/about.html)** - Learn about our mission and approach
- **[Enterprise Consulting](https://houtini.ai/enterprise.html)** - Contact Us: Custom solutions and support
- **[Examples](https://github.com/houtini-ai/examples)** - Working integration patterns

## Built for Developers, Vibe Coders and People Who Make

We understand the pain of API costs eating into project budgets and context windows limiting creativity. Houtini puts unlimited AI processing power directly on your machine, preserving your Claude context for strategic thinking.

**Perfect for:**
- **Agency developers** who need competitive pricing
- **Vibe Coders** who need a library of powerful prompts to speed up their work reliably
- **Freelancers** building client solutions efficiently  
- **Teams** scaling individual productivity
- **Anyone** tired of rationing their AI interactions

---

<div align="center">
  <p>
    <strong>Ready to build without barriers?</strong><br>
    <a href="https://github.com/houtini-ai/lm">Explore @houtini/lm</a> and start generating unlimited code locally
  </p>
  
  <br>
  
  <a href="https://github.com/houtini-ai/lm">⭐ Star the main repo</a> • 
  <a href="https://houtini.ai">🌐 Visit houtini.ai</a> • 
  <a href="https://houtini.ai/docs-index.html">📖 Read the docs</a>
</div>
