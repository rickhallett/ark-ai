# Ark.ai

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
<!-- [![Tests](https://img.shields.io/badge/tests-100%25-success.svg)](#) -->
[![Docker](https://img.shields.io/badge/docker-ready-blue.svg)](#)
[![Python](https://img.shields.io/badge/python-3.11+-blue.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#)

Ark.ai is a private suite of LLM-driven pipelines, chat bots, automations, and third-party integrations extending a Zulip chat server. It harnesses AI models, event-driven architectures, and data integrations to streamline data ingestion, team collaboration, and operational logistics.

---

## Stack

### Backend
- [FastAPI](https://fastapi.tiangolo.com/) for high-performance API handling, 
- [PostgreSQL](https://www.postgresql.org/) with [pgvector](https://github.com/pgvector/pgvector) for robust data and vector storage, 
- [Redis](https://redis.io/) and [Celery](https://docs.celeryq.dev/) for reliable task processing
- [Pydantic](https://docs.pydantic.dev/) for strict type safety across models
- [Docker](https://www.docker.com/) for containerized deployments
- [Pytest](https://docs.pytest.org/) for robust testing framework
- [OpenAI](https://openai.com/) and [Anthropic](https://www.anthropic.com/) for language model capabilities

### Frontend
- [Vite](https://vitejs.dev/) 
- [React](https://react.dev/)
- [TypeScript](https://www.typscriptlang.org/) 
- [Tailwind](https://tailwindcss.com/)
- [Vercel](https://vercel.com/) for deployment
- [Zulip](https://zulip.com/) for chat server, hosted on [Digital Ocean](https://www.digitalocean.com/)

---

## Features

- **silver-tongue**  
  Automatic transcription of audio recordings powered by OpenAI Whisper v2.

- **Dufresne**  
  Automated transcript summarization, topic assignment, filesystem integration.

- **ask-gates**  
  Agentic AI assistant enabling natural language interaction and data queries.

- **captains-log**  
  AI assistant that provides both daily and cumulative conversation summaries, actions, and outcomes. Maintains a chronological event timeline rendered in a React micro-service.

- **guthrie**  
  Project definition, task assignment, and management through Trello API.

- **max**  
  Graph-based node tree capturing key social network relationships, psychometrics, and critical events.

- **rackham**  
  AI-based researcher leveraging gpt-researcher, orchestrating extended investigations.

- **featherstone**  
  Real-time bookkeeping of assets, liabilities, costs, and wages.

- **teach**  
  Rigorous critique of promises versus deliverables, highlighting inconsistencies.

- **orca**  
  Overviews asymmetrical investments (crypto, stocks) for structured reporting.

- **the-tavern**  
  RSS aggregator (AI, big tech, science, geopolitics) with webhook imports. Summaries configured weekly by focus settings.

- **timeless**  
  Daily random quotes from Black Sails or pinned messages, enhancing focus and motivation.

- **llk**  
  Direct integration with multiple LLMs (small to enterprise grade) for contextual thread assistance in Zulip.

- **ready-aim-fire**  
  Tracks real-time git commit history for team-wide visibility.

- **billy-bones**  
  Daily accountability system integrated with [idonethis.com](https://www.idonethis.com).

- **black-pearls**  
  Facilitates point allocation among team members, fostering collaboration and recognition.
