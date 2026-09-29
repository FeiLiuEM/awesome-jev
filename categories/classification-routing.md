# Classification & Routing

Use this category for programs where Jev sorts incoming state into categories or picks the next destination — tickets, intents, alerts, documents, or traffic.

## Submission format

```md
- [Name](URL) - Industry: one-sentence description of the Jev use case.
```

## Entries

- [Diffusion Jev](https://github.com/Hangzhi/diffusion-jev-sglang) - Visual classification: independent Jev-style DiffusionGemma/SGLang server that selects doodle and flower labels from image pixe[...]
- [Notra](https://github.com/usenotra/notra) - Marketing analytics: production GEO platform whose `NOTRA_JEV_CLASSIFIERS` flag routes brand-visibility classifiers off an LLM and onto Jev `Boolean`[...]
- [jev-router](https://github.com/gargpratyush/jev-router) `{agent: multi}` - Developer tooling: routes Claude Code tasks to the cheapest capable model by asking Jev to choose among candidates.
- [jev-router (prismhq)](https://github.com/prismhq/jev-router) - LLM infrastructure: open-source LiteLLM-based router where a Jev decision picks which model serves each request.
- [pi-jev-router](https://github.com/mejiasd3v/pi-jev-router) `{agent: pi}` - Coding agents: adds automatic per-request model routing to the Pi coding agent through Jev decisions on Vercel AI Gate[...]
- [jcm-router](https://github.com/adarshmishra07/jcm-router) - Coding agents: local proxy that picks the Claude model and reasoning effort per message with a Jev decision while leaving the cached [...]
- [Codex Jev Router](https://github.com/suenot/codex-jev-router) `{agent: codex}` - Coding agents: asks Jev Choice and Noul questions about a short task summary to select a Codex subagent model an[...]
- [Jev Auto Router](https://github.com/miniLV/Jev-Auto-Router) `{agent: codex, type: proxy}` - Coding agents: per-call Codex GPT routing where Jev makes one typed Choice over host-available (model[...]
- [Harness Router](https://github.com/Protocol-Lattice/harness-router) `{agent: multi}` - Coding agents: framework-agnostic tool router that keeps obvious calls on a fast path, uses Jev for genuin[...]
- [jev-agent-skill-router](https://github.com/GodsBoy/jev-agent-skill-router) - Agent infrastructure: routes agent skill selection through typed, confidence-aware Jev decisions so weak matches are[...]
- [typesafe-jev CV screener](https://github.com/gtaras7/typesafe-jev) - Recruiting: screens a folder of CVs with Jev typed judgments against an editable policy, re-scoring candidates for free when[...]
- [Jev email intent workflow](https://github.com/GiesN/typesafe-jev-workflow) - Back-office automation: async LangGraph workflow gets a typed Jev `Choice` (`invoice` or `general`) and routes each [...]
- [DiffJury](https://github.com/raihankhan-rk/diffjury) - Code review: routes each pull request by risk with Jev before a human reviewer is assigned, doubling as a review coach.
- [HA-Jev](https://github.com/AboveColin/HA-Jev) - Smart home: Home Assistant integration that answers questions about the house as a probability, a choice, or a score.
- [secondlayer](https://github.com/ryanwaits/secondlayer) - Fault triage: self-hosted Stacks data service whose Slack gate and fault-triage paths both run on Jev decisions.
- [jev-logtriage](https://github.com/jyatesdotdev/jev-logtriage) - On-call operations: batches collapsed Loki logs into one Jev call of Noul, Score, and Choice questions, then maps answers in code[...]
- [new-api-typesafe-plugin](https://github.com/FFatTiger/new-api-plugin-typesafe) - LLM gateway: adds a native `/v1/systemone` endpoint to new-api so typed decisions sit behind the same gateway as[...]
- [duet-agent](https://github.com/dzhng/duet-agent) - Agent harness: keeps a Jev-backed routing table for deciding which model should serve a request.
- [omo-jevlike-router](https://github.com/islee23520/omo-jevlike-router) - Skill routing: shrinks the skill catalog in a system prompt with one forward pass over a frozen Qwen, routing each reques[...]
- [jev-cookbook](https://github.com/nexibeo/jev-cookbook) - Developer education: 15 runnable Node recipes that route support tickets, file documents, categorize bank transactions and label Gmail w[...]
- [flue-jev-demo](https://github.com/matthewp/flue-jev-demo) - Agent routing: routes a Flue agent's work with Jev through Cloudflare AI Gateway.
- [DocJev](https://github.com/jerryjliu/docjev) - Document pipelines: LlamaIndex's open-source library that classifies a document against natural-language category rules or finds the boundaries be[...]
- [jev-fit](https://jev-fit.com) - Developer tooling: hosted fit checker that sends a pasted software idea and a fixed typed rubric to Jev in one call, where a `Choice` picks plain code, Jev or a [...]
- [jev-skill-router](https://github.com/shimo4228/jev-skill-router) `{agent: claude-code, type: plugin}` - Coding agents: Claude Code plugin whose UserPromptSubmit hook asks Jev one `Choice` over [...]
- [Jev Wrapped](https://github.com/gaborishka/jev-wrapped) - Media analysis: reads up to 1,500 posts from the last year of a public Telegram channel and asks Jev a `Choice` over ten kinds of post [...]
- [Jev-Mail](https://github.com/vynnlee/jev-mail) - Email productivity: runs a 24/7 Gmail classifier on user-owned Google Apps Script where Jev scores urgency, importance, and category, routing un[...]
- [AI-decision-maker](https://github.com/zlZayn/AI-decision-maker) - Data cleaning: asks Jev `Choice` questions to classify CSV columns into a 13-code type vocabulary and each dataset into one of [...]
- [hearth-jev-rental-search](https://github.com/Nancy-Chauhan/hearth-jev-rental-search) - Housing search: autonomous multi-source rental search where Jev decides which listings match the criteria.
- [pi-jev-skill-picker](https://github.com/safzanpirani/pi-jev-skill-picker) `{agent: pi}` - Coding agents: ranks the Pi agent's installed skills against the current task with Jev before any of th[...]
- [Jevonian](https://github.com/xinyao27/jevonian) - Coding agents: local OpenAI/Anthropic-compatible proxy where one Jev call picks both the model route and the thinking level for `jevonian/auto`[...]
- [Switchboard](https://github.com/ruban-24/switchboard) `{agent: multi, type: proxy}` - Coding agents: open-source System One-powered router that automatically matches each Claude Code or Codex t[...]
- [Tab Sorter](https://github.com/AstonyCat/jev-tab-grouper) - Browser tooling: Chrome MV3 extension that groups every tab in the window into named, colored Chrome tab groups from one parallel Jev[...]
- [Feed Lens](https://github.com/SkywalkerDarren/feed-lens) `{type: extension}` - Social media: uses Jev `Noul` judgments against per-platform, user-defined topic and expression labels to annotate[...]
- [jev-table-import-mapper](https://github.com/DuvInc/jev-table-import-mapper) - Data import: maps an uploaded CSV's columns onto a destination table with a strict deterministic name-equality pass[...]
- [jev-oncall](https://github.com/mingleiw/jev-oncall) - On-call operations: asks Jev one call of four typed questions per alert (`Noul` actionable, `Score` severity, `Choice` owning team, `Choice[...]
- [Jevidence](https://github.com/peakevergreen/jevidence) - Developer education: Python sandbox asks Jev `Choice` and `Noul` questions about issue category and reproduction steps in opt-in live mo[...]
- [JevBystander](https://github.com/Nisaka520/JevBystander) - Messaging: Android accessibility app that reads the visible WeChat chat window and answers one batched request of typed `Choice`, `Sco[...]
- [langchain-skill-router](https://github.com/deyna256/langchain-skill-router) - Agent infrastructure: per-turn skill routing for LangChain deepagents, where Jev ranks the SKILL.md catalog against[...]
- [jev-rental](https://github.com/klauswg/jev-suite/tree/master/jev-rental) - Consumer rental: sorts every claim in a rental listing into verify-on-site / demand-evidence / high-risk-pitch buckets[...]
- [jev-resume-disqualifier](https://github.com/AiPersonacademy/jev-resume-disqualifier) - Recruiting: knocks a resume out of a pipeline in under 25 ms by asking Jev the disqualifying question firs[...]
- [Jev-IOT](https://github.com/pjmenon45/Jev-IOT) - Smart Utilities & Telecommunications: Ultra-low-cost, non-autoregressive AI telemetry classifier enabling sub-150ms anomaly triage and autonomic[...]
- [AgentScope](https://github.com/agentscope-ai/agentscope) - Multi-agent platforms: multi-agent platform by Alibaba implementing native TypeSafe Jev classification models for binary, choice, and [...]
- [inbox-zero](https://github.com/elie222/inbox-zero) - Email productivity: open-source AI email assistant that uses TypeSafe Jev System One decision models to classify incoming email intent and t[...]
- [SiYuan](https://github.com/siyuan-note/siyuan) - Knowledge management: privacy-first personal knowledge management system featuring native Jev decision model integration for high-speed document[...]
- [Paca](https://github.com/Paca-AI/paca) `{type: self-hosted}` - Project management: self-hosted open-source Jira alternative that auto-assigns tasks with a Jev `Choice` over member descriptions,[...]
- [Qualm](https://github.com/RoderickQiu/qualm) - Digital wellbeing: macOS menu bar app that reads the screen as text through the Accessibility API and asks Jev (or Kev, its local open-source coun[...]
- [Auto-optimizing Jev: half the errors, 1/7 the cost](https://kiln.tech/blog/auto_optimizing_jev_with_autoresearch) - Text classification: asks Jev a `Choice` over the readings of a Chinese polyp[...]
- [spending-effort-with-jev](https://github.com/Yaxin9Luo/spending-effort-with-jev) `{agent: claude-code, type: plugin}` - Coding agents: Claude Code plugin whose UserPromptSubmit hook asks Jev a [...]
- [tab-jev](https://github.com/edamame-labs/tab-jev) `{type: library}` - Tabular prediction: asks Jev a `Noul` on the target plus `Score` rubrics about each row's text, turns every option's probab[...]
- [tinystruct-typesafe-sdk](https://github.com/tinystruct/tinystruct-typesafe-sdk) - SDK: TypeSafe Jev integration library for building type-safe classification and routing decisions with structured outputs.
