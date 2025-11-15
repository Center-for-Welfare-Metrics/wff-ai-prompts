# 🌱 Welfare Footprint Framework — AI Prompts Repository

This repository contains the **canonical, production-of-record** AI prompts used across all software projects of the **Welfare Footprint Framework (WFF)**.

These files are *not* mirrors of other repositories.  
They are the **single source of truth** for every WFF prompt, and all WFF applications must read from here.

Prompts are plain text. They contain no secrets, no API keys, and no backend logic — only the reasoning, structure, and scientific logic that guide the LLMs powering the WFF ecosystem.

---

## 🌐 Purpose

AI prompts encode the shared cognitive foundation used across WFF tools:
- Scientific reasoning criteria  
- Ethical rules  
- Domain knowledge  
- Pain and welfare logic  
- Output schemas  
- Detection heuristics  
- Metadata and provenance instructions  

Centralizing them:
- Enables scientific transparency  
- Allows community review  
- Ensures consistency across all WFF apps  
- Prevents “prompt drift” between tools  
- Creates a clean chain of versioning  
- Allows collaboration with researchers who do not write code  

---

## 📁 Folder Structure

Each WFF project has its own top-level folder, prefixed with **AI_** for clarity:

```text
wff-ai-prompts/
├── AI_SCANNER_APP/
│   ├── analyze_user_material.md
│   ├── confirm_refine_items.md
│   ├── analyze_product.md
│   ├── analyze_focused_item.md
│   ├── suggest_ethical_swap.md
│   ├── fragments.md
│   └── README.md
│
├── AI_WELFAREDATA/
│   └── README.md
│
├── AI_HEDONIC_TRACK/
│   └── README.md
│
├── AI_PAIN_ATLAS/
│   └── README.md
│
└── STANDARDS/
    ├── prompt_writing_standards.md
    ├── response_schema.md
    └── project_conventions.md

└── README.md   ← (this document)
```


### 📌 Naming Convention Rule

All top-level project folders must start with the prefix:


Examples:
- `AI_SCANNER_APP`
- `AI_WELFAREDATA`
- `AI_HEDONIC_TRACK`
- `AI_PAIN_ATLAS`

This guarantees that:
- contributors immediately understand the purpose  
- all WFF AI projects remain grouped together  
- interfaces across repos become predictable  

---

## 📄 Required README in Each Project Folder

Every `AI_<PROJECT_NAME>/README.md` must include:

1. **A description of that project’s AI logic**
2. **Hyperlinks to every prompt file** in that folder
3. **Explanations of how prompts interact**
4. **Data schemas when relevant**

This allows you to send a **single link** to any scientist or collaborator, giving them everything they need to review or contribute.

---

## 🔍 Relationship to Production Systems

- These prompts **are** the production versions.  
- All applications must **load prompts directly from this repository** (via HTTP, GitHub raw, or embedded sync scripts).
- No developer should maintain parallel or “shadow” copies in other repos.

### ✨ Why this matters

This eliminates:
- drift  
- version mismatch  
- silent divergence between apps  
- accidental overwrites  

And creates:
- a unified standard  
- one authoritative source  
- clear collaboration workflows  

---

## 💬 How to Contribute

Everyone is welcome to contribute — scientists, ethicists, developers, and the general public.

Ways to participate:
- Open **GitHub Issues** with improvements or critiques  
- Comment on clarity, logic, ethics, or scientific grounding  
- Submit Pull Requests  

**No coding skills required.**  
Prompts are plain text.

---

## 🔐 Security Note

This repository contains:
- ❌ no API keys  
- ❌ no secrets  
- ❌ no server code  
- ❌ no authentication logic  

It is 100% safe to be public.

---

## 📐 WFF Standard Response Schema

All prompts that return structured output must follow the official schema:

👉 **[WFF Standard AI Response Schema](STANDARDS/response_schema.md)**

---

## 🧭 Prompt Writing Standards

Prompts across all projects must follow shared style and structure conventions:

👉 **[WFF Prompt Writing Standards](STANDARDS/prompt_writing_standards.md)**

---

## 🧠 Philosophy

This repository is built on three principles:

1. **Transparency** — AI reasoning should be inspectable and scientifically grounded.  
2. **Standardization** — all WFF tools share the same conceptual backbone.  
3. **Collaboration** — anyone can understand, critique, and improve our welfare logic.

---

## 🌟 Final Note

This repository is the intellectual backbone of the WFF software ecosystem.  
Treat it as you would treat a scientific manuscript:  
with clarity, rigor, structure, and openness to critique.

