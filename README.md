# BackForge

## 🎭 Project: "Smart" RP Sheet Generator for GTA RP

### 🧩 Goal  
BackForge is a web app designed to create, enrich, and manage consistent, typed RP backgrounds for GTA RP characters. It leverages a local AI (with optional API) to generate rich, detailed profiles tailored to selected archetypes.

---

## 💡 Key Features

- **Guided Character Creation**  
  Typed fields (name, age, origin, job, personality traits) with automatic validation (Zod).

- **Background Generation**  
  Provide a few details (e.g., "mechanic's son from Sandy Shores"), the AI crafts a coherent backstory.  
  Partial regeneration possible (e.g., "redo his criminal past").

- **AI-Enriched Profiles**  
  Generates RP goals, hidden flaws, potential relationships based on archetypes.

- **Local AI Model**  
  Integration with Ollama (Mistral, LLaMA3) for local inference, with optional API fallback.

- **Export & Import**  
  Export sheets as `.json`, `.pdf`, `.md` — fully typed.  
  Local storage and easy reimport supported.

- **Tag / Archetype System**  
  Influences generation (e.g., "criminal," "traumatized," "loyal"), affecting tone and content.

- **Manual Editor & History**  
  All changes tracked with typed snapshots, allowing rollback.

- **"Storyteller Helper" Mode**  
  AI suggests plot twists and potential conflicts between characters.

---

