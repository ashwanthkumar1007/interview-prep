# Interview Prep — Ashwanth Kumar Alagesan

**Targeting:** AI Engineer · Forward Deployed Engineer · GenAI Software Engineer · SWE  
**Level:** Mid (3 YOE) → Senior at big tech & startups  
**Stack strengths:** Python, Go, microservices, AWS, Kafka, gRPC, ML (TF/Keras)  
**Gaps to close:** DSA medium/hard, LLM/GenAI depth, ML system design

---

## Plan Overview

| Phase | Focus | Duration |
|-------|-------|----------|
| 1 | DSA Foundations & Patterns | Weeks 1–3 |
| 2 | DSA Medium → Hard | Weeks 4–6 |
| 3 | System Design (Distributed + ML) | Weeks 5–8 |
| 4 | AI/GenAI Deep Dive | Weeks 6–9 |
| 5 | Behavioral + Role-specific | Weeks 9–10 |
| 6 | Mock Interviews & Polish | Weeks 10–12 |

> Assumes ~1.5 hrs weekdays, ~3 hrs each weekend day (~15 hrs/week)

---

## Phase 1 — DSA Foundations & Patterns (Weeks 1–3)

Focus: build pattern recognition, not memorisation.

### Patterns to master (in order)
- [ ] Arrays & Sliding Window
- [ ] Two Pointers
- [ ] Fast & Slow Pointers (LinkedList)
- [ ] HashMap / HashSet patterns
- [ ] Stack & Monotonic Stack
- [ ] Binary Search (and variants)
- [ ] Recursion & Backtracking basics
- [ ] BFS / DFS on graphs and trees
- [ ] Heap / Priority Queue
- [ ] Prefix Sum

### Resources
- [NeetCode 150](https://neetcode.io/practice) — work by pattern, not random
- [LeetCode Patterns](https://seanprashad.com/leetcode-patterns/)

### Weekly targets
| Week | Goal |
|------|------|
| 1 | Arrays, Two Pointers, Sliding Window — 15 easys |
| 2 | HashMap, Stack, Binary Search — 10 easy + 5 medium |
| 3 | Trees, BFS/DFS, Heap — 10 medium |

---

## Phase 2 — DSA Medium → Hard (Weeks 4–6)

Focus: timed practice, simulate interview conditions (25 min per problem).

### Topics
- [ ] Dynamic Programming (1D → 2D → interval)
- [ ] Graphs: Dijkstra, Union-Find, Topological Sort
- [ ] Tries
- [ ] Advanced Backtracking
- [ ] Greedy

### Weekly targets
| Week | Goal |
|------|------|
| 4 | DP patterns — 12 mediums |
| 5 | Graphs + Tries — 10 mediums, 2 hards |
| 6 | Mixed timed sets — 15 mediums, 3 hards |

### Big tech bar
- Google/Meta/Apple: expect medium-hard, sometimes 2 problems in 45 min
- Startups: usually 1 medium, more focus on clean code & discussion

---

## Phase 3 — System Design (Weeks 5–8)

Your background (gRPC, Kafka, MQTT, Docker, AWS, microservices) is a strong base — go deeper on scale.

### Distributed System Design
- [ ] URL shortener / Pastebin
- [ ] Rate limiter
- [ ] Notification system
- [ ] Chat system (WhatsApp)
- [ ] News feed / Twitter timeline
- [ ] Ride-sharing (Uber/Lyft)
- [ ] Distributed key-value store
- [ ] Consistent hashing deep dive

### ML System Design (critical for AI Engineer roles)
- [ ] Design a recommendation system
- [ ] Design a fraud detection pipeline
- [ ] Design a real-time ML inference service
- [ ] Design a RAG pipeline at scale
- [ ] Design a document processing + LLM system
- [ ] Feature store design
- [ ] A/B testing infrastructure

### Resources
- *Designing Data-Intensive Applications* (Kleppmann) — chapters 1–6, 11–12
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [ML System Design Interview](https://www.educative.io/courses/machine-learning-system-design)

---

## Phase 4 — AI / GenAI Deep Dive (Weeks 6–9)

This is your differentiator. Big tech AI roles and GenAI startups will probe this hard.

### LLM Fundamentals (must know cold)
- [ ] Transformer architecture (attention, multi-head, positional encoding)
- [ ] BERT vs GPT family differences
- [ ] Tokenization (BPE, WordPiece)
- [ ] Context windows, KV cache
- [ ] Temperature, top-k, top-p sampling
- [ ] Hallucination causes and mitigations

### RAG (Retrieval-Augmented Generation)
- [ ] Chunking strategies (fixed, semantic, recursive)
- [ ] Embedding models (OpenAI, sentence-transformers)
- [ ] Vector databases (Pinecone, Chroma, Weaviate, pgvector)
- [ ] Retrieval strategies: dense, sparse (BM25), hybrid
- [ ] Re-ranking (cross-encoders)
- [ ] RAG evaluation (RAGAS framework)

### Agents & Orchestration
- [ ] Tool use / function calling
- [ ] ReAct pattern
- [ ] LangChain / LangGraph basics
- [ ] Multi-agent systems
- [ ] Memory types (in-context, external, episodic)

### Fine-tuning & Optimization
- [ ] When to fine-tune vs RAG vs prompt engineering
- [ ] LoRA / QLoRA
- [ ] RLHF concepts
- [ ] Quantization (INT8, INT4)
- [ ] Model serving: vLLM, TGI, Triton

### Prompt Engineering
- [ ] Chain-of-thought, few-shot, zero-shot
- [ ] Prompt injection & guardrails
- [ ] Structured outputs (JSON mode, function calling)

### AI-specific system design questions to prep
- Design ChatGPT
- Design a RAG-based enterprise search
- Design an AI coding assistant
- Design a content moderation system using LLMs
- Design a multi-agent customer support system

---

## Phase 5 — Behavioral (Weeks 9–10)

Use **STAR format** (Situation, Task, Action, Result) for every answer.

### Stories to prepare from your experience

| Theme | Your angle |
|-------|-----------|
| Leadership / ownership | Spearheading ROS2 cloud integration at Magna |
| Technical complexity | MQTT+Kafka pipeline for autonomous bots |
| Impact with numbers | 60% reduction in storage via sliding window compression |
| Cross-functional work | Design-first API approach with Swagger at Magna |
| Handling ambiguity | Building simulator for delivery bots from scratch |
| Failure / learning | (pick one, frame growth) |

### Common behavioral questions
- [ ] Tell me about yourself (2-min pitch ready)
- [ ] Why this company / why AI?
- [ ] Most impactful project you've owned
- [ ] Conflict with a teammate
- [ ] Time you disagreed with your manager
- [ ] Biggest technical mistake and what you learned
- [ ] Where do you want to be in 3 years?

---

## Phase 6 — Mock Interviews & Polish (Weeks 10–12)

- [ ] 2 mock DSA sessions/week (use [Pramp](https://www.pramp.com) or [Interviewing.io](https://interviewing.io))
- [ ] 1 system design mock/week
- [ ] Record yourself answering behavioral questions
- [ ] Review and update resume to add GenAI keywords
- [ ] Build 1 visible GenAI project to demo (RAG app, AI agent, etc.)

---

## Resume Gaps to Close

Based on your current resume, AI/GenAI roles will expect to see:

| Missing | Action |
|---------|--------|
| LLM / OpenAI API experience | Build a project using it |
| Vector DB (Pinecone, Chroma) | Add to RAG project |
| LangChain / LangGraph | Use in a project |
| Hugging Face | Fine-tune a small model |
| GenAI keywords in skills | Update resume skills section |

---

## Folder Structure

```
interview-prep/
  interview-prep.html       # visual dashboard
  README.md                 # this file
  dsa/
    arrays/
    dp/
    graphs/
    trees/
    notes.md
  system-design/
    distributed/
    ml-system-design/
    notes.md
  ai-genai/
    rag/
    agents/
    llm-concepts/
    notes.md
  behavioral/
    stories.md
  resources.md
```

---

## Progress Tracker

| Week | DSA | System Design | AI/GenAI | Behavioral | Status |
|------|-----|---------------|----------|------------|--------|
| 1 | | | | | ⬜ Not started |
| 2 | | | | | ⬜ Not started |
| 3 | | | | | ⬜ Not started |
| 4 | | | | | ⬜ Not started |
| 5 | | | | | ⬜ Not started |
| 6 | | | | | ⬜ Not started |
| 7 | | | | | ⬜ Not started |
| 8 | | | | | ⬜ Not started |
| 9 | | | | | ⬜ Not started |
| 10 | | | | | ⬜ Not started |
| 11 | | | | | ⬜ Not started |
| 12 | | | | | ⬜ Not started |
