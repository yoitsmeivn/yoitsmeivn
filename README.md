<h1 align="left">Ivan Severinov</h1>

<p align="left">
  <b>AI engineer in private markets &amp; startups.</b> I build AI for operations and investment teams: agent systems that run real workflows end to end, and research tools that help investors see more and decide faster.
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <br />
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Mistral_AI-FA520F?style=flat-square&logo=mistralai&logoColor=white" alt="Mistral AI" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Agentic_RAG-6E40C9?style=flat-square" alt="Agentic RAG" />
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j" />
  <img src="https://img.shields.io/badge/Vector_DBs-0B7285?style=flat-square" alt="Vector databases" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <br />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square" alt="AWS" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square" alt="Azure" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
</p>

<!--
  TODO(Ivan): replace this comment with 2–3 lines on what you're working on right now.
  HTML comments don't render on GitHub, so this stays hidden until you fill it in.
-->

### What I work on

- **AI for investment teams**: sourcing, diligence and research copilots grounded in a firm's own data, filings and data rooms
- **AI for operations**: agents that take back-office work from request to done (intake, approvals, bookings, reconciliation), with people in the loop where it matters
- **AI brains & operating systems**: shared memory, orchestration, tools and guardrails, so many agents work as one system
- **Retrieval & context graphs**: agentic RAG across documents and live sources, plus knowledge graphs that give each agent exactly the context it needs

### Selected work

**Soar** · 🥈 2nd place, OpenAI hackathon · <sub>private</sub><br />
An AI operating system for business travel. Soar reads Slack, Teams, calendar, email, CRM and finance tools and links them into a context graph, so it knows *why* a trip is happening before anything is booked. It then builds the itinerary, routes approval, books, codes the expense, and afterwards learns which trips actually moved deals forward.

**[Canard Security](https://github.com/yoitsmeivn/MistralAIHackathon)** · 🥉 3rd of ~70 teams, Mistral AI Worldwide Hackathon (SF)<br />
A voice-phishing ("vishing") simulation platform. An AI agent calls employees over Twilio as an executive, IT support or a promotional caller, and adapts live to what they say, using Mistral for the conversation and ElevenLabs for the voice. Security teams load in real roles and reporting lines, so the calls feel real and expose weak spots before attackers find them.

**[Multi-View Industrial Clustering](https://github.com/yoitsmeivn/Multi-View-Industrial-Clustering-Semantic-Labeling-Pipeline)**<br />
Turns messy data on UK companies into a clean, three-level sector taxonomy (broad → sub-sector → niche). Each company is embedded from six angles (services, business model, markets, name and domain, metadata, location), and the views are fused in a spectral clustering pipeline written from scratch. An LLM then names every cluster.

**[Chinook Support Agent (LangChain + LangSmith)](https://github.com/yoitsmeivn/LangChain-Demo)**<br />
A production-style customer support agent built on LangGraph and Claude. It handles music search, order history and refunds, with guards against SQL injection and access to other customers' data, human approval before any refund, and LangSmith tracing and evaluation, showing how to take an agent from demo to something you can trust.

**[agentplan](https://github.com/yoitsmeivn/Snowflake-Agent-Token-Hackathon)** · Snowflake × Beta Fund × Evermind agent & token economy hackathon<br />
Cuts the cost of coding agents. Claude Code stays the planner and, through an MCP tool, hands well-defined subtasks to the cheapest model that can do them: Codex, or Qwen3-4B running locally. A live terminal dashboard tracks every delegated task and the money saved against an all-frontier baseline, and EverOS memory feeds lessons from past runs back into planning.

Also: ML coursework from Imperial College London ([neural networks](https://github.com/yoitsmeivn/Artifical-Neural-Networks), [maths for ML](https://github.com/yoitsmeivn/Kryptonite-N)) and hackathon builds with H Company and YC.

### Activity

<p align="center">
  <img src="metrics.isocalendar.svg" alt="Contribution calendar for the past year" width="480" />
</p>

### Hackathon wins

<table>
  <tr>
    <td width="50%" valign="top">
      <b>🥈 2nd place · OpenAI hackathon</b><br />
      <sub>Soar: infrastructure for business travel</sub><br /><br />
      <img src="assets/soar-openai-2nd-place.jpg" alt="Soar landing page: Traveler context, unlocked. Infrastructure for travel." width="100%" />
    </td>
    <td width="50%" valign="top">
      <b>🥉 3rd place · Mistral AI Worldwide Hackathon</b><br />
      <sub>Canard Security · <a href="https://news.ucsc.edu/2026/03/ucsc-trio-takes-third-at-2026-mistral-ai-hackathon-with-cybersecurity-platform/">UC Santa Cruz News coverage</a></sub><br /><br />
      <a href="https://news.ucsc.edu/2026/03/ucsc-trio-takes-third-at-2026-mistral-ai-hackathon-with-cybersecurity-platform/"><img src="assets/mistral-3rd-place.jpg" alt="Anthony Lamas, Ivan Severinov and Daniel Perlov on stage after placing 3rd at the 2026 Mistral AI Worldwide Hackathon" width="100%" /></a>
    </td>
  </tr>
</table>

<sub>Most of my work lives in private repositories. It counts toward the calendar above, but repository names never appear.</sub>
