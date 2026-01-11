<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00FF41&height=120&section=header"/>

<p align="center">
<img src="assets/terminal-card.svg" width="1100" alt="Terminal profile card"/>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/zlash65"><img src="https://img.shields.io/badge/LinkedIn-zlash65-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn zlash65"/></a>
<a href="https://github.com/Zlash65"><img src="https://img.shields.io/badge/GitHub-Zlash65-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://zlash.xyz"><img src="https://img.shields.io/badge/Portfolio-zlash.xyz-667eea?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio"/></a>
<a href="mailto:zarrar65@gmail.com"><img src="https://img.shields.io/badge/Email-zarrar65%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
<a href="https://www.npmjs.com/package/@zlash65/postgresql-ssh-mcp"><img src="https://img.shields.io/npm/v/@zlash65/postgresql-ssh-mcp?color=667eea&label=@zlash65/postgresql-ssh-mcp&logo=npm" alt="npm"/></a>
<a href="https://pypi.org/project/amazon-bedrock-knowledge-base-mcp/"><img src="https://img.shields.io/pypi/v/amazon-bedrock-knowledge-base-mcp?color=764ba2&label=amazon-bedrock-knowledge-base-mcp&logo=pypi&logoColor=white" alt="PyPI"/></a>
<img src="https://komarev.com/ghpvc/?username=Zlash65&color=667eea&style=flat" alt="Profile views"/>
</p>

<p align="center">
<img src="assets/metrics-pills.svg" alt="8+ years Experience · ₹1B+ Transactions · $72K+/yr Cost Saved · 70% Docker Reduction"/>
</p>

<p align="center">Open to local + global remote opportunities</p>

<p align="center"><b>Open to DevOps · SRE · Backend · Platform · Infrastructure · GenAI roles.</b></p>

---

## Featured: Published MCP Servers

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">PostgreSQL SSH MCP Server</h3>

<p align="center">
  <a href="https://www.npmjs.com/package/@zlash65/postgresql-ssh-mcp"><img src="https://img.shields.io/npm/v/@zlash65/postgresql-ssh-mcp?color=667eea&label=npm&logo=npm" alt="npm"/></a>
  <a href="https://www.npmjs.com/package/@zlash65/postgresql-ssh-mcp"><img src="https://img.shields.io/npm/dm/@zlash65/postgresql-ssh-mcp?color=667eea&label=downloads" alt="downloads"/></a>
</p>

<p align="center">
Secure PostgreSQL access with <b>built-in SSH tunneling</b> (bastions), plus a remote-friendly Streamable HTTP transport.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
</p>

<p align="center">
  <a href="https://github.com/Zlash65/postgresql-ssh-mcp">GitHub</a> ·
  <a href="https://www.npmjs.com/package/@zlash65/postgresql-ssh-mcp">npm</a> ·
  <a href="https://dev.to/zlash65/postgresql-mcp-server-with-built-in-ssh-tunneling-2geb">Blog</a>
</p>

</td>
<td width="50%" valign="top">

<h3 align="center">Amazon Bedrock Knowledge Base MCP</h3>

<p align="center">
  <a href="https://pypi.org/project/amazon-bedrock-knowledge-base-mcp/"><img src="https://img.shields.io/pypi/v/amazon-bedrock-knowledge-base-mcp?color=764ba2&label=pypi&logo=pypi" alt="PyPI"/></a>
  <a href="https://pypi.org/project/amazon-bedrock-knowledge-base-mcp/"><img src="https://img.shields.io/pypi/dm/amazon-bedrock-knowledge-base-mcp?color=764ba2&label=downloads" alt="downloads"/></a>
</p>

<p align="center">
Query <b>Amazon Bedrock Knowledge Bases</b> with filtering, schema discovery, and reranking support.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat&logo=amazonwebservices&logoColor=white" alt="AWS Bedrock"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI"/>
</p>

<p align="center">
  <a href="https://github.com/Zlash65/amazon-bedrock-knowledge-base-mcp">GitHub</a> ·
  <a href="https://pypi.org/project/amazon-bedrock-knowledge-base-mcp/">PyPI</a>
</p>

</td>
</tr>
</table>

<details>
<summary><b>Production deployment docs (Linux + systemd + nginx + HTTPS) - transferable setup</b></summary>
<br/>

Both MCP repos include an end-to-end deployment guide that's usable beyond "toy demos":

- **Full Linux setup**: DNS -> nginx reverse proxy -> Let's Encrypt (certbot) -> health checks & logs.
- **Systemd-managed service**: restart policies, log tailing via `journalctl`, simple upgrades.
- **Streamable HTTP**: remote clients + connectors (including ChatGPT).
- **Optional OAuth**: Auth0-backed flows for secure remote access.

This process is broadly transferable to any **HTTP-streamable** MCP server: swap the binary + port, keep the hardened server pattern.

Quick links:
- PostgreSQL SSH MCP: [server setup](https://github.com/Zlash65/postgresql-ssh-mcp/blob/main/docs/server-setup.md) · [streamable HTTP](https://github.com/Zlash65/postgresql-ssh-mcp/blob/main/docs/streamable-http.md) · [ChatGPT setup](https://github.com/Zlash65/postgresql-ssh-mcp/blob/main/docs/chatgpt-setup.md)
- Amazon Bedrock Knowledge Base MCP: [server setup](https://github.com/Zlash65/amazon-bedrock-knowledge-base-mcp/blob/main/docs/server-setup.md) · [streamable HTTP](https://github.com/Zlash65/amazon-bedrock-knowledge-base-mcp/blob/main/docs/streamable-http.md) · [ChatGPT setup](https://github.com/Zlash65/amazon-bedrock-knowledge-base-mcp/blob/main/docs/chatgpt-setup.md)

</details>

---

## Highlights

<details>
<summary><b>Click to view highlights by company</b></summary>
<br/>

**Clipboard Health** (YC S17)
- **20+ services** — migrated from Heroku → AWS, zero downtime
- **70% faster deploys** — 50+ min → under 15 min via pipeline optimization
- **50% smaller images** — Docker optimization + multi-stage builds
- **75% less infra drift** — IaC refactoring + multi-env guardrails
- **75% Terraform cost reduction** — $2K/month → under $500/month
- **Private Terraform modules** published (ECS, RDS, VPC)

**Stealth Startup**
- **$60K+/year saved** — cloud optimization + Terraform standardization
- **70% smaller images** — Docker optimization + multi-stage builds
- **GenAI CRM** — multi-source ingestion (Zoom, Granola, OpenPhone, Gmail, PostHog, Calendly)
- **GenAI KB** — In-house CRM + Bedrock KB + OpenSearch vector store, Claude/ChatGPT queryable
- **Private Terraform modules** published (ECS, ElastiCache, RDS, VPC)

**Kredily**
- **₹1B+ transactions** at 99% uptime — fintech payroll platform

**Open Source**
- **MCP servers** published (npm + PyPI) with production deployment docs

</details>

---

## Tech Stack

<div align="center">
<table>
<tr>
<td valign="top" width="50%">

<h3 align="center">Backend</h3>

<p align="center">
  <a href="https://www.python.org/"><img src="assets/skill-icons/python-dark.svg" height="48" alt="Python"/></a>&nbsp;&nbsp;
  <a href="https://nodejs.org/"><img src="assets/skill-icons/nodejs-dark.svg" height="48" alt="Node.js"/></a>&nbsp;&nbsp;
  <a href="https://expressjs.com/"><img src="assets/skill-icons/expressjs-dark.svg" height="48" alt="Express.js"/></a>&nbsp;&nbsp;
  <a href="https://fastapi.tiangolo.com/"><img src="assets/skill-icons/fastapi.svg" height="48" alt="FastAPI"/></a>&nbsp;&nbsp;
  <a href="https://www.djangoproject.com/"><img src="assets/skill-icons/django.svg" height="48" alt="Django"/></a>&nbsp;&nbsp;
  <a href="https://flask.palletsprojects.com/"><img src="assets/skill-icons/flask.svg" height="48" alt="Flask"/></a>
</p>

<p align="center">
  <a href="https://www.postgresql.org/"><img src="assets/skill-icons/postgresql-dark.svg" height="48" alt="PostgreSQL"/></a>&nbsp;&nbsp;
  <a href="https://redis.io/"><img src="assets/skill-icons/redis-dark.svg" height="48" alt="Redis"/></a>&nbsp;&nbsp;
  <a href="https://www.rabbitmq.com/"><img src="assets/skill-icons/rabbitmq-dark.svg" height="48" alt="RabbitMQ"/></a>&nbsp;&nbsp;
  <a href="https://www.mongodb.com/"><img src="assets/skill-icons/mongodb.svg" height="48" alt="MongoDB"/></a>&nbsp;&nbsp;
  <a href="https://mariadb.org/"><img src="assets/skill-icons/mariadb-dark.svg" height="48" alt="MariaDB"/></a>&nbsp;&nbsp;
  <a href="https://aws.amazon.com/dynamodb/"><img src="assets/skill-icons/dynamodb-dark.svg" height="48" alt="Amazon DynamoDB"/></a>
</p>

<p align="center">
  <a href="https://frappeframework.com/"><img src="assets/frappe.svg" height="48" alt="Frappe"/></a>&nbsp;&nbsp;
  <a href="https://erpnext.com/"><img src="assets/erpnext.svg" height="48" alt="ERPNext"/></a>
</p>

</td>
<td valign="top" width="50%">

<h3 align="center">DevOps / Cloud</h3>

<p align="center">
  <a href="https://aws.amazon.com/"><img src="assets/skill-icons/aws-dark.svg" height="48" alt="AWS"/></a>&nbsp;&nbsp;
  <a href="https://www.linux.org/"><img src="assets/skill-icons/linux-dark.svg" height="48" alt="Linux"/></a>&nbsp;&nbsp;
  <a href="https://www.gnu.org/software/bash/"><img src="assets/skill-icons/bash-dark.svg" height="48" alt="Bash"/></a>&nbsp;&nbsp;
  <a href="https://git-scm.com/"><img src="assets/skill-icons/git-dark.svg" height="48" alt="Git"/></a>&nbsp;&nbsp;
  <a href="https://www.docker.com/"><img src="assets/skill-icons/docker.svg" height="48" alt="Docker"/></a>
</p>

<p align="center">
  <a href="https://kubernetes.io/"><img src="assets/skill-icons/kubernetes.svg" height="48" alt="Kubernetes"/></a>&nbsp;&nbsp;
  <a href="https://www.terraform.io/"><img src="assets/skill-icons/terraform-dark.svg" height="48" alt="Terraform"/></a>&nbsp;&nbsp;
  <a href="https://github.com/features/actions"><img src="assets/skill-icons/githubactions-dark.svg" height="48" alt="GitHub Actions"/></a>&nbsp;&nbsp;
  <a href="https://www.jenkins.io/"><img src="assets/skill-icons/jenkins-dark.svg" height="48" alt="Jenkins"/></a>&nbsp;&nbsp;
  <a href="https://nginx.org/"><img src="assets/skill-icons/nginx.svg" height="48" alt="nginx"/></a>
</p>

<p align="center">
  <a href="https://aws.amazon.com/ecs/"><img src="assets/skill-icons/ecs.svg" height="48" alt="Amazon ECS"/></a>&nbsp;&nbsp;
  <a href="https://aws.amazon.com/lambda/"><img src="assets/skill-icons/lambda.svg" height="48" alt="AWS Lambda"/></a>&nbsp;&nbsp;
  <a href="https://systemd.io/"><img src="assets/skill-icons/systemd-dark.svg" height="48" alt="systemd"/></a>
</p>

</td>
</tr>
<tr>
<td valign="top" width="50%">

<h3 align="center">AI / LLM</h3>

<p align="center">
  <a href="https://openai.com/"><img src="assets/skill-icons/openai-dark.svg" height="48" alt="OpenAI"/></a>&nbsp;&nbsp;
  <a href="https://www.anthropic.com/"><img src="assets/skill-icons/anthropic-dark.svg" height="48" alt="Anthropic"/></a>&nbsp;&nbsp;
  <a href="https://aws.amazon.com/bedrock/"><img src="assets/skill-icons/bedrock-dark.svg" height="48" alt="Amazon Bedrock"/></a>&nbsp;&nbsp;
  <a href="https://huggingface.co/"><img src="assets/skill-icons/huggingface-dark.svg" height="48" alt="Hugging Face"/></a>&nbsp;&nbsp;
  <a href="https://python.langchain.com/"><img src="assets/skill-icons/langchain-dark.svg" height="48" alt="LangChain"/></a>
</p>

<p align="center">
  <a href="https://streamlit.io/"><img src="assets/skill-icons/streamlit-dark.svg" height="48" alt="Streamlit"/></a>&nbsp;&nbsp;
  <a href="https://docs.trychroma.com/"><img src="assets/skill-icons/chromadb-dark.svg" height="48" alt="ChromaDB"/></a>&nbsp;&nbsp;
  <a href="https://github.com/facebookresearch/faiss"><img src="assets/skill-icons/faiss-dark.svg" height="48" alt="FAISS"/></a>&nbsp;&nbsp;
  <a href="https://ai.google.dev/"><img src="assets/skill-icons/gemini-dark.svg" height="48" alt="Gemini"/></a>&nbsp;&nbsp;
  <a href="https://groq.com/"><img src="assets/skill-icons/groq-dark.svg" height="48" alt="Groq"/></a>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2005.11401"><img src="assets/skill-icons/rag-dark.svg" height="48" alt="RAG"/></a>&nbsp;&nbsp;
  <a href="https://modelcontextprotocol.io/"><img src="assets/skill-icons/modelcontextprotocol-dark.svg" height="48" alt="Model Context Protocol"/></a>
</p>

</td>
<td valign="top" width="50%">

<h3 align="center">Frontend</h3>

<p align="center">
  <a href="https://react.dev/"><img src="assets/skill-icons/react-dark.svg" height="48" alt="React"/></a>&nbsp;&nbsp;
  <a href="https://nextjs.org/"><img src="assets/skill-icons/nextjs-dark.svg" height="48" alt="Next.js"/></a>&nbsp;&nbsp;
  <a href="https://vuejs.org/"><img src="assets/skill-icons/vuejs-dark.svg" height="48" alt="Vue.js"/></a>&nbsp;&nbsp;
  <a href="https://vitejs.dev/"><img src="assets/skill-icons/vite-dark.svg" height="48" alt="Vite"/></a>&nbsp;&nbsp;
  <a href="https://tailwindcss.com/"><img src="assets/skill-icons/tailwindcss-dark.svg" height="48" alt="Tailwind CSS"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/docs/Web/HTML"><img src="assets/skill-icons/html.svg" height="48" alt="HTML"/></a>
</p>

<p align="center">
  <a href="https://developer.mozilla.org/docs/Web/CSS"><img src="assets/skill-icons/css.svg" height="48" alt="CSS"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/docs/Web/JavaScript"><img src="assets/skill-icons/javascript.svg" height="48" alt="JavaScript"/></a>&nbsp;&nbsp;
  <a href="https://www.typescriptlang.org/"><img src="assets/skill-icons/typescript.svg" height="48" alt="TypeScript"/></a>&nbsp;&nbsp;
  <a href="https://sass-lang.com/"><img src="assets/skill-icons/sass.svg" height="48" alt="Sass"/></a>&nbsp;&nbsp;
  <a href="https://getbootstrap.com/"><img src="assets/skill-icons/bootstrap.svg" height="48" alt="Bootstrap"/></a>&nbsp;&nbsp;
  <a href="https://graphql.org/"><img src="assets/skill-icons/graphql-dark.svg" height="48" alt="GraphQL"/></a>
</p>

</td>
</tr>
</table>

<p align="center">
  <a href="https://www.datadoghq.com/"><img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" alt="Datadog"/></a>&nbsp;&nbsp;
  <a href="https://www.metabase.com/"><img src="https://img.shields.io/badge/Metabase-509EE3?style=flat-square&logo=metabase&logoColor=white" alt="Metabase"/></a>&nbsp;&nbsp;
  <a href="https://www.appsmith.com/"><img src="https://img.shields.io/badge/Appsmith-000000?style=flat-square&logo=appsmith&logoColor=white" alt="Appsmith"/></a>&nbsp;&nbsp;
  <a href="https://retool.com/"><img src="https://img.shields.io/badge/Retool-0086FF?style=flat-square&logo=retool&logoColor=white" alt="Retool"/></a>&nbsp;&nbsp;
  <a href="https://www.atlassian.com/software/jira"><img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira"/></a>&nbsp;&nbsp;
  <a href="https://www.atlassian.com/software/confluence"><img src="https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white" alt="Confluence"/></a>&nbsp;&nbsp;
  <a href="https://bitrise.io/"><img src="https://img.shields.io/badge/Bitrise-683D87?style=flat-square&logo=bitrise&logoColor=white" alt="Bitrise"/></a>&nbsp;&nbsp;
  <a href="https://developer.apple.com/xcode/"><img src="https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white" alt="Xcode"/></a>&nbsp;&nbsp;
  <a href="https://developer.android.com/studio"><img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white" alt="Android Studio"/></a>
</p>
</div>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center">RAG PDF Chatbot (V3)</h3>
<p align="center"><i>Multi-LLM RAG pipeline with a production-leaning architecture</i></p>
<p align="center"><a href="https://github.com/Zlash65/rag-bot-fastapi">GitHub</a> · <a href="https://dev.to/zlash65/rag-pdfbot-v3-from-prototype-to-production-ready-ish-32f7">Blog</a></p>

</td>
<td width="50%" valign="top">

<h3 align="center">Agentic AI Chatbot</h3>
<p align="center"><i>Tool-calling agent patterns with FastAPI + Streamlit</i></p>
<p align="center"><a href="https://github.com/Zlash65/agentic-ai-chatbot-example">GitHub</a> · <a href="https://dev.to/zlash65/building-an-ai-chatbot-with-langchain-fastapi-streamlit-377m">Blog</a></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3 align="center">Gen-AI Dockerfile Generator</h3>
<p align="center"><i>AWS Bedrock + Terraform + Lambda</i></p>
<p align="center"><a href="https://github.com/Zlash65/aws-bedrock-example">GitHub</a> · <a href="https://dev.to/zlash65/build-a-gen-ai-dockerfile-generator-with-aws-bedrock-lambda-and-terraform-17n8">Blog</a></p>

</td>
<td width="50%" valign="top">

<h3 align="center">Portfolio Website</h3>
<p align="center"><i>Next.js + Tailwind</i></p>
<p align="center"><a href="https://zlash.xyz">View Site</a> · <a href="https://github.com/Zlash65/zlash.xyz">GitHub</a></p>

</td>
</tr>
</table>

---

## Writing

<p>
  <a href="https://dev.to/zlash65"><img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" alt="Dev.to"/></a>
  <a href="https://medium.com/@zlash65"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
</p>

- [PostgreSQL MCP Server with Built-in SSH Tunneling](https://dev.to/zlash65/postgresql-mcp-server-with-built-in-ssh-tunneling-2geb)
- [RAG PDFBot V3: Prototype to Production](https://dev.to/zlash65/rag-pdfbot-v3-from-prototype-to-production-ready-ish-32f7)
- [Building an AI Chatbot with LangChain](https://dev.to/zlash65/building-an-ai-chatbot-with-langchain-fastapi-streamlit-377m)
- [Gen-AI Dockerfile Generator with AWS Bedrock](https://dev.to/zlash65/build-a-gen-ai-dockerfile-generator-with-aws-bedrock-lambda-and-terraform-17n8)
- [Self-hosted Jitsi Meet for Remote Teams](https://medium.com/@zlash65/setting-up-jitsi-meet-on-your-server-b29ca29ef345)

---

## Open Source

<details>
<summary><b>Contributions & integrations</b></summary>
<br/>

- [ERPNext PRs](https://github.com/frappe/erpnext/pulls?q=is%3Apr+author%3AZlash65+is%3Aclosed)
- [Frappe Framework PRs](https://github.com/frappe/frappe/pulls?q=is%3Apr+author%3AZlash65+is%3Aclosed)
- [Mattermost-related repos](https://github.com/Zlash65?tab=repositories&q=mattermost)
- [Jitsi-related repos](https://github.com/Zlash65?tab=repositories&q=jitsi)

</details>

---

## GitHub Stats

<p align="center">
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github_dark/0-profile-details.svg#gh-dark-mode-only" alt="Profile details (dark)"/>
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github_dark/3-stats.svg#gh-dark-mode-only" alt="Stats (dark)"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github_dark/1-repos-per-language.svg#gh-dark-mode-only" alt="Repos per language (dark)"/>
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github_dark/2-most-commit-language.svg#gh-dark-mode-only" alt="Most commit language (dark)"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github/0-profile-details.svg#gh-light-mode-only" alt="Profile details (light)"/>
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github/3-stats.svg#gh-light-mode-only" alt="Stats (light)"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github/1-repos-per-language.svg#gh-light-mode-only" alt="Repos per language (light)"/>
  <img src="https://raw.githubusercontent.com/Zlash65/Zlash65/main/profile-summary-card-output/github/2-most-commit-language.svg#gh-light-mode-only" alt="Most commit language (light)"/>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00FF41&height=120&section=footer"/>
