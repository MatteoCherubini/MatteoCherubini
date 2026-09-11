Hi, I'm @MatteoCherubini — a developer from Tuscany who builds knowledge systems, secures them, and writes down what happened.

I studied Computer Science in Florence ([thesis on Progressive Web Apps](https://github.com/MatteoCherubini/text-editor-pwa/blob/master/presentazioneCherubini4.pdf), 2022), then spent three years on the front-end of Italian digital publishing and cultural heritage — school platforms, library collections, a lot of accessibility work — and in 2026 went independent to work on the things that kept getting postponed.

## What I'm building

**My Homelab** — A fully containerized self-hosted stack: reverse proxy, private Git, workflow automation, local LLM inference on GPU. Reproducible, modular, boring in the best possible way.

**Knowledge Genome Orchestrator** — a distributed, encrypted, multi-domain knowledge base. An LLM agent incrementally builds and maintains a persistent wiki instead of re-discovering everything at query time: no vector DB, no embedding pipeline, no retrieval server. Knowledge compiled once and kept current, rather than re-derived on every question. Two-phase agent architecture with a hard trust boundary between semantic work and deterministic post-processing, per-genome AES-256 encryption, keys injected at runtime that never touch disk, and a human review gate through pull requests.

**NETKIT** — a TUI for professional network auditing with a legal engine: non-repudiable consent hashes, a fail-closed scope guard, NIS2/GDPR alignment. Built on [Bun](https://bun.sh/) + OpenTUI.

## The stack, honestly

TypeScript on Bun, Node.js, Angular. Docker, Proxmox, Forgejo, n8n. [Ollama](https://ollama.com/) for local models. git-crypt and Vaultwarden for anything that matters. [Obsidian](https://obsidian.md/) for everything I need to remember.

## What changed

I first became interested in this field around 2020. I read everything I could on the subject, and at the time there was a real buzz in the open-source world. I wrote my thesis on Progressive Web Apps because I saw them as a democratic tool: a single source code, with no gatekeepers. Within a few years, I watched those ideas saturate. The market, which previously wanted us divided into front-end and back-end roles, began to demand that we be standardised instead. By the time implementation had become that predictable, there was very little in it a model couldn't learn.

What drew me in was the ideas, and that part hasn't changed. Models can generate implementations, but they don't understand design concepts, and they don't carry the consequences of the decisions they make. So the work moves up a level: understanding a system well enough to decide what can be delegated, what can be verified, and what still requires human judgment. Orchestration rather than implementation — but only if you've earned the understanding needed to orchestrate.

So now I work where ideas still have room: local-first AI, knowledge that maintains itself, tools that take responsibility for what they touch.

## Beyond the code

Specialty coffee. Sustainable, non-intensive agriculture — my family works land in Umbria, and I care about who grows what, and how. Wine: [AIS](https://aisitalia.it/la-storia-di-ais/) member, sommelier in training, and quietly obsessed with [G.R.A.S.P.O.](https://www.graspo.wine/chi-siamo/), the people recovering ancient and near-extinct grape varieties for the sake of biodiversity. [Slow Food](https://www.slowfood.it/chi-siamo/che-cose-slow-food/), ethical finance, [microcredit](https://www.bancaetica.it/il-microcredito-per-linclusione-sociale-e-finanziaria/).

Italian is my mother tongue and I work in English every day. French is the language I'm learning now: A1 today, A2 is the next milestone.

I also write things down at [Medium](https://medium.com/@cherubinimatte).

CV: [PDF, English](https://github.com/MatteoCherubini/MatteoCherubini/blob/main/cherubini_matteo_cv.pdf) · [Europass, Italian](https://github.com/MatteoCherubini/MatteoCherubini/blob/main/cv_europass_matteo_cherubini.md)

---

Still mediocre 👀, just with much better tools 👍
