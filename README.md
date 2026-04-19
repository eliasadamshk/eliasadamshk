# Elias Adams

Full-stack engineer building AI agent infrastructure — orchestration, tool systems, and runtime plumbing for autonomous agents in production. TypeScript, Python, and everything between FastAPI and Kubernetes.

Background in Product & Industrial Design — it shapes how I think about system interfaces and developer experience.

## Projects

### [Cadence](https://github.com/eliasadamshk/cadence)

Real-time standup board automation. A tool that listens to your standup, transcribes it in real-time with speaker identification, and extracts project management actions (moving cards, creating tickets, flagging blockers) as people talk. Built with FastAPI, AssemblyAI streaming, Gemini via OpenRouter, and a native SwiftUI menu bar app for macOS. Includes an eval suite covering 6 scenarios at 100% F1.

### [call-me](https://github.com/eliasadamshk/call-me) *(fork of [ZeframLou/call-me](https://github.com/ZeframLou/call-me))*

MCP server that lets background AI agents (Claude Code, Cursor Cloud Agents, custom loops) phone you when they're stuck, done, or need a decision. My fork adds:

- **Security hardening** — required API auth tokens, webhook signature enforcement, timing-safe WebSocket authentication, removal of ngrok free-tier auth bypasses
- **Docker Compose deployment** with MCP over Streamable HTTP — cloud-hosted agents can use it as a remote server, not just local CLI tools
- **Background-agent focus** — designed for long-running, unattended agents that need a reliable way to reach a human

Currently integrating **OpenAI Realtime** for lower-latency, natural-sounding voice, and exploring **conversation memory** so agents can self-resolve routine queries from prior call context instead of phoning every time.

## Current Focus

Agent tool/skills systems backed by Postgres, production SSE streaming with zero-downtime K8s rollouts, browser automation as an agent capability layer, and multi-agent orchestration prototypes.

---

*Particularly interested in voice AI applications and bringing the productivity gains software engineers have experienced through GenAI to a wider range of industries. Open to connecting on agentic AI infrastructure, LLM orchestration, or developer tooling.*
