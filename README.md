# Asad Ullah

I build AI systems that run without anyone watching them, and I test the parts that break.

Most of what's here is automation: agents that take a phone call, read an inbox, or qualify a lead and write it somewhere useful. The rest is the testing work that keeps them honest — because a system nobody checks is a system quietly failing.

Right now I'm writing and publishing technical content for a cybersecurity client, which mostly means finding out what vendors will and won't put in writing.

---

### Things worth looking at

**[AI Voice Agent](https://github.com/greatman-786/ai-voice-agent)**
A bilingual English/Urdu agent on a live phone number. Books appointments, qualifies leads, escalates to a human, and logs every call. It holds 22 behaviour rules. Shipped with 13 test cases and 5 documented defects — including a webhook firing in bursts and quietly writing 52 empty records to the database. Nothing errored. I found it by checking the data rather than trusting the response.

**[AI Testing Portfolio](https://github.com/greatman-786/ai-testing-portfolio)**
An evaluation framework for LLM output: factual accuracy, JSON schema validity, latency, hallucination detection. Mocked responses instead of live API calls, which cut a run from minutes to under half a second per commit.

**[QA Portfolio](https://github.com/greatman-786/qa-portfolio)**
Playwright and PyTest suites running on every push through GitHub Actions. Public, green [run history](https://github.com/greatman-786/qa-portfolio/actions) — the point being you can check rather than take my word for it.

**[AI Automation Projects](https://github.com/greatman-786/ai-automation-projects)**
Production n8n workflows: webhook-triggered lead pipelines, a WhatsApp agent holding conversation state, automated email follow-up. Retry logic and duplicate-event filtering on all of them, because unattended means unattended.

---

### What I work with

**AI** — Claude, Gemini, GPT · LangChain · ChromaDB · RAG · vector embeddings · prompt engineering · LLM evaluation
**Automation** — n8n · Zapier · Make.com · webhooks · REST APIs · Vapi
**Python** — NumPy · Pandas · Matplotlib · Seaborn · FastAPI · BeautifulSoup
**Testing** — Playwright · PyTest · Postman · SQL validation · GitHub Actions
**Build & deploy** — Docker · GitHub Actions · CI/CD · Vercel

---

### Elsewhere

[Portfolio](https://asad-portfolio-drab.vercel.app) · [LinkedIn](https://linkedin.com/in/asad-ullah-b0190a236) · asadullah541989@gmail.com

Based in Sialkot, Pakistan. Twelve years lived and worked in the UK, so time zones and written English are not a problem.

<!--
**greatman-786/greatman-786** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
