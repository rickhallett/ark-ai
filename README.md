# Ark.ai

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Tests](https://img.shields.io/badge/tests-100%25-success.svg)](#)
[![Docker](https://img.shields.io/badge/docker-ready-blue.svg)](#)
[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](#)

Ark.ai is a private suite of LLM-driven pipelines, chat bots, automations, and third-party integrations extending a Zulip chat server. It harnesses AI models, event-driven architectures, and data integrations to streamline data ingestion, team collaboration, and operational logistics.

---

## Stack
- **Python** and **TypeScript**  
- **Vite** with a custom micro-service (UI mapping key relationships)  
- **FastAPI** (wrapping Zulip CLI commands)  
- **Pydantic** (strict type safety across models)  
- **Postgres** (via SQLAlchemy)  
- **Docker** (containerized deployments)  
- **Pytest** (robust testing framework)

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
