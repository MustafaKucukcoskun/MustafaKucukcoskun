# Mustafa Küçükcoşkun

**Data & AI · Shipbuilding and Ocean Engineering student at Istanbul Technical University**

I build LLM-powered systems, optimization models and the full-stack apps around them. My goal is to work on data and AI in the maritime industry.

- **ITU IT Department** (student assistant, 2024 – present): designed and built Nöbetçi, the department's duty-scheduling system, on my own initiative. It is in official use for 40+ people.
- **Beebird Technology** (AI intern, 2024 – 2025): built a RAG chatbot prototype with LangChain and OpenAI and ran ML experiments on Vertex AI.
- **YZTA 5.0 scholar**: AI and Technology Academy, Data Science track.

## Projects

### Nöbetçi *(code owned by ITU)*

Duty scheduling for ITU's IT Department. Two constraint programs on OR-Tools CP-SAT assign 40+ people to day, evening and night shifts. Hard rules (full coverage, no night-to-morning transitions, load caps) are never broken. Everything else is a five-tier penalty model, and fairness carries over from one period to the next.

`Python` `OR-Tools CP-SAT` `FastAPI` `Next.js 16` `Supabase`

### [İTÜ Otostop](https://github.com/MustafaKucukcoskun/itu-otostop)

Course-registration automation for ITU's student information system. A request has to reach the server within milliseconds of the registration window opening, so the backend calibrates its clock against NTP, measures latency to the server, builds and pre-warms every request before the target time, and hands each registration to its own Cloud Run container to avoid GIL contention. Load-tested with 40 concurrent users, covered by 400+ backend tests.

`Python` `FastAPI` `WebSocket` `Next.js 16` `Supabase` `Google Cloud Run`

### [Catan Tournament Hub](https://github.com/MustafaKucukcoskun/catan-tournament)

Tournament manager for Catan: Swiss-style league rounds, 4-player elimination pods, a constraint-based board generator and a live leaderboard over Supabase Realtime. Pairing, tiebreak and board-generation logic is plain TypeScript with unit tests.

`Next.js 16` `TypeScript` `Supabase` `Vitest`

## Stack

- **AI & data:** LLM apps and agents (LangChain, LangGraph) · RAG · pandas · NumPy · PyTorch
- **Optimization:** OR-Tools CP-SAT
- **Languages:** Python · TypeScript · C# · SQL
- **Backend & infra:** FastAPI · PostgreSQL / Supabase · Docker · Google Cloud
- **Frontend:** Next.js · React · Tailwind CSS

## Türkçe

İTÜ'de Gemi ve Deniz Teknolojisi Mühendisliği okuyorum. Büyük dil modelleriyle çalışan sistemler, optimizasyon modelleri ve bunların etrafındaki web uygulamalarını geliştiriyorum. İTÜ Bilgi İşlem Daire Başkanlığında resmî olarak kullanılan nöbet planlama sistemi Nöbetçi'yi geliştirdim. İleride denizcilik sektöründe veri ve yapay zekâ üzerine çalışmak istiyorum.

## Contact

[LinkedIn](https://www.linkedin.com/in/mustafa-k%C3%BC%C3%A7%C3%BCkco%C5%9Fkun/) · [Email](mailto:m.kucukcoskunn@gmail.com) · [CV](https://web.itu.edu.tr/kucukcoskun21/cv/) · [X](https://x.com/mkucukcoskun_)
