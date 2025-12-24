
---

# 📁 day-3-mcp-agentic/README.md

```md
# Day 3 — MCP & Agentic Architecture

## Objective
Understand how large language models interact with external systems using agentic architectures and MCP concepts.

---

## Why MCP?
A language model alone cannot:
- send emails,
- access databases,
- call internal services,
- perform real-world actions.

MCP (Model Context Protocol) acts as a controlled bridge between:
- the LLM,
- external tools and services.

---

## Core idea
LLM  
→ MCP layer  
→ APIs / tools / services  
→ Controlled execution

---

## What I learned
- Why direct LLM access is unsafe
- How MCP enables secure and structured tool execution
- Difference between agent reasoning and action execution
- How MCP fits into enterprise architectures

---

## Local experimentation
I simulated MCP concepts locally using:
- FastAPI
- Executable HTTP endpoints
- Browser-based interaction

This helped me understand MCP behavior without cloud dependencies.

---

## Key takeaway
MCP is not an API by itself.
It is an architectural pattern that enables safe, auditable and extensible AI agents.
