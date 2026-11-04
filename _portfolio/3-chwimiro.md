---
title: "Chwimiro (취미로)"
excerpt: "A no-install web agent that recommends hobbies based on each user's time, budget, energy, and social preferences, and suggests a concrete first step. Jul 2026 · My role: planning, back-end/AI, and front-end."
collection: portfolio
---

**Period:** Jul 2026  
**SeSAC mini project**  
**Code:** [github.com/jeseo-lab/sesac_mini_project](https://github.com/jeseo-lab/sesac_mini_project)

Overview
------
Chwimiro uses a short survey and optional free-text input to understand a user's constraints (time, budget, energy, and sociability). It then "prescribes" hobbies, together with a concrete first action and a path to get started.

My role
------
* **Planning:** Designed a low-pressure onboarding, a 9-axis survey, prescription-style recommendation cards, "unexpected" recommendations, one round of feedback-based re-recommendation, hand-off to external platforms, and key metrics.
* **Back-end and AI:** Built FastAPI recommendation and feedback flows; designed a hybrid tag + embedding + LLM recommender; designed ChromaDB and Supabase data structures; planned RAG, sensitive-information handling, and safety branching.
* **Front-end:** Helped implement the step-by-step survey, recommendation cards, feedback and re-recommendation, and action-path screens, including responsive, loading, and error states.

**Tech stack:** FastAPI, LLM, embeddings, ChromaDB, Supabase
