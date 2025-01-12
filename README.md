# Ark.ai

Ark.ai is a private suite of LLM-driven pipelines, chat bots, automations, and third-party integrations extending a Zulip chat server. It leverages advanced AI models, event-driven architectures, and data integrations to provide an extensive range of automated capabilities for team communication, data ingestion, and operational efficiency.

## Stack
- **Python** and **TypeScript**  
- **Vite** with a custom micro-service (UI mapping key relationships)  
- **FastAPI** (wrapping Zulip CLI commands)  
- **Pydantic** (strict type safety across models)  
- **Postgres** (managed via SQLAlchemy)  
- **Docker** (containerized deployments)  
- **Pytest** (testing framework for robust CI/CD)

## Features

- **silver-tongue**  
  Automatic transcription of audio recordings powered by OpenAI Whisper v2.  

- **Dufresne**  
  Summarizes transcripts, auto-assigns topics, and integrates filesystem operations.  

- **ask-gates**  
  Agentic AI assistant providing a natural language interface for transcript data query and manipulation.  

- **captains-log**  
  AI assistant generating daily and cumulative summaries of conversations, actions, and results. Maintains a chronological event timeline, which is rendered on a dedicated React micro-service.  

- **guthrie**  
  Project definition and task assignment through the Trello API, streamlining project management.  

- **max**  
  Graph-based node tree for logging key social network relationships, psychometrics, and noteworthy events.  

- **rackham**  
  GPT-based researcher that automates extended AI-driven investigations via the gpt-researcher open-source Python project.  

- **featherstone**  
  Realtime monitoring of assets, liabilities, business costs, and wages. Maintains coherent bookkeeping.  

- **teach**  
  Conducts critical comparisons of promises versus deliverables and highlights discrepancies.  

- **orca**  
  Monitors asymmetrical investments (crypto, stocks) for periodic reporting.  

- **the-tavern**  
  Wrapper around assorted RSS feeds (AI, big tech, science, geopolitics) with a webhook that imports and aggregates news. Provides weekly summaries tailored by configurable focus settings.  

- **timeless**  
  Delivers daily random quotes from Black Sails or pinned messages to encourage focus and underscore business objectives.  

- **llk**  
  Direct chat integration with a spectrum of LLMs (small, medium, enterprise-grade) for on-demand assistance in any Zulip thread.  

- **ready-aim-fire**  
  Real-time visibility into git commit history for tracking team progress.  

- **billy-bones**  
  A daily accountability system integrating with [idonethis.com](https://www.idonethis.com) to ensure transparent status updates.  

- **black-pearls**  
  Mechanism allowing team members to allocate points to colleagues (but never to themselves) for recognition and motivation.
