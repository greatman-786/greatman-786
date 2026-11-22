# Asad Ullah

I build AI systems that run without anyone watching them, and I test the parts that break.

Most of what's here is automation: agents that take a phone call, read an inbox, or qualify a lead and write it somewhere useful. The rest is the testing work that keeps them honest — because a system nobody checks is a system quietly failing.

Right now I'm writing and publishing technical content for a cybersecurity client, which mostly means finding out what vendors will and won't put in writing.

---

### Things worth looking at

**[Accessibility Audit Portfolio](https://github.com/greatman-786/accessibility-audit-portfolio)**

WCAG 2.1 AA audits of nine production sites — BBC, Amazon, Emirates, LinkedIn, AliExpress and others. 174 issues documented with severity, affected elements and what to change. AliExpress prices sit at 4.39:1 contrast against a 4.5:1 requirement. noon.com has 24 category links with no accessible name. Every number is traceable to a file in the repo, and the method section says plainly that automated scanning catches only 30–40% of real barriers.

**[AI Testing Portfolio](https://github.com/greatman-786/ai-testing-portfolio)**

An evaluation framework for LLM output: factual accuracy, JSON schema validity, latency, hallucination detection. Runs against recorded responses by default, so the suite finishes in under half a second; live API calls run only on request.

**[AI Voice Agent](https://github.com/greatman-786/ai-voice-agent)**

A bilingual English/Urdu agent on a live phone number. Books appointments, qualifies leads, escalates to a human, and logs every call. Shipped with 13 test cases and 5 documented defects — including a webhook reporting 52 consecutive successes while writing mostly empty rows. Nothing errored. I found it by checking the data rather than trusting the response.

**[QA Portfolio](https://github.com/greatman-786/qa-portfolio)**

Five Playwright tests covering login, cart and checkout on a demo storefront, plus a SQLite round-trip check, wired to a GitHub Actions workflow.

**[MarketMind](https://github.com/greatman-786/marketmind)**

A marketing copy generator that remembers what it wrote. Three drafts per request, tone presets, searchable history, CSV and Markdown export, per-user accounts. Next.js and TypeScript with Prisma underneath — SQLite locally, Postgres in production. [Live](https://marketmind-gray.vercel.app).

**[n8n Agents](https://github.com/greatman-786?tab=repositories)**

Four working agents — lead qualification, WhatsApp, email, content — each repo carrying the actual workflow export, not a screenshot. Import the JSON into your own n8n and it runs.

---

### What I work with

- **AI** — Claude · Gemini · LangChain · ChromaDB · RAG · vector embeddings · prompt engineering · LLM evaluation
- **Automation** — n8n · Zapier · Make.com · webhooks · REST APIs · Vapi
- **Python** — NumPy · Pandas · Matplotlib · Seaborn · FastAPI · BeautifulSoup
- **Testing** — PyTest · Playwright · axe DevTools · WCAG 2.1 AA · test case design · defect reporting
- **Build & deploy** — Docker · GitHub Actions · CI/CD · Vercel

---

### Elsewhere

[Portfolio](https://asad-portfolio-drab.vercel.app) · [LinkedIn](https://linkedin.com/in/asad-ullah-b0190a236) · asadullah541989@gmail.com

Based in Sialkot, Pakistan. Twelve years lived and worked in the UK, so time zones and written English are not a problem.
