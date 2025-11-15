# 🌱 Welfare Footprint Framework — AI Prompts Repository  


This repository hosts the public, human-readable versions of all AI prompts used across the software ecosystem of the Welfare Footprint Framework (WFF).
These prompts power tools such as the Scanner App, WelfareData, Hedonic-Track, Pain-Atlas, and future WFF applications.

The goal of this repository is to make our AI logic transparent, reviewable, and collaboratively improvable by the broader community.

⸻

🌐 Purpose

AI prompts in the WFF ecosystem encode the reasoning rules, ethical boundaries, domain knowledge, and structured outputs used by LLMs inside our tools.

Keeping them public allows:
	•	Scientific transparency
	•	Community review and critique
	•	Easier collaboration with researchers and developers
	•	Versioned, documented evolution of WFF methods
	•	A reference source for syncing with production code

This repo contains no executable code and no API keys — only text prompts and documentation.

⸻

📁 Folder Structure

Each WFF project has its own folder containing the prompts used by that tool.

To keep everything clear and easy to navigate, all project folders follow the naming convention AI_<PROJECT_NAME>.
This helps both technical and non-technical collaborators instantly recognize the domain of each set of prompts.

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
└── README.md   (this file)
```


This simple, flat structure ensures fast navigation — especially for collaborators without technical experience.

⸻

📘 Mandatory README in Each Project Folder

Each project folder must include its own README.md, containing:
	1.	A clear explanation of what the prompts in that folder do
	2.	Hyperlinks to each file in that folder, so a scientist or external collaborator can access everything from a single document
	3.	Guidelines or context for how to evaluate or propose edits to those prompts

This allows you to share just one link with a collaborator, and they immediately see:
	•	What the prompts do
	•	What they influence
	•	Where each prompt is located
	•	How they can contribute

It dramatically reduces friction and confusion in scientific collaboration.

⸻

🔍 How This Repo Relates to the Production System
	•	The prompts here are the canonical human-editable versions
	•	In production (Lovable / Supabase Edge Functions), prompts are embedded directly in code due to serverless file-system restrictions
	•	After editing a prompt here, maintainers manually sync it into production and bump the prompt version

Thus, this repo serves as the source of truth for editing, even though the deployed system uses embedded versions.

⸻

💬 How to Contribute

Contributions are welcome from scientists, developers, designers, and interested members of the public.

Ways to contribute:
	•	Propose improvements via GitHub Issues
	•	Suggest edits for clarity, structure, evidence, or ethical consistency
	•	Submit Pull Requests (no coding experience needed — prompts are plain text)

⸻

🔐 Security Note

This repository contains:
	•	No API keys
	•	No database credentials
	•	No backend logic or private infrastructure details

It is fully safe to be publicly accessible.

⸻
