
# Hi, I'm Alex T. Rosen 👋

**AI systems · Full-stack software · Autonomous agents · Interactive 3D**

Cloud Consultant at **Spaulding Ridge** · Informatics, **Indiana University** · Chicago, Illinois  
[LinkedIn](https://www.linkedin.com/in/alexrosen03/) · [Portfolio repository](https://github.com/AlexRosen23/alextrosen-portfolio)

I build software that connects **AI, automation, simulation, and interactive experiences**. My projects range from multi-agent engineering tools and algorithmic trading research to robotics interfaces, geospatial digital twins, and games.

I develop with [Claude Code](https://claude.com/claude-code) as an AI engineering partner. **I set the direction, define requirements and architecture, review changes, run evaluations, and decide what ships; Claude writes much of the implementation.** That division of work is intentional and transparent. I care about whether a system is useful, testable, and reproducible—not who typed each line.

Most of my work connects through **[The Constellation](https://github.com/AlexRosen23/constellation)**: a local-first, interactive 3D command center where independent projects appear as explorable worlds and coding agents can be monitored in context.

## By the numbers

| Projects | Git commits | Measured Claude Code session time | Illustrative conventional-development effort |
|:--|:--|:--|:--|
| **~40** | **~2,700** | **~177 hours** | **~1,000–3,000 hours** |

*Snapshot of work since October 2026. The first three numbers are project/activity counts; the final figure is a rough scope-based estimate, assuming 25–75 hours of conventional solo development per project. It is **not measured time saved**, and the 177 hours reflect measured Claude Code sessions—not all human planning, review, or testing time. Project maturity and complexity vary.*

> **About private repositories:** Many projects remain private while I refine their architecture, tests, security boundaries, and integrations. Their READMEs describe purpose, stack, setup, and measured development activity. I'm happy to discuss the work and provide access when appropriate. Four are public with full write-ups: [Morrowglass Model Foundry](https://github.com/AlexRosen23/morrowglass-model-foundry), [The Inkfall Vault](https://github.com/AlexRosen23/inkfall-vault), [Spectral Canary Works](https://github.com/AlexRosen23/spectral-canary-works) and [Engineering case studies](https://github.com/AlexRosen23/engineering-case-studies).

## Flagship: The Constellation

### [The Constellation](https://github.com/AlexRosen23/constellation)

**One interactive environment for an expanding ecosystem of independent software.**

A local-first 3D command center that represents projects as worlds, connects engineering workflows, and shows where Claude Code and other coding agents are working. It brings together visualization, orchestration, project telemetry, and navigation without requiring each project to give up its own repository or runtime.

**Stack:** TypeScript · React Three Fiber · Node.js · SQLite  
**Repository activity:** 1,700+ commits · 355 merged PRs · 446 unit/integration test files and 133 end-to-end specs

## Selected projects

These are a few of the systems that best represent what I'm building:

| Project | Focus | What it does |
|---|---|---|
| [Morrowglass Model Foundry](https://github.com/AlexRosen23/morrowglass-model-foundry) | Language models · **public** | Small language-model lab: a decoder-only Transformer in plain PyTorch on public-domain Shakespeare, count-based baselines, pre-registered experiments and OpenAI-compatible serving |
| [The Inkfall Vault](https://github.com/AlexRosen23/inkfall-vault) | Retrieval & access control · **public** | Evidence workbench over fictional legal, finance and policy documents: access control before retrieval, word-for-word citations or abstention, and an audit log |
| [Spectral Canary Works](https://github.com/AlexRosen23/spectral-canary-works) | MLOps · **public** | Model-release lab: offline gates, shadow, a 10% canary with statistical guardrails and audited automatic rollback; real scikit-learn models, simulated traffic, plus an LLM prompt-release lane |
| [Scalp City](https://github.com/AlexRosen23/scalp-city) | Trading research | Paper-trading research platform with market experiments and a trading-city dashboard; **simulated only** |
| [Chicago Alive](https://github.com/AlexRosen23/chicago-alive) | 3D / geospatial | Open-data-driven Chicago digital twin built with Blender and Three.js |
| [ELARA Command Deck](https://github.com/AlexRosen23/elara-command-deck) | AI / hardware | Connects a 12-key physical macro pad to coding-agent and voice workflows |
| [The Arena](https://github.com/AlexRosen23/the-arena) | Agent evaluation | Reproducible competitions for tool-using AI agents with independent evaluation |
| [BLUEPRINT ZERO](https://github.com/AlexRosen23/blueprint-zero) | Generative CAD | Turns a sketch and written requirements into editable multi-part CAD with STEP/STL export |
| [Last Legend](https://github.com/AlexRosen23/LASTLEGEND) | Games / simulation | Public browser-based battle-royale simulator |

## Project directory

### AI agents & command centers

| Project | What it does |
|---|---|
| [Multi-AI Command Center](https://github.com/AlexRosen23/multi-ai-command-center) | Local control surface for Claude Code and six fallback coding agents |
| [ELARA Command Deck](https://github.com/AlexRosen23/elara-command-deck) | Physical macro-pad interface for coding agents and voice commands |
| [NexMacro for Mac](https://github.com/AlexRosen23/nexmacro-mac) | Native Swift macOS configurator for the macro pad |
| [The Arena](https://github.com/AlexRosen23/the-arena) | Reproducible agent tournaments with independent evaluation |
| [Claude Free Swarm](https://github.com/AlexRosen23/claude-free-swarm) | Claude Code-led orchestration of local and free-tier models, with MCP and CLI interfaces |
| [Claude Skills](https://github.com/AlexRosen23/claude-skills) | Custom development skills, efficiency tooling, and validation |

### AI engineering & ML systems

| Project | What it does |
|---|---|
| [Morrowglass Model Foundry](https://github.com/AlexRosen23/morrowglass-model-foundry) | Decoder-only Transformer from scratch in PyTorch, baselines, pre-registered ablations and a locked test split; every number read from a saved run (public) |
| [The Inkfall Vault](https://github.com/AlexRosen23/inkfall-vault) | Permission-aware evidence workbench: cited answers or abstention over fictional documents, two-person approval for briefs; runs on CPU (public) |
| [Spectral Canary Works](https://github.com/AlexRosen23/spectral-canary-works) | Release and rollback lab for ML models and an LLM prompt lane, with every decision in a hash-chained audit log (public) |
| [Iron Signal](https://github.com/AlexRosen23/iron-signal) | Predictive maintenance on NASA's simulated C-MAPSS turbofan data: DuckDB + dbt pipeline, remaining-useful-life models behind validation gates, drift replay |

### Generative maker tools

*Tools that turn natural-language instructions and real-world inputs into editable outputs.*

| Project | What it does |
|---|---|
| [BLUEPRINT ZERO](https://github.com/AlexRosen23/blueprint-zero) | Sketch + description → multi-part CAD assembly with STEP/STL export |
| [MAKESHIFT](https://github.com/AlexRosen23/makeshift) | Photos + caliper measurements → printable replacement parts with fit checks |
| [SKIN](https://github.com/AlexRosen23/skin) | Object dimensions + style prompt → printable custom shell |
| [FOLD](https://github.com/AlexRosen23/fold) | Description + object dimensions → 3D packaging and full-scale dielines |
| [SPARK](https://github.com/AlexRosen23/spark) | Described hardware reaction → state machine, simulation, ESP32 wiring, and firmware |
| [BRIDGE](https://github.com/AlexRosen23/bridge) | Plain-English mapping from keyboard, gamepad, or WebHID inputs to actions |
| [SYNAPSE Flow](https://github.com/AlexRosen23/synapse-flow) | Prompt-to-integration builder for typed, permission-scoped local workflows |
| [FRANKENAPP](https://github.com/AlexRosen23/frankenapp) | Prompt-driven app combinations built around user-owned data |
| [AIRWAVE](https://github.com/AlexRosen23/airwave) | Ten-finger, hand-tracked beat-making workstation in the browser |

### 3D, simulation & forecasting

| Project | What it does |
|---|---|
| [Chicago Alive](https://github.com/AlexRosen23/chicago-alive) | Blender + Three.js digital twin of Chicago using open geographic data |
| [Chronos](https://github.com/AlexRosen23/chronos) | Evidence-linked explorer for historical 3D reconstructions |
| [Mirror](https://github.com/AlexRosen23/mirror) | Photos-to-3D workflow that distinguishes recovered details from estimates |
| [Vanguard](https://github.com/AlexRosen23/vanguard) | Simulated warehouse robotics environment comparing classical planning and learned policies |
| [Oracle](https://github.com/AlexRosen23/oracle) | Auditable rainfall forecasts for 35 cities, with backtests and calibration |
| [Sentinel](https://github.com/AlexRosen23/sentinel) | Service observability and dry-run self-healing experiments |

### Games & interactive worlds

| Project | What it does |
|---|---|
| [Roblox Game Factory](https://github.com/AlexRosen23/roblox-game-factory) | AI-assisted Roblox game production with a local HQ dashboard |
| [Orbital Foundry](https://github.com/AlexRosen23/orbital-foundry) | Native macOS aerospace engineering sandbox built with Godot |
| [Project Meridian](https://github.com/AlexRosen23/project-meridian) | Expedition game using validated weather and earthquake data |
| [Last Legend](https://github.com/AlexRosen23/LASTLEGEND) | Public browser battle-royale simulator |

### Data, research & markets

| Project | What it does |
|---|---|
| [DataAtlas](https://github.com/AlexRosen23/dataatlas) | Interactive museum of 15 public-data experiences, including U.S. and NASA datasets |
| [NFL Big Data Bowl](https://github.com/AlexRosen23/NFL-Big-Data-Bowl) | Research pipeline and scouting app for the 2027 competition |
| [RecallRadar](https://github.com/AlexRosen23/recallradar) | Searchable, update-oriented NHTSA and CPSC recall explorer |
| [MacroKitchen](https://github.com/AlexRosen23/macro-kitchen) | USDA FoodData Central-powered recipe nutrition calculations |
| [Scalp City](https://github.com/AlexRosen23/scalp-city) | Short-duration options research and paper-trading experiments; no live trading claimed |
| [CYCLE 96](https://github.com/AlexRosen23/cycle96) | Paper-trading research for 15-minute prediction markets |
| [Linewise](https://github.com/AlexRosen23/linewise) | Sports-betting research and record-keeping; does not place bets |

### Products & personal projects

| Project | What it does |
|---|---|
| [PuzzleForge](https://github.com/AlexRosen23/puzzleforge) | Generator of machine-validated printable puzzle books |
| [DevForge](https://github.com/AlexRosen23/devforge) | Free browser-based developer utilities |
| [alextrosen.com](https://github.com/AlexRosen23/alextrosen-portfolio) | Space-themed personal portfolio built with Astro and Three.js |
| [Engineering case studies](https://github.com/AlexRosen23/engineering-case-studies) | Sanitized write-ups of four private projects: how each is built and tested, what went wrong, what was measured (public) |

## How I work

**AI-assisted, human-directed.** I use AI extensively for implementation while keeping project direction, architecture decisions, review, and release approval under my control.

**Branch-based development.** Each project has its own repository, with branches, pull requests, and secret scanning using gitleaks before pushes.

**Evidence over demos.** I distinguish live data from synthetic data, measured results from estimates, and working functionality from planned features.

**Reproducibility.** Project READMEs document the stack, setup process, and development activity. Claude Code usage is measured from session transcripts; prompt-cache reads are reported separately to avoid inflated totals.

**Tools I use:** TypeScript · React · Three.js / React Three Fiber · Node.js · Python · SQLite · Vite · Vitest · Playwright · Blender · Godot · Swift · Claude Code

---

*I'm interested in making AI-assisted engineering more capable, transparent, and measurable—and in building systems that become more useful when they're connected.*
