# Elias Adams

Full-stack engineer building AI agent infrastructure — orchestration, tool systems, and runtime plumbing for autonomous agents in production. TypeScript, Python, and everything between FastAPI and Kubernetes.

Background in Product & Industrial Design — it shapes how I think about system interfaces and developer experience.

## Projects

### Pheme *(don't get too attached to the name, it'll probably change)*

AI-powered phone assistant for small businesses. Owners sign up, configure their business details (name, hours, FAQs, greeting, persona) and get a dedicated phone number. When customers call, an AI agent picks up instantly, answers common questions, and escalates gracefully to a human or voicemail when needed. Built with FastAPI, Next.js, Twilio, and MongoDB.

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
