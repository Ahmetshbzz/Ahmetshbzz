<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
  <img alt="Ahmet Şahbazoğlu — Mobile Security &amp; Systems Engineer" src="assets/hero-light.svg" width="100%">
</picture>

![Tech stack](assets/marquee.svg)

</div>

---

I build high-performance distributed systems in Go, Python and Rust. Most of my recent work is mobile security: reverse engineering Android and iOS applications, instrumenting them at runtime, and building the protections that have to survive the same treatment. Underneath that sits system-level work — eBPF, TUN stacks, low-level networking — and native Swift on Apple platforms.

---

## What I can own

I take the whole thing: the data model and its correctness, the runtime that carries it, and the interface people actually touch. The list below is not about which client it was for; it is about what can be handed to me.

> Some of this work sits under confidentiality, so names, scope and outcomes are deliberately left out. What is described here is the capability, not the engagement.

| Capability | Scope |
|---|---|
| **Mobile application security** | Reverse engineering and defense at the same table. APK/DEX and Mach-O analysis, runtime instrumentation with Frida, working past SSL pinning, root, emulator and tamper detection — then building those same mechanisms into production code: RASP, self-integrity verification, debugger detection. Findings ship with evidence locations, attack path and remediation, and speculative claims stay separated from confirmed ones. |
| **Money-correct cores** | Ledgers where a single minor unit may not drift: double-entry records, integer amounts, idempotency keys and maker-checker approval. Reconciliation is a scheduled job that produces evidence, not a manual ritual. |
| **Multi-tenant platforms** | Modular monoliths split along bounded contexts, tenant isolation enforced at the database level, fail-closed configuration. Outbox, saga, dead-letter handling and leader election keep asynchronous work correct under retries. |
| **Real-time media and data pipelines** | Multi-source ingest, composition, encoding and packaging with deterministic timestamps. The media core links into forked libraries in-process instead of spawning a process per stream. |
| **Identity and authorization** | Passkeys, second factors, key rotation and sealed credentials. Machine access stays separate from human sessions; trust is decided at the socket, not from a forwarded header. |
| **AI agent systems** | Multi-service agent platforms with tool orchestration, persistent memory over vector and graph stores, and MCP servers as a first-class interface. |
| **Apple platform applications** | Native SwiftUI on iOS and macOS: menu bar tools, permission onboarding, Keychain-backed secrets, speech and audio capture, and distribution that passes review. |
| **Low-level systems and networking** | Engineering at the kernel and network layer with eBPF, TUN stacks and raw sockets. |
| **Browser automation and proof-carrying tools** | Headless automation that extracts real structure, rebuilds it deterministically, and proves the result with a pixel diff instead of claiming success. |

![Section divider](assets/divider.svg)

## Open source

| Project | What it does | |
|---|---|---|
| **[claude-skills](https://github.com/Ahmetshbzz/claude-skills)** | Versioned skill catalog with primary-source references and eval suites. Includes the mobile RE workflow and the Frida hooking, SSL pinning and root/jailbreak bypass references I work from. | `Python` |
| **[ctx-agent](https://github.com/Ahmetshbzz/ctx-agent)** | Universal Agent Context Protocol. Lets AI agents understand a codebase without running it; single binary, SQLite, offline. No LLM, no cloud. | `Rust` ★10 |
| **[browser-guard](https://github.com/Ahmetshbzz/browser-guard)** | Framework-independent anti-inspection package for the web: debugger traps, inspection shortcut control, lifecycle-aware timers. States its own security boundary instead of implying a guarantee. | `TypeScript` |
| **[anthropic-turkce-courses](https://github.com/Ahmetshbzz/anthropic-turkce-courses)** | Turkish translation of Anthropic's official course material. | `Jupyter` ★19 |
| **[voicman](https://github.com/Ahmetshbzz/voicman)** | macOS menu bar dictation app. Global shortcut, live transcription with Apple Speech, paste into the active app. | `Swift` |
| **[web-search-mcp](https://github.com/Ahmetshbzz/web-search-mcp)** | Agent-first MCP server: multi-provider web search, content extraction and browser automation. | `Python` |
| **[DockNest](https://github.com/Ahmetshbzz/DockNest)** | macOS Dock launcher. Discovers installed developer tools from metadata and opens them by drag and drop. No telemetry, no network access. | `Swift` |
| **[json](https://github.com/Ahmetshbzz/json)** | Browser extension: displays JSON readably. Light/dark theme, API performance metrics, export. | `JavaScript` |

## Technology

**Security & reverse engineering**

![Frida](https://img.shields.io/badge/Frida-0B0B0B?style=flat-square)
![Ghidra](https://img.shields.io/badge/Ghidra-B32B2B?style=flat-square)
![IDA](https://img.shields.io/badge/IDA-2E6DB4?style=flat-square)
![jadx](https://img.shields.io/badge/jadx-4B5563?style=flat-square)
![radare2](https://img.shields.io/badge/radare2-2F3A45?style=flat-square)
![LLDB](https://img.shields.io/badge/LLDB-3B6EA5?style=flat-square)
![MobSF](https://img.shields.io/badge/MobSF-24425C?style=flat-square)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square)

**Backend**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

**Frontend & mobile**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Infrastructure & data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

## Contribution graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahmetshbzz/Ahmetshbzz/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahmetshbzz/Ahmetshbzz/output/snake-light.svg">
  <img alt="Contribution graph" src="https://raw.githubusercontent.com/Ahmetshbzz/Ahmetshbzz/output/snake-dark.svg">
</picture>

</div>

---

## Contact

<div align="center">

[![Website](https://img.shields.io/badge/ahmetshbzz.com-000000?style=for-the-badge&logo=globe&logoColor=white)](https://ahmetshbzz.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ahmet-%C5%9Fahbazo%C4%9Flu-77701917a)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/ahmetshbzx)
[![Email](https://img.shields.io/badge/Mail-6D4AFF?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:ahmetcanshbz@proton.me)

</div>
