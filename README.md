### AI Engineer who also owns the backend. I take LLM agents from notebook to production and wire them into WhatsApp, CRMs and ad platforms.

> Backend engineer since 2023, now building LLM systems that run in production. At SellEasy I build multi-agent sales and support workflows (LangGraph, CrewAI, RAG) that cut response latency by 32%, and I led the integration work behind its Meta Certified Tech Provider accreditation. Remote from Venezuela (UTC-4), with full overlap with US Eastern and LatAm hours.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langgraph&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)

Also in my production work: CrewAI, Qdrant, NestJS, Celery, Docker and the Meta WhatsApp Cloud API.

## What I've built

**[Cobrix](https://cobrix-frontend.vercel.app/)** · `public repo` · [frontend](https://github.com/Manuel-jimenez10/cobrix-frontend) · [backend](https://github.com/Manuel-jimenez10/cobrix-backend)<br>
WhatsApp debt collection for Mexican SMBs. A rule-based 0-100 score decides who to contact first and a Gemini assistant drafts each reminder; a person on the team sends every message. Model outputs are Zod-validated (amounts never above the balance, dates always in the future) and fall back to rules when the model or the quota fails. Try it as a guest at [/demo](https://cobrix-frontend.vercel.app/demo), no login.<br>
*TypeScript · React · Hono · Vercel AI SDK · Gemini · Supabase*

**Evento Maiawa** · `private` · built at SellEasy<br>
Software for "Lost in Paradise", an in-person event in Cartagena (Nov 2026): NFC passports, WhatsApp missions, voice clues played on a vintage telephone and an NFC-locked treasure chest. I designed the API the NFC readers call on every tap. It returns an action code plus the audio clip, and fails safe with a "deny" so a reader never hangs. Voice clues are pre-generated with ElevenLabs and tuned to mono 32 kbps MP3, which took a 10-second clip from ~213 KB to ~54 KB of base64.<br>
*TypeScript · Next.js · Supabase · ElevenLabs · WhatsApp Business API · NFC hardware*

**Hivara** · `private` · collaboration, Jun to Sep 2026<br>
WhatsApp conversational platform on a Python engine (FastAPI, Celery, Redis, RabbitMQ) with LLMs and vector RAG. I redesigned a 100-node dealership flow, taking false terminations from 14/18 to 0/18 with 100% clean data capture, and traced worker-level race conditions (>1,200 CAS conflicts) that led to fixes in the core engine. To test it, I built a local harness that runs the real engine and LLM with external systems mocked.<br>
*Python · LangGraph · Celery · RAG*

## Experience

- **AI Engineer · SellEasy** (Colombia, remote) · since Dec 2025<br>
  Ad-ops agents across Meta, TikTok and Google Ads that cut marketing management time by 23%. Semantic search on Qdrant with prompt caching and per-inference cost tracking in Helicone.
- **Senior Backend Engineer · Netcare IT** (Mexico, remote) · since Jun 2024<br>
  Meta WhatsApp Cloud API connected to EspoCRM, which cut administrative workload by 21%. REST and WebSocket omnichannel messaging that lifted sales output by 22%.
- **Backend Developer · Seagloo** (Argentina, remote) · Jul 2023 to Aug 2024<br>
  AI emergency detection for 911 dispatch that cut alert transmission time by 17%, with LLM pipelines that raised incident classification accuracy by 20%.

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-manueljimenezlopez-0A66C2)](https://www.linkedin.com/in/manueljimenezlopez/)
[![Email](https://img.shields.io/badge/Email-manuel28042005%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:manuel28042005@gmail.com)
