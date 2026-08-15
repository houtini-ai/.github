<div align="center">
  <img src="https://raw.githubusercontent.com/houtini-ai/.github/main/profile/houtini-logo.svg" alt="Houtini" height="130">

  <h3>Tools to make Web work easier and faster.</h3>
</div>

<div align="center">

  [![SEO Audit Console](https://img.shields.io/badge/flagship-SEO_Audit_Console-5b5fff?style=flat-square)](https://github.com/houtini-ai/seo-audit)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm?label=lm&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/lm)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/gemini-mcp?label=gemini&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/gemini-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/yubhub?label=yubhub&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/yubhub)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/metacog?label=metacog&color=5b5fff&style=flat-square)](https://www.npmjs.com/package/@houtini/metacog)
  [![GitHub Stars](https://img.shields.io/github/stars/houtini-ai?style=social)](https://github.com/houtini-ai)

</div>

---

## AI isn't coming for your job. It's coming to make it easier.

We're Houtini, an agentic-AI consultancy from the founder of Builtvisible. We embed with data, marketing and e-commerce teams and build the agent layer: the automation that does the grunt work, so the people get back to the thinking. The strategy, the creative, the planning.

This repo is the open-source side of that work. MCP servers and hooks for your AI assistant - Claude, Cursor, Cline, whatever you run - free, MIT, on npm. Every one started as something we needed on real client work, then cleaned up and given away. The work we ship for clients goes further; this is what we can hand you for nothing.

No hype. No enterprise pricing for a Tuesday-morning problem. Need something we haven't built? [Get in touch](mailto:hello@houtini.com).

---

## The flagship

### 🔦 **[SEO Audit Console](https://github.com/houtini-ai/seo-audit)** - one assistant for both sides of SEO
[![Source Available](https://img.shields.io/badge/license-source--available-5b5fff?style=flat-square)](https://github.com/houtini-ai/seo-audit)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-server-8b5cf6?style=flat-square)](https://modelcontextprotocol.io)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/seo-audit?style=social)](https://github.com/houtini-ai/seo-audit)

The issues that are costing you and the opportunities you're missing, in one prioritised list, inside Claude. SEO Audit Console merges your **Google Search Console** history, a **first-party crawl** of your site, and on-demand **DataForSEO** market data into a single audit: 90 checks covering crawlability, indexation, canonicalisation, structured data, Core Web Vitals and hreflang, right through to cannibalisation, striking-distance queries, content gaps, competitors and AI-search readiness.

The difference is the ranking. A flat crawler sells you severity. This ranks by yield - every finding ordered by the clicks it could actually recover, every fix written for you: paste-ready redirects, JSON-LD, internal links, grounded content briefs. It finds the page sitting at position #3 on 150,000 impressions with a 0.2% click-through rate, tells you a title rewrite is probably worth thousands of clicks, and puts that *above* the cosmetic stuff. One line underneath all of it:

> **Your crawl is intent. Search Console is reality. The money is where they diverge.**

What used to be a fortnight of crawling and cross-referencing spreadsheets is twenty minutes and a prompt. Run it in Claude Code and it closes the loop: finds the issue, writes the fix, applies it to your repo, commits it, re-crawls to verify. Your data never leaves your machine.

```bash
git clone https://github.com/houtini-ai/seo-audit.git
```

---

## The rest, most-starred first

### 🤖 **[Houtini LM](https://github.com/houtini-ai/houtini-lm)** - save Claude Code tokens with a local LLM or cloud API
[![NPM Version](https://img.shields.io/npm/v/@houtini/lm)](https://www.npmjs.com/package/@houtini/lm)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm)](https://www.npmjs.com/package/@houtini/lm)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/houtini-lm?style=social)](https://github.com/houtini-ai/houtini-lm)

MCP server that connects Claude Code to any local or cloud LLM. Claude keeps the reasoning - architecture, planning, tool orchestration - and hands the grunt work to whatever cheaper model you've got running: code review, test stubs, commit messages, format conversion. Benchmarked at 93.3% token savings on specific, file-level tasks against real source files. It auto-profiles models via HuggingFace, routes each task to the best loaded model, strips think-blocks, and counts every token it kept off your bill.

Works with LM Studio, Ollama, vLLM, DeepSeek, Groq, Cerebras - anything speaking the OpenAI format.

```bash
npx @houtini/lm@latest
```

### 🚀 **[Gemini MCP](https://github.com/houtini-ai/gemini-mcp)** - Google Gemini inside Claude
[![NPM Version](https://img.shields.io/npm/v/@houtini/gemini-mcp)](https://www.npmjs.com/package/@houtini/gemini-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/gemini-mcp)](https://www.npmjs.com/package/@houtini/gemini-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/gemini-mcp?style=social)](https://github.com/houtini-ai/gemini-mcp)

Connect Claude to Google's Gemini: search grounding, deep research, image generation and analysis, SVG creation, video generation, YouTube video analysis. For when you need real-time information Claude doesn't have, a second opinion, or Gemini's multimodal side. Created images, landing pages, SVGs and video preview inline in Claude Desktop through MCP Apps. Works with Gemini 2.5 Pro and Flash.

```bash
npx @houtini/gemini-mcp@latest
```

### 🔎 **[Google Knowledge Graph MCP](https://github.com/houtini-ai/google-knowledge-graph-mcp)** - verified entity data, no scraping
[![NPM Version](https://img.shields.io/npm/v/@houtini/google-knowledge-graph-mcp)](https://www.npmjs.com/package/@houtini/google-knowledge-graph-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/google-knowledge-graph-mcp)](https://www.npmjs.com/package/@houtini/google-knowledge-graph-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/google-knowledge-graph-mcp?style=social)](https://github.com/houtini-ai/google-knowledge-graph-mcp)

Search Google's public Knowledge Graph for structured facts about people, places, organisations and concepts - the same data behind the info boxes on search results. I built it because I needed quick access to verified entity data without web scraping. Uses Google's free public API, not the Enterprise version, so there's no billing account to set up.

```bash
npx @houtini/google-knowledge-graph-mcp@latest
```

### 🧠 **[Metacog](https://github.com/houtini-ai/metacog)** - a nervous system for your coding agent
[![NPM Version](https://img.shields.io/npm/v/@houtini/metacog)](https://www.npmjs.com/package/@houtini/metacog)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/metacog)](https://www.npmjs.com/package/@houtini/metacog)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/metacog?style=social)](https://github.com/houtini-ai/metacog)

AI coding agents are brains in vats. They can't feel their context window filling up, don't know how long they've been working, can't sense when they're going in circles, and have no peripheral vision of how a change lands on the wider codebase. Metacog gives them a nervous system: five proprioceptive senses that fire silently after every tool call. Cross-session reinforcement carries behavioural lessons forward - and unlike naive time-decay systems, a rule that keeps suppressing its target failure gets reinforced by its own success.

Two Claude Code hooks. Zero dependencies. Zero tokens when everything's normal.

```bash
npx @houtini/metacog --install
```

### 💰 **[FMP MCP](https://github.com/houtini-ai/fmp-mcp)** - financial market data in the conversation
[![NPM Version](https://img.shields.io/npm/v/@houtini/fmp-mcp)](https://www.npmjs.com/package/@houtini/fmp-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/fmp-mcp)](https://www.npmjs.com/package/@houtini/fmp-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/fmp-mcp?style=social)](https://github.com/houtini-ai/fmp-mcp)

Financial Modeling Prep from your AI assistant: stock quotes, financial statements, market data, company profiles. I built it for a client who needed financial data piped into their content workflow without switching tabs. The free tier covers most of what you'll ask; the MCP just makes the API conversational.

```bash
npx @houtini/fmp-mcp@latest
```

### 📋 **[YubHub](https://github.com/houtini-ai/yubhub)** - any careers page to a structured job feed
[![NPM Version](https://img.shields.io/npm/v/@houtini/yubhub)](https://www.npmjs.com/package/@houtini/yubhub)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/yubhub)](https://www.npmjs.com/package/@houtini/yubhub)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/yubhub?style=social)](https://github.com/houtini-ai/yubhub)

Point it at a company's jobs URL and it finds every open role, scrapes the listings, enriches them with AI - title normalisation, category tagging, salary extraction, company research - and publishes them as an XML feed. Supports Greenhouse, Lever, Workable, Workday, Oracle HCM, SmartRecruiters, Ashby, Pinpoint, Phenom and more. Create feeds, trigger runs, check jobs, browse market stats, all from your AI assistant. It's run about six months on real feeds with almost no intervention.

```bash
npx @houtini/yubhub@latest
```

### 🧹 **[node-session-reaper](https://github.com/houtini-ai/node-session-reaper)** - stop leaked MCP servers eating your RAM
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/node-session-reaper?style=social)](https://github.com/houtini-ai/node-session-reaper)

Run Claude Code with a stack of MCP servers on Windows and you've probably watched `node.exe` climb into the tens of GB over a day until the machine crawls. Windows doesn't cascade-kill child processes when the parent dies, so closed sessions leave their whole set of node servers running forever. This is a small, safe PowerShell reaper plus a scheduled task and a session hook that keep it in check. The safety rule is strict: a process is reapable only if no live Claude session owns it, so it can never touch a session you're using. Windows only.

```powershell
git clone https://github.com/houtini-ai/node-session-reaper
cd node-session-reaper; ./install.ps1
```

### 🛒 **[Amazon Creators MCP](https://github.com/houtini-ai/amazon-creators-mcp)** - paste-ready affiliate cards, straight into the post
[![NPM Version](https://img.shields.io/npm/v/@houtini/amazon-creators-mcp)](https://www.npmjs.com/package/@houtini/amazon-creators-mcp)
[![MCP Apps](https://img.shields.io/badge/MCP_Apps-inline_previews-8b5cf6?style=flat-square)](https://modelcontextprotocol.io)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/amazon-creators-mcp?style=social)](https://github.com/houtini-ai/amazon-creators-mcp)

Ask Claude to find Amazon products and it hands back embeddable affiliate cards - image, price, savings, your tag already baked in - previewed inline in Claude Desktop through MCP Apps before you paste a thing. Search the catalogue, look up specific ASINs, build a single card or a whole grid.

The format worth knowing about is `html-deals`. Most affiliate tooling gives you a card that looks like a card, which is exactly wrong the moment it lands in a post that already has house styling. This emits structural markup instead - `.amazon-deals-section` wrapping one `.amazon-deal-row` per product - so if your theme already styles those classes, the output inherits them and there's nothing to restyle. Compact 70px rows, so ten products read as a list rather than ten screens of scrolling.

<img src="https://raw.githubusercontent.com/houtini-ai/amazon-creators-mcp/main/assets/deals-row-output.png" alt="Three product deal rows - thumbnail, title, brand, price, savings and a View on Amazon button" width="700">

It won't print a Prime badge or a star rating it doesn't have: nothing in the API says whether an item is Prime-eligible, and review data is restricted per Associates account. Inventing either on a page someone might buy from isn't worth the polish. Built on the Amazon Creators API, the REST replacement for Product Advertising API 5.0.

```bash
npx @houtini/amazon-creators-mcp@latest
```

### 🕵️ **[ai-detect](https://github.com/houtini-ai/ai-detect)** `beta` - is the copy you're buying handwritten?
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-server-8b5cf6?style=flat-square)](https://modelcontextprotocol.io)
[![Model](https://img.shields.io/badge/model-DeBERTa--v3-5b5fff?style=flat-square)](https://huggingface.co/desklib/ai-text-detector-v1.01)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/ai-detect?style=social)](https://github.com/houtini-ai/ai-detect)

Find out, free and at scale, on your own machine. A local AI-content detector built on a DeBERTa-v3 model - the RAID benchmark's top-ranked one - that scores copy sentence by sentence and, better than a single number, tells you *why* a line reads as machine-written: the formal verbs, the missing contractions, the "Furthermore" openers, each with a plain rewrite. It's an MCP server too, so Claude can score a draft for you without it being pasted into the chat. No API key, and it runs offline after the first model download. It's no Pangram Labs, but where there's smoke there's fire.

```bash
git clone https://github.com/houtini-ai/ai-detect
cd ai-detect && pip install .     # installs the ai-detect CLI and the ai-detect-mcp server
```

## Retired

Five tools have come out of the set. The repos are archived rather than deleted and the npm packages still install, so nothing anyone has running breaks - but they get no further releases.

- **SEO Crawler MCP** and **Better Search Console** are now inside [SEO Audit Console](https://github.com/houtini-ai/seo-audit). The crawler and the Search Console sync both survived the move; what they gained was each other. A crawl tells you what a page is for, Search Console tells you what it earns, and most of the useful questions live where those two disagree.
- **GEO Analyzer** folded into [SEO Audit Console](https://github.com/houtini-ai/seo-audit) as well. AI-search readiness - whether a page gets cited in AI Overviews, how extractable its answers are, how it scores for agents - belongs next to the audit that can act on it, not in a tool of its own.
- **Voice Analyser** was always flagged experimental and we are not keeping it current. The code is MIT if you want it.
- **Brevo MCP** was a thin wrapper over somebody else's API, and a stale integration is worse than none.

## Quick start

The flagship installs from source:

```bash
git clone https://github.com/houtini-ai/seo-audit.git   # SEO Audit Console - GSC + crawl + DataForSEO, ranked by recoverable clicks
```

The rest are one `npx` away - pick your flavour:

```bash
npx @houtini/lm@latest                           # Local LLM delegation (93% token savings)
npx @houtini/gemini-mcp@latest                   # Google Gemini integration
npx @houtini/amazon-creators-mcp@latest          # Amazon affiliate deal rows
npx @houtini/google-knowledge-graph-mcp@latest   # Entity data
npx @houtini/metacog --install                   # Agent proprioception + reinforcement
npx @houtini/fmp-mcp@latest                      # Financial market data
npx @houtini/yubhub@latest                       # Job feed pipeline
```

**[ai-detect](https://github.com/houtini-ai/ai-detect)** (`beta`, AI-content detection) installs from source, straight from its repo.

Then configure in Claude Desktop (or Claude Code, Cursor, Cline):

```json
{
  "mcpServers": {
    "gemini": {
      "command": "npx",
      "args": ["-y", "@houtini/gemini-mcp@latest"],
      "env": {
        "GEMINI_API_KEY": "your-key-here"
      }
    }
  }
}
```

That's it. You're running.

## Who this is for

- **In-house marketing, data and e-commerce teams** who want the grunt work automated so the thinking time survives
- **SEO consultants** who've been quoted four figures for a commodity audit and know they can do better
- **Web workers and freelancers** juggling a dozen tools who can't justify another monthly subscription
- **Anyone** getting their site - and their team - ready for the customers who arrive via AI search, or their own agents

We're not building for enterprise. We're building for the Tuesday morning when you need to ship something and the usual tools aren't cutting it.

## The story

I'm Richard. I founded [Builtvisible](https://builtvisible.com) and exited in 2025 - twenty years in technical SEO and content infrastructure. Houtini is what came next: the agent layer for the teams I used to consult, and the open-source tools underneath it.

Every tool here started as a problem I hit on real client work. I needed it, built it, cleaned it up, gave it away. Turns out other people needed it too.

Want the fuller version? The [Houtini blog](https://houtini.com/articles/) is where I write up how this actually works, week by week.

## Support

- 📖 **[Houtini Blog](https://houtini.com/articles/)** - getting started with MCP and AI tools, written by Richard
- 💬 **[GitHub Discussions](https://github.com/orgs/houtini-ai/discussions)** - share what you're building
- 🐛 **[Issues](https://github.com/orgs/houtini-ai/repositories)** - report problems, request features
- ✉️ **[Email](mailto:hello@houtini.com)** - direct line if you need it

Brought to you by **[Houtini.com](https://houtini.com)** - agentic-AI consultancy building the agent layer for data, marketing and e-commerce teams. **Operating · accepting briefs.**

## Philosophy

AI shouldn't need a PhD or a massive budget. It should just help you work better - no replacement for the creative work, but as a productivity tool it's hard to beat. Every tool here follows three rules: it solves a real problem, it works, and it doesn't need a manual to understand.

That's the whole pitch, honestly. It's AI, it works reliably, and it makes a difference. That's us.

---

<div align="center">

**Ready to get your team agent-ready?**

Pick a tool above and get started. Or [book a call](https://houtini.com/contact) - forty-five minutes, no pitch deck.

Built with coffee and frustration in the UK 🇬🇧

</div>
