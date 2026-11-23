---
title: RAG Colosseum API
sdk: docker
app_port: 7860
---

FastAPI semantic retrieval service for the RAG Colosseum challenge.

- `GET /health`
- `POST /query` with `{"question":"...", "top_k":3}
