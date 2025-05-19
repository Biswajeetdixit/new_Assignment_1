# README — SlateMate AI/ML Assignment

## 📘 Title
**Harm to Hope: AI Replacement of Unsafe Content**

## 🧠 Problem Statement
SlateMate aims to go beyond filtering unsafe content by replacing it with positive, motivational, and educational alternatives aligned with the emotional well-being and interests of children.

This project processes 100 harmful social media text posts and:
- Detects the underlying **theme** (e.g., toxic language, gossip, violence)
- Suggests a **safe and educational replacement**
- Outputs the results in `replacement_feed.csv`

---

## ⚙️ Approach

### 1. Theme Detection
- Used **keyword-based mapping** to detect themes like:
  - `toxic language`, `emotional distress`, `violent gaming`, etc.
- Fallback to category tag from dataset when no keywords matched

### 2. Educational Replacement
- Used a **theme-to-replacement mapping dictionary**
- For each theme, suggested one of the following:
  - ✅ **AI-generated motivational message**
  - ✅ **YouTube educational video**
  - ✅ **Short positive affirmation or link to learning resource**

---

## 📂 Files

| File | Description |
|------|-------------|
| `harmful_metadata.csv` | Input dataset of harmful posts |
| `slatemate_assignment_notebook.ipynb` | Complete implementation |
| `replacement_feed.csv` | Output file with safe replacements |
| `README.md` | This documentation file |

---

## ✅ Replacement Types Used

- `AI-generated`: Uplifting messages written in human tone
- `YouTube link`: Safe educational content for kids
- `Motivational redirects`: Emotionally aligned with interests like coding, psychology, resilience

---

## ✍️ Notes

- No external APIs were used — all content is **curated or written in-code**.
- All logic is explained and reproducible inside the Jupyter Notebook.
- Bonus-ready markdown samples can be added if needed for presentation.

---

Made with 💡 for SlateMate
