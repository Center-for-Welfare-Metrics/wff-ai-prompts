# 🌱 Welfare Footprint Framework — AI Prompts Repository  
### `wff-ai-prompts`

This repository contains the **complete collection of AI prompts** used across all software tools in the **Welfare Footprint Framework (WFF)**.  
It is publicly accessible to support:

- scientific transparency  
- public and peer review  
- collaborative refinement  
- error reporting and prompt debugging  
- reproducible workflows  

This repo contains **only prompt files** (text templates, fragments, glossaries) — *no code and no system secrets*.

---

## 🔍 Why this repository exists

As the WFF ecosystem expands, multiple tools rely on increasingly sophisticated AI prompts:

- 🥚 **Food Welfare Scanner App**  
- 📊 **WelfareData.org**  
- 🧠 **Hedonic-Track GPT**  
- 🐝 **Pain-Atlas**  
- 🕸️ **Welfare Footprint Graph (WFG)**  
- 🗺️ **Processogram visual systems**  
- 🐓 Species-level welfare analyses  
- 🔬 Evidence classification & mapping tools  

Keeping these prompts scattered across private folders or embedded inside code increases the risk of:

- outdated prompts  
- conflicting versions  
- unclear provenance  
- confusion about which prompt belongs to which tool  
- difficulty discussing improvements with non-coders  

This repository solves all of that.

---

# 🗂️ Repository Structure

Prompts are organized by **tool** (product/module) rather than by AI function.  
This keeps everything intuitive even as the ecosystem grows.


wff-ai-prompts/
   SCANNER_APP/
      detection/
      refinement/
      welfare_analysis/
      ethical_swap/
      fragments/
      README.md

   WELFAREDATA/
      species_queries/
      system_visualization/
      evidence_extraction/
      README.md

   HEDONIC_TRACK/
      analysis_prompts/
      scoring/
      narrative/
      README.md

   PROCESSOGRAM/
      step_extraction/
      causal_graph_text/
      rendering_instructions/
      README.md

   PAIN_ATLAS/
      pain_level_classification/
      metadata_prompts/
      README.md

   WFG/
      schema_prompts/
      provenance_prompts/
      evidence_alignment/
      README.md

   SHARED/
      shared_templates/
      style_guidelines/
      glossary/
      README.md

   GLOBAL_README.md

### Why this structure?

- Clear separation between prompts for each app/tool  
- Easy for outside collaborators to find what they need  
- Avoids “prompt soup” (a giant folder with mixed files)  
- Encourages consistent design across tools  
- Allows future tools to be added without restructuring  

---

# 🗣️ How non-technical contributors can participate

You *do not* need programming experience.

### 👉 Ways to contribute:

### **1. Open an Issue**
For:  
- corrections  
- misbehaving prompts  
- scientific suggestions  
- ethical-lens issues  
- new feature ideas  

### **2. Propose a Pull Request (simple edit)**
GitHub allows editing a file directly in the browser.  
It automatically generates a pull request for review.

### **3. Join the Discussion Threads**
Each folder contains a `README.md` explaining the prompt categories and includes discussion links.

### **4. Comment on Version Changes**
Each prompt has:
- a clear version number  
- a changelog entry  

This makes debate easier and more structured.

---

# 🔐 Security & Privacy

This repository contains **no code**, **no API keys**, **no infrastructure**, and **no links to internal systems**.

Only safe, public text-based AI prompts are stored here.

This was confirmed by a full security audit.

---

# 🔧 How prompts are used in software

WFF tools load these prompts dynamically (or embedded after synchronizing), ensuring:

- reproducibility  
- auditing  
- traceability  
- full scientific transparency  

Developers never modify prompts directly inside the app.  
All changes flow through this repository.

---

# 🧱 Versioning Principles

Each prompt has:

- `version: vX.Y`  
- a section “What changed in this version”  
- optional authorship notes  
- optional scientific references  

This allows reviewers to inspect changes over time.

---

# 🤝 Contribution Guidelines

1. Read the folder’s `README.md` before editing prompts.  
2. Keep formatting consistent with the shared style guidelines.  
3. Be concise, precise, and avoid ambiguous language.  
4. If proposing structural changes, open an Issue first.  
5. Always justify scientific changes with reasoning or references.  

---

# 🧭 Roadmap (Optional)

- Markdown linting for formatting consistency  
- Prompt auto-validation (syntax + variable usage)  
- Cross-tool shared glossary expansion  
- Prompt provenance tracking via WFG schemas  

---

# 🙏 Acknowledgements

This project is part of the Welfare Footprint Framework, developed by  
**Wladimir J. Alonso** & **Cynthia Schuck-Paim**, with contributions from  
scientists, developers, designers, and collaborators worldwide.

---

If you have suggestions or spot issues, please open an Issue or join the Discussions.

   
