# 🌱 Welfare Footprint Framework — AI Prompts Repository  

This repository hosts the public, human-readable versions of all AI prompts used across the software ecosystem of the Welfare Footprint Framework (WFF).
These prompts power tools such as the Scanner App, WelfareData, Hedonic-Track, Pain-Atlas, and future WFF applications.

The goal of this repository is to make our AI logic transparent, reviewable, and collaboratively improvable by the broader community.

⸻

🌐 Purpose

AI prompts in the WFF ecosystem encode the reasoning rules, ethical boundaries, domain knowledge, and structured outputs used by LLMs inside our tools.
Keeping them public allows:
	•	Scientific transparency
	•	Community review & critique
	•	Ease of collaboration with researchers and developers
	•	Versioned, documented evolution of the AI logic
	•	A reference source for syncing with production code

This repo does not contain runnable code or API keys—only text prompts and documentation.

⸻

📁 Folder Structure

Each WFF project has its own folder containing the prompts used by that tool.

```text
wff-ai-prompts/
├── SCANNER_APP/
│   ├── analyze_user_material.md
│   ├── confirm_refine_items.md
│   ├── analyze_product.md
│   ├── analyze_focused_item.md
│   ├── suggest_ethical_swap.md
│   ├── fragments.md
│   └── README.md
│
├── WELFAREDATA/
│   └── README.md   (future prompts)
│
├── HEDONIC_TRACK/
│   └── README.md   (future prompts)
│
├── PAIN_ATLAS/
│   └── README.md   (future prompts)
│
└── README.md   (this file)
This structure keeps things simple, flat, and fast to navigate, especially for non-technical collaborators.
```



⸻

🔍 How This Repo Relates to the Production System


	•	The prompts here are the canonical human-editable versions.
	•	In production (e.g., inside Lovable or Supabase Edge Functions), prompts are also embedded in code as runtime strings (due to serverless environment constraints).
	•	After editing a prompt here, maintainers manually sync it with the production copy and bump the prompt version.

The prompts here are therefore the source of truth for editing, even though the runtime uses embedded versions.

⸻

💬 How to Contribute

Contributions are welcome from scientists, developers, and any interested members of the public.

Ways to contribute:
	•	Propose improvements or corrections via GitHub Issues
	•	Comment on clarity, evidence requirements, ethics boundaries, formatting, etc.
	•	Submit Pull Requests for edits

No coding experience is required—prompts are plain text.

⸻

🔐 Security Note

This repository contains no secrets, no API keys, and no backend code.
It is fully safe to be public.
All sensitive credentials remain inside private infrastructure.

⸻
   
