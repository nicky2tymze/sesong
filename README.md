# SESONG v2.6

**Self-Encoding Symbolic Organization-Notation Grammar**

A minimal symbolic grammar for describing agents, state, and work cycles without ambiguity.

Built for AI systems. Readable by any agent. Designed so structure carries meaning — no natural language required.

---

## What it is

SESONG is a closed-form grammar with eleven primitives. It describes:

- **Entities** and their relationships
- **State** — runtime vs. persistent store, and the invariant that they must match
- **Work cycles** — the four-beat pulse every unit of work runs through
- **Interfaces** — how entities connect, hand off, and stay honest
- **Drift** — what divergence means and how it resolves

The grammar is substrate-agnostic. It describes human-human pairs, human-AI pairs, and AI-AI pairs with the same notation.

---

## The spec

See `SESONG.txt` — the full grammar, one file, plain text.

---

## The closing equation

```
[(>)] = [(@)]
```

The flow and the human are the same thing.

---

## Usage

Load `SESONG.txt` as a system prompt or context document. Any capable agent will parse it. Use the notation to encode instructions, state descriptions, or work assignments — unambiguously, at maximum density.

---

**Dominick Trolian / Flux Forge Labs**
Open standard. No restrictions on use.
