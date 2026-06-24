# isi-2026-group1-property-valuation
# ISI Summer Internship 2026 — Group 1
## AI Property Valuation Assistant

A 6-week data-science project where we build, compare, and evaluate two
machine-learning models that predict house prices from real data — then add
an AI layer that explains each prediction in plain English.

---

## What we're building

1. **Two prediction models** — Linear Regression (baseline) and Random Forest
2. **A valuation app** — price a single house or a whole batch at once
3. **An AI assistant** — uses Groq (free LLM) to explain each predicted price in plain English
4. **Optional UI** — ipywidgets demo inside the notebook (only if time allows)

The entire project runs inside **one Jupyter notebook on Google Colab**.

---

## The pipeline
Expected results:
- Linear Regression: R² ≈ 0.88
- Random Forest: R² ≈ 0.92 ✅ winner

---

## The dataset

**Ames Housing Dataset** — Dean De Cock (2011)
- 2,930 home sales × 82 columns
- We use a hand-picked subset of **14 features** to predict `SalePrice`
- File: `AmesHousing.csv` (shared via Microsoft Teams)
---

## Sprint plan

| Meeting | Date | Modules | Deliverable |
|---------|------|---------|-------------|
| 1 · Kickoff | Tue 23 Jun | — | Roles assigned, plan set |
| 2 | Tue 30 Jun | M0 · M1 · M2 | Data loads, X (2925×14) ready |
| 3 | Tue 7 Jul | M3 · M4 · M5 | EDA charts, Linear Regression R² ~0.88 |
| 4 | Tue 14 Jul | M6 · M7 | Random Forest, winner chosen |
| 5 | Tue 21 Jul | M8 · M9 | Predict app + AI assistant working |
| 6 | Tue 28 Jul | M10 (optional) | Clean notebook, report draft |
| Submit | Fri 31 Jul | — | Final report submitted to ISI |

---

## Setup instructions

### 1. Clone / open the notebook
- Go to [colab.research.google.com](https://colab.research.google.com)
- **File → Open notebook → GitHub**
- ✅ Tick **Include private repos**
- Search: `manidharc7/isi-2026-group1-property-valuation`
- Open `ISI_Project_Property_Valuation.ipynb`

### 2. Upload the dataset
- Get `AmesHousing.csv` from the Teams channel
- In Colab, drag it into the 📁 Files panel on the left

### 3. Run the notebook
- **Runtime → Run all**
- Always run from the top — Colab loses variables when the session resets

### 4. Save changes back to GitHub
- **File → Save a copy in GitHub** after every session
- Branch: `main`, add a short commit message (e.g. `"M3 complete"`)

### 5. Groq API key (needed for M9 only)
- Sign up free at [console.groq.com](https://console.groq.com)
- In Colab, click the 🔑 Secrets panel → Add `GROQ_API_KEY`
- **Never paste keys into the notebook or push them to GitHub**

---

## Key rules

- **One notebook, one repo** — never work on a separate copy
- **Commit to GitHub every session** — don't let work sit only in Colab
- **Split before you preprocess** — test set must stay unseen (random_state=42)
- **The model predicts, the LLM explains** — never claim the AI invents a price

---

## Report

Due: **Friday 31 July 2026**
Format: ISI official template (confirmed at Meeting 2)

---

*ISI Summer Internship 2026 · Group 1 · Mentor: Dev Dutta*
