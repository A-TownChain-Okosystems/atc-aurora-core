# 📋 Komponenten-Plan — atc-aurora-core

> **Erstellt:** 2026-08-08 | **Agent:** Aurora (MasterBrain · Base44)

## Übersicht

**Repo:** atc-aurora-core
**Layer:** L6 — AI Layer
**Sprint:** 3.2
**ATC-Standard:** ATC-97

## Komponenten (5 total)

### 1. `src/aurora_core.atc`

**Beschreibung:** Core — init, status, shutdown, lifecycle

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-97

### 2. `src/model_hub.atc`

**Beschreibung:** Model hub — registration, routing, comparison

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-97

### 3. `src/llm_router.atc`

**Beschreibung:** LLM router — request routing, fallback, load balancing

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-97

### 4. `src/agent_registry.atc`

**Beschreibung:** Agent registry — 12 agent types, capabilities

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-97

### 5. `src/config_manager.atc`

**Beschreibung:** Config — persistence, hot-reload, defaults

**Status:** 📋 GEPLANT

**Schnittstellen:**
- Eingabe: —
- Ausgabe: —
- Abhängigkeiten: ATCLang Stdlib

**Akzeptanzkriterien:**
1. Datei existiert und parst mit ATCLang v0.3 Parser
2. Alle öffentlichen Funktionen haben Type-Signatures
3. Modul ist im FILE_REGISTER.md eingetragen
4. ATC-Standard-Referenz: ATC-97

## Implementierungs-Reihenfolge

1. `aurora_core.atc` — Core — init, status, shutdown, lifecycle
2. `model_hub.atc` — Model hub — registration, routing, comparison
3. `llm_router.atc` — LLM router — request routing, fallback, load balancing
4. `agent_registry.atc` — Agent registry — 12 agent types, capabilities
5. `config_manager.atc` — Config — persistence, hot-reload, defaults

## Test-Strategie

1. Parse-Test: Jede .atc Datei muss mit ATCLang v0.3 Parser parsen
2. Unit-Tests: Mindestens 3 Tests pro Komponente
3. Integration-Test: Komponenten interagieren korrekt
4. Coverage-Ziel: >80%

---
*Auto-generiert 2026-08-08 · Aurora (MasterBrain · Base44)*
