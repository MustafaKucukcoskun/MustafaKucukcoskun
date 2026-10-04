# Mustafa Küçükcoşkun

**Shipbuilding & Ocean Engineering student at Istanbul Technical University. I build software for the maritime industry.**

My degree is in naval architecture. Alongside it I write software: constraint-based schedulers, full-stack web apps and LLM-powered tools. I want to apply that to maritime problems such as crew scheduling, vessel data and ship stability calculations.

- **ITU IT Department** (student assistant, 2024 – present): built the department's duty-scheduling system on Google OR-Tools CP-SAT, FastAPI and Next.js. The department uses it for 40+ staff. The code belongs to ITU, so it is not public.
- **Beebird Technology** (AI intern, 2024 – 2025): built a RAG chatbot prototype with LangChain and OpenAI and ran ML experiments on Vertex AI.
- **YZTA 5.0 scholar**: AI and Technology Academy, Data Science track.

## Projects

### [İTÜ Otostop](https://github.com/MustafaKucukcoskun/itu-otostop)

Course-registration automation for ITU's student information system. A request has to reach the server within milliseconds of the registration window opening, so the backend calibrates against the server clock, builds and pre-warms every request before the target time, and hands each registration to its own Cloud Run container to avoid GIL contention. Load-tested with 40 concurrent users, covered by 380+ backend tests.

`Python` `FastAPI` `WebSocket` `Next.js 16` `TypeScript` `Supabase` `Google Cloud Run`

### [Catan Tournament Hub](https://github.com/MustafaKucukcoskun/catan-tournament)

Tournament manager for Catan: Swiss-style league rounds, 4-player elimination pods, a constraint-based board generator and a live leaderboard over Supabase Realtime. Pairing, tiebreak and map-generation logic is plain TypeScript with unit tests.

`Next.js 16` `TypeScript` `Supabase` `Vitest`

### Ship watch scheduler *(in progress)*

Watch plans for a ship's bridge and engine-room crew under the STCW and MLC 2006 rest-hour rules (at least 10 hours of rest in any 24 hours and 77 hours in any 7 days), solved with OR-Tools CP-SAT. When no legal plan exists, it reports which rule is binding.

`Python` `OR-Tools` `FastAPI` `pytest`

## Stack

- **Languages:** Python · TypeScript · C# · SQL
- **Backend:** FastAPI · PostgreSQL / Supabase · Docker · Google Cloud Run
- **Frontend:** Next.js · React · Tailwind CSS
- **Optimization & AI:** OR-Tools (CP-SAT) · pandas · LLM APIs · RAG

## Türkçe

İTÜ'de Gemi ve Deniz Teknolojisi Mühendisliği okuyorum ve bölümün yanında yazılım geliştiriyorum. İTÜ Bilgi İşlem Daire Başkanlığında 40'tan fazla kişinin nöbetlerini planlayan sistemi geliştirdim. Şimdi denizcilik verisiyle çalışan projeler yapıyorum. İlki, gemi personelinin vardiyalarını dinlenme kurallarına göre planlayan bir araç.

## Contact

[LinkedIn](https://www.linkedin.com/in/mustafa-k%C3%BC%C3%A7%C3%BCkco%C5%9Fkun/) · [Email](mailto:m.kucukcoskunn@gmail.com) · [CV](https://web.itu.edu.tr/kucukcoskun21/cv/) · [X](https://x.com/mkucukcoskun_)
