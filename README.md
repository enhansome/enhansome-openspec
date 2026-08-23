# Awesome OpenSpec with stars

> A curated list of awesome OpenSpec resources, tools, and Spec-Driven Development (SDD) resources.

OpenSpec is a lightweight, open-source spec-driven development framework that
helps AI coding assistants follow instructions more effectively. It works with
30+ tools including Claude Code, Cursor, GitHub Copilot, and more.

Browse this list as a searchable website with live star counts at
[speclib.github.io/awesome-openspec](https://speclib.github.io/awesome-openspec/).

## Contents

* [Key Concepts](#key-concepts)
* [Official Resources](#official-resources)
* [UIs](#uis)
* [Tools](#tools)
* [OpenSpec as Integration or Plugin](#openspec-as-integration-or-plugin)
* [Schemas & Extensions](#schemas--extensions)
* [Templates & Starters](#templates--starters)
* [GitHub Actions](#github-actions)
* [Videos](#videos)
* [Articles & Tutorials](#articles--tutorials)
* [Community](#community)
* [Exotic Use Cases](#exotic-use-cases)
* [Competitors & Comparisons](#competitors--comparisons)
* [Related Projects](#related-projects)

## Key Concepts

### What is Spec-Driven Development

<!--lint disable awesome-list-item-->

Spec-Driven Development (SDD) is a methodology where you and your AI coding assistant agree on what to build before any code is written. OpenSpec implements this through:

* **Proposals** - Structured change requests with technical designs
* **Specifications** - Living documentation that captures functional requirements
* **Task Checklists** - Implementation tasks with AI guidance
* **Archives** - Completed changes preserved for reference

### Core Workflow

```
/opsx:explore → /opsx:propose → /opsx:apply → /opsx:verify → /opsx:archive
```

### Why OpenSpec

* **Universal** - Works with 30+ AI coding assistants
* **Open Source** - MIT licensed, no vendor lock-in
* **No API Keys** - Runs locally without external dependencies
* **Brownfield-First** - Designed for mature codebases, not just greenfield projects
* **Persistent Context** - Specs live in your repo alongside code

 <!--lint enable awesome-list-item-->

## Official Resources

* [Getting Started Guide](https://github.com/Fission-AI/OpenSpec/blob/main/docs/getting-started.md) ⭐ 65,981 | 🐛 200 | 🌐 TypeScript | 📅 2026-08-23 - Official getting started documentation.
* [OpenSpec](https://github.com/Fission-AI/OpenSpec/) ⭐ 65,981 | 🐛 200 | 🌐 TypeScript | 📅 2026-08-23 - Official OpenSpec CLI. Spec-driven development (SDD) for AI coding assistants.
* [npm Package](https://www.npmjs.com/package/@fission-ai/openspec) - Official npm package for installation.
* [OpenSpec Pro](https://openspec.pro/) - Additional OpenSpec resources and documentation.
* [OpenSpec Website](https://openspec.dev/) - Official website with documentation and getting started guide.

## UIs

* [OpenSpecUI](https://github.com/jixoai/openspecui) ⭐ 103 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-19 - Web interface for OpenSpec workflows with live mode and static export support.
* [Spek](https://github.com/spekhq/spek) ⭐ 47 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-19 - Read-only viewer with BDD highlighting and full-text search for web, VS Code, and IntelliJ.
* [openspec-ui](https://github.com/ToruAI/openspec-ui) ⭐ 28 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27 - Real-time Kanban dashboard for tracking changes across multiple repositories.
* [speclens](https://github.com/dansreis/speclens) ⭐ 23 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-17 - Desktop reader for tracing requirement evolution and commenting on specs.
* [dossier](https://github.com/fselich/dossier) ⭐ 13 | 🐛 4 | 🌐 Go | 📅 2026-07-23 - Keyboard-driven TUI for navigating proposals, designs, specs, and tasks.
* [openspec-webui](https://github.com/oioi555/openspec-webui) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20 - Interactive browser UI for browsing and managing specifications.
* [openspec-viewer](https://github.com/MusicAdam/openspec-viewer) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-05 - Browser viewer with live reload, markdown rendering, and full-text search.
* [Specboard](https://github.com/sflueckiger/specboard) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-17 - Web dashboard for monitoring progress across workspaces with swimlane visualization.

## Tools

* [spec-gen](https://github.com/clay-good/spec-gen) ⭐ 289 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-23 - Reverse-engineers OpenSpec specs from existing codebases via static analysis and LLMs.
* [ralphy-openspec](https://github.com/wenqingyu/ralphy-openspec) ⭐ 182 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-27 - Combines OpenSpec with Ralph Loop for iterative AI-assisted coding.
* [Coding Corgi Flow](https://github.com/ricoyudog/Coding_Corgi_flow) ⭐ 103 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-19 - OpenSpec GitFlow with structured AI workflows and issue tracking.
* [gitguardex](https://github.com/opencue/gitguardex) ⭐ 25 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-17 - Runs parallel coding agents in isolated worktrees with OpenSpec auto-wired.
* [openspec-agents](https://github.com/gmf520/openspec-agents) ⭐ 17 | 🐛 0 | 🌐 PowerShell | 📅 2026-05-03 - State-machine multi-agent framework built on OpenSpec docs. (Chinese)
* [openspec-playwright](https://github.com/wxhou/openspec-playwright) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-22 - Playwright E2E testing with a self-healing three-agent pipeline.
* [veriplan](https://github.com/autonomous-toaster/veriplan) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-08-13 - Formal verification of plans by translating requirements to LTL for SPIN.
* [OmniDev Kit](https://github.com/zy-eagle/omnidev-kit) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-18 - Toolkit combining OpenSpec with cross-session memory and project intelligence.
* [OpenSpec.sh](https://github.com/biancalana/OpenSpec.sh) ⭐ 4 | 🐛 1 | 🌐 Shell | 📅 2026-01-19 - Minimal POSIX shell implementation of OpenSpec CLI for environments without Node.js.

## OpenSpec as Integration or Plugin

* [openflow](https://github.com/fastknifes/openflow) ⭐ 180 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-04 - OpenCode companion plugin combining OpenSpec with Superpowers.
* [opencode-plugin-openspec](https://github.com/Octane0411/opencode-plugin-openspec) ⭐ 157 | 🐛 5 | 🌐 TypeScript | 📅 2026-03-24 - OpenCode plugin with Architect mode for spec-only writes.
* [ClawSpec](https://github.com/bytegh/clawspec) ⭐ 42 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-29 - OpenClaw plugin bringing OpenSpec workflows into chat with background execution.
* [claude-plugin-sdd](https://github.com/joestump/claude-plugin-sdd) ⭐ 31 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19 - Claude Code plugin for SDD with ADRs, OpenSpec specs, and sprint planning.
* [Flokay](https://github.com/pacaplan/flokay) ⭐ 30 | 🐛 1 | 🌐 Shell | 📅 2026-07-29 - Claude Code and Cursor plugin with plan-then-implement workflow and subagent dispatch.
* [openspec-mcp](https://github.com/Lumiaqian/openspec-mcp) ⭐ 30 | 🐛 2 | 🌐 TypeScript | 📅 2026-01-12 - MCP server exposing the OpenSpec CLI as tools, with a Kanban web dashboard.
* [openspec-for-copilot](https://github.com/atman-33/openspec-for-copilot) ⭐ 22 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-22 - VS Code extension integrating OpenSpec with GitHub Copilot Chat.
* [OpenSpec-Zed](https://github.com/uwzis/OpenSpec-Zed) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-03-13 - Zed editor extension adding OpenSpec workflow slash commands to the Assistant panel.
* [openspec-superpowers-opencode](https://github.com/moyaspace/openspec-superpowers-opencode) ⭐ 14 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-10 - Superpowers and OpenSpec combined in OpenCode.
* [openspec-skills](https://github.com/chyiiiiiiiiiiii/openspec-skills) ⭐ 12 | 🐛 0 | 📅 2026-01-25 - Spec-Driven Development skills for Claude Code.
* [claude-connoisseur](https://github.com/eugeniosegala/claude-connoisseur) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2026-04-27 - Claude Code plugin uniting skills, rules, and hooks with OpenSpec.
* [openspec.nvim](https://github.com/ctchen222/openspec.nvim) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2026-07-04 - Neovim control surface for OpenSpec workflows.
* [openspec.el](https://github.com/Zacalot/openspec.el) ⭐ 8 | 🐛 0 | 🌐 Emacs Lisp | 📅 2026-02-06 - Emacs interface for OpenSpec workflows.
* [intellij-openspec](https://github.com/johnnyblabs/intellij-openspec) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2026-08-21 - IntelliJ IDEA plugin for OpenSpec, available on the JetBrains Marketplace.
* [opencode-openspec](https://github.com/AngDrew/opencode-openspec) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-01 - OpenSpec spec-driven development plugin for OpenCode.
* [openspec-ext](https://github.com/RandyZ/openspec-ext) ⭐ 6 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-23 - VS Code and Cursor extension with a visual dashboard for changes and specs.
* [openspec-tdd](https://github.com/yuritoledo/openspec-tdd) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-30 - Plugin for Claude Code, OpenCode, and Pi generating failing tests from specs.
* [opsx-feature-dev](https://github.com/mbertani/opsx-feature-dev) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2026-04-10 - Claude Code and Copilot plugin with a 7-phase feature development workflow.
* [openspec-ui-vscode](https://github.com/coderj001/openspec-ui-vscode) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17 - VS Code/Cursor extension with a visual dashboard, Mermaid diagrams, and artifact comments.
* [vitepress-plugin-openspec](https://github.com/stritti/vitepress-plugin-openspec) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21 - VitePress plugin rendering OpenSpec folders as doc pages.

## Schemas & Extensions

* [spec-superflow](https://github.com/MageByte-Zero/spec-superflow) ⭐ 759 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-16 - OpenSpec planning with Superpowers execution across 17 platforms. (Chinese)
* [flow-kit](https://github.com/rihebty/flow-kit) ⭐ 388 | 🐛 1 | 📅 2026-05-13 - Workflow kit merging BMAD, Spec-Kit, OpenSpec, GSD, and Superpowers. (Chinese)
* [openspec-schemas by JiangWay](https://github.com/JiangWay/openspec-schemas) ⭐ 217 | 🐛 5 | 📅 2026-06-10 - Community schemas including a superpowers-bridge integration.
* [superpowers-openspec-team-skills](https://github.com/SYZ-Coder/superpowers-openspec-team-skills) ⭐ 191 | 🐛 0 | 🌐 PowerShell | 📅 2026-06-12 - Self-learning team skill library. (Chinese)
* [openspec-plus](https://github.com/sudokar/openspec-plus) ⭐ 153 | 🐛 0 | 📅 2026-07-23 - Agentic skills improving discovery, requirements, design decisions, and execution.
* [openspec-schemas](https://github.com/intent-driven-dev/openspec-schemas) ⭐ 90 | 🐛 1 | 📅 2026-08-16 - Custom workflow schemas including minimalist and event-driven templates.
* [HyperSpec](https://github.com/wind7rui/HyperSpec) ⭐ 74 | 🐛 2 | 📅 2026-07-05 - Workflow skill coordinating OpenSpec specs with Superpowers TDD. (Chinese)
* [SuperSpec](https://github.com/danielhanold/superspec) ⭐ 57 | 🐛 0 | 📅 2026-05-26 - Drop-in schema integrating Superpowers execution discipline for traceable workflows.
* [openspec-spec-driven-superpowers](https://github.com/Veath/openspec-spec-driven-superpowers) ⭐ 26 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-27 - Adds superpowers-style planning and readiness gates.
* [openspec-schemas by kmhalvin](https://github.com/kmhalvin/openspec-schemas) ⭐ 4 | 🐛 0 | 📅 2026-04-09 - Subagent-driven development and QRSPI multi-phase reasoning schemas.
* [openspec-reviewed-workflow](https://github.com/griffithkk3-del/openspec-reviewed-workflow) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-03-27 - Adds a review gate between proposal and spec phases.
* [e2e-runbooks](https://github.com/Lukk17/openspec-schemas) ⭐ 0 | 🐛 0 | 📅 2026-06-25 - Capability-level e2e runbooks with behaviour-only assertions and token accounting.

## Templates & Starters

* [Harness-Starter](https://github.com/chenklein26-maker/Harness-Starter) ⭐ 120 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-03 - Claude Code harness template with OpenSpec SDD workflow. (Chinese)
* [intent-driven-template](https://github.com/intent-driven-dev/intent-driven-template) ⭐ 115 | 🐛 2 | 🌐 Python | 📅 2026-08-23 - Template with ADRs, C4 diagrams, Gherkin, and TDD.
* [speccoding-template](https://github.com/beautifulSoup/speccoding-template) ⭐ 61 | 🐛 0 | 📅 2026-05-03 - Full-stack AI dev template with OpenSpec and Superpowers. (Chinese)
* [nuxt-supabase-starter](https://github.com/YuDefine/nuxt-supabase-starter) ⭐ 45 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-21 - Nuxt and Supabase starter with OpenSpec-based AI workflow. (Chinese)
* [opencode-onboard](https://github.com/CKGrafico/opencode-onboard) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-22 - Prepares codebases for AI by wiring OpenCode, OpenSpec, and codegraph.

## GitHub Actions

* [OpenSpec Badge Action](https://github.com/wearetechnative/openspec-badge-action) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-26 - GitHub Action generating SVG badges for OpenSpec metrics.

## Videos

* [I Found the Simplest AI Dev Tool Ever](https://www.youtube.com/watch?v=cQv3ocbsKHY) - Short introduction video to OpenSpec.
* [Launch Video](https://youtu.be/N-MftbmnmMo) - An introduction to OpenSpec by Tabish Bidiwale.
* [OpenSpec Changes Everything / No More Vibe Coding](https://www.youtube.com/watch?v=5oUmpdpbejk) - Full tutorial on OpenSpec workflow.
* [OpenSpec Will Change How You Vibe Code Forever](https://www.youtube.com/watch?v=nFq4POtqom4) - Overview of OpenSpec and SDD by Sean Kochel.
* [OpenSpec: NEW Toolkit Ends Vibe Coding!](https://www.youtube.com/watch?v=gHkdrO6IExM) - Full tutorial by WorldofAI covering the complete workflow.

## Articles & Tutorials

* [OpenSpec-practise](https://github.com/ForceInjection/OpenSpec-practise) ⭐ 589 | 🐛 1 | 📅 2026-08-19 - Practical guide to OpenSpec v1.3.0 with SDD examples. (Chinese/English)
* [OpenSpec + Beads](https://github.com/cameronsjo/spec-compare/blob/main/docs/cheatsheet-beads-openspec.md) ⭐ 122 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-19 - Cheatsheet for OpenSpec with Beads.
* [spec-compare](https://github.com/cameronsjo/spec-compare) ⭐ 122 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-19 - Comparison of six SDD tools with decision frameworks and scoring matrices.
* [OpenSpec-cn](https://github.com/sohaha/studyzy-OpenSpec-cn) ⭐ 95 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-05 - Chinese translation of the OpenSpec documentation.
* [OpenSpec-Docs-zh](https://github.com/radebit/OpenSpec-Docs-zh) ⭐ 83 | 🐛 0 | 🌐 HTML | 📅 2026-05-26 - Chinese community documentation for OpenSpec.
* [genai-development-techniques](https://github.com/olivomarco/genai-development-techniques) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-08 - Evidence-based comparison of AI coding methodologies.
* [openspec-practice](https://github.com/gqcn/openspec-practice) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2026-04-07 - Practice project demonstrating the OpenSpec workflow.
* [openspec-tutorial](https://github.com/aiyinluya/openspec-tutorial) ⭐ 8 | 🐛 1 | 📅 2026-04-09 - Beginner tutorial for OpenSpec. (Taiwanese)
* [openspec-learning-guide](https://github.com/xiaojian98/openspec-learning-guide) ⭐ 6 | 🐛 0 | 📅 2026-03-05 - Chinese learning guide for getting started with OpenSpec.
* [Cursor Forum](https://forum.cursor.com/t/openspec-lightweight-portable-spec-driven-framework-for-ai-coding-assistants/134052) - OpenSpec + Cursor.
* [Dev.to Intro](https://dev.to/webdeveloperhyper/how-to-make-ai-follow-your-instructions-more-for-free-openspec-2c85) - Getting started tutorial.
* [OpenSpec on IntentDriven](https://intent-driven.dev/knowledge/openspec/) - IntentDriven development resource with a focus on OpenSpec.
* [What Is Spec-Driven Development?](https://felipefontoura.com/articles/what-is-spec-driven-development/) - A practitioner's guide to SDD.

## Community

* [Discord](https://discord.gg/YctCnvvshC) - Official OpenSpec Discord community for support and discussions.

## Exotic Use Cases

* [novel-writer-openspec](https://github.com/wordflowlab/novel-writer-openspec) ⭐ 31 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-24 - OpenSpec for fiction with character and plot specs. (Chinese)
* [OpenSpec-Video](https://github.com/mr7thing/openspec-video) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-15 - Spec-as-Code framework compiling Markdown specs into AI video generation job queues.

## Competitors & Comparisons

* [Spec-Kit](https://github.com/github/spec-kit) ⭐ 130,927 | 🐛 353 | 🌐 Python | 📅 2026-08-21 - GitHub's official SDD toolkit with CLI, templates, scaffolding, and AI integrations.
* [Get Shit Done](https://github.com/gsd-build/get-shit-done) ⚠️ Archived - Spec-driven workflow with multi-agent orchestration and wave-based parallel execution.
* [BMAD-METHOD](https://github.com/bmad-code-org/BMAD-METHOD) ⭐ 52,190 | 🐛 147 | 🌐 JavaScript | 📅 2026-08-22 - Agile AI-driven development using formal specs as single source of truth.
* [Kiro](https://github.com/kirodotdev/Kiro) ⭐ 4,217 | 🐛 1,565 | 🌐 TypeScript | 📅 2026-06-22 - AWS agentic IDE converting natural language into structured specs.
* [Spec Kitty](https://github.com/Priivacy-ai/spec-kitty) ⭐ 1,568 | 🐛 684 | 🌐 Python | 📅 2026-08-23 - SDD CLI workflow with Kanban dashboard, Git worktree isolation, and auto-merge.
* [ProductSpec](https://github.com/gokulrajaram/ProductSpec) ⭐ 269 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-19 - Open standard for capturing software intent before implementation.
* [Tessl SDD Tile](https://github.com/tesslio/spec-driven-development-tile) ⭐ 52 | 🐛 0 | 🌐 Shell | 📅 2026-03-30 - Tile teaching MCP-compatible AI agents to write specs before coding.
* [FullSpec](https://github.com/NSEvteev/FullSpec) ⭐ 32 | 🐛 5 | 🌐 Python | 📅 2026-07-31 - Spec-driven framework turning ideas into code through formal analysis chains.
* [OpenSpecification](https://github.com/spenceriam/OpenSpecification) ⭐ 30 | 🐛 18 | 🌐 TypeScript | 📅 2025-11-03 - Web-based take on Kiro IDE's Spec Mode.
* [pi-sdd-kit](https://github.com/felipefontoura/pi-sdd-kit) ⭐ 21 | 🐛 0 | 📅 2026-07-04 - Spec-driven development as skills for the Pi coding agent, with approval gates.
* [ContractSpec](https://github.com/Pluviobyte/ContractSpec) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-09 - OpenSpec-compatible contract-driven workflow for AI full-stack development.
* [dataspec](https://github.com/raydez/dataspec) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-03 - AI-native data development tool, an OpenSpec for data teams. (Chinese)
* [spectr](https://github.com/connerohnesorge/spectr) ⭐ 3 | 🐛 26 | 🌐 Go | 📅 2026-05-29 - Validatable spec-driven development inspired by OpenSpec and Kiro.

## Related Projects

* [Awesome AI-Driven Development](https://github.com/eltociear/awesome-AI-driven-development) ⭐ 522 | 🐛 2 | 📅 2026-08-19 - Curated list of 500+ AI-powered development tools.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
