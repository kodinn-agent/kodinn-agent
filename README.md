# <img src="./kodinn-logo.svg?v=4" alt="Kodinn Logo" width="160px" align="center" /> Kodinn
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@Kodinn-IA)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com//company/kodinn)
> An intelligent, autonomous AI coding assistant built to streamline development workflows, automate repetitive tasks, and help developers write cleaner code faster.

---

### ✨ Features

- Kodinn is a desktop AI workspace and agent for Windows (macOS coming soon). It writes code, runs commands, works with Git, handles mail/notes/documents, and supports 30+ AI providers or fully offline local models. - All data stays encrypted on your computer.Core / Why Kodinn
- **Data always encrypted — Database, conversations, credentials and mail encrypted at rest with a key derived from your PIN.
### PrivacyGuard — Masks names, emails, IBANs, tax codes and keys (with real validators across 32 countries) before any message leaves your computer; restores real values in the answer.
- **Many models, one team — 30+ preconfigured providers, multiple instances, different model per role, automatic failover. No lock-in.
- **Offline when you want — Local models run inside Kodinn on CPU or GPU via DesireeIA. No network, no account, no per-token cost.
### QualityGuard — Static analysis across 27 languages with a Quality Gate used by the agent on the code it writes.
- **Caveman(by Digitalsolutions c# suite) — Compresses conversation context instead of cutting it; routes by content type, aligns with provider cache, protects critical content.
- **Real application — Sessions, chat, Git, diff, browser and panels side-by-side. Interface in Italian, English and Chinese.
- **Extensible without restarting — Hot-installable plugins, each with its own encrypted database and explicit consent.
### Code Studio (full development environment)
- **Complete IDE: menus, solutions, editor, language servers, build, debug, tests, quality and Git in one window.
- **29 ready-to-use language servers (C# / Roslyn with Razor & Blazor, TypeScript, Python, Go, Rust, C/C++, Java, PHP, Dart, and many more).
- **6 built-in debuggers (.NET, Python, Node.js, Go, Rust/C/C++, PHP) with conditional breakpoints and watches.
- **13 bottom panels: errors, output, build, debug, QualityGuard, outline, references, hierarchy, breakpoints, NuGet, npm, terminal, tests.
- **10 IDE-style menus (File, Edit, View, Project, Build, Debug, Test, Tools, Help, Window).
- **Full IntelliSense (completion, hover, go-to-definition, rename, quick fixes, formatting, references, CodeLens, inlay hints, etc.).
- **Monaco editor with minimap, breadcrumbs, sticky scroll, multi-cursor, Emmet, .editorconfig support, VS Code snippets.
- **Build / Run / Debug for .NET, Node, Rust, Go, Python, Java, PHP, C/C++ (launch profiles from Visual Studio / VS Code).
- **Tests & coverage (discovery, run all/project/single, debug, Cobertura coverage in editor margin).
- **QualityGuard always on + QualityCode (report sent to AI with order to fix).
- **Full-screen Git integration (graph, diff, rebase, stash, PRs, merge conflict resolution).
- **NuGet / npm consoles, package management, VSIX extensions from Open VSX (themes, snippets, grammars — code never executed).
- **Tasks from .kodinn/tasks.json or .vscode/tasks.json, multi-shell terminal.
- **AI docked beside the code: agent reads/edits/builds, Plan-only mode, plain chat, 7 file actions (explain, write tests, document, refactor, review, fix errors, answer).
- **Three orchestration modes: single, plan (planner + executor), review (with reviewer).
- **Supports opening solutions, projects and workspaces for many stacks (including Flutter, CMake, etc.).
### Kodinn AI / Agent
- **AI lives inside every module (not a bolted-on chatbot).
- **Local — DesireeIA runs GGUF models on CPU/GPU.
- **Remote — 30+ providers (OpenAI-compatible, Azure, Anthropic, Ollama, etc.).
- **Orchestrated — 32 roles + 19 orchestration patterns; different model per role, automatic failover, per-minute limits, timeout watchdog.
- **~80 tools (files, search, shell, build, Git, browser, memory, databases…), each with allow/ask permission.
- **Undoable edits with per-file diff, plan mode, sub-agents and teams.
- **Credentials never exposed to the model (stay in vault).
- **Action bar: Analyze, Debug, Implement, Refactor, Explain, Test, Team.
- **Telemetry panels for tokens, cost, limits, permissions, active processes.
### QualityGuard
- **Static analysis for 27 languages (C# to Python, Terraform, Kubernetes…).
- **~3,980 rules (639 security rules) with data-flow analysis.
- **A–E ratings for security, reliability, maintainability.
- **Quality Gate (PASSED / FAILED) with conditions.
- **Bugs, vulnerabilities, hotspots, code smells, duplication and technical debt in one panel.
- **DesireeIA (proprietary local inference engine)
- **Native C++17 core + .NET API.
- **Detects hardware (CPU features, GPU, NPU, RAM).
- **Automatic plan for RAM budget, threads, quantization and format.
- **Supports GGUF and safetensors; multi-architecture dense models; MoE with streaming experts + LRU cache; compressed KV cache.
- **Backends (priority): Axelera NPU → NVIDIA CUDA → Intel Arc → Apple Metal → CPU.
### Fully offline, in-process.
- **Local Model Hub
- **Compares models against your actual RAM / VRAM / NPU (“Fits this PC”, “Tight on memory”, “Too big”).
- **Trusted sources (Hugging Face, recommended, favorites, trusted publishers).
- **Resumable downloads with fingerprint verification.
- **Automatic parameter selection by DesireeIA.
- **Model Catalog (remote)
- **Merges public sources (238+ providers, 9,000+ models).
- **Specs, costs (auto-refreshed, never guessed), connection and security info.
- **35 providers preconfigured with multiple instances.
### Skills Market
- **47 ready-made skills (install / enable / disable in one click).
- **Import from Claude Code, OpenCode, Agents, folder or GitHub.
- **Create your own (SKILL.md + rules).
- **Full transparency (overview, parameters/scripts, permissions/safety, files/origin).
- **Agent can list, read and run them (also via /skills and MCP).
- **Other Markets
- **Python Market — Curated packages + full PyPI in isolated environment; vulnerability/update checks; script library the agent can run.
- **Extensions Market — Open VSX themes, snippets, TextMate grammars, language configs (code never executed; license checks).
- **IDE / CI-CD Integrations
- **Full-screen Git — Complete Git client + AI commit messages / explanations / reviews.
- **Azure DevOps — Dashboard, Boards, Pipelines, Releases, Test plans, Code, Resources. AI assistant (permission per organization). Agent cannot approve/complete PRs or deploy.
- **AWS — S3, EC2, Lambda, ECS, CodePipeline, CodeBuild, CodeDeploy, CloudFormation, CloudWatch, costs. IAM keys encrypted; agent cannot terminate instances or delete critical resources.
- **FTP / SFTP / FTPS / S3 / WebDAV / Storj — Two-pane client with queue, site manager, AI chat that can list/read/transfer (with confirmation).
- **RDP — Remote Desktop client; AI can drive the session (mouse, keyboard, screen) under permissions.
- **Agents / Orchestration
- **Advisor Flow: Lead + parallel background sub-agents + Advisor that intervenes only at specific points (before plan, repeated error, before done, critical file).
- **32 roles + 19 patterns (pipeline, router, fan-out, hierarchical, generator-critic, debate, ensemble…).
- **Server groups for load balancing of local models.
- **PE-IDIS (Prompt Engineering Lab)
- **Prompt as graph (system, context, guardrails, schema, branches, output).
- **Token probe (probabilities, entropy, attention with local models).
- **Text scoring, Monte Carlo benchmarks, node importance analysis, A/B comparison.
- **Evolutionary auto-compiler for improved prompts.
### Voice
- **Always-on microphone with speech detection.
- **Sentence-by-sentence local transcription (Whisper) — voice never leaves the PC.
- **Auto-send on natural pause. Supports Italian, English, Chinese.
### Modules (full workplace suite)
- **EmailFlow — Full IMAP/SMTP client (OAuth, rules, identities, scheduled/undoable send). Agent reads, summarises, translates, drafts (never sends alone).
- **MemoFlow — Kanban board, notes, calendar, reminders, daily planner. Natural-language entry (“call Marco tomorrow at 3pm”). AI plans your day.
- **Sinapsi — REST, SOAP, GraphQL, WebSocket client with collections, environments, OAuth 2, test scripts, OpenAPI/Postman/cURL import. Agent can call APIs (credentials hidden).
- **Archive & GraphRAG — Encrypted knowledge base + concept graph. Agent searches with citations.
- **Database Manager — PostgreSQL, MySQL, SQL Server, Oracle, MongoDB (multiple instances). Enforced read-only for agent; schema-aware query assistant.
- **Browser — Built-in browser the agent can drive in the same session (navigate, click, type, capture). Per-domain policy.
- **Terminal — Multi-shell; agent runs commands under permission + optional sandbox.
- **Vault — PIN-encrypted password/token store. Model never sees contents.
- **MCP — Client (auto-detect servers) + Server (expose Kodinn tools to Claude Desktop, VS Code, Cursor…).
- **Plugins — Public SDK, hot install, explicit consent, per-plugin encrypted DB.
- **79 connectors — Slack, Teams, Telegram, WhatsApp, GitHub, GitLab, Jira, Stripe, Salesforce, Notion, AWS services and more. Credentials from vault.
- **Desktop control — Agent moves mouse, types, uses shortcuts, captures screen (always behind permission).
- **Telemetry — Live tokens, costs, limits, timeouts, permissions.
- **Encryption at rest — Everything encrypted with PIN-derived key.
- **Chat web server — Embedded server per chat for instant previews.
- **Cowork (coming soon) — Teams of up to 5 people (digitalsolutions.it accounts); prompts and local settings stay private.
- **Comparison highlights vs Claude Code / OpenCode / LangChainKodinn is a full desktop application (not just a terminal or library) with built-in encryption, PrivacyGuard, multi-provider orchestration, offline models, QualityGuard, browser, mail, notes, vault, API client, desktop control, plugins with consent, and Italian/English/Chinese UI.All features are listed as presented on the official page (as of the latest available content).

---
