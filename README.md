# 👋 Hi, I'm Shambhoo Narwaria

### Backend Engineer · Java, Spring Boot, TypeScript & Node.js · IIT Roorkee CSE '25 · CGPA 8.36/10

I build **scalable backend systems and distributed APIs** — grounded in deep CS fundamentals.  
Strong in **system design, concurrency, networking, and event-driven architecture**.

---

## Featured Projects

### [Deterministic Replay Engine for Distributed Systems](https://github.com/shambhoo-narwaria/Deterministic-Replay-Engine-for-Distributed-Systems)
> Production-grade debugging framework for distributed microservices.

- Built with **Node.js, Apache Kafka, PostgreSQL, Redis**
- Captures every event in a distributed transaction via **event sourcing**
- Allows engineers to **deterministically replay** any failed production flow with **full side-effect isolation** — no double-charging, no duplicate emails, zero live consequences
- Implements **dual-layer idempotency** (Redis hot path + PostgreSQL fallback)
- Distributed tracing via **correlation IDs** across all microservices
- Fully Dockerized with 5 independent services, debug dashboard UI included

`Node.js` `Apache Kafka` `PostgreSQL` `Redis` `Docker` `Event Sourcing` `Distributed Systems`

---

### [Scalable URL Shortening Service](https://github.com/shambhoo-narwaria/Scalable-URL-Shortening-Service)
> High-performance URL redirection system with real-time analytics.

- Built with **Spring Boot + Redis + PostgreSQL**
- **Base62 encoding** for compact short links
- **Redis caching** for low-latency redirection
- Custom aliases, rate limiting, and a modern responsive UI
- Fully Dockerized for production deployment

`Spring Boot` `Java` `Redis` `PostgreSQL` `Docker` `System Design`

---

### [HTML Code Generation Using LLM](https://github.com/shambhoo-narwaria/HTML-Code-Generation-Using-LLM)
> Fine-tuned Falcon-7B to generate HTML from natural language instructions.

- Used **PEFT (Parameter-Efficient Fine-Tuning)** techniques
- Explores LLM adaptation on constrained compute budgets
- Demonstrates ML/NLP depth beyond pure backend engineering

`Python` `Falcon-7B` `PEFT` `Jupyter Notebook` `NLP` `LLM Fine-Tuning`

---

### [Reliable UDP Protocol](https://github.com/shambhoo-narwaria/Reliable-UDP-Protocol-Network-Communication)
> Simulates TCP reliability mechanisms on top of raw UDP.

- Implemented **Stop & Wait, Go-Back-N, Selective Repeat**
- Checksum validation and simulated **packet loss handling**
- Deep dive into transport-layer protocol design

`Java` `Networking` `UDP` `TCP` `Protocols`

---

### [Text to Sign Language Translator](https://github.com/shambhoo-narwaria/Text-to-Sign-Language-Translator) ⭐ 4
> Converts live audio speech into sign language animations in real time.

- Web app using the **Web Speech API** for live transcription
- Displays corresponding sign language animations for accessibility
- Focus: inclusive and accessible communication tooling

`JavaScript` `HTML` `CSS` `Web Speech API` `Accessibility`

---

### [AI Testcase Recorder](https://github.com/shambhoo-narwaria/AI-Testcase-Recorder)
> AI-powered Playwright test recorder that converts natural language goals into reusable browser automation flows.

- Give it a **start URL + plain English goal** — it figures out the steps autonomously
- Opens a real browser with **Playwright**, inspects the live DOM, and asks an AI model for the next best action
- Executes actions step-by-step and saves them as a **reusable JSON test case**
- **Plug-and-play LLM support** — works with OpenAI, OpenRouter, or any OpenAI-compatible provider via `.env` config
- Supports **fallback models** if the primary model fails
- Recorded test cases can be replayed independently via the playback script

`TypeScript` `Playwright` `Node.js` `LLM` `Browser Automation` `AI Agents`

---

### PsyGuage Backend API
> Production-oriented REST API for psychological assessments.

- Built with **Node.js, Express, MongoDB**
- **JWT-based authentication & authorization**
- APIs for user management, assessments, and analytics
- Modular architecture with clean separation of concerns

`Node.js` `Express.js` `MongoDB` `JWT` `REST API`

---

## Tech Stack

**Backend**  
`Spring Boot` `Node.js` `Express.js` `Apache Kafka` `RESTful API` `FastAPI`

**Languages**  
`Java` `TypeScript` `JavaScript` `Python` `C++`

**Databases**  
`PostgreSQL` `MongoDB` `MySQL` `Redis`

**DevOps & Cloud**  
`Docker` `AWS` `Linux` `Git`

**CS Fundamentals**  
`Operating Systems` `Computer Networks` `DBMS` `System Design (HLD + LLD)` `DSA`

---

## Engineering Principles

- **Event-driven first** — Full service decoupling via message brokers. State as immutable events.
- **Observability by design** — Distributed tracing via correlation IDs. Every action reconstructible from the log.
- **Side-effect isolation** — Dry-run before deploy. No live consequences during debugging.
- **Deep CS fundamentals** — Understand WHY things work, not just HOW to use them.

---

## Current Focus

- System Design (HLD + LLD) — CAP theorem, consistency models, distributed coordination
- Backend Performance Optimization — profiling, caching strategies, query tuning
- Distributed Systems — consensus algorithms, fault tolerance, replication
- Competitive Programming in C++ — algorithm optimization and problem solving

---

## Connect With Me

- LinkedIn: [linkedin.com/in/shambhoo-narwaria](https://www.linkedin.com/in/shambhoo-narwaria/)
- GitHub: [github.com/shambhoo-narwaria](https://github.com/shambhoo-narwaria)
- Email: shambhoo.narwaria@gmail.com

---

> *Build systems that scale. Understand systems deeply. Avoid surface-level engineering.*
