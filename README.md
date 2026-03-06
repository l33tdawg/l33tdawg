# L33tdawg

### Hacker, Maker, Builder & Breaker
---

## About

Creator of **[LevelUp CTF](https://levelupctf.com)** — a self-evolving, fully agentic AI Capture The Flag platform — and author of **[(S)AGE](https://github.com/l33tdawg/sage)** (Sovereign Agent Governed Experience), a new infrastructure layer for AI agents. Founder & CEO of **[Hack In The Box (HITB)](https://conference.hitb.org)** — the premier deep-knowledge security conference series running since 2003. When I'm not building stuff, I'm vibe coding tools or dabbling with modular (see **[eurorack](https://en.wikipedia.org/wiki/Eurorack)**) techno music production.

---

## (S)AGE — Sovereign Agent Governed Experience

My current focus and what I think is the most important thing I've built. **(S)AGE** is a governed, verifiable, experience-weighted **institutional memory layer for multi-agent systems**. Infrastructure, not a library.

The problem: every AI agent today — even the frontier models — is **Leonard Shelby from Memento**. Brilliant within a session. Complete amnesia between sessions. We've been giving them better tattoo ink for years. (S)AGE cures the amnesia.

**What it does:** Agents propose knowledge from experience → validators vote using reputation-weighted Proof of Experience → BFT consensus commits it as institutional truth → future agents query governed, verified knowledge. Memories decay when stale, get challenged when wrong, and accumulate across agents and sessions.

**The stack:** CometBFT consensus (raw ABCI 2.0), Go state machine, PostgreSQL + pgvector, Protobuf txs, Python SDK, local embeddings via Ollama. Fully sovereign — zero cloud API calls. Two commands and you've got a 4-node consensus network running. 956 req/s submissions, 21.6ms P95 queries, 0% errors under load.

**Why it matters:** We spent decades building consensus for financial transactions. A bad transaction loses money. A bad institutional memory corrupts every future decision that relies on it. BFT consensus for knowledge isn't overkill — it's the minimum.

4 research papers published. Open-source under Apache 2.0. Because we don't gatekeep stuff.

**Read the full story:**
- [Part 1: Leonard Shelby and the AI Memory Problem](https://medium.com/@dhillon.andrew/leonard-shelby-and-the-ai-memory-problem-what-building-a-multi-agent-ai-ctf-platform-taught-me-4f4c8fd6ab78) — what building a 12-agent CTF platform taught me about what's missing
- [Part 2: Memories Are All We Are](https://medium.com/@dhillon.andrew/memories-are-all-we-are-i-made-what-i-think-the-road-to-agi-is-missing-b1821744dc59) — the architecture, the threat model, and why I think this is what the road to AGI is missing

**Links:** [GitHub](https://github.com/l33tdawg/sage) | [Architecture Paper (Zenodo)](https://doi.org/10.5281/zenodo.18856658) | [Empirical Results Paper](https://doi.org/10.5281/zenodo.18856774)

---

## Other Projects

- **[Aether](https://github.com/l33tdawg/aether)** — AI-powered smart contract security analysis and PoC generation framework
- **[CFP Directory](https://github.com/l33tdawg/cfp-directory-self-hosted)** — Self-hosted Call for Papers management platform

---

## HITB / OOTB Conference Series

- https://conference.hitb.org/
- https://ootb.net/

---

*"Attention is all you need to think. But memories are all you are."*
