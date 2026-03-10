# Hey, I'm Sourabh 👋

7 years shipping software. Now building AI agents that do real work.

### About Me

- 7+ years building production software across startups and enterprise SaaS
- Currently diving deep into open source and the AI agent ecosystem
- Based in Bengaluru, India

---

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Puppeteer-40B5A4?style=flat&logo=puppeteer&logoColor=white" alt="Puppeteer" />
  <img src="https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel AI SDK" />
  <img src="https://img.shields.io/badge/LLM_Orchestration-8A2BE2?style=flat" alt="LLM Orchestration" />
</p>

---

### Projects

**Closed Source**

- [chromext.app](https://www.chromext.app/) — Chrome extension for flash-sale automation. 5,000+ active users
- [lootkar.com](https://www.lootkar.com/) — Multi-agent shopping assistant for Indian e-commerce (in development)

**Open Source**

- [sotto](https://github.com/sourabhbgp/sotto) — Voice input for Claude Code via local whisper.cpp
- [ecom-extract](https://github.com/sourabhbgp/ecom-extract) — Extract structured product data from any e-commerce URL
- [dikto](https://github.com/diktoapp/dikto) — Voice-to-text for macOS. Local transcription via Whisper + Parakeet. No cloud. (Rust, SwiftUI)

---

### What I'm Working On

**Twitter Agent** *(coming soon — open source)*

CLI-first autonomous Twitter engagement agent. You define workflows (follower-growth, hashtag-niche, or custom), and the agent runs on autopilot — fetching your feed from three sources (mentions, timeline, keyword discovery), having Claude analyze each tweet, and taking actions (reply, like, quote, retweet, follow) within configurable rate limits.

What makes it interesting:
- **Workflow system** — Each workflow has its own strategy prompt, action biases (heavy/moderate/light per action type), feed filters, watch accounts, and isolated memory
- **Graph memory (Neo4j)** — Tracks per-handle relationship strength, reply-back rates, topic history, and interaction patterns. This context is injected into Claude's system prompt so it knows "I've talked to this person 12 times about AI agents, they reply back 40% of the time"
- **Scheduling** — Cron-based job scheduler with platform-native backends (launchd on macOS, systemd on Linux, in-process daemon for Docker). Set it and forget it
- **Safety guardrails** — Spam pre-filtering, blocked account lists, session/daily action caps, global safety state shared across workflows
- **Two modes** — Auto (Claude decides everything) and manual (interactive approve/edit/skip loop per tweet)

Built with Bun, TypeScript, Commander.js, Anthropic SDK, and rettiwt-api. Includes a read-only Next.js dashboard for monitoring.

---

### Connect

<p>
  <a href="https://twitter.com/sourabhbgp"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white" alt="Twitter" /></a>
  <a href="https://www.linkedin.com/in/sourabhbgp/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>
