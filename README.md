# Mustafa Küçükcoşkun

**Data & AI · Python · C# / .NET**

I build data and AI systems, optimization models and the web apps around them, mostly in Python and C# / .NET. My goal is to work on data and AI in the maritime industry.

## Projects

### [JARVIS](https://github.com/MustafaKucukcoskun/jarvis-overview) *(code private)*

Personal AI assistant that plans my day, records what actually happened and calibrates the next plan. 15 modules and 92 tools on LangGraph, an approval gate and permission tiers for anything risky, a bi-temporal memory, and an eval suite scored deterministically from the audit log. 1,400+ Python tests.

`Python` `LangGraph` `FastAPI` `Gemini` `Claude` `pytest`

### [Nöbetçi](https://github.com/MustafaKucukcoskun/itu-nobetci) *(code owned by ITU)*

Duty scheduling for ITU's IT Department. Two constraint programs on OR-Tools CP-SAT assign 35–55 people to day, evening and night shifts. Hard rules (full coverage, no night-to-morning transitions, load caps) are never broken. Everything else is a five-tier penalty model, and fairness carries over from one period to the next.

`Python` `OR-Tools CP-SAT` `FastAPI` `Next.js 16` `PostgreSQL`

### [İTÜ Otostop](https://github.com/MustafaKucukcoskun/itu-otostop)

Course-registration automation for ITU's student information system. A request has to reach the server within milliseconds of the registration window opening, so the backend calibrates its clock against NTP, measures latency to the server, builds and pre-warms every request before the target time, and hands each registration to its own Cloud Run container to avoid GIL contention. Load-tested with 40 concurrent users, covered by 400+ backend tests.

`Python` `FastAPI` `WebSocket` `Next.js 16` `Supabase` `Google Cloud Run`

### [Refine Agent Kit](https://github.com/MustafaKucukcoskun/Refine-agent-kit)

AI agent toolkit published on npm. One command installs 21 specialist agents and 70 skill modules into a project, picks the right agent for the file being edited and blocks generic AI output.

`Node.js` `AI agents` `CLI` `npm`

### [ForumWebApp](https://github.com/MustafaKucukcoskun/ForumWebApp)

Discussion forum in ASP.NET Core MVC on .NET 10. Four layers (web, business, data access, entities), EF Core on SQL Server, nested reply threads built from a single query, cookie authentication with roles, BCrypt-hashed passwords and soft-deleted users.

`C#` `ASP.NET Core MVC` `Entity Framework Core` `SQL Server`

### [Catan Tournament Hub](https://github.com/MustafaKucukcoskun/catan-tournament)

Tournament manager for Catan: Swiss-style league rounds, 4-player elimination pods, a constraint-based board generator and a live leaderboard over Supabase Realtime. Pairing, tiebreak and board-generation logic is plain TypeScript with unit tests.

`Next.js 16` `TypeScript` `Supabase` `Vitest`

## Stack

- **AI & data:** LLM apps and agents (LangChain, LangGraph) · RAG · pandas · NumPy · PyTorch
- **Languages:** Python · C# · TypeScript · SQL
- **Backend:** FastAPI · ASP.NET Core · Entity Framework Core · PostgreSQL · SQL Server · Docker
- **Optimization:** OR-Tools CP-SAT
- **Frontend:** Next.js · React · Razor · Tailwind CSS

## Türkçe

Python ve C# / .NET ile veri ve yapay zekâ sistemleri, optimizasyon modelleri ve bunların etrafındaki web uygulamalarını geliştiriyorum. İleride denizcilik sektöründe veri ve yapay zekâ üzerine çalışmak istiyorum.

## Contact

[LinkedIn](https://www.linkedin.com/in/mustafa-k%C3%BC%C3%A7%C3%BCkco%C5%9Fkun/) · [Email](mailto:m.kucukcoskunn@gmail.com) · [CV](https://web.itu.edu.tr/kucukcoskun21/cv/) · [X](https://x.com/mkucukcoskun_)
