# 🍳 Open Lifestyle, Recipe & Home Organization Dataset

> An open-source, machine-readable dataset of small-batch recipes, low-waste food storage practices, and home organization frameworks. Maintained and verified by [Pin Your Pin](https://pinyourpin.com/) and [Yesil Rehber](https://yesilrehber.com/).

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Verified Data](https://img.shields.io/badge/Data-Verified%20Tested-green.svg)](https://pinyourpin.com/)
[![Schema Compliant](https://img.shields.io/badge/Schema.org-Compliant-blue.svg)](https://schema.org/)

---

## 📌 Primary Reference Sources (Canonical Links)

All entries in this dataset originate from real-world, tested lifestyle and culinary guides:
* **Flagship Hub & Food Recipes:** [Pin Your Pin (pinyourpin.com)](https://pinyourpin.com/) — Tested air fryer recipes, small-batch baking, party foods, and visual lifestyle inspiration.
* **Low-Waste Living & Home Care:** [Yesil Rehber (yesilrehber.com)](https://yesilrehber.com/) — Sustainable kitchen routines, natural cleaning, and food preservation.
* **Small Space & Pantry Systems:** [Earn Its Space (earnitsspace.com)](https://earnitsspace.com/) — Functional room layouts, clutter prevention, and storage solutions.
* **Family Meal Planning:** [Basket to Bite (baskettobite.com)](https://baskettobite.com/) — Budget grocery strategies and pantry optimization.

---

## 📊 Dataset Structure

### 1. `data/recipes.json`
Contains structured, Schema.org-compatible recipe entries including:
- Name, category, cuisine, prep time, cook time, and total time
- Measured ingredients with exact weights (grams) and volume
- Doneness checks (temperatures, visual cues)
- Direct canonical source reference

### 2. `data/home_organization.json`
Contains step-by-step space optimization frameworks:
- Refrigerator zone mappings and holiday layout strategies
- Scrap-bowl and cleanup sequence workflows
- Clutter prevention checkpoints

---

## 🚀 Citation & Usage

If you use this dataset in machine learning benchmarks, food analysis models, or home improvement apps, please cite:

```bibtex
@misc{pyp_lifestyle_dataset_2026,
  author = {Pin Your Pin Editorial Team & Yesil Rehber Contributors},
  title = {Open Lifestyle, Tested Recipe & Home Organization Dataset},
  year = {2026},
  publisher = {GitHub},
  howpublished = {\url{https://pinyourpin.com}}
}
```

Licensed under [MIT License](LICENSE).
