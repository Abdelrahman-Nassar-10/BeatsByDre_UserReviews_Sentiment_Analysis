# Beats by Dre — Sentiment Analysis Of User Reviews 

A professional packaging of my capstone project from an online internship with **Beats by Dre**.
This repository contains the original analysis notebook and a clean project structure to make it easy to review, reproduce, and extend.

> **Note on data**: All data files are stored locally on my machine. To run this project, place the required data files in the appropriate folder as described below.

---

## Repository Structure

```
beats-by-dre-capstone/
├─ notebooks/
│  └─ Beats by dre project capstone.ipynb
├─ src/
│  └─ .gitkeep
├─ data/
│  ├─ raw/           # Put original/raw data files here (not tracked by git)
│  │  └─ .gitkeep
│  └─ processed/     # Put intermediate/processed files here (not tracked by git)
│     └─ .gitkeep
├─ reports/
│  └─ figures/       # Auto-generated figures/plots (gitignored)
│     └─ .gitkeep
├─ requirements.txt
├─ .gitignore
└─ README.md
```

---


## Create a Python environment and install dependencies

Using **pip + venv**:

```bash
python -m venv .venv
# Windows
.\.venv\Scripts\activate
# macOS/Linux
# source .venv/bin/activate

pip install -r requirements.txt
python -m ipykernel install --user --name beats-capstone --display-name "Python (beats-capstone)"
```

> If you prefer `conda`, create an env and then `pip install -r requirements.txt` inside it.



## Project Outline

This capstone explores data and insights relevant to the Beats by Dre internship tasking. The work typically includes:
- Data loading and cleaning
- Exploratory data analysis (EDA) and visualization
- Feature engineering and modeling (if applicable)
- Evaluation and recommendations

> See `notebooks/Beats by dre project capstone.ipynb` for the full analysis and results.



