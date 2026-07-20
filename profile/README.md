<div align="center">
  <img src="https://raw.githubusercontent.com/houtini-ai/.github/main/profile/houtini-logo.svg" alt="Houtini" height="130">

  <h3>We build the agent layer.</h3>
  <p>Agentic-AI consultancy from the founder of Builtvisible. We build the agent layer for data, marketing and e-commerce teams — and these are the open-source tools we built along the way. Free, MIT, on npm.</p>
</div>

<div align="center">

  [![SEO Audit Console](https://img.shields.io/badge/flagship-SEO_Audit_Console-5b5fff?style=flat-square)](https://github.com/houtini-ai/seo-audit)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm?label=lm&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/lm)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/gemini-mcp?label=gemini&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/gemini-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/fanout-mcp?label=fanout&color=5b5fff&style=flat-square)](https://www.npmjs.com/package/@houtini/fanout-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/geo-analyzer?label=geo&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/geo-analyzer)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/seo-crawler-mcp?label=seo%20crawler&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/seo-crawler-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/google-knowledge-graph-mcp?label=knowledge%20graph&color=5b5fff&style=flat-square)](https://www.npmjs.com/package/@houtini/google-knowledge-graph-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/voice-analyser?label=voice&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/voice-analyser)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/better-search-console?label=search%20console&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/better-search-console)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/brevo-mcp?label=brevo&color=5b5fff&style=flat-square)](https://www.npmjs.com/package/@houtini/brevo-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/fmp-mcp?label=fmp&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/fmp-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/yubhub?label=yubhub&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/yubhub)
  [![GitHub Stars](https://img.shields.io/github/stars/houtini-ai?style=social)](https://github.com/houtini-ai)

</div>

---

## What we're about

Houtini is an agentic-AI consultancy from the founder of Builtvisible. We embed with data, marketing and e-commerce teams and build the agent layer — the automation that does the grunt work, so the people get back to the thinking: the strategy, the creative, the planning.

AI isn't coming for your job. It's coming to make it easier.

This repo is the open-source side of that work. MCP servers and tools for your AI assistant — Claude, Cursor, Cline, or whatever you run — free, MIT, on npm. Every one of them started as something we needed on real client work, then cleaned up and given away. No hype. No enterprise pricing for a Tuesday-morning problem. Need something we haven't built? [Get in touch](mailto:hello@houtini.com).

## Our Tools

### 🔦 **[SEO Audit Console](https://github.com/houtini-ai/seo-audit)** — the complete technical SEO audit, at conversation speed
[![Source Available](https://img.shields.io/badge/license-source--available-5b5fff?style=flat-square)](https://github.com/houtini-ai/seo-audit)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-server-8b5cf6?style=flat-square)](https://modelcontextprotocol.io)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/seo-audit?style=social)](https://github.com/houtini-ai/seo-audit)

Our flagship. It merges your **Google Search Console** history, a **first-party crawl** of your site, and on-demand **DataForSEO** market data into one prioritised audit inside Claude — 90 checks covering crawlability, indexation, canonicalisation, structured data, Core Web Vitals and hreflang, right through to cannibalisation, striking-distance queries, content gaps, competitors and AI-search readiness.

The difference is the ranking. Your crawl is intent; Search Console is reality; the money is where they diverge. Every finding is ordered by the clicks it could actually recover, and every fix is written for you — paste-ready redirects, JSON-LD, internal links, grounded content briefs. What used to be a fortnight of crawling and cross-referencing spreadsheets is twenty minutes and a prompt. Your data never leaves your machine.

```bash
git clone https://github.com/houtini-ai/seo-audit.git
```

---

### 🧠 **[Metacog](https://github.com/houtini-ai/metacog)** — proprioceptive nervous system for AI agents
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/metacog?style=social)](https://github.com/houtini-ai/metacog)

AI coding agents are brains in vats. They can't feel their context window filling up, don't know how long they've been working, can't sense when they're going in circles, and have no peripheral vision of how their changes affect the wider codebase. Metacog gives them a nervous system. Five proprioceptive senses fire silently after every tool call. Cross-session reinforcement tracking carries forward behavioural lessons — and unlike naive time-decay systems, rules that successfully suppress their target failure get reinforced by their own success.

Two Claude Code hooks. Zero dependencies. Zero tokens when everything is normal.

```bash
npx @houtini/metacog --install
```

---

### 🤖 **[Houtini LM](https://github.com/houtini-ai/lm)** — save Claude Code tokens with a local LLM or cloud API
[![NPM Version](https://img.shields.io/npm/v/@houtini/lm)](https://www.npmjs.com/package/@houtini/lm)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm)](https://www.npmjs.com/package/@houtini/lm)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/lm?style=social)](https://github.com/houtini-ai/lm)

MCP server that connects Claude Code to any local or cloud LLM. Claude keeps the reasoning — architecture, planning, tool orchestration — and delegates the grunt work to whatever cheaper model you've got running. Code review, test stubs, commit messages, format conversion. Benchmarked at 93.3% token savings on specific, file-level tasks using real source files. Auto-profiles models via HuggingFace, routes tasks to the best loaded model, strips think-blocks, and tracks every token offloaded.

Works with LM Studio, Ollama, vLLM, DeepSeek, Groq, Cerebras — anything speaking the OpenAI format.

```bash
npx @houtini/lm@latest
```

### 🚀 **[Gemini MCP](https://github.com/houtini-ai/gemini-mcp)** — Google Gemini inside Claude
[![NPM Version](https://img.shields.io/npm/v/@houtini/gemini-mcp)](https://www.npmjs.com/package/@houtini/gemini-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/gemini-mcp)](https://www.npmjs.com/package/@houtini/gemini-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/gemini-mcp?style=social)](https://github.com/houtini-ai/gemini-mcp)

Connect Claude to Google's Gemini with search grounding, deep research, image generation and analysis, SVG creation, video generation, and YouTube video analysis. When you need real-time information Claude doesn't have, a second opinion, or Gemini's multimodal capabilities. Works with Gemini 2.5 Pro and Flash.

```bash
npx @houtini/gemini-mcp@latest
```

---

### 🔍 **[Fan-Out MCP](https://github.com/houtini-ai/fanout-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/fanout-mcp)](https://www.npmjs.com/package/@houtini/fanout-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/fanout-mcp)](https://www.npmjs.com/package/@houtini/fanout-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/fanout-mcp?style=social)](https://github.com/houtini-ai/fanout-mcp)

Advanced content gap analysis using Query Decomposition and Keyword Fan-Out (Google's patented methodology). Tells you exactly what user queries your content covers - and what it misses. Built on academic research because I needed to understand how AI search engines actually evaluate content.

Works with Self-RAG validation, so no hallucinations. Every coverage claim includes exact quotes from your content.

```bash
npx @houtini/fanout-mcp@latest
```

### 🌍 **[GEO Analyzer](https://github.com/houtini-ai/geo-analyzer)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/geo-analyzer)](https://www.npmjs.com/package/@houtini/geo-analyzer)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/geo-analyzer)](https://www.npmjs.com/package/@houtini/geo-analyzer)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/geo-analyzer?style=social)](https://github.com/houtini-ai/geo-analyzer)

SEO is dead. Long live GEO (Generative Engine Optimisation). This tool shows you exactly how AI search engines see your content - claim density, writing quality, E-E-A-T signals, extractability. Research-backed metrics that correlate with 40% higher AI citation rates.

Built it because traditional SEO metrics stopped predicting what gets cited by ChatGPT, Perplexity, and Gemini. Turns out AI search engines care about different signals.

```bash
npx @houtini/geo-analyzer@latest
```

### 🕷️ **[SEO Crawler MCP](https://github.com/houtini-ai/seo-crawler-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/seo-crawler-mcp)](https://www.npmjs.com/package/@houtini/seo-crawler-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/seo-crawler-mcp)](https://www.npmjs.com/package/@houtini/seo-crawler-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/seo-crawler-mcp?style=social)](https://github.com/houtini-ai/seo-crawler-mcp)

Crawl your entire website and detect technical SEO issues that actually matter. 25+ analysis queries covering broken links, duplicate content, security headers, content quality, and optimisation opportunities. Built with Crawlee for smart crawling and SQLite for local analysis.

Works via CLI for large sites or through Claude for AI-powered analysis. Run the crawl overnight, hand the results to Claude, get intelligent recommendations. No external dependencies, everything stays local.

```bash
npx @houtini/seo-crawler-mcp@latest
```

### 🔎 **[Google Knowledge Graph MCP](https://github.com/houtini-ai/google-knowledge-graph-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/google-knowledge-graph-mcp)](https://www.npmjs.com/package/@houtini/google-knowledge-graph-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/google-knowledge-graph-mcp)](https://www.npmjs.com/package/@houtini/google-knowledge-graph-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/google-knowledge-graph-mcp?style=social)](https://github.com/houtini-ai/google-knowledge-graph-mcp)

Search Google's public Knowledge Graph for structured entity information. Get facts about people, places, organisations, and concepts from Google's database - the same data that powers those info boxes on search results.

Built it because I needed quick access to verified entity data without web scraping. Uses Google's free public API (not the Enterprise version), so no billing account required.

```bash
npx @houtini/google-knowledge-graph-mcp@latest
```

### 🎙️ **[Voice Analyser](https://github.com/houtini-ai/voice-analyser-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/voice-analyser)](https://www.npmjs.com/package/@houtini/voice-analyser)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/voice-analyser)](https://www.npmjs.com/package/@houtini/voice-analyser)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/voice-analyser-mcp?style=social)](https://github.com/houtini-ai/voice-analyser-mcp)

Extract your writing voice from published articles and generate immersive style guides. Traditional style guides list rules - this tool extracts the statistical fingerprint of how you actually write. Sentence rhythm, vocabulary patterns, argument flow, the micro-rhythms that make writing feel human.

Feed it your sitemap, get back a guide that teaches LLMs to replicate your voice through examples, not rules. Experimental but effective.

```bash
npx @houtini/voice-analyser@latest
```

### 📊 **[Better Search Console](https://github.com/houtini-ai/better-search-console)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/better-search-console)](https://www.npmjs.com/package/@houtini/better-search-console)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/better-search-console)](https://www.npmjs.com/package/@houtini/better-search-console)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/better-search-console?style=social)](https://github.com/houtini-ai/better-search-console)

Pull your Google Search Console data via API into a local SQLite database. Pre-configured queries for the analysis you actually run — top queries, growing pages, declining keywords, opportunities sitting at positions 5–20. Generates interactive dashboards through MCP Apps in Claude Desktop.

The GSC web interface is fine for a quick glance. This is for when you need to ask real questions of your data.

```bash
npx @houtini/better-search-console@latest
```

### 💰 **[FMP MCP](https://github.com/houtini-ai/fmp-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/fmp-mcp)](https://www.npmjs.com/package/@houtini/fmp-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/fmp-mcp)](https://www.npmjs.com/package/@houtini/fmp-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/fmp-mcp?style=social)](https://github.com/houtini-ai/fmp-mcp)

Financial Modeling Prep API access from your AI assistant. Stock quotes, financial statements, market data, company profiles. Built it for a client who needed financial data piped into their content workflow without switching tabs.

Free tier covers most use cases. The API is well documented, the MCP just makes it conversational.

```bash
npx @houtini/fmp-mcp@latest
```

### 📧 **[Brevo MCP](https://github.com/houtini-ai/brevo-mcp)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/brevo-mcp)](https://www.npmjs.com/package/@houtini/brevo-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/brevo-mcp)](https://www.npmjs.com/package/@houtini/brevo-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/brevo-mcp?style=social)](https://github.com/houtini-ai/brevo-mcp)

Brevo (formerly Sendinblue) email marketing from your AI assistant. Manage contacts, campaigns, analytics, and transactional emails without leaving your editor. Covers the full API — contacts, lists, campaigns, templates, sending.

If you're already on Brevo, this saves the context switch. If you're not, it's a solid free-tier email platform.

```bash
npx @houtini/brevo-mcp@latest
```

### 📋 **[YubHub](https://github.com/houtini-ai/yubhub)**
[![NPM Version](https://img.shields.io/npm/v/@houtini/yubhub)](https://www.npmjs.com/package/@houtini/yubhub)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/yubhub)](https://www.npmjs.com/package/@houtini/yubhub)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/yubhub?style=social)](https://github.com/houtini-ai/yubhub)

Turn any careers page into a structured job feed. Point it at a company's jobs URL and it discovers every open role, scrapes the listings, enriches them with AI (title normalisation, category tagging, salary extraction, company research) and publishes them as an XML feed.

Supports Greenhouse, Lever, Workable, Workday, Oracle HCM, SmartRecruiters, Ashby, Pinpoint, Phenom and more. Create feeds, trigger runs, check on jobs, view dashboards, browse market stats — all from your AI assistant.

```bash
npx @houtini/yubhub@latest
```

## Quick Start

The flagship installs from source:

```bash
git clone https://github.com/houtini-ai/seo-audit.git   # SEO Audit Console — GSC + crawl + DataForSEO, ranked by recoverable clicks
```

The rest are one `npx` away — pick your flavour:

```bash
npx @houtini/metacog --install                  # Agent proprioception + reinforcement tracking
npx @houtini/lm@latest                           # Local LLM delegation (93% token savings)
npx @houtini/gemini-mcp@latest                   # Google Gemini integration
npx @houtini/fanout-mcp@latest                   # Content gap analysis
npx @houtini/geo-analyzer@latest                 # AI search optimisation
npx @houtini/seo-crawler-mcp@latest              # Technical SEO crawl
npx @houtini/google-knowledge-graph-mcp@latest   # Entity data
npx @houtini/voice-analyser@latest               # Writing style extraction
npx @houtini/better-search-console@latest        # GSC data + dashboards
npx @houtini/fmp-mcp@latest                      # Financial market data
npx @houtini/brevo-mcp@latest                    # Email marketing
npx @houtini/yubhub@latest                       # Job feed pipeline
```

Then configure in Claude Desktop (or Claude Code, Cursor, Cline):

```json
{
  "mcpServers": {
    "fanout": {
      "command": "npx",
      "args": ["-y", "@houtini/fanout-mcp@latest"],
      "env": {
        "ANTHROPIC_API_KEY": "your-key-here"
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
- **Anyone** getting their site — and their team — ready for the customers who arrive via AI search or their own agents

We're not building for enterprise. We're building for the Tuesday morning when you need to ship something and the usual tools aren't cutting it.

## The real story

I'm Richard. I founded [Builtvisible](https://builtvisible.com) and exited in 2025 — twenty years in technical SEO and content infrastructure. Houtini is what came next: the agent layer for the teams I used to consult, and the open-source tools underneath it.

Every tool here addresses a problem I've actually hit on client work. I needed them, built them, cleaned them up, gave them away. Turns out other people needed them too.

Want the full story? Read the [Houtini blog](https://houtini.com/articles/) for guidance on getting started.

## Support

- 📖 **[Houtini Blog](https://houtini.com/articles/)** — guidance on getting started with MCP and AI tools
- 💬 **[GitHub Discussions](https://github.com/orgs/houtini-ai/discussions)** — share what you're building
- 🐛 **[Issues](https://github.com/orgs/houtini-ai/repositories)** — report problems, request features
- ✉️ **[Email](mailto:hello@houtini.com)** — direct line if you need it

Brought to you by **[Houtini.com](https://houtini.com)** — agentic-AI consultancy building the agent layer for data, marketing and e-commerce teams. **Operating · accepting briefs.**

## Philosophy

AI shouldn't be complicated. It shouldn't require a PhD or a massive budget. It should just help you work better — no replacement for the creative work, but as a productivity tool it's hard to beat.

Every tool we build follows three rules:
1. It solves a real problem
2. It works
3. It doesn't need a manual to understand

That's it. No manifestos. No disruption. Just tools that work.

---

<div align="center">

**Ready to get your team agent-ready?**

Pick a tool above and get started. Or just [star a repo](https://github.com/houtini-ai) to follow along.

Built with coffee and frustration in the UK 🇬🇧

</div>
