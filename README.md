# Sumith Sadanand Bhandari

AI Software Engineer in London. I build production AI agents and the backend systems around them, in Python and TypeScript.

[Portfolio](https://sumithsb.github.io/portfolio) · [LinkedIn](https://linkedin.com/in/sumith-sadanand-bhandari) · [Email](mailto:sumithsbhandari@gmail.com)

## What I do

I have 4+ years of backend and AI agent work: multi-agent workflows, RAG and document extraction pipelines, LLM integrations (Anthropic, OpenAI) and the APIs, databases and deployments that keep them running.

- **Goodspeed Studio** (AI Engineer, Jul 2026 to present, contract then freelance). I build and run production AI agents: a Slack agent used daily by 16+ people, with multi-tenant memory, human-review steps and integrations into business tools, and a website chat agent that I took through a GDPR, PECR and EU AI Act review before launch.
- **Visiminds Technologies** (Software Engineer, 2025). Built a VAPT automation platform in Python, Flask and MongoDB that runs 14 security tools and writes the client report. A job queue with 20 concurrent workers cut scan and report time from about 4 hours to under 15 minutes.
- **TechMachinery** (Software Engineer, 2021 to 2024). Led backend work on Pluto, a TechMachinery platform where engineers query and design heat exchanger systems in plain language. Multi-agent system on Strands (AWS) with pgvector retrieval; document parsing reached 94% extraction accuracy on a 50-document test set.

I hold an MSc in Advanced Computer Science (Distinction) from the University of Leicester.

I'm open to AI Software Engineer and Forward Deployed Engineer roles in London, contract or permanent.

## Projects

**[Claude Anchor](https://github.com/SumithSB/claude-anchor)**: a desktop app that routes Claude Code to the right Claude account for each project folder. It tracks the 5-hour and weekly rate limits per account, moves to an account with headroom before a session stalls, and continues a conversation on another account with its history. Swift menu bar app on macOS, Rust/Tauri tray app on Windows and Linux, plus an `anchor` CLI. Install with Homebrew or a checksum-verified script. MIT, no telemetry.

**[Brainvault](https://github.com/SumithSB/brainvault)** ([PyPI](https://pypi.org/project/brainvault/)): persistent local memory for AI coding agents such as Claude Code and Cursor. One SQLite vault, 12 MCP tools, session hooks, FTS5 search and optional semantic search with fastembed and sqlite-vec. `pip install brainvault`.

**Fashion AI** (MSc dissertation, Best Technical Project 2026): a mobile styling app built with Flutter, FastAPI and pgvector. It includes skin tone analysis, a recommender over a 59,447-product catalogue and a RAG styling chat (MRR@6 of 0.91 over 53 evaluation queries).

## Stack

- **Languages:** Python, TypeScript, SQL, Node.js, Dart (Flutter)
- **AI:** Anthropic and OpenAI APIs, MCP, multi-agent orchestration (Strands), tool-calling agents, RAG, embeddings, prompt caching, retrieval evaluation
- **Backend:** FastAPI, Flask, Express.js, REST, webhooks, WebSockets
- **Data:** PostgreSQL, pgvector, SQLite, Supabase, MongoDB, Redis
- **Infra:** AWS (EC2, S3, Lambda, IAM, CloudWatch), GCP, Docker, GitHub Actions, Railway, Vercel
