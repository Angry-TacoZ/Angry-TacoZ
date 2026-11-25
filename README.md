# James Lane

Nontraditional, Neurodivergent systems-oriented builder working at the intersection of healthcare operations, workflow analysis, AI-assisted tooling, and practical web application development.

I currently spend my time building source-grounded assistants, stakeholder-facing demos, workflow tools, and interactive web projects. I am usually strongest where a problem is ambiguous and you want outside-the-box thinking grounded in SWE fundamentals.

## Selected work

### Featured AI & workflow systems

1. **[Enthusiast Lens](https://github.com/Angry-TacoZ/enthusiast-lens)** *(Recorded benchmark demo · Python, TypeScript)*  
   Evaluates Full-Web vs. Hybrid (exact-VIN vPIC + web) vehicle-fact acquisition against a frozen 12-fixture, 288-slot benchmark. On the four-vehicle representative execution subset, Full-Web completed 4/4 and Hybrid completed 3/4 (90s GR86 timeout), with matched-pair macro CEFC of 72.45% (Full-Web) vs. 73.07% (Hybrid) — a mixed result with no claim of statistical significance or universal Hybrid advantage; full measurements live in the benchmark README.  
   **[Compare recorded runs](https://angry-tacoz.github.io/enthusiast-lens/)** · [Repository & benchmark README](https://github.com/Angry-TacoZ/enthusiast-lens)

2. **[Delivery Composer](https://github.com/Angry-TacoZ/delivery-composer)** *(Deterministic public demo · FastAPI, React, Cloud Run)*  
   Turns unstructured consulting briefs into constraint-gated, auditable team recommendations with human review, alongside a separate optional server-side Gemini and PostgreSQL/`pgvector` extension path in the repository.  
   **[Try a synthetic brief](https://composer.jamesai.space/)** · [Repository & architecture](https://github.com/Angry-TacoZ/delivery-composer)

3. **[Verified Cruise Control](https://github.com/Angry-TacoZ/verified-cruise-control)** *(Local multimodal audit tool · Python, Chrome MV3)*  
   Multimodal ADAS verification architecture comparing advertised vehicle features against listing photos and documentation using Meta Muse Spark, SAM 3.1, deterministic five-state reconciliation, and enforced spend caps, with adaptive cruise control (ACC) as the current real-listing verification workflow. Offline reconciliation evaluation is validated in CI (`v2`/`v4`/`v5` goldens), while reference-assisted live inference remains unvalidated.  
   **[Inspect a multimodal audit (PR #6)](https://github.com/Angry-TacoZ/verified-cruise-control/pull/6)** · [Repository & evals](https://github.com/Angry-TacoZ/verified-cruise-control)

### Additional featured projects

4. **[Living Resume AI (`jamesai.space`)](https://jamesai.space/)** *(Live bounded assistant with deterministic fallback · JavaScript, Firebase Functions, Claude Haiku)*  
   Canonical interactive portfolio and resume separating deterministic source retrieval from server-side allowlisted Claude synthesis.  
   **[Explore `jamesai.space`](https://jamesai.space/)** · [Repository](https://github.com/Angry-TacoZ/james-lane-assistant)

5. **[CogFit Jobs](https://cogfit-jobs.web.app/)** *(Signed-out sample + authenticated Gemini callable · React, Firebase Auth, App Check)*  
   Compares job ads against work style, evidence, and day-to-day role demands with server-side model keys and source-default per-user/global daily quotas.  
   **[Try signed-out sample](https://cogfit-jobs.web.app/)** · [Repository](https://github.com/Angry-TacoZ/cogfit-jobs)

6. **[LQRI — Legitimate Question Response Index](https://lqri.web.app/)** *(Published LLM behavioral benchmark · Astro, TypeScript)*  
   Evaluates lawful, sensitive, and self-referential prompts across 6 configurations in v2 (six dimensions, three runs each) plus 7 archived v1 entries, with preserved transcripts and explicit caveats.  
   **[View v2 leaderboard](https://lqri.web.app/)** · [Methodology](https://lqri.web.app/methodology) · [Limitations](https://lqri.web.app/limitations) · [Repository](https://github.com/Angry-TacoZ/lqri-site)

### Secondary, deterministic & in-progress work

- [Personal Job Discovery](https://github.com/Angry-TacoZ/personal-job-discovery) *(Local deterministic Python — no LLM)* — Local-first monitor for public Greenhouse, Lever, and Ashby boards with Pydantic normalization, SQLite tracking, and explainable scoring (planned to merge into CogFit Jobs; strong alternate for Python backend roles).
- [PDF Equipment Checker](https://github.com/Angry-TacoZ/pdf-equipment-checker) *(Deterministic Python document parser — repo link while hosted demo is offline)* — Compares floor-plan equipment tags against multi-column schedule rows with confidence diagnostics.
- [Forrest AI](https://github.com/Angry-TacoZ/forrest-ai) *(In-progress foundation — mock provider pipeline)* — Consented, source-grounded interview assistant with claim verification and fixed eval harness.
- Consulting, design & side projects: [JamesLaneAI.com](https://jameslaneai.com/) · [Blue ambient shopping UX concept](https://github.com/Angry-TacoZ/best-buy-blue-concept) · [Cruis'n PA](https://cruisnpa.fun/) · [Masters of Metal](https://mastersofmetal.web.app/)

## What I bring

- Systems thinking
- Practical AI implementation
- Workflow analysis, process clarification, and tool design
- Fast prototype-to-demo execution
- Honest, evidence-based communication about fit, tradeoffs, and scope

## Tools and platforms I use

- AI and model tooling: Anthropic Claude, Google Gemini, Meta Muse / SAM, Codex
- Application and backend stack: Python, FastAPI, TypeScript, JavaScript, React, Vite, Astro
- Cloud, testing, and deployment: Firebase Hosting/Functions, Cloud Run, Docker, GitHub Actions, Pytest, Vitest, Playwright
- Data and enterprise tooling: PostgreSQL/`pgvector`, SQL, Power BI, ServiceNow, Microsoft 365
- Domain context: healthcare operations, audit-sensitive environments

## How I use AI coding agents

I use AI coding agents to help write software, then review and verify changes before they ship:

- Inspect existing contracts, trust boundaries, and related systems before editing.
- Keep secrets and paid API keys server-side, never in browser-delivered code or public build artifacts.
- Prefer framework primitives, typed interfaces, allow-list validation, and parameterized data access over ad hoc shortcuts.
- Test denied, malformed, missing, and boundary cases, run relevant build/lint/test/runtime checks, and report verification results, remaining uncertainty, and scope limitations.
- Govern agent work with GitAgent, project-specific `AGENTS.md` contracts, and a two-model PR workflow: independent review followed by cross-validation of findings against repository evidence before human merge approval.

My [Codex-wide agent instructions](docs/codex/AGENTS.md) describe the rules I use across projects. The [changelog](docs/codex/CHANGELOG.md) explains what I changed and why.

## Accessibility and work design

I'm open about being autistic and having ADHD because both influence how I approach problems, learn new skills, and work with technology.

I do my best work when I can investigate a problem, understand how the pieces fit together, and develop a solution through experimentation. I prefer clear expectations, direct communication, and the freedom to focus deeply on the work.

I share this context to help people understand how I work, but I want my technical abilities to be judged by the projects I've built and the problems I've solved.

## Writing

- [Medium](https://medium.com/@Angry_TacoZ)  
  Public writing on AI analysis, civic issues, politics, and personal essays.

## Contact

- [LinkedIn](https://www.linkedin.com/in/james-lane-1051291a9/)
- [Living Resume](https://jamesai.space/)
- [Email](mailto:tiburo13@gmail.com)
