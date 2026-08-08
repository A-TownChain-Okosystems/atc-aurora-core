# 🏗️ Architektur — atc-aurora-core

> **Erstellt:** 2026-08-08 | **Agent:** Aurora

## Architektur-Baum

```
atc-aurora-core/
├── README.md
├── ARCHITECTURE.md
├── COMPONENT_PLAN.md
├── ROADMAP.md
├── STATUS.md
├── CHANGELOG.md
├── FILE_REGISTER.md
└── src/
    ├── aurora_core.atc                 Core — init, status, shutdown, lifecycle
    ├── model_hub.atc                   Model hub — registration, routing, comparison
    ├── llm_router.atc                  LLM router — request routing, fallback, load balancing
    ├── agent_registry.atc              Agent registry — 12 agent types, capabilities
    ├── config_manager.atc              Config — persistence, hot-reload, defaults
```

## Statistik

| Metrik | Wert |
|--------|------|
| .atc Dateien | 5 |
| Layer | L6 — AI Layer |
| ATC-Standard | ATC-97 |
| Sprint | 3.2 |
| Status | 📋 GEPLANT |

---
*Auto-generiert 2026-08-08 · Aurora (MasterBrain · Base44)*
