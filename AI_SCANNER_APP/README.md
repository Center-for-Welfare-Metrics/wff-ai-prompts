# 🤖 AI Prompts — WFF Scanner App

This folder contains all prompts used by the **Welfare Footprint Scanner App**, which analyzes foods, identifies animal-derived ingredients, evaluates welfare impacts, and suggests ethical alternatives.

These prompts are the **canonical production versions** used by the Scanner App.  
The application loads these `.md` files directly.

---

## 📄 Prompt Files

### **1. analyze_user_material.md**
Parses the user’s text or scanned labels to identify food items, ingredients, and relevant context.

### **2. confirm_refine_items.md**
Validates and refines the candidate items extracted from the user material.

### **3. analyze_product.md**
Evaluates each product at the level of species, farming system, and welfare impact category.

### **4. analyze_focused_item.md**
Provides a deeper analysis of a single selected item, linking it to Welfare Footprint Framework concepts.

### **5. suggest_ethical_swap.md**
Suggests possible alternative choices based on the user’s ethical lens and the welfare impacts involved.

### **6. fragments.md**
Contains reusable prompt fragments shared across multiple prompts (e.g., ethical lens rules, structured output formats).

---

## 🧭 How to Use This Folder

Share this README with collaborators — each file above links to a specific component of the AI reasoning for the Scanner App.

Edits to these files propagate to the production system automatically (no second copy exists elsewhere).

---
