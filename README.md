# Awesome-Agent-Orchestration-Platforms

## AI Agent Orchestration Platforms & Tools for Claude Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multi-Agent Orchestration with Claude / Anthropic Models*  
**Last updated: March 2026**

This repository tracks notable **platforms** and **open-source projects** for **agent orchestration**, especially those optimized for or compatible with **Claude** (Anthropic). These tools enable building, coordinating, and scaling teams of AI agents for complex workflows like software development, research, automation, and multi-step reasoning.

**Examples** include Claude Code Agent Teams, Claude Flow, LangGraph, CrewAI, and specialized multi-Claude tools. Emphasis is on frameworks that support parallel execution, shared memory, task delegation, and collaboration between agents powered by Claude.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local/custom Claude-compatible setups (via APIs or proxies), and full control over orchestration logic.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products / Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products / Platforms

### Core Orchestration Platforms for Claude

- **[Claude Code Agent Teams](https://code.claude.com/docs/en/agent-teams)**  
  Anthropic's native multi-agent collaboration feature in Claude Code. Allows spawning multiple Claude instances that share task lists, communicate directly, claim work, and coordinate in parallel (team lead + teammates model).

- **[Claude Flow](https://github.com/ruvnet/ruflo)** (and related tools)  
  Multi-agent swarm orchestrator built for Claude Code. Supports hierarchical and mesh coordination with dozens of specialized agents for complex development and automation tasks.

- **[LangGraph](https://github.com/langchain-ai/langgraph)**  
  Leading graph-based agent orchestration framework. Excellent Claude support via LangChain. Enables stateful, controllable multi-agent workflows with persistence, human-in-the-loop, and complex branching logic.

- **[CrewAI](https://github.com/crewAIInc/crewAI)**  
  Popular role-based multi-agent orchestration framework. Easy to define crews of agents with roles/goals; strong compatibility with Claude models for collaborative task execution.

### Specialized Multi-Claude Tools

- Other tools leveraging Claude's strengths in coding, reasoning, and tool use for agent teams, often built on top of Claude Code or the Anthropic SDK.

**Other notable mentions**: AutoGen (Microsoft), OpenAI Swarm (adaptable), Google ADK, and various Claude-specific wrappers.

## Open-Source GitHub Projects

### Dedicated Claude / Multi-Agent Orchestration Projects

- **[Claude Flow / ruvnet tools](https://github.com/ruvnet/ruflo)**  
  Enterprise-grade multi-agent orchestration platform for Claude Code. Features 60+ specialized agents, hive-mind/swarm intelligence, shared memory, and hierarchical coordination.

- **[LangGraph](https://github.com/langchain-ai/langgraph)**  
  Production-ready graph orchestration for agents. Stateful workflows, checkpoints, persistence, and excellent integration with Anthropic Claude models. Widely used for complex, reliable agent systems.

- **[CrewAI](https://github.com/crewAIInc/crewAI)**  
  Role-based multi-agent framework. Simple yet powerful for creating collaborative agent teams. Full support for Claude via API and strong community adoption.

- **[AutoGen (Microsoft)](https://github.com/microsoft/autogen)**  
  Multi-agent conversation framework. Agents communicate via messages; highly flexible for research and dynamic collaboration with Claude.

- **[Claude Agent SDK / related forks]**  
  Tools and extensions around Anthropic's Agent SDK for building custom orchestration layers.

### Additional Strong Open-Source Options

- **Composio Agent Orchestrator** — Tool integration and orchestration for multiple agents including Claude.
- **Smolagents** — Lightweight, efficient agent framework compatible with various models including Claude.
- **Pydantic AI** — Structured output and agent tooling with strong typing.
- Many community projects combining LangGraph/CrewAI with Claude for specific domains (coding agents, research swarms, automation).

**Frameworks for building custom agents**: LangGraph for control, CrewAI for speed, AutoGen for conversational flexibility. Combine with Anthropic SDK, MCP (Model Context Protocol), and local proxies for enhanced Claude usage.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agent orchestration tools, especially with powerful models like Claude, can consume significant tokens and costs. Always monitor usage and implement guardrails.
- For production use, ensure compliance with Anthropic's terms, data privacy, and security best practices.

---

**Made for developers, AI engineers, and teams building with Claude.**  
Let's make agent orchestration more powerful, controllable, and accessible.

## Star History

<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Agent-Orchestration-Platforms&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Agent-Orchestration-Platforms&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Agent-Orchestration-Platforms&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Agent-Orchestration-Platforms&type=date&legend=bottom-right" />
 </picture>
</a>
