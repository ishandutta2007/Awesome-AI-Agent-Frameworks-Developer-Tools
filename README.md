# Awesome-AI-Agent-Frameworks-Developer-Tools

## Top AI Agent Frameworks & Developer Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Multi-Agent Orchestration, Agent Coding Skills, Structured LLM SDKs, Model Gateways & Developer Tooling*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Frameworks & Developer Tools**. These tools provide composable abstractions for building autonomous agents, multi-agent collaboration graphs, modular coding agent skills, structured outputs, unified model routing, and production observability.



**Examples** include LangChain, LlamaIndex, CrewAI, AutoGen, Semantic Kernel, Haystack, Prompt flow, Langfuse, Mirascope, LiteLLM, and addyosmani/agent-skills (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for Python and TypeScript agent orchestration, engineering skill packs for coding agents, type-safe LLM developer SDKs, local model gateways, and evaluation/tracing toolkits — ideal for AI software engineers, developer advocates, and teams building transparent agentic applications.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global AI agents and agentic developer tools market is estimated at **$10.7B to $14.6B in 2026** and projected to exceed **$50B to $65B+ by 2030** (growing at a ~35%–45% CAGR) as software shifts from passive prompts to autonomous, multi-step agent execution. The sector is currently **moderately fragmented**: foundational cloud hyperscalers (Microsoft, AWS, Google) command the infrastructure and compute tier, but specialized orchestration, observability, and evaluation middleware remain highly competitive with rapid developer-led, open-core adoption rather than a single winner-take-all monopoly.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Description | Starting Paid Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure AI Foundry / Prompt flow Cloud](https://microsoft.com)** | **$3.8T Market Cap** (Microsoft) / $245B+ Annual Revenue | Enterprise cloud AI studio and managed Prompt flow runtime for authoring, evaluating, and deploying multi-agent pipelines with enterprise governance. | **Pay-as-you-go** compute & token billing (e.g. Standard VM from ~$0.096/hr; GPT-4o from $2.50/1M input tokens) | **Free subscription tier**: Restricted to testing/learning with strict TPM/RPM throttling and basic models; includes $200 Azure credit for 30 days on new accounts. |
| **[Langfuse Cloud](https://langfuse.com)** | **$15B Valuation** (Acquired by ClickHouse; ClickHouse Series D at $15B) | Managed cloud deployment of the open-source LLM engineering platform providing trace analytics, prompt versioning, datasets, and online agent evaluations. | **$29/month** (Core plan, includes 100k events/mo; overages at $10/100k) | **Hobby Plan (Free forever)**: Up to 50,000 observations/events per month, 30-day data retention, 2 user seats, no credit card required. |
| **[LangSmith & LangGraph Platform (LangChain)](https://langchain.com)** | **$3.0B Valuation** (Series C) / ~$15M ARR | Managed cloud platform for deploying, scaling, debugging, and evaluating stateful LangChain and LangGraph agent workflows in production. | **$39/seat/month** (Plus plan, includes 50k traces/mo; overages at $0.005/trace) | **Developer Plan (Free forever)**: 1 seat, up to 5,000 base traces per month, 14-day data retention, hard-capped (no accidental overages). |
| **[Braintrust](https://braintrust.dev)** | **$800M Valuation** (Series B) / $10M+ ARR | Enterprise AI evaluation, prompt playground, and observability platform designed to benchmark agent developer workflows and catch regressions. | **$249/month** (Pro plan, includes 5 GB processed data, 50k scores/mo, $100 model credit) | **Starter Plan (Free forever)**: $0/month, 1 GB data processed per month, 10,000 scores per month, 14-day retention, $10 included model credits, no credit card required. |
| **[Dify Cloud](https://dify.ai)** | **$180M Valuation** (Series Pre-A) / ~$3.1M ARR | Hosted LLM application and agentic workflow builder combining visual orchestration, RAG pipelines, model routing, and API publishing. | **$59/month** (Professional plan; or $590/year for 3 team members & 5,000 message credits/mo) | **Sandbox Plan (Free forever)**: 1 workspace member, up to 10 apps, 200 message credits, 5MB vector storage (BYO API keys to bypass rate limits). |
| **[Flowise Cloud](https://flowiseai.com)** | **$100M+ Enterprise Unit** (Acquired by Workday; $65B+ Market Cap) / ~$1M ARR | Cloud-hosted low-code visual platform for building, testing, and embedding multi-agent flows and tool-calling assistants. | **$35/month** (Starter plan; unlimited flows, 10,000 predictions/month, 1GB storage) | **Free Tier**: $0/month, up to 2 active flows, 100 predictions per month, 5MB storage, community support. |
| **[LlamaCloud (LlamaIndex)](https://llamaindex.ai)** | **$89M Valuation** (Series A) / $3M+ ARR | Enterprise cloud platform offering LlamaParse document parsing, managed knowledge indexing, and context-augmented agent infrastructure. | **$50/month** (Starter plan, includes 40,000 credits/month; overages up to $500/month at $1.25/1k credits) | **Free Plan**: 10,000 credits per month (approx. 1,000 standard pages/month), hard stop with no overages. |
| **[CrewAI Enterprise](https://crewai.com)** | **$75M–$100M Valuation** (Series A) / ~$3M ARR | Hosted multi-agent orchestration studio providing visual workflow builders, RBAC security, real-time telemetry, and managed crew deployments. | **$25/month** (Professional plan; expanded execution limits for small teams) | **Basic Plan (Free forever)**: $0/month, includes visual workflow builder, AI copilot, and up to 50 workflow executions per month. |
| **[Portkey Cloud](https://portkey.ai)** | **$50M+ Enterprise Unit** (Acquired by Palo Alto Networks; $110B+ Market Cap) / ~$5M ARR | Managed AI gateway and observability suite offering multi-provider routing, semantic caching, guardrails, and virtual key management. | **$49/month** (Production plan; 100,000 logs/month, 30-day retention, $9 per additional 100k requests) | **Developer Plan (Free forever)**: $0/month, 10,000 recorded log requests per month, 3-day data retention, unlimited guardrails and virtual keys. |

## Open-Source GitHub Projects



- **[addyosmani/agent-skills](https://github.com)**  

  Production-grade open-source (`MIT`) engineering workflow skills (`SKILL.md` specs, slash commands, and quality gates) for Claude Code, Cursor, Gemini CLI, and Windsurf covering planning, TDD, debugging, and code review.



- **[LangChain & LangGraph](https://github.com)**  

  Industry-leading open-source (`MIT`) Python and TypeScript ecosystem for composable LLM chains, tool integrations, and cyclic stateful multi-agent graphs ([LangGraph](https://github.com)).



- **[LlamaIndex](https://github.com)**  

  Open-source (`MIT`) data framework and event-driven workflow engine built for connecting LLMs and autonomous agents to private enterprise data sources.



- **[CrewAI](https://github.com)**  

  Popular open-source (`MIT`) Python framework for orchestrating role-playing autonomous AI agents and deterministic event-driven Flows.



- **[Microsoft AutoGen](https://github.com)**  

  Open-source programming framework and AutoGen Studio UI for building event-driven, multi-agent conversational and asynchronous workflows.



- **[Semantic Kernel](https://github.com)**  

  Enterprise-grade open-source (`MIT`) SDK from Microsoft for integrating LLM agents, plugins, planners, and memory across Python, C#/.NET, and Java.



- **[Haystack (deepset)](https://github.com)**  

  Modular open-source (`Apache-2.0`) Python AI orchestration framework for building customizable agent pipelines, tool-calling loops, and hybrid RAG systems.



- **[Microsoft Prompt flow](https://github.com)**  

  Open-source (`MIT`) developer tool suite designed to streamline the end-to-end development cycle of LLM-based agentic applications from prototyping to CI/CD evaluation.



- **[Mirascope](https://github.com)**  

  Clean, Pythonic open-source (`MIT`) LLM developer toolkit emphasizing type safety, colocation of prompts/parameters, structured outputs, and provider-agnostic tool calling.



- **[LiteLLM](https://github.com)**  

  Open-source (`MIT`) Python SDK and OpenAI-compatible proxy server unifying 100+ LLM providers with load balancing, fallbacks, and spend tracking.



- **[Langfuse](https://github.com)**  

  Self-hostable open-source LLM engineering platform for full-stack agent tracing, prompt management, session replays, and automated evaluations.



- **[Pydantic AI](https://github.com)**  

  Type-safe open-source (`MIT`) Python agent framework engineered by the Pydantic team for validated structured outputs, dependency injection, and durable execution.



- **[OpenAI Agents SDK](https://github.com)**  

  Lightweight open-source (`MIT`) Python runtime for multi-agent handoffs, guardrails, session persistence, and built-in trace inspection.



- **[Google Agent Development Kit (ADK)](https://github.com)**  

  Code-first open-source (`Apache-2.0`) toolkit for developing, evaluating, and deploying modular multi-agent hierarchies with bidirectional audio/video streaming.



- **[Agno (formerly Phidata)](https://github.com)**  

  High-performance open-source (`MPL-2.0`) Python framework and runtime for building multi-modal agents with shared memory, knowledge bases, and deterministic workflows.



- **[DSPy (Stanford NLP)](https://github.com)**  

  Open-source (`MIT`) declarative framework for programming—rather than hand-prompting—language models and agents using self-improving algorithmic optimizers.



- **[Instructor (`567-labs/instructor`)](https://github.com)**  

  Widely adopted open-source (`MIT`) library built on Pydantic for extracting validated, typed structured outputs and tool schemas from LLMs across Python, TypeScript, and Rust.



- **[Vercel AI SDK](https://github.com)**  

  Leading open-source (`Apache-2.0`) TypeScript toolkit for building streaming AI user interfaces, multi-step tool-calling agents, and generative UI components.



- **[Mastra](https://github.com)**  

  Open-source (`Apache-2.0`) TypeScript agent framework featuring stateful workflows, memory management, RAG, evals, and native Next.js/React integration.



- **[Smolagents (Hugging Face)](https://github.com)**  

  Minimalist open-source (`Apache-2.0`) Python library centered on code-executing agents that write and run Python actions directly inside secure sandboxes.



### Additional Strong Open-Source Options



- **[Model Context Protocol (MCP) SDKs & Servers](https://github.com)** for standardized tool, filesystem, and API connectivity across any agent framework or IDE.

- **[Rig (`0xPlaygrounds/rig`)](https://github.com)** and **[Eino (`cloudwego/eino`)](https://github.com)** for high-performance, type-safe AI agent development in Rust and Go.

- **[Letta (formerly MemGPT)](https://github.com)** and **[Mem0](https://github.com)** for persistent hierarchical agent memory and long-term cross-session recall.

- **[OpenHands](https://github.com)** and **[Aider](https://github.com)** for open-source autonomous software-engineering agents and terminal pair-programming workflows.

- **[Promptfoo](https://github.com)** and **[Arize Phoenix](https://github.com)** for CI/CD agent regression testing, red-teaming, and OpenTelemetry trace diagnostics.



**Frameworks for building custom systems**: Combine **LangGraph** or **Pydantic AI** with **Mirascope / Instructor** (structured outputs), **LiteLLM** (model routing), **Model Context Protocol (MCP)** (tools), **addyosmani/agent-skills** (coding workflows), and **Langfuse** (observability) for end-to-end open-source AI agent engineering.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agent frameworks with code execution, shell access, or external API tool-calling require proper sandboxing (e.g., Docker, gVisor, or Firecracker MicroVMs) and human-in-the-loop approval gates.
