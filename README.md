# Lexprobe

**Indian-legal research assistant** — retrieval-augmented generation with a **citation-audit** layer so answers stay grounded in sources.

## Status

This repository is a **public-facing stub**. The application codebase is **closed source** while the product is in **closed beta**.

- **Architecture:** FastAPI backend, Postgres, Qdrant, Redis, Ollama (Llama 3 family), Next.js 14 frontend — designed for production-style deployment.
- **What it does:** Natural-language queries over Indian legal material; hallucination-prone outputs are filtered through an audit pipeline before anything ships to the user.

## Links

- **Dossier / builder:** [Personal site — Issue #001](https://siddarthb07.github.io/siddarthb/) (case file for Lexprobe).
- **GitHub profile:** [@Siddarthb07](https://github.com/Siddarthb07)

## Technical note

`LexProbe_System_Design.docx` in this repo is a **high-level design export** for reviewers (admissions / mentors). It is not the runnable product.

For collaboration or demo requests, use the email on the personal site.

---

MIT License applies only to files explicitly marked in this repository. The closed-source application is not licensed here.
