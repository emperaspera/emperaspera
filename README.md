<!--
**emperaspera/emperaspera** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<h1 align="center">Emil Khamedov</h1>

<p align="center">
  <a href="https://emperaspera.com"><img src="https://img.shields.io/badge/Portfolio-emperaspera.com-0b7285?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/emil-khamedov"><img src="https://img.shields.io/badge/LinkedIn-emil--khamedov-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:emil.khamedov.uk@gmail.com"><img src="https://img.shields.io/badge/Email-get_in_touch-c92a2a?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <b>AI &amp; Software Engineering</b> · <b>AI Agents, Automation &amp; Integration</b> · <b>Fintech &amp; Quantitative Systems</b>
</p>

---

<table align="center">
<tr>
<td align="center" width="25%"><h3>5</h3>production systems<br>shipped</td>
<td align="center" width="25%"><h3>2M+</h3>citizens served by<br>systems I built</td>
<td align="center" width="25%"><h3>~170</h3>daily organic<br>sign-ups on my SaaS</td>
<td align="center" width="25%"><h3>~30%</h3>inference cost<br>reduction</td>
</tr>
</table>

---

BSc Computer Science, **First Class Honours (4.0/4.0)**, University of Birmingham · **MSc Finance, UCL** from September 2026.

I build production systems end to end: AI agent infrastructure, payment and billing backends, and quantitative tooling. Most recently a quantitative developer at an investment fund, building market data pipelines and deploying MCP servers that connect LLMs to live market data.

> **Most repositories below are private** — they contain client systems, production credentials or commercial code. Happy to walk through architecture, trade-offs and code in a call.

---

## Selected work

<details open>
<summary><b>Multimodal AI Generation Platform</b> — live SaaS, solo-built</summary>
<br>

Image, video, audio and chat generation with real-time AI voice and video calling, running on a self-hosted inference stack.

| | |
|---|---|
| **Scale** | ~170 daily organic sign-ups, SEO-led |
| **Revenue** | Subscriptions and token purchases |
| **Timeline** | Dec 2025 – present, built solo |

- Real-time voice pipeline on **LiveKit Agents** with Deepgram STT and ElevenLabs TTS
- Self-hosted **ComfyUI** generation on autoscaled GPU workers — **~30% inference cost reduction** by consolidating image and video onto shared workers
- Multi-agent marketing pipeline (**Claude subagents, MCP, LangChain, Temporal**) generating and publishing content with human-in-the-loop approval
- Append-only **PL/pgSQL** billing ledger with idempotency keys, verified webhooks and revenue reconciliation

`Next.js` `TypeScript` `Supabase` `LiveKit` `ComfyUI` `PostgreSQL` `Vercel`

</details>

<details>
<summary><b>ZHULDYZ OS</b> — multi-industry ERP, deployed</summary>
<br>

A corporate operating system for a holding company spanning **construction, oil production and property rental**.

- Approval workflows with SLA escalations and accounting integration
- Telegram intake and notifications; AI site-camera monitoring producing daily activity summaries
- Self-hosted LLM layer (**vLLM, Ollama, Whisper**) for AI-assisted drafting
- Playwright end-to-end coverage across 17 role accounts

`Frappe/ERPNext` `Python` `MariaDB` `Docker`

</details>

<details>
<summary><b>UK Property Investment Research Engine</b></summary>
<br>

Aggregates UK auctions and listings, scoring each deal against valuation logic developed over three months of R&amp;D.

- Sources **Rightmove, Zoopla, HM Land Registry, ONS**
- Buy-to-let **ROI** and **UK SDLT** engines, refurbishment cost models, weighted ranking
- Claude multimodal condition assessment of listing photos as one scoring input

`Python` `FastAPI` `Playwright` `Claude API` `Supabase`

</details>

<details>
<summary><b>E-commerce Payments Platform</b> — live</summary>
<br>

Headless commerce platform with subscriptions and members-only purchasing.

- Led a full processor migration from **Authorize.Net to Stripe**
- Fail-closed payment safeguards, **PCI-compliant** tokenisation, idempotent retries, order reconciliation

`Medusa v2` `Next.js` `Stripe` `PostgreSQL` `Redis`

</details>

<details>
<summary><b>Restaurant AI CRM Ecosystem</b> — deployed in 6 restaurants</summary>
<br>

Three integrated applications — owner, employee and customer — covering inventory, shift scheduling, staff productivity and payments.

`Flutter` `Node.js` `Supabase` `Stripe`

</details>

---

## Toolkit

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white">
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
</p>

**AI &amp; agents** &nbsp; Multi-agent orchestration · MCP (client &amp; server) · LangChain · LangGraph · tool calling &amp; structured outputs · prompt engineering · RAG &amp; embeddings (pgvector) · LLM evaluation · computer vision · PyTorch · TensorFlow · self-hosted inference (vLLM, Ollama, Qwen)

**Backend** &nbsp; Node.js · NestJS · FastAPI · Spring Boot · REST &amp; GraphQL · microservices · Apache Kafka · Temporal · WebRTC · PostgreSQL · MariaDB · Redis · Supabase

**Frontend** &nbsp; React · Next.js · Angular · Flutter · Tailwind CSS

**Infrastructure** &nbsp; Docker · Kubernetes · AWS · Terraform · GitHub Actions · Linux · n8n · monitoring &amp; observability · Playwright · Jest

**Quantitative** &nbsp; Factor modelling · algorithmic trading · backtesting · market data pipelines · pandas · NumPy · payment reconciliation

---

## Also

Computer vision and embedded electronics (YOLOv8 training, Arduino, USB HID) · a client/server firewall written in C · piano, guitar and competitive mathematics.

<p align="center">
  <a href="mailto:emil.khamedov.uk@gmail.com"><b>Get in touch →</b></a>
</p>
