# Eli Fayerman

Attorney and software engineer. I build AI tools that cite their sources and software that makes its rules explicit.

---

### Open Source

- **[Google Gemini CLI](https://github.com/google-gemini/gemini-cli)**: Proposed, designed and implemented native voice input with Gemini and local Whisper backends, recording controls, authentication integration and automated tests. Refined it through multiple rounds of maintainer review; the team ultimately shipped a separate implementation ([#18499](https://github.com/google-gemini/gemini-cli/pull/18499)). Also contributed a merged fix for false profiler warnings during extension startup ([#20101](https://github.com/google-gemini/gemini-cli/pull/20101)).
- **[danielmiessler/LifeOS](https://github.com/danielmiessler/LifeOS)** (formerly Personal AI Infrastructure): Merged a Google Cloud TTS voice provider ([#285](https://github.com/danielmiessler/LifeOS/pull/285)) and Linux compatibility fixes ([#288](https://github.com/danielmiessler/LifeOS/pull/288)).

---

### Current Work

🏃 **[RunningSchedule.com](https://runningschedule.com/?utm_source=github&utm_medium=profile&utm_campaign=pilot)**  
*Half and full marathon plans that explain every change.*

[![Pilot testers wanted: half and full marathon runners](https://img.shields.io/badge/%F0%9F%8F%83%20pilot%20testers%20wanted-half%20%26%20full%20marathon%20runners-FFD500?style=for-the-badge&labelColor=1f2328)](https://runningschedule.com/?utm_source=github&utm_medium=profile&utm_campaign=pilot)

**Looking for runners training for a half marathon or a marathon to test a free pilot.** It uses a transparent, deterministic rule engine that re-plans from evidence and explains every change in plain English. If you try it, reach out to tell me where the plan gets things wrong or misses something.

💡 **[1mil.app](https://1mil.app/?utm_source=github&utm_medium=profile&utm_campaign=1mil)**  
*Business opportunities matched to what you already know.*

Describe your field and what you're good at, and it searches the live web for business opportunities that fit, then ranks them. The top five come with named competitors and checked prices, so you can see what already exists before you build. **[Try it free, no signup required](https://1mil.app/?utm_source=github&utm_medium=profile&utm_campaign=1mil)**

📋 **[Startup Ideas Worth Building](https://github.com/fayerman-source/startup-ideas)**  
*Problems people describe in public, sorted by market.*

A public list of problem spaces drawn from discussions such as Reddit threads, each linked to the post it came from. Any idea on the list can be run through 1mil.app as a starting point for your own research.

⚖️ **[SERP-to-Spend](https://serptospend.com/?utm_source=github&utm_medium=profile&utm_campaign=serp-to-spend)**  
*Ad review grounded in legal and platform sources.*

Reviews ad copy for Meta, Google, and TikTok against FTC, FDA, and platform rules, and drafts new ads from live Google results. Each verdict names the policy area and legal standard it applies, drawn from a curated source library checked against primary legal texts and published platform policies. See [how the grounding works](https://serptospend.com/how-it-works?utm_source=github&utm_medium=profile&utm_campaign=serp-to-spend).

Next.js 15, TypeScript, Clerk, and Gemini on Vertex AI, with Claude as an alternate provider. Pull requests to main must pass type checks, tests, a build, and static analysis. The source is private; happy to walk through it.

---

### Tools I've Published

📈 **[Startup Growth Playbook](https://github.com/fayerman-source/startup-growth-playbook)**  
*Distribution-first marketing, run by your coding agent.*

Clone it into any startup repo and an LLM agent reads the codebase, picks the best 2 to 3 of 7 strategies, writes a plan with tasks and metrics, and produces the marketing artifacts.

✍️ **[Deslop](https://github.com/fayerman-source/deslop)**  
*Plain English for legal writing and AI prose.*

An agent skill for Claude Code, Antigravity, and similar tools that rewrites legalese and verbose AI text into plain English, built on plain-language drafting rules in the tradition of Bryan Garner. It keeps legal terms of art intact.

🧑‍💻 **[agent-team](https://github.com/fayerman-source/agent-team)**  
*Run several Claude Code sessions as a small dev team.*

A Claude Code plugin with roles (reviewer, coordinator, builders), a merge gate, and a hook that makes each session report where it stands. Its 31 rules are lessons from failures in real multi-session projects.

📹 **[Ring Camera Recorder](https://github.com/fayerman-source/ring-camera-recorder)**  
*Record your Ring cameras locally, no subscription.*

A self-hosted Node/TypeScript service that saves Ring live video to disk automatically on motion or doorbell events.

---

### Previous Work

🏅 **[Runium](https://runium.ai)**  
*An AI running coach with training-load limits built in.*

Co-founded Runium and built its AI coach: a probabilistic coaching engine with deterministic rule-based constraints, plus a chat coach that uses the training schedule as context and can adjust it. Python, FastAPI, and React. It reached private beta; I've since sold my stake.

Also from the running side: **[Race Replay](https://fayerman-source.github.io/race-replay/)** ([source](https://github.com/fayerman-source/race-replay)), which turns static track results into an animated race replay.

---

### About

I wrote production code at Thomson Reuters on financial data systems. After law school, I spent five years as an attorney with the SBA, advising on federal lending programs, disaster relief, and regulatory compliance.

Both jobs shape how I build now. SERP-to-Spend draws on a curated source library checked against primary legal texts and published platform policies. RunningSchedule changes a training plan through a purely deterministic rule engine. And code changes go through review before they merge: required checks, automated reviewers, and, when several AI sessions work at once, agent-team's merge gate.

Day to day: CLI-first, Linux on WSL2.

---

### Let's Connect

Open to connecting around AI, business opportunity discovery, and the intersection of law, systems, and product building.

Find me on [LinkedIn](https://www.linkedin.com/in/efayerman/) or [X](https://x.com/SadhakaDev).
