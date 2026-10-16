# Awesome AI Workflow & Agent Builders [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best AI workflow automation platforms, visual LLM agent builders, and autonomous multi-agent orchestration frameworks (SaaS & Open-Source).

---

## Overview

Welcome to the comprehensive directory of **AI Workflow Builders**, **Visual LLM Orchestration Tools**, and **Autonomous Agent Platforms**. 

Whether you are looking for enterprise SaaS solutions or self-hosted open-source frameworks, this guide tracks production-grade platforms designed to visually design, test, prototype, and deploy LLM agents, RAG pipelines, and multi-agent workflows without writing boilerplate code from scratch.

### Key Capabilities Tracked
- 🎨 **Visual Drag-and-Drop Builders**: No-code & low-code node-based flow canvases.
- 🤖 **Multi-Agent Orchestration**: Autonomous agent loops, supervisor-worker models, and crew collaboration.
- 📚 **RAG & Knowledge Bases**: Retrieval-Augmented Generation, vector database connectors, and document chunking.
- 🔌 **Model Context Protocol (MCP)**: Native MCP client & server integrations for interoperable AI tool calling.
- 🛡️ **Human-in-the-Loop (HITL)**: Approval gates, verification steps, and safe action execution.
- 📊 **LLMOps & Observability**: Tracing, latency monitoring, prompt evaluations, and debugging.

---

## Table of Contents

- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source Agent & Workflow Builders](#open-source-agent--workflow-builders)
  - [Featured Open-Source Frameworks](#featured-open-source-frameworks)
  - [Workflow Automation & Multi-Agent Frameworks](#workflow-automation--multi-agent-frameworks)
- [Feature & Ecosystem Comparison](#feature--ecosystem-comparison)
- [How to Choose an AI Agent Builder](#how-to-choose-an-ai-agent-builder)
- [Contributing](#contributing)
- [License & Disclaimer](#license--disclaimer)

---

## SaaS & Hosted Platforms

A comparison of leading cloud-hosted AI workflow builders and managed agent platforms.

| Platform | Primary Focus | Pricing Model | Free Tier Limits | Key Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Retool](https://retool.com/)** | Enterprise Internal Tools & AI Agents | Freemium (Free, Team from $10/user/mo, Business from $50/user/mo, Enterprise) | Free up to 5 users; standard Retool features included (Cloud public beta for Retool Agents) | Enterprise RBAC, SSO, 100+ native data connectors, proprietary MCP server, production HITL |
| **[Stack AI](https://www.stack-ai.com/)** | Enterprise AI Automation & RAG | Freemium (Free, Starter from $199/mo, Enterprise custom) | Free tier available with monthly credit caps & standard builder access | Visual pipeline builder, SOC 2 compliance, RAG pipelines, enterprise security |
| **[Voiceflow](https://www.voiceflow.com/)** | Conversational AI & Voice/Chat Agents | Freemium (Free, Pro from $50/editor/mo, Enterprise custom) | Free up to 2 editors, 100k knowledge base tokens, 100 monthly agent credits | Conversation design canvas, interactive prototyping, omni-channel deployment (Web, WhatsApp, Alexa) |
| **[Botpress Cloud](https://botpress.com/)** | Managed Conversational AI Platform | Pay-as-you-go / Freemium | Free tier includes $5/month AI spend, unlimited bots, and standard channels | Visual flow builder, native NLU engine, knowledge base grounding, multi-channel deployment |
| **[Lindy](https://www.lindy.ai/)** | Autonomous Business Automation Agents | Freemium (Free, Pro from $49/mo, Business custom) | Free tier includes limited monthly task credits and core app integrations | No-code agent creation, native integrations (Gmail, Slack, CRMs), background automated execution |
| **[SuperAGI Cloud](https://superagi.com/)** | Managed Autonomous Agent Infrastructure | Freemium / Usage-based | Free tier includes limited concurrent runs and trial tool executions | Agent marketplace, 70+ built-in tools, concurrent execution monitor, graphical agent dashboard |

---

## Open-Source Agent & Workflow Builders

Self-hostable, transparent, and extensible open-source projects for building production-ready AI workflows and autonomous agents.

### Featured Open-Source Frameworks

#### 1. [Langflow](https://github.com/langflow-ai/langflow)
- **License**: MIT | **Tech Stack**: Python / React
- **Overview**: The most popular open-source visual drag-and-drop builder for AI-powered agents and workflows.
- **Key Features**:
  - Turns every flow into an API endpoint or **MCP server** natively.
  - Interactive playground for step-by-step node debugging and execution tracing.
  - Full source code customizability: edit or create any component in Python.
  - Integrates with LangSmith, Langfuse, and Arize Phoenix for observability.
  - Available as Docker container, PyPI package (`uv pip install langflow`), or Desktop app (macOS/Windows).

#### 2. [Flowise](https://github.com/FlowiseAI/Flowise)
- **License**: Apache-2.0 | **Tech Stack**: TypeScript / Node.js
- **Overview**: Open-source generative AI development platform for LLM workflows, conversational bots, and multi-agent systems.
- **Key Features**:
  - **Three Visual Canvas Types**: Assistant (conversational RAG), Chatflow (linear LLM chains), and Agentflow (complex multi-agent orchestration).
  - **Flowise 3.0**: Natural language prompt-to-flow generator.
  - 100+ integrations covering vector DBs, memory stores, and external tools.
  - Native Human-in-the-Loop (HITL) approval controls for tool calls.
  - Quick start via Docker or NPM: `npx flowise start`.

#### 3. [Dify](https://github.com/langgenius/dify)
- **License**: Apache-2.0 derivative | **Tech Stack**: Python / Next.js
- **Overview**: Comprehensive production-grade LLM application development platform with 150K+ GitHub stars.
- **Key Features**:
  - Combines visual AI workflow canvas, RAG pipelines, Prompt IDE, and agentic workflows in one dashboard.
  - Autonomous agents with secure sandboxed code execution (Docker-isolated).
  - Robust document parsing (PDF, DOCX, Markdown, PPT) and vector indexing.
  - Native LLMOps analytics, log tracking, and multi-tenant user access control.
  - Publish applications as web apps, APIs, embedded widgets, or MCP tools.

#### 4. [Rivet](https://github.com/Ironclad/rivet)
- **License**: MIT | **Tech Stack**: TypeScript / Electron
- **Overview**: Open-source visual AI programming environment and TypeScript runtime engine by Ironclad.
- **Key Features**:
  - Desktop-native graphical IDE for complex prompt chaining and hierarchical graphs.
  - `@ironclad/rivet-core` TypeScript library allows running visual graphs directly inside backend code.
  - Zero-latency local debugging with variable inspection and step-through graph execution.

#### 5. [SuperAGI](https://github.com/TransformerOptimus/SuperAGI)
- **License**: MIT | **Tech Stack**: Python
- **Overview**: Open-source autonomous AI agent framework designed for building, managing, and running autonomous agent loops.
- **Key Features**:
  - Agent marketplace with 70+ extensible tools.
  - Concurrent multi-agent execution with resource monitoring.
  - Action console with agent performance logs and looping safeguards.

#### 6. [Botpress](https://github.com/botpress/botpress)
- **License**: MIT | **Tech Stack**: TypeScript
- **Overview**: Developer-friendly conversational AI platform and bot engine with 12K+ stars.
- **Key Features**:
  - Flow-based visual dialogue builder with custom JavaScript actions.
  - Built-in NLU engine and knowledge retrieval.
  - Native connectors for Slack, Microsoft Teams, Telegram, and web chat.

---

### Workflow Automation & Multi-Agent Frameworks

Complementary open-source orchestration engines and code-first multi-agent frameworks:

- **[n8n](https://github.com/n8n-io/n8n)** — Fair-code workflow automation with advanced AI agent nodes, LangChain connectors, and 400+ API integrations.
- **[Activepieces](https://github.com/activepieces/activepieces)** — Open-source no-code automation platform (MIT); automatically exposes every integration as an MCP server.
- **[ToolJet](https://github.com/ToolJet/ToolJet)** — Open-source internal tool builder with AI capabilities and open-source MCP server support.
- **[AutoGen (Microsoft)](https://github.com/microsoft/autogen)** — Multi-agent conversation framework enabling collaborative AI task solving.
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Popular framework for orchestrating role-playing autonomous AI agents.
- **[LangGraph](https://github.com/langchain-ai/langgraph)** — Cyclical graph-based stateful multi-agent orchestration engine.

---

## Feature & Ecosystem Comparison

| Project / Platform | Type | Visual Canvas | Multi-Agent Support | MCP Native | Self-Hostable | License / Pricing |
| :--- | :--- | :---: | :---: | :---: | :---: | :--- |
| **Langflow** | Open-Source | ✅ | ✅ | ✅ | ✅ | MIT |
| **Flowise** | Open-Source | ✅ | ✅ | ✅ | ✅ | Apache-2.0 |
| **Dify** | Open-Source | ✅ | ✅ | ✅ | ✅ | Apache-2.0 (derivative) |
| **Rivet** | Open-Source | ✅ | ✅ | 🟡 (via TS) | ✅ | MIT |
| **SuperAGI** | Open-Source | ✅ | ✅ | ❌ | ✅ | MIT |
| **n8n** | Open-Source | ✅ | ✅ | ✅ | ✅ | Sustainable Use License |
| **Activepieces** | Open-Source | ✅ | ✅ | ✅ | ✅ | MIT |
| **Retool** | SaaS / Hybrid | ✅ | ✅ | ✅ | 🟡 (Enterprise) | Freemium ($10-$50/user) |
| **Stack AI** | SaaS | ✅ | ✅ | 🟡 | ❌ | Freemium (from $199/mo) |
| **Voiceflow** | SaaS | ✅ | 🟡 | 🟡 | ❌ | Freemium (from $50/mo) |

---

## How to Choose an AI Agent Builder

1. **For Rapid Prototyping & Flow Experiments**: Choose **[Langflow](https://github.com/langflow-ai/langflow)** or **[Flowise](https://github.com/FlowiseAI/Flowise)**. Both provide instantaneous drag-and-drop authoring and massive pre-built component catalogs.
2. **For Production-Grade End-to-End Apps**: Choose **[Dify](https://github.com/langgenius/dify)**. It includes RAG, prompt management, sandboxed execution, and LLMOps analytics out of the box.
3. **For Embedding in TypeScript / Node Backend**: Choose **[Rivet](https://github.com/Ironclad/rivet)**. Design graphs visually in the IDE, execute them natively via `@ironclad/rivet-core`.
4. **For Business Process & API Automation**: Choose **[n8n](https://github.com/n8n-io/n8n)** or **[Activepieces](https://github.com/activepieces/activepieces)** to combine classic SaaS triggers with LLM agent steps.
5. **For Enterprise Internal Tools**: Choose **[Retool](https://retool.com/)** if you require granular RBAC, enterprise database integration, and cloud-hosted agent orchestration.

---

## Contributing

Contributions are warmly welcomed! Help keep this ecosystem guide up-to-date:

1. Fork the repository.
2. Add or update tools in [README.md](file:///C:/Users/ishan/Documents/Projects/Awesome-AI-Workflow-Agent-Builders/README.md) following the existing table or list format.
3. Ensure descriptions are factual, objective, and reference official project documentation.
4. If submitting a SaaS product, please include pricing tier details and free tier limits in accordance with our catalog standards.
5. Submit a Pull Request with a concise summary of changes.

---

## License & Disclaimer

- Distributed under the [MIT License](file:///C:/Users/ishan/Documents/Projects/Awesome-AI-Workflow-Agent-Builders/LICENSE).
- **Disclaimer**: This is an independent community-curated list. Product names and trademarks belong to their respective owners.
- **Production Safety Notice**: When deploying autonomous agents with write permissions or external API access, always enforce **Human-in-the-Loop (HITL)** approvals and adhere to least-privilege principles.
