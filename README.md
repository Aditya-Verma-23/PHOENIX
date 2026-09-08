# PHOENIX
## Phase 1

                    User Request
                         │
                         ▼
                 ┌───────────────┐
                 │  AI Gateway   │
                 │ Model Routing │
                 └───────┬───────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Intent / Purpose│
                │   Detection     │
                └────────┬────────┘
                         │
              ┌──────────┼───────────┐
              ▼          ▼           ▼
           RAG Agent   Harvest    Match Agent
              │          │           │
              ▼          ▼           ▼
        Retrieval     Extraction   Similarity
              │          │           │
              └──────────┼───────────┘
                         ▼
                ┌─────────────────┐
                │ Agent/Concierge │
                │ Orchestration   │
                └────────┬────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │ Guardrails + RBAC   │
              │ Consent + Policies  │
              └──────────┬──────────┘
                         │
                         ▼
                  Final AI Response
                         │
                         ▼
                  Audit + Logging
