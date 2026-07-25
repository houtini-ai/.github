<div align="center">
  <img src="https://raw.githubusercontent.com/houtini-ai/.github/main/profile/houtini-logo.svg" alt="Houtini" height="130">

  <h3>We build the agent layer.</h3>
  <p>Agentic-AI consultancy from the founder of Builtvisible. We build the agent layer for data, marketing and e-commerce teams - and these are the open-source tools we made along the way. Free, MIT, on npm.</p>

  <sub><b>Operating · accepting briefs</b></sub>
</div>

<div align="center">

  [![SEO Audit Console](https://img.shields.io/badge/flagship-SEO_Audit_Console-5b5fff?style=flat-square)](https://github.com/houtini-ai/seo-audit)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/lm?label=lm&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/lm)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/gemini-mcp?label=gemini&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/gemini-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/geo-analyzer?label=geo&color=5b5fff&style=flat-square)](https://www.npmjs.com/package/@houtini/geo-analyzer)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/seo-crawler-mcp?label=seo%20crawler&color=8b5cf6&style=flat-square)](https://www.npmjs.com/package/@houtini/seo-crawler-mcp)
  [![NPM Downloads](https://img.shields.io/npm/dt/@houtini/better-search-console?label=search%20console&color=d946ef&style=flat-square)](https://www.npmjs.com/package/@houtini/better-search-console)
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

### 🌍 **[GEO Analyzer](https://github.com/houtini-ai/geo-analyzer)** - see your content the way AI search does
[![NPM Version](https://img.shields.io/npm/v/@houtini/geo-analyzer)](https://www.npmjs.com/package/@houtini/geo-analyzer)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/geo-analyzer)](https://www.npmjs.com/package/@houtini/geo-analyzer)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/geo-analyzer?style=social)](https://github.com/houtini-ai/geo-analyzer)

Generative Engine Optimisation analysis for the search engines that don't show ten blue links. It scores what actually gets you cited by ChatGPT, Perplexity and Gemini: claim density, writing quality, E-E-A-T signals, extractability. Research-backed metrics, not vibes.

I built it because traditional SEO metrics stopped predicting what gets quoted in an AI answer. Turns out those engines care about different signals, and this shows you which.

```bash
npx @houtini/geo-analyzer@latest
```

### 🕷️ **[SEO Crawler MCP](https://github.com/houtini-ai/seo-crawler-mcp)** - crawl the whole site, keep it local
[![NPM Version](https://img.shields.io/npm/v/@houtini/seo-crawler-mcp)](https://www.npmjs.com/package/@houtini/seo-crawler-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/seo-crawler-mcp)](https://www.npmjs.com/package/@houtini/seo-crawler-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/seo-crawler-mcp?style=social)](https://github.com/houtini-ai/seo-crawler-mcp)

Crawl your entire website and surface the technical issues that actually matter: broken links, duplicate content, security headers, content quality, optimisation gaps. 25+ analysis queries, built on Crawlee for the crawl and SQLite for the analysis. Run the crawl overnight via CLI on a big site, hand the results to Claude in the morning, get intelligent recommendations back. No external dependencies, everything stays on your machine.

```bash
npx @houtini/seo-crawler-mcp@latest
```

### 📊 **[Better Search Console](https://github.com/houtini-ai/better-search-console)** - ask real questions of your GSC data
[![NPM Version](https://img.shields.io/npm/v/@houtini/better-search-console)](https://www.npmjs.com/package/@houtini/better-search-console)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/better-search-console)](https://www.npmjs.com/package/@houtini/better-search-console)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/better-search-console?style=social)](https://github.com/houtini-ai/better-search-console)

Pull your Google Search Console data via API into a local SQLite database, then interrogate it. Pre-built queries for the analysis you actually run - top queries, growing pages, declining keywords, opportunities sitting at positions 5 to 20 - and interactive dashboards through MCP Apps in Claude Desktop.

The GSC web interface is fine for a quick glance. This is for when the question is bigger than the interface.

```bash
npx @houtini/better-search-console@latest
```

### 🎙️ **[Voice Analyser](https://github.com/houtini-ai/voice-analyser-mcp)** - teach an LLM to write like you
[![NPM Version](https://img.shields.io/npm/v/@houtini/voice-analyser)](https://www.npmjs.com/package/@houtini/voice-analyser)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/voice-analyser)](https://www.npmjs.com/package/@houtini/voice-analyser)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/voice-analyser-mcp?style=social)](https://github.com/houtini-ai/voice-analyser-mcp)

Extract your writing voice from published articles and generate a Claude Skill from it. A traditional style guide lists rules; this measures the statistical fingerprint of how you actually write - sentence rhythm, vocabulary patterns, argument flow, the micro-rhythms that make prose sound human - and teaches the model by example instead. Feed it your sitemap, get back a skill that mimics real samples. Experimental, but it works.

```bash
npx @houtini/voice-analyser@latest
```

### 🔍 **[Fan-Out MCP](https://github.com/houtini-ai/fanout-mcp)** - what your content covers, and what it misses
[![NPM Version](https://img.shields.io/npm/v/@houtini/fanout-mcp)](https://www.npmjs.com/package/@houtini/fanout-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/fanout-mcp)](https://www.npmjs.com/package/@houtini/fanout-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/fanout-mcp?style=social)](https://github.com/houtini-ai/fanout-mcp)

Content gap analysis using query decomposition and keyword fan-out - Google's own patented methodology. It tells you exactly which user queries a page answers, and which it leaves on the table. I built it on the academic research because I needed to understand how AI search engines actually evaluate content, not how we assume they do.

Self-RAG validation means no hallucinations: every coverage claim comes with an exact quote from your content.

```bash
npx @houtini/fanout-mcp@latest
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

### 📝 **[Content Marketing Ideas](https://github.com/houtini-ai/contentmarketingideas-mcp)** - the editorial research loop, automated
[![NPM Version](https://img.shields.io/npm/v/@houtini/contentmarketingideas)](https://www.npmjs.com/package/@houtini/contentmarketingideas)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/contentmarketingideas)](https://www.npmjs.com/package/@houtini/contentmarketingideas)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/contentmarketingideas-mcp?style=social)](https://github.com/houtini-ai/contentmarketingideas-mcp)

The MCP for [Content Marketing Ideas](https://contentmarketingideas.co), the editorial copilot I built because I was tired of the same research loop: you read a lot, notice patterns, get ideas, write. The reading and pattern-spotting is the slow part, and most of it is mechanical. This pulls the lot into Claude - source monitoring, editorial briefs, voice-matched drafts, RAG corpus search, Search Console data, WordPress publishing. Around 70 tools, one `npx`. Needs a free account for the API key.

```bash
npx @houtini/contentmarketingideas
```

### 🛒 **[Amazon Creators MCP](https://github.com/houtini-ai/amazon-creators-mcp)** - paste-ready affiliate cards, straight into the post
[![Install from source](https://img.shields.io/badge/install-from_source-5b5fff?style=flat-square)](https://github.com/houtini-ai/amazon-creators-mcp)
[![MCP Apps](https://img.shields.io/badge/MCP_Apps-inline_previews-8b5cf6?style=flat-square)](https://modelcontextprotocol.io)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/amazon-creators-mcp?style=social)](https://github.com/houtini-ai/amazon-creators-mcp)

Ask Claude to find Amazon products and it hands back embeddable affiliate cards - image, price, rating, your tag already baked in - previewed inline in Claude Desktop through MCP Apps before you paste a thing. Search the catalogue, look up specific ASINs, build a single card or a whole grid. Built on the Amazon Creators API, the REST replacement for Product Advertising API 5.0.

```bash
git clone https://github.com/houtini-ai/amazon-creators-mcp.git
cd amazon-creators-mcp && npm install && npm run build
```

### 📧 **[Brevo MCP](https://github.com/houtini-ai/brevo-mcp)** - email marketing without the context switch
[![NPM Version](https://img.shields.io/npm/v/@houtini/brevo-mcp)](https://www.npmjs.com/package/@houtini/brevo-mcp)
[![NPM Downloads](https://img.shields.io/npm/dt/@houtini/brevo-mcp)](https://www.npmjs.com/package/@houtini/brevo-mcp)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/brevo-mcp?style=social)](https://github.com/houtini-ai/brevo-mcp)

Brevo (formerly Sendinblue) from your AI assistant: contacts, lists, campaigns, templates, analytics, transactional sends - the full API without leaving your editor. If you're already on Brevo, this saves the tab-hop. If you're not, it's a solid free-tier platform to start on.

```bash
npx @houtini/brevo-mcp@latest
```

### 🎬 **[MCP Kling](https://github.com/houtini-ai/mcp-kling)** - Kling AI video generation in Claude
[![NPM Version](https://img.shields.io/npm/v/mcp-kling)](https://www.npmjs.com/package/mcp-kling)
[![NPM Downloads](https://img.shields.io/npm/dt/mcp-kling)](https://www.npmjs.com/package/mcp-kling)
[![GitHub stars](https://img.shields.io/github/stars/houtini-ai/mcp-kling?style=social)](https://github.com/houtini-ai/mcp-kling)

Full Kling AI access from Claude: text-to-video, image generation, lip-sync, effects, virtual try-on. 13+ tools across Kling v1.0 to v1.6 and KOLORS for images, with generated content saved locally automatically. Bring your own Kling API key.

```bash
npx mcp-kling
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

## Quick start

The flagship installs from source:

```bash
git clone https://github.com/houtini-ai/seo-audit.git   # SEO Audit Console - GSC + crawl + DataForSEO, ranked by recoverable clicks
```

The rest are one `npx` away - pick your flavour:

```bash
npx @houtini/lm@latest                           # Local LLM delegation (93% token savings)
npx @houtini/gemini-mcp@latest                   # Google Gemini integration
npx @houtini/geo-analyzer@latest                 # AI-search optimisation
npx @houtini/seo-crawler-mcp@latest              # Technical SEO crawl
npx @houtini/better-search-console@latest        # GSC data + dashboards
npx @houtini/voice-analyser@latest               # Writing-style extraction
npx @houtini/fanout-mcp@latest                   # Content gap analysis
npx @houtini/google-knowledge-graph-mcp@latest   # Entity data
npx @houtini/metacog --install                   # Agent proprioception + reinforcement
npx @houtini/fmp-mcp@latest                       # Financial market data
npx @houtini/yubhub@latest                        # Job feed pipeline
npx @houtini/contentmarketingideas                # Editorial research copilot
npx @houtini/brevo-mcp@latest                     # Email marketing
npx mcp-kling                                     # Kling AI video
```

Two more install from source, straight from their repos: **[Amazon Creators MCP](https://github.com/houtini-ai/amazon-creators-mcp)** (affiliate cards) and **[ai-detect](https://github.com/houtini-ai/ai-detect)** (`beta`, AI-content detection).

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
