# Eli Fayerman

Attorney and software engineer building AI tools.

---

### Hackathons

🔬 **[Five Sigma Review](https://github.com/fayerman-source/five-sigma-review)**: Gemini 4 NYC Hackathon, Nov 2026  
*First-pass legal document review, with uncertain calls routed to a human.*

Built in one day. Each scanned page is transcribed, and each call (responsive, which request, privileged) is given a probability. A supporting quote is extracted for each call and matched against the page. A document is coded automatically only when the confidence is high and the quote matches. Every other document is routed to a human reviewer, with the reason. On 76 degraded Enron scans, 35 were coded automatically, and no labeler disputed a responsiveness or privilege call on any of those 35. The labels were made by models, not attorneys. [Demo video](https://youtu.be/DxOfqChEowc).

🏦 **[Cross Border FBAR](https://github.com/fayerman-source/cross-border-fbar)**: Meta Global AI Developer Hackathon, Indie Developer Track, Nov 2026  
*Foreign bank statements to FBAR figures, each linked to its source line.*

A review tool for tax preparers whose clients have foreign bank accounts. Each statement page is transcribed with Muse Spark: Korean, German, and Thai statements, flatbed scans, and sideways phone photos. Every balance is then recomputed in code, and each account's highest balance is converted at the Treasury year-end rate. The preparer clicks any figure to see its source line, corrects misreads, and signs off. On a 49-page synthetic test set, 280 of 280 transaction rows were transcribed correctly. The same pages, run on a local GPU with Muse Glimmer, Meta's open-weights model, produced the same total, so statements can stay on the preparer's machine. [Demo video](https://youtu.be/BL4UVxhOP9Y) · [Live demo](https://sadhakadev-fbar-worksheet-demo.hf.space).

---

### Open Source

- **[Google Gemini CLI](https://github.com/google-gemini/gemini-cli)**: Proposed, designed and implemented native voice input with Gemini and local Whisper backends, recording controls, authentication integration and automated tests, refined through multiple rounds of maintainer review ([#18499](https://github.com/google-gemini/gemini-cli/pull/18499)). Also contributed a merged fix for false profiler warnings during extension startup ([#20101](https://github.com/google-gemini/gemini-cli/pull/20101)).
- **[danielmiessler/LifeOS](https://github.com/danielmiessler/LifeOS)** (formerly Personal AI Infrastructure): Merged a Google Cloud TTS voice provider ([#285](https://github.com/danielmiessler/LifeOS/pull/285)) and Linux compatibility fixes ([#288](https://github.com/danielmiessler/LifeOS/pull/288)).

---

### Current Work

⚖️ **[SERP-to-Spend](https://serptospend.com/?utm_source=github&utm_medium=profile&utm_campaign=serp-to-spend)**  
*Ad review grounded in legal and platform sources.*

Ad copy for Meta, Google, and TikTok is reviewed against FTC, FDA, and platform rules, and new ads are drafted from live Google results. Each verdict names the policy area and the legal standard applied, from a source library checked against primary legal texts and published platform policies. See [how the grounding works](https://serptospend.com/how-it-works?utm_source=github&utm_medium=profile&utm_campaign=serp-to-spend).

Built with Next.js 15, TypeScript, Clerk, and Gemini on Vertex AI, with Claude as an alternate provider. The source is private.

🏃 **[RunningSchedule.com](https://runningschedule.com/?utm_source=github&utm_medium=profile&utm_campaign=pilot)**  
*Half and full marathon plans, with every change explained.*

[![Pilot testers wanted: half and full marathon runners](https://img.shields.io/badge/%F0%9F%8F%83%20pilot%20testers%20wanted-half%20%26%20full%20marathon%20runners-FFD500?style=for-the-badge&labelColor=1f2328)](https://runningschedule.com/?utm_source=github&utm_medium=profile&utm_campaign=pilot)

A free pilot for runners training for a half marathon or a marathon. Plans are adjusted by a deterministic rule engine, and each change comes with a plain-English reason. If you try it, tell me where the plan gets things wrong.

💡 **[1mil.app](https://1mil.app/?utm_source=github&utm_medium=profile&utm_campaign=1mil)**  
*Business opportunities matched to what you already know.*

Describe your field and what you're good at, and get a ranked list of matching business opportunities from a live web search. The top five come with named competitors and checked prices. A companion public list, [Startup Ideas Worth Building](https://github.com/fayerman-source/startup-ideas), collects problems people describe in public, each linked to its source post.

---

### Tools I've Published

📈 **[Startup Growth Playbook](https://github.com/fayerman-source/startup-growth-playbook)**  
*Distribution-first marketing, run by your coding agent.*

Clone it into any startup repo and run it with a coding agent. The output is a plan built on the best 2 to 3 of 7 strategies for that codebase, with tasks, metrics, and the marketing artifacts.

✍️ **[Deslop](https://github.com/fayerman-source/deslop)**  
*Plain English for legal writing and AI prose.*

An agent skill for Claude Code, Antigravity, and similar tools, for rewriting legalese and verbose AI text in plain English. It is built on plain-language drafting rules in the tradition of Bryan Garner, and legal terms of art stay intact.

🧑‍💻 **[agent-team](https://github.com/fayerman-source/agent-team)**  
*Run several Claude Code sessions as a small dev team.*

A Claude Code plugin with roles (reviewer, coordinator, builders), a merge gate, and a status report required from each session. Its 31 rules come from failures in real multi-session projects.

📹 **[Ring Camera Recorder](https://github.com/fayerman-source/ring-camera-recorder)**  
*Record your Ring cameras locally, no subscription.*

A self-hosted Node/TypeScript service for saving Ring live video to disk on motion or doorbell events.

---

### Previous Work

🏅 **[Runium](https://runium.ai)**  
*An AI running coach with training-load limits built in.*

Co-founded Runium and built its AI coach: a probabilistic coaching engine with deterministic rule-based constraints, plus a chat interface with the training schedule as context, where the schedule can be adjusted. Python, FastAPI, and React. It reached private beta; I've since sold my stake.

Also from the running side: **[Race Replay](https://fayerman-source.github.io/race-replay/)** ([source](https://github.com/fayerman-source/race-replay)), an animated race replay built from static track results.

---

### About

I wrote production code at Thomson Reuters on financial data systems. After law school, I spent five years as an attorney with the SBA, advising on federal lending programs, disaster relief, and regulatory compliance.

Both jobs shape how I build: legal sources are checked against primary texts, rules are deterministic where they can be, and code changes go through review before they merge.

Day to day: CLI-first, Linux on WSL2.

---

### Let's Connect

Open to connecting about AI, legal engineering, and business opportunity discovery.

Find me on [LinkedIn](https://www.linkedin.com/in/efayerman/) or [X](https://x.com/SadhakaDev).
