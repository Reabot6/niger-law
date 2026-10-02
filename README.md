# Niger Law 🇳🇬

> Making Nigerian law accessible to every young Nigerian — in plain language, powered by AI.

## What is this?

Niger Law is an open-source AI legal assistant built specifically for Nigerians.

A lot of Nigerians don't know their basic rights — and when you don't know your rights,
it becomes much easier for those in positions of authority to take advantage of that ignorance.
This tool is being built to change that.

You'll be able to:
- **Browse common situations** — police encounters, tenant issues, workplace rights, and more
- **Ask questions in plain English** — and get answers grounded in actual Nigerian law
- **Know what to do and what to avoid** — in real situations, in real time

The AI is powered by a RAG (Retrieval-Augmented Generation) system trained on real Nigerian
legal documents — the Constitution, ACJA, Police Act, Labour Act, and more.

---

## Status: 🟡 Live & In Development

This project is actively being built. We are currently in **Phase 1**.

### Phase 1 — Foundation (Current)
- [x] Project scoped and architecture decided
- [x] Collaborating with a law student to identify priority situations
- [ ] UI prototype (chat interface + situation guides)
- [ ] Legal document corpus sourced and cleaned
- [ ] RAG pipeline built and tested

### Phase 2 — RAG Integration
- [ ] Documents chunked and embedded into vector database
- [ ] Retrieval wired to chat responses
- [ ] Citation display (show which law is being quoted)

### Phase 3 — Scale
- [ ] More legal domains added
- [ ] Pidgin English support
- [ ] Mobile-first polish

---

## What We're Prioritizing for V1

The target audience is **young Nigerians** — students, fresh graduates, people in their 20s.
We're starting with the situations they most commonly face:

| Situation | Key Law/Document |
|---|---|
| Police harassment & unlawful detention | 1999 Constitution (Chapter IV), ACJA 2015 |
| Arrest rights (what to say, what not to say) | Police Act 2020, ACJA 2015 |
| Tenant rights (first-time renters) | Rent Control Laws, Tenancy Laws |
| Workplace rights (interns, entry-level) | Labour Act |
| Gender-based violence & harassment | VAPP Act |

We're deliberately keeping V1 narrow and deep rather than broad and shallow.
As we validate what works, we'll expand to more legal domains.

---

## Tech Stack

| Layer | Tool |
|---|---|
| Frontend | React + Tailwind CSS |
| Hosting | Vercel |
| Vector DB | Supabase (pgvector) |
| Embeddings | OpenAI text-embedding-3-small |
| LLM | Claude (Anthropic API) |
| Backend | Next.js API Routes |

---

## Getting Started (Coming Soon)

Setup instructions will be added as the project matures.

---

## Contributing

See [COLLABORATION.md](./COLLABORATION.md) for how to get involved.

---

## License

MIT — open source, free to use, built for the people.
