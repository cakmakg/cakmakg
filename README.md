<h1 align="center">Gökhan Cakmak</h1>
<h3 align="center">AI Systems Engineer · Full-Stack-Entwickler</h3>

<p align="center">
  Ich entwickle <b>produktionsreife, autonome KI-Systeme</b> — keine Prototypen.<br/>
  Multi-Agenten-Architekturen · LangGraph · n8n-Automatisierung · AWS Bedrock · MCP
</p>

<p align="center">
  <a href="https://gokhancakmak.vercel.app/">🌐 Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/g%C3%B6khan-cakmak/">💼 LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:gokhan.cakmak@web.de">✉️ E-Mail</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Offen%20f%C3%BCr-AI%20Engineer%20%2F%20AI%20Solutions%20Engineer-brightgreen?style=flat-square" alt="Offen für Anstellung" />
  <img src="https://img.shields.io/badge/Bonn%20%C2%B7%20K%C3%B6ln-oder%20Remote-blue?style=flat-square" alt="Standort" />
</p>

---

Ich entwickle **autonome KI-Systeme, die echte Geschäftsprozesse automatisieren** — produktionsreif, keine Proof-of-Concepts. Mein Fokus liegt auf **Multi-Agenten-Architekturen**, **n8n-Automatisierungspipelines** und tiefer **LLM-Integration**.

Vor meiner Tech-Karriere habe ich ein eigenes Unternehmen geführt — deshalb denke ich nicht nur in Code, sondern in **Geschäftswert**. Die Systeme, die ich baue, lösen echte Probleme.

🔭 **Aktuell:** Ich entwickle den **Autonomous SecOps Agent** (agentisches Security-Command-Center mit LangGraph & AWS) sowie **AI Orchestra**, eine autonome B2B-Pipeline mit 11 Agenten.

---

## 🛠️ Tech-Stack

<div align="center">

**🤖 Generative KI & Agenten**

<img src="https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
<img src="https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS Bedrock" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/RAG-5A67D8?style=for-the-badge" alt="RAG" />
<img src="https://img.shields.io/badge/Human--in--the--Loop-4B5563?style=for-the-badge" alt="HITL" />

**⚙️ Automatisierung**

<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n" />
<img src="https://img.shields.io/badge/Model_Context_Protocol-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="MCP" />
<img src="https://img.shields.io/badge/Webhook--Design-2088FF?style=for-the-badge&logo=webhooks&logoColor=white" alt="Webhook Design" />

**💻 Core Stack**

<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,express,mongodb,tailwind&theme=dark" alt="Core Stack" />

**🔧 DevOps & Tools**

<img src="https://skillicons.dev/icons?i=docker,aws,git,github,postman,vscode&theme=dark" alt="DevOps & Tools" />

</div>

---

## 🌟 Ausgewählte Projekte

### 🛡️ Autonomous SecOps Agent — Enterprise Security Command Center &nbsp;·&nbsp; [Code](https://github.com/cakmakg/Autonomous-secops-agent)
Produktionsreifes B2B-SecOps-System: Express-API + **agentische LangGraph-Pipeline mit 7 Knoten**, die Cyber-Bedrohungen erkennt, kritische Fälle über ein Human-in-the-Loop-Gate leitet und automatisch AWS-WAF-IP-Blocking ausführt.
- **Threat Detection:** AWS SageMaker (Random Cut Forest) Anomalie-Scoring + Enrichment via n8n (VirusTotal / AbuseIPDB / Shodan)
- **Agentische Pipeline:** ThreatAnalyzer → InputGuardrail (Prompt-Injection-Schutz) → HITL-Gate (`interrupt()` + WebSocket-Alert) → MitigationStrategist → IncidentWriter → QACritic
- **Enterprise-Grade:** Multi-Tenancy mit AES-256-GCM-Secret-Verschlüsselung, MCP-Tool-Server, JWT-Auth, MongoDB
- **Stack:** TypeScript · LangGraph · Claude 3.5 (Sonnet + Haiku) · AWS SageMaker & WAF · Express · WebSocket · MongoDB

### 🎼 AI Orchestra — Autonomes System mit 11 Agenten &nbsp;·&nbsp; [Fallstudie](https://gokhancakmak.vercel.app/)
Produktionsreifes Multi-Agenten-System, das **B2B-Content, Research und E-Mail-Outreach vollständig autonom koordiniert**.
- **Orchestrierung:** LangGraph steuert 11 spezialisierte Agenten end-to-end
- **Human-in-the-Loop:** Freigabe-Gates über Telegram vor jeder externen Aktion
- **Memory & Retrieval:** RAG über MongoDB Atlas Vector Search
- **Stack:** LangGraph · Claude API · MongoDB Vector Search · Telegram · Node.js / TypeScript

### ✈️ Reisegesucht — Full-Stack-Reiseportal &nbsp;·&nbsp; [Code](https://github.com/cakmakg/reisegesucht-website)
Produktives Reiseportal (App Router) mit MVC-artiger Backend-Schicht — im beruflichen Umfeld entwickelt.
- **Custom-JWT-Auth:** Access- + Refresh-Tokens, httpOnly-Cookies, argon2-Passwort-Hashing
- **Affiliate-Integration** (travianet TBE2, travelsystem) + MongoDB-Katalog & Merkliste
- **Stack:** Next.js 16 · React 19 · TypeScript (strict) · Tailwind CSS v4 · shadcn/ui · Mongoose

---

## 💼 Berufserfahrung

| Rolle | Unternehmen | Zeitraum |
| :--- | :--- | :--- |
| Web Developer | Reisegesucht | Feb 2026 – heute |
| IT Support Specialist | GIS GmbH | Nov 2025 – Feb 2026 |
| Web Developer | Vidinli Software | Sep 2025 – Nov 2025 |
| Systemadministrator | emlak-ag.de | Feb 2024 – Jun 2024 |
| IT Support Specialist | UNHCR (UN-Flüchtlingshilfe) | Sep 2023 – Okt 2023 |

🎓 **Fachinformatiker – Anwendungsentwicklung** (FAW) &nbsp;·&nbsp; **Full-Stack Web Dev Bootcamp** (Clarusway)

---

## 📈 GitHub-Statistiken

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=cakmakg&show_icons=true&theme=tokyonight&hide_border=true&locale=de" alt="GitHub-Statistiken von Gökhan" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cakmakg&layout=compact&theme=tokyonight&hide_border=true&locale=de" alt="Meistgenutzte Sprachen" height="165" />
</p>
