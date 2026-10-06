# Awesome Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools for building and running AI agents safely.

## Security & Policy Enforcement

- [AgentWall](https://github.com/agentwall/agentwall) — Policy-enforcing MCP proxy 
  that blocks dangerous tool calls before they execute. Works with Claude Desktop, 
  Cursor, Windsurf, OpenClaw.
- [mcp-scan](https://github.com/invariantlabs-ai/mcp-scan) — Scans MCP servers for 
  prompt injection and tool poisoning vulnerabilities.
- [LlamaFirewall](https://github.com/meta-llama/PurpleLlama/tree/main/LlamaFirewall) 
  — Meta's security framework for LLM applications.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA's toolkit 
  for adding programmable guardrails to LLM-based apps.

- [agent-guard](https://github.com/hahahahahahahahah6/agent-guard) — Behavior-guardrail
  hooks for Claude Code that block test-tampering, destructive shell commands, and
  secret exfiltration. Python stdlib only, MIT licensed.
## MCP Frameworks & Dev Tools

- [FastMCP](https://github.com/jlowin/fastmcp) — Fast, Pythonic way to build 
  MCP servers.
- [mcp-use](https://github.com/mcp-use/mcp-use) — Open source MCP client library.
- [Glama](https://glama.ai/mcp/servers) — Directory of 12,000+ MCP servers.
- [PulseMCP](https://pulsemcp.com) — MCP server directory and weekly newsletter.

## Orchestration Frameworks

- [LangGraph](https://github.com/langchain-ai/langgraph) — Framework for building 
  stateful, multi-actor agent applications.
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's multi-agent 
  conversation framework.
- [CrewAI](https://github.com/crewAIInc/crewAI) — Framework for orchestrating 
  role-playing autonomous AI agents.
- [smolagents](https://github.com/huggingface/smolagents) — Hugging Face's minimal 
  agent framework.

## MCP Clients

- [Claude Desktop](https://claude.ai/download) — Anthropic's desktop client with 
  native MCP support.
- [Cursor](https://cursor.sh) — AI code editor with MCP integration.
- [Windsurf](https://codeium.com/windsurf) — Agentic IDE by Codeium.
- [OpenClaw](https://openclaw.dev) — Open source agentic coding client.

## Learning & Resources

- [MCP Documentation](https://modelcontextprotocol.io) — Official MCP protocol docs.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) — 80K+ 
  star curated list of MCP servers.
- [r/mcp](https://reddit.com/r/mcp) — MCP community on Reddit.

## Contributing

Know a great agent tool? Open a PR.