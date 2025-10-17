# 🧠 KeelerApp Political Analytics — Synthetic Split-Vote Simulation

**Author:** [Alexandra Bustos Frati, PhD](https://keeler.app)  
**Organization:** KeelerApp — Applied AI & Political Data Science  
**Version:** 1.0 • **License:** Apache 2.0  
**Tags:** #DataScience #Analytics #PoliticalAI #ExplainableAI #SyntheticData

---

## 🪄 What this project is

This repository hosts an **open, fully synthetic demo** of KeelerApp’s analytical framework  
for political data interpretation — modeling how **tone**, **topic**, and **scope** (local vs. national)  
affect *split-ticket voting* behavior in an urban municipality.

All data are synthetic. No client or real data are used or inferred.

---

## 📂 Repository Structure

| File | Description |
|------|--------------|
| `SplitVote_Simulation.ipynb` | Main Jupyter Notebook — reproducible end-to-end demo |
| `SplitVote_Simulation.html` | Pre-rendered HTML version for web preview |
| `README.md` | This document |
| `LICENSE` | Apache License 2.0 |
| *(optional future)* `/assets/` | static plots, thumbnails, exported visuals |

---

## 📊 What the notebook demonstrates

1. **Synthetic data generation** — three urban neighborhoods with different signal biases.  
2. **Explainable modeling** — logistic regression (StatsModels) with transparent coefficients.  
3. **Correlations & signals** — interpretable patterns between tone and split-voting tendency.  
4. **Didactic narrative** — Markdown interleaved with code for non-technical comprehension.  
5. **Ethical analytics** — synthetic-only, HITL-aware, reproducible, bias-auditable.

---

## 🧩 Technical stack

| Component | Purpose |
|------------|----------|
| Python ≥3.10 | runtime |
| NumPy, pandas | data manipulation |
| Matplotlib | visualization |
| StatsModels | logistic modeling |
| IPython | rendering support |
| JupyterLab / Notebook 7 | execution environment |

Install dependencies:

```bash
python3 -m pip install numpy pandas matplotlib statsmodels jupyterlab
```

---

## ⚙️ How to run

1. **Clone the repository**
   ```bash
   git clone https://github.com/keelerapp/keeler-splitvote-simulation.git
   cd keeler-splitvote-simulation
   ```
2. **Install dependencies**
   ```bash
   python3 -m pip install -r requirements.txt
   ```
   *(optional)* create and activate a virtual environment:
   ```bash
   python3 -m venv venv && source venv/bin/activate
   ```
3. **Launch Jupyter**
   ```bash
   jupyter notebook SplitVote_Simulation.ipynb
   ```
4. **Run all cells**
   Use: *Kernel → Restart & Run All*  
   Outputs and plots will appear inline.

---

## 🧭 Methodology

- **Transparent scoring** (no black boxes).  
- **Synthetic-only data** with fixed seeds for reproducibility.  
- **Explainable models** emphasizing clarity over prediction.  
- **Human-in-the-loop (HITL)** validation embedded in workflow.  
- **Ethical reflection** — every analytical step is documented and interpretable.

---

## 🧱 Why it matters

This notebook showcases how *KeelerApp* transforms  
qualitative insights (discourse, focus groups, sentiment)  
into quantitative reasoning that preserves human interpretability.

It’s not about predicting voters — it’s about **understanding the framing**  
through transparent, reproducible computation.

---

## 🧭 KeelerApp Framework Reference

| Pillar | Description |
|--------|--------------|
| **Strategy** | Data-to-decision reframing for campaign and governance. |
| **Analytics** | Transparent, synthetic, and reproducible modeling. |
| **Agenticity** | Multi-agent orchestration of interpretive intelligence. |
| **Training** | Pedagogical transformation: explainable computation as education. |

> “From simulation to strategy, from data to understanding —  
> KeelerApp builds intelligence that listens before it decides.”

---

## 📜 License

This repository is licensed under the **Apache License 2.0**.  
You may use, modify, and distribute the contents provided that you:

- Retain attribution to **Alexandra Bustos Frati (KeelerApp)**.  
- Do not use the *KeelerApp* brand or logo to imply endorsement.  
- Include the license text in derivative works.

See the LICENSE file for full terms.

---

## 🧠 About KeelerApp

**KeelerApp** is an applied AI consultancy focused on **agentic intelligence**, **explainable analytics**, and **pedagogical systems for human-centered AI**.  It integrates data science, process automation, and strategic consulting under the **Tetradic Framework** — *Strategy, Analytics, Agenticity, Training.*

> Learn more at [keeler.app](https://keeler.app)

---
