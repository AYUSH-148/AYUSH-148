# Ayush Negi

Backend & AI engineer. Recent IT graduate from ABV-IIIT Gwalior.

Previously interned at **CoinSwitch** (India's largest crypto platform), building distributed backend services for their F&O trading exchange and security infrastructure. Before that, built real-time conversation intelligence at **Profimatix.AI**.

## What I work on

- **Backend & distributed systems** — built 4+ production services handling trade movement, liquidity, and ledger entries at CoinSwitch
- **AI agent infrastructure** — contributed to a production MCP gateway giving LLM agents secure access to internal tools (Grafana, OpenSearch, Bitbucket) via OAuth 2.1 & SAML
- **RAG systems & LLM evaluation** — built a [self-healing RAG](https://github.com/AYUSH-148/self-healing-rag) agent that reduced hallucination rate from 5.9% → 0.0% with a deterministic eval pipeline and CI gate
- **Voice AI** — built with Vapi, ElevenLabs (Flash v2.5, multilingual_v2), and Recall.ai

## Featured projects

| Project | What it does |
|---------|-------------|
| [**Self-Healing RAG**](https://github.com/AYUSH-148/self-healing-rag) | LangGraph agent that self-critiques and retries its own answers. Hallucination rate 5.9% → 0.0%, with a golden-set eval pipeline in CI. Runs locally on Ollama. |
| [**MediFlow Assistant**](https://github.com/AYUSH-148/MediFlow-Assistant) | Hybrid GraphRAG medical assistant — vector retrieval + TF-IDF + knowledge graph, merged via Reciprocal Rank Fusion. PII redaction, semantic caching, Langsmith observability. |
| [**Threads**](https://github.com/AYUSH-148/threads) | Full-stack social platform with a write-time notification pipeline: transactional outbox → Redis Streams → SSE. Idempotent delivery, Redis Streams chosen over Kafka based on actual retention needs. |

## Stack

**Languages:** Python, Go, TypeScript/JavaScript, C++, SQL

**AI/LLM:** LangChain, LangGraph, Langsmith, Ollama, Hugging Face, RAG, MCP, Vapi, ElevenLabs, Recall.ai

**Backend:** Node.js, Express, FastAPI, Flask, gRPC, PostgreSQL, MongoDB, MySQL, Redis, Kafka, RabbitMQ

**Frontend:** React, Next.js, Tailwind, Redux, Jest/RTL

**Cloud & Infra:** AWS (EC2, S3, ELB, Lambda), Docker, GitHub Actions

## Competitive programming

- **LeetCode Knight** — 1900+ rating, 750+ problems solved
- **Global rank 323** — LeetCode Biweekly Contest 135

## Links

- [Portfolio](https://ayush-negi-portfolio.vercel.app/)
- [LinkedIn](https://www.linkedin.com/in/ayush-negi-300209257/)
- [LeetCode](https://www.leetcode.com/ayyush_007)
- [Medium](https://medium.com/@ayushpro111)

---

*Building systems that survive production, not just demos.*
