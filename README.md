# Hi, I'm Colin Emmanuel 👋

**Computer Science @ Columbia University · Break Through Tech AI Fellowship graduate (Cornell Tech)**

I build machine learning systems end-to-end — from framing the problem and engineering features to
ensembling, calibration, and making the whole thing reproducible. My work spans survival analysis,
recommender systems, computer vision, and applied data analysis, with a bias toward projects where the
model has to be *trustworthy*, not just accurate.

- 🔭 Most recent: a top-27% finish in the **WiDS Global Datathon 2026** (wildfire survival forecasting)
- 🌱 Interests: applied ML, survival analysis, recommender systems, computer vision, NLP
- 📫 Reach me: **c.j.emmanuel@columbia.edu** · [GitHub](https://github.com/Colin-J-Emmanuel) · [LinkedIn](https://www.linkedin.com/in/colin-j-emmanuel/)

---

## 🚀 Featured Projects

| Project | What it is | Highlight | Stack |
|---|---|---|---|
| **[🔥 Wildfire Survival Forecasting](https://github.com/Colin-J-Emmanuel/wildfire-survival-forecasting)** | Multi-horizon survival model predicting when a wildfire threatens an evacuation zone (WiDS Datathon 2026) | **0.874 → 0.964**, top **~27%** of 1,754 teams | XGBoost Cox · scikit-survival · Optuna · calibration |
| **[🎓 Break Through Tech AI — Portfolio](https://github.com/Colin-J-Emmanuel/break-through-tech-ai)** | My full fellowship portfolio: ML Foundations coursework + industry AI Studio projects | 47 notebooks across the ML life cycle + team projects | Python · scikit-learn · Keras · pandas |
| **[🎵 Spotify Music Recommendation System](https://github.com/Colin-J-Emmanuel/Music-Recommendation-System)** | Hybrid recommender combining content-based and collaborative filtering | ~250k tracks; cosine similarity + SVD | Python · Spotify API · NumPy/SciPy · JS |
| **[🎮 GTA Online Player Analysis](https://github.com/Colin-J-Emmanuel/gtao-datathon-analysis)** | Engagement-vs-monetization analysis for the Rockstar Games Datathon | Surfaced that top spenders play *less* — strategy insight | Python · pandas · Seaborn · SciPy |

---

### 🔥 Wildfire Survival Forecasting — *flagship*
[`wildfire-survival-forecasting`](https://github.com/Colin-J-Emmanuel/wildfire-survival-forecasting)

Given only the **first five hours** of a wildfire's behavior, forecast the probability it reaches an
evacuation zone within 12/24/48/72 hours — a right-censored **survival-analysis** problem. My team
improved the provided XGBoost Cox baseline from **0.87397 to 0.96366**, finishing **477 / 1,754 teams
(top ~27%)**. The biggest gain came from diagnosing that the baseline was *overconfident about distant
fires* and fixing it with distance-aware features and **per-horizon probability calibration**. The repo
is built for reproducibility: a reusable `src/` package, twin GitHub/Kaggle notebooks generated from one
source, and figures regenerated from the actual submission.

`survival analysis` · `XGBoost Cox PH` · `Random Survival Forest` · `Optuna` · `isotonic/Platt calibration` · `ensembling`

### 🎓 Break Through Tech AI — Portfolio Hub
[`break-through-tech-ai`](https://github.com/Colin-J-Emmanuel/break-through-tech-ai)

The complete record of my Break Through Tech AI fellowship: **47 notebooks** spanning the full ML life
cycle (data prep → classical models → deep learning → NLP), plus my contributions to the **Fall AI
Studio with Ursa Space Systems** (SAR satellite-image classification, icebergs vs. vessels, using ViT /
ConvNeXT embeddings). A good single link for seeing my breadth and progression.

`scikit-learn` · `Keras/TensorFlow` · `pandas` · `computer vision` · `NLP` · `transfer learning`

### 🎵 Spotify Music Recommendation System
[`Music-Recommendation-System`](https://github.com/Colin-J-Emmanuel/Music-Recommendation-System)

A hybrid recommendation engine that blends **content-based filtering** (Spotify audio features, genre
vectors) with **collaborative filtering**, using cosine similarity and SVD over a ~250k-track dataset.
Includes a Spotify OAuth flow for pulling real listening data. Built with two teammates at Columbia.

`recommender systems` · `Spotify Web API` · `cosine similarity` · `SVD` · `NumPy/SciPy`

### 🎮 GTA Online Player Analysis
[`gtao-datathon-analysis`](https://github.com/Colin-J-Emmanuel/gtao-datathon-analysis)

An engagement-vs-monetization study of **9,476 GTA Online players** for the Rockstar Games Datathon.
The analysis surfaced a counter-intuitive result — the biggest spenders actually *play less* than
average, pointing to an "efficient achiever" segment — and turned it into concrete monetization
recommendations.

`data analysis` · `pandas` · `statistical testing` · `data visualization`

---

## 🛠️ Skills & Tools

**Languages:** Python, JavaScript, SQL
**ML / Data:** scikit-learn · scikit-survival · XGBoost · Keras / TensorFlow · Optuna · pandas · NumPy · SciPy
**Techniques:** survival analysis · feature engineering · ensembling · probability calibration · hyperparameter optimization · recommender systems · computer vision · NLP
**Practices:** reproducible ML pipelines · cross-validation · Git-based collaboration
**Viz:** Matplotlib · Seaborn · Plotly

---

## 🎯 Background

- **B.S./B.A. Computer Science**, Columbia University
- **Break Through Tech AI Fellowship** (Cornell Tech), completed — ML Foundations + two industry AI Studios (Ursa Space Systems; WiDS Datathon)

---

## 📫 Get in touch

I'm open to opportunities in machine learning and data science.

- 📧 **c.j.emmanuel@columbia.edu**
- 💼 **LinkedIn:** [@Colin J. Emmanuel](https://www.linkedin.com/in/colin-j-emmanuel/)
- 🐙 **GitHub:** [@Colin-J-Emmanuel](https://github.com/Colin-J-Emmanuel)