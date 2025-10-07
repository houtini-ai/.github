# Houtini

<div align="center">
  <img src="https://raw.githubusercontent.com/houtini-ai/.github/refs/heads/main/houtini-logo.jpg" alt="Houtini Logo" height="180">
  
  <h3>Work Smarter, Not Harder</h3>
  <p>Tools that actually help you get stuff done with AI</p>
</div>

<div align="center">
  
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lite?label=lite%20downloads&color=00CC88)](https://www.npmjs.com/package/@houtini/lite)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm?label=lm%20downloads&color=0066FF)](https://www.npmjs.com/package/@houtini/lm)
  [![License](https://img.shields.io/github/license/houtini-ai/houtini-lite)](https://github.com/houtini-ai/houtini-lite/blob/main/LICENSE)
  [![GitHub Stars](https://img.shields.io/github/stars/houtini-ai?style=social)](https://github.com/houtini-ai)
  [![Node.js](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen?logo=node.js)](https://nodejs.org/)
  
</div>

---

## What We're Building

Right, here's the thing. AI tools are powerful but they're also overwhelming. Documentation written by robots for robots. Enterprise solutions when you just need to get Tuesday's work done.

We build the bridges. MCP servers that connect your tools. Local AI that saves your API budget. Practical stuff that works.

No hype. No £997 courses. Just tools that help you work smarter.

## Our Tools

### 🎯 **[Houtini Agents](https://github.com/houtini-ai/houtini-agents)** *(Coming Soon)*
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/houtini-agents?style=social)](https://github.com/houtini-ai/houtini-agents)

Autonomous AI agents that actually understand your workflow. Not the sci-fi version - the practical "do this repetitive task while I grab coffee" version.

### ⚡ **[Houtini Lite](https://github.com/houtini-ai/houtini-lite)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/lite)](https://www.npmjs.com/package/@houtini/lite)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lite)](https://www.npmjs.com/package/@houtini/lite)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/houtini-lite?style=social)](https://github.com/houtini-ai/houtini-lite)

The streamlined version. Same power, less setup. Perfect when you need local AI analysis without the full toolkit. One command, you're running.

```bash
npm install -g @houtini/lite
```

### 🌍 **[GEO Analyzer](https://github.com/houtini-ai/geo-analyzer)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/geo-analyzer)](https://www.npmjs.com/package/@houtini/geo-analyzer)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/geo-analyzer)](https://www.npmjs.com/package/@houtini/geo-analyzer)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/geo-analyzer?style=social)](https://github.com/houtini-ai/geo-analyzer)

SEO is dead. Long live GEO (Generative Engine Optimisation). This tool shows you exactly how AI search engines see your content. Built it because I needed it. Now you can use it too.

### 🚀 **[Gemini MCP](https://github.com/houtini-ai/gemini-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/gemini-mcp)](https://www.npmjs.com/package/@houtini/gemini-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/gemini-mcp)](https://www.npmjs.com/package/@houtini/gemini-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/gemini-mcp?style=social)](https://github.com/houtini-ai/gemini-mcp)

Connect Claude to Google's Gemini. Why? Because sometimes you need a second opinion. Or the first opinion. Or just want to see what happens when AIs talk to each other.

### 📧 **[Brevo MCP](https://github.com/houtini-ai/brevo-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/brevo-mcp)](https://www.npmjs.com/package/@houtini/brevo-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/brevo-mcp)](https://www.npmjs.com/package/@houtini/brevo-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/brevo-mcp?style=social)](https://github.com/houtini-ai/brevo-mcp)

Email marketing meets AI. Analyse campaigns, segment lists, write better copy. All from Claude. Because switching between seventeen tabs is nobody's idea of productivity.

### 🔧 **[Houtini LM](https://github.com/houtini-ai/lm)** *(Original)*
[![NPM Version](https://img.shields.io/npm/v/@houtini/lm)](https://www.npmjs.com/package/@houtini/lm)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm)](https://www.npmjs.com/package/@houtini/lm)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/lm?style=social)](https://github.com/houtini-ai/lm)

Where it all started. The full toolkit with 50+ expert functions. Code analysis, generation, WordPress development, even games. Still actively maintained for power users who want everything.

## Quick Start

Pick your flavour:

```bash
# Lightweight version (recommended for most)
npm install -g @houtini/lite

# Full toolkit (if you want everything)
npm install -g @houtini/lm

# GEO Analysis (check your AI search visibility)
npm install -g @houtini/geo-analyzer
```

Then configure in Claude Desktop:

```json
{
  "mcpServers": {
    "houtini-lite": {
      "command": "npx",
      "args": ["@houtini/lite"]
    }
  }
}
```

That's it. You're running local AI.

## Who This Is For

- **Freelancers** who can't justify another monthly subscription
- **Agencies** trying to stay competitive without burning budget
- **Developers** who know enough to be dangerous
- **Anyone** tired of context window limits and API rate limits

We're not building for enterprise. We're building for Tuesday morning when you need to ship something and Claude's context window is full.

## The Real Story

I'm Richard. Twenty years on the web, two years deep in AI. Started building these tools because I needed them. Turns out other people need them too.

Every tool here solves a real problem I've hit. No theoretical "this might be useful" stuff. Just practical solutions to actual work problems.

Want the full story? [Read about it here](https://houtini.com/about/).

## Get Involved

**Need help?** Open an issue. I actually read them.

**Found a bug?** Tell me. I'll fix it.

**Want to contribute?** PRs welcome. Keep it simple, make it useful.

**Just want to chat?** Find me on [X/Twitter](https://x.com/houtini_lm) or [LinkedIn](https://www.linkedin.com/company/houtini/).

## Support

- 📖 [Documentation](https://houtini.com/docs/) - Guides written by humans for humans
- 💬 [GitHub Discussions](https://github.com/houtini-ai/houtini-lite/discussions) - Share what you're building
- 🐛 [Issues](https://github.com/orgs/houtini-ai/repositories) - Report problems, request features
- ✉️ [Email](mailto:hello@houtini.ai) - Direct line if you need it

## Philosophy

AI shouldn't be complicated. It shouldn't require a PhD or a massive budget. It should just help you work better.

Every tool we build follows these rules:
1. It solves a real problem
2. It works out of the box
3. It doesn't require a manual to understand

That's it. No manifestos. No disruption. Just tools that work.

---

<div align="center">
  
**Ready to work smarter?**

Pick a tool above and get started. Or just [star a repo](https://github.com/houtini-ai) to follow along.

Built with coffee and frustration in the UK 🇬🇧

</div>