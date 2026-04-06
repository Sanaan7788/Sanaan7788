<div align="center">

# Zahiruddin Sanaan Syed

**Software Engineer · Full Stack · AI Systems**

Houston, TX &nbsp;|&nbsp; [linkedin.com/in/sanaan7788](https://www.linkedin.com/in/sanaan7788/) &nbsp;|&nbsp; [sanaan7788@gmail.com](mailto:sanaan7788@gmail.com) &nbsp;|&nbsp; [github.com/Sanaan7788](https://github.com/Sanaan7788)

</div>

---

## About

Software Engineer with 4+ years building production systems across healthcare, AI, and web domains. Currently engineering a HIPAA-compliant EHR platform (NestJS · Next.js · MariaDB) with a focus on complex data pipelines, authorization workflows, and PDF generation at scale. AWS Certified. MS Computer Science — Lamar University.

---

## Tech Stack

**Languages** — TypeScript · JavaScript · Python · Java · C++ · Dart · Go

**Frontend** — React · Next.js · Flutter · Vite · Tailwind CSS · Three.js · Framer Motion

**Backend** — NestJS · Node.js · Express · TypeORM · Drizzle ORM · REST

**Databases** — MariaDB · PostgreSQL · MySQL · MongoDB · Neon

**AI / ML** — OpenAI API · Anthropic Claude · Google Gemini · LangChain · Ollama · DeepSeek · Groq API · Tavily

**Scraping / Automation** — Playwright · Chromium · Stealth Plugin

**Infrastructure** — AWS · Docker · Vercel · Render · GitHub Actions · BullMQ · Redis

---

## Projects

### [local-business-finder](https://github.com/Sanaan7788/local-business-finder)
End-to-end lead generation and CRM system for finding offline businesses and building their web presence. Scrapes Google Maps via Playwright (Chromium) using a pre-collect pattern to avoid DOM re-render issues. Deduplicates across sessions by phone and name/address indexes. LLM layer generates SEO keywords, business summaries, and full single-file HTML websites — then pushes to GitHub and deploys to Vercel via API. CRM pipeline tracks leads from discovery through close with a 0–100 scoring model. Supports batch mode across 50+ category searches per area.

`TypeScript` `Node.js` `Express` `React 18` `Vite` `Tailwind CSS` `TanStack Query` `Playwright` `PostgreSQL` `Drizzle ORM` `Neon` `Zod` `Winston` `p-queue` `Octokit SDK` `Vercel API` `DeepSeek` `Claude` `OpenAI`

---

### [company-intelligence](https://github.com/Sanaan7788/company-intelligence)
Analyst-grade company research tool for job hunters. AI research agent generates structured intelligence dossiers — recent news, tech problems, and market opportunities — sourced from Reddit, LinkedIn, HackerNews, blogs, and job postings. Features company discovery by location/zip, bulk import, background task tracker, shortlist, tags, PDF export, and a research cache (if two companies share a website, research is cloned instantly). Pluggable LLM backends (DeepSeek V3 via NVIDIA NIM, Claude, OpenAI, Ollama). Anthropic uses native web_search tool; others inject context via Tavily or SerpAPI. npm workspaces monorepo with a shared TypeScript types package. Deployable to Render via `render.yaml`.

`TypeScript` `React 18` `Vite` `Node.js` `Express` `PostgreSQL` `Neon` `npm workspaces` `DeepSeek` `NVIDIA NIM` `Claude` `OpenAI` `Ollama` `Tavily` `SerpAPI` `Render`

---

### [autoapply](https://github.com/Sanaan7788/autoapply)
Automated job application system built as a full-stack monorepo. NestJS backend handles job discovery via Playwright + stealth plugin on LinkedIn. LLM layer (Ollama — mistral:7b for JSON extraction, qwen2.5:14b for writing) customizes resumes per job, rewrites bullet points against ATS keywords, and generates cover letters. Resume export to DOCX and PDF. BullMQ + Redis handles scheduled scraping. Kanban-style application tracker. Roadmap includes multi-board scraping (Indeed, Glassdoor), Gmail API monitoring, skills gap analysis, and Stripe-based monetization.

`TypeScript` `NestJS` `TypeORM` `React` `Vite` `Tailwind CSS` `PostgreSQL` `Docker` `Ollama` `Playwright` `BullMQ` `Redis` `Gmail API` `Stripe`

---

### [indian-stocks-halal](https://github.com/Sanaan7788/indian-stocks-halal)
Shariah-compliance screener for Nifty 50 equities. Processes stock data from CSV (nifty50_final.csv), runs each company through an LLM-powered halal evaluation (halal-bot.ts), and outputs a structured halal report. Single-file HTML frontend. Designed for swing traders screening pharma, solar, and minerals sectors.

`TypeScript` `HTML` `Groq API` `CSV`

---

### [tppes](https://github.com/Sanaan7788/tppes)
Production client website for Three Phase Power Engineering Services, a Houston-based engineering firm. Animated UI with Framer Motion. Automated contact form via EmailJS. Fully responsive layout. Actively used by the client.

`React` `Tailwind CSS` `Framer Motion` `EmailJS` `Vite`

---

### [cillies-cakes](https://github.com/Sanaan7788/cillies-cakes)
3D interactive landing page for Cillie's Cakes & Snacks, a Houston-based bakery. Built with Three.js and WebGL shaders. Features an animated 3D scene with a light/blush pink theme and native anchor-link navigation.

`Three.js` `WebGL` `JavaScript` `HTML` `CSS`

---

### [airbnb-clone](https://github.com/Sanaan7788/airbnb-clone)
Early-stage Airbnb clone — backend scaffolded in JavaScript. Property listing and booking flow architecture in progress.

`JavaScript` `Node.js`

---

### [Jewellery-website1](https://github.com/Sanaan7788/Jewellery-website1)
E-commerce style landing page for a jewellery brand. Responsive product showcase with modern UI layout.

`React` `Tailwind CSS` `Vite`

---

### [golden-rock](https://github.com/Sanaan7788/golden-rock)
Client website for Golden Rock, deployed live on Vercel. Built with React and Tailwind CSS.

`React` `JavaScript` `Tailwind CSS` `Vite` `Vercel`

---

### [unitec-website](https://github.com/Sanaan7788/unitec-website)
Corporate website for Uni-Tec Trade Inc., a Houston-based industrial supply company. React + Vite + Tailwind CSS stack.

`React` `JavaScript` `Tailwind CSS` `Vite`

---

### [tx-islamic-society](https://github.com/Sanaan7788/tx-islamic-society)
Mosque website for a Texas Islamic Society chapter. Community-facing site with prayer times, events, and contact info. Deployed live on Vercel.

`React` `JavaScript` `Tailwind CSS` `Vercel`

---

### [sample-business-websites](https://github.com/Sanaan7788/sample-business-websites)
Collection of static HTML business website templates used as client demos and AI-generated site output samples. Includes iterations of the Cillie's Cakes site. Deployed via GitHub Actions.

`HTML` `TypeScript` `CSS` `GitHub Actions`

---

### [first-llm](https://github.com/Sanaan7788/first-llm)
First exploration of LLM API integrations — separate Python wrappers for OpenAI GPT (gpt_wrapper.py) and Google Gemini (gemini_wrapper.py), unified under a Streamlit interface (home.py). Starting point for understanding multi-provider AI abstraction patterns.

`Python` `OpenAI API` `Google Gemini API` `Streamlit`

---

### [ai-pdf-summarizer](https://github.com/Sanaan7788/ai-pdf-summarizer)
PDF Q&A system using LangChain and Streamlit. Processes documents and answers natural language questions against their content.

`Python` `LangChain` `Streamlit`

---

### [tic-tac-toe](https://github.com/Sanaan7788/tic-tac-toe)
Browser-based Tic-Tac-Toe game built with React and Vite. Game state management and win detection logic.

`React` `JavaScript` `Vite` `CSS`

---

### [Personal-Budget-Manager-master](https://github.com/Sanaan7788/Personal-Budget-Manager-master)
Personal finance tracker built in Go with a proper MVC architecture — config, controllers, models, services, and utils layers. Containerized with Docker Compose. Built to explore Go's type system and web server patterns outside the JS ecosystem.

`Go` `Docker` `Docker Compose` `MVC`

---

### [todolist](https://github.com/Sanaan7788/todolist)
Cross-platform to-do list app built with Flutter and Dart. Targets Android, iOS, web, desktop (Linux, macOS, Windows) from a single codebase.

`Flutter` `Dart`

---

### [Competitive-Programming](https://github.com/Sanaan7788/Competitive-Programming)
Archive of competitive programming solutions. ICPC South Central USA Region participant. HackerRank certified in Java and Problem Solving.

`C++` `Algorithms` `Data Structures`

---

## Open Source Contributions

| Repository | Description |
|---|---|
| [PlaidwareSolutions/fixorata](https://github.com/PlaidwareSolutions/fixorata) | Business management platform |
| [plaidware-solutions/grantoptima](https://github.com/plaidware-solutions/grantoptima) | Grant optimization tool |
| [kfnawaz/escapelify](https://github.com/kfnawaz/escapelify) | Escape room booking app |
| [kfnawaz/grantoptima](https://github.com/kfnawaz/grantoptima) | Grant management system |
| [kfnawaz/crwn-clothing](https://github.com/kfnawaz/crwn-clothing) | E-commerce clothing app |
| [kfnawaz/imessage-clone](https://github.com/kfnawaz/imessage-clone) | Real-time messaging clone |

---

## Achievements

| | |
|---|---|
| ☁️ | AWS Certified Cloud Practitioner |
| 🏆 | ICPC South Central USA Region Participant |
| 📈 | Ranked 644 / 12,000+ — Newton Coding Challenge |
| 🥈 | 2nd Prize — Best Engineering Project |
| ✅ | HackerRank Certified — Java & Problem Solving |

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sanaan7788&show_icons=true&theme=tokyonight&hide_border=true" height="160"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sanaan7788&layout=compact&theme=tokyonight&hide_border=true" height="160"/>

</div>

---

<div align="center">
<sub>Most production work lives on a private org repo. This account reflects personal and open-source projects.</sub>
</div>
