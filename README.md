# 🌱 Welfare Footprint Framework — AI Prompts Repository

This repository hosts the public, human-readable versions of all AI prompts used across the software ecosystem of the Welfare Footprint Framework (WFF). These are the **canonical source-of-truth** prompts: production systems read these files directly, so no separate “synced copies” exist.

The goal is to make our AI reasoning fully transparent, reviewable, and collaboratively improvable.

---

## 🌐 Purpose

The prompts stored here define the reasoning rules, domain logic, constraints, and output formats used by LLMs in WFF applications, such as the Scanner App, WelfareData, Hedonic-Track, and Pain-Atlas.

Keeping them public enables:

- Scientific transparency  
- Expert review & critique  
- Collaboration with developers and researchers  
- Clear versioning and documented evolution of our AI logic  
- A stable reference point for all WFF applications  

This repo contains **only** plain text prompts and documentation — no code, no secrets, no API keys.

---

## 📁 Folder Structure

Each WFF application has its own folder, following the naming pattern:

```
AI_<APPLICATION_NAME>
```

Example structure:

```
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
└── README.md
```

This structure keeps everything simple, flat, and easy to navigate — especially for non-technical collaborators.

---

## 🔍 How This Repo Integrates With Production

- These files are **the single source of truth** for all prompts.  
- WFF applications (Scanner App, etc.) load these `.md` files directly.  
- There is **no secondary prompt copy** inside Supabase or Lovable.  
- Updating a prompt here updates the logic used in production.

---

## 📝 Folder-Level README Requirement

Each application folder (e.g., `AI_SCANNER_APP/`) must include its own `README.md` containing:

- A description of what the prompts in that folder do  
- Hyperlinks to each prompt file  
- Any notes about intended usage or versioning  

This allows you to share a single folder-level README with scientists or developers and give them clean, direct access to the relevant prompts.

---

## 💬 How to Contribute

Contributions are welcome from scientists, developers, and the general public.

Ways to contribute:

- Open GitHub Issues to propose improvements or corrections  
- Comment on scientific accuracy, clarity, structure, ethics boundaries, etc.  
- Submit Pull Requests with suggested edits  

No coding experience is required — prompts are plain text.

---

## 🔐 Security Note

This repository contains **no secrets**, **no API keys**, and **no runnable backend code**.  
It is fully safe to be public.  
All sensitive credentials remain stored privately inside WFF infrastructure.

---
