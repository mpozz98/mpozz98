

# Hi, I'm Giorgos Stefanidis 👋

**Business & Data Analyst** — turning customer, pricing and behavioural data into decisions
people can act on.

Business Administration graduate from **AUEB** (Accounting & Finance), with machine learning
training through AUEB's AI Data Factory bootcamp and a year of client-facing commercial
experience in Athens real estate.

That combination is the point: I read a business question before I open a notebook, and I say
plainly what the data does and does not support.

📍 Athens, Greece
📫 **[giorgstefanidis@gmail.com](mailto:giorgstefanidis@gmail.com)** ·
**[LinkedIn](https://www.linkedin.com/in/georgios-stefanidis-a00a392b5)**

---

## What I'm looking for

Junior **Business Analyst / Data Analyst** roles where the job is to answer a business
question with data. Strongest fit: **banking and credit risk, customer & CRM analytics,
pricing and real estate analytics** — the domains my background and projects already cover.

---

## Featured projects

### 🏦 [Bank Customer Churn — and a Lesson in Target Leakage](https://github.com/mpozz98/bank-customer-churn-analysis)
Gradient boosting scored 0.646 ROC-AUC on 2,996 banking customers. Logistic regression scored
0.502. That gap was the clue: the cleaning step had imputed missing values with a
**target-grouped mean**, writing the answer into 13% of the rows. Corrected, the score fell to
0.527 — these features do not predict churn. The honest answer, and the reasoning that found it.
`pandas` · `scikit-learn` · target leakage · cross-validation

### 🏠 [House Price Prediction — Ensemble & Boosting Models](https://github.com/mpozz98/house-price-prediction)
Predicting sale prices from 79 property features. Six models benchmarked against a dummy
baseline with 5-fold CV; **Gradient Boosting won at RMSLE 0.1239**. Includes permutation
importance, residual analysis showing exactly where the model becomes unreliable, and a written
report. Built on a year of working in the property market.
`scikit-learn` · `xgboost` · pipelines · RMSLE

### 🗄️ [SQL Data Analysis](https://github.com/mpozz98/sql-data-analysis)
Data cleaning and exploratory analysis in SQL across US income and global life expectancy
datasets, plus an Excel-based US debt tracker. Window functions, CTEs, aggregation and joins on
messy real-world data.
`SQL` · `Excel` · data cleaning · EDA

### 🎯 [Customer Segmentation with K-Means](https://github.com/mpozz98/customer-segmentation)
Six actionable customer segments from age, income and spending score, with `k` chosen by
silhouette rather than by eye. Two segments — 32% of the base — drive the highest spending; the
largest tier is where upsell has room to move.
`scikit-learn` · clustering · marketing analytics

### 🎬 [Movie Recommender System](https://github.com/mpozz98/movie-recommender-system)
Matrix factorisation with SGD written from scratch on 1M MovieLens ratings — **test RMSE 0.911**
on a temporal hold-out. Includes a cold-start design for users with no history, and a Bayesian
volume correction that reversed the genre ranking completely.
`numpy` · `pandas` · matrix factorisation · cold start

### 💬 [Airline Sentiment — BiLSTM vs DistilBERT](https://github.com/mpozz98/airline-sentiment-analysis)
The same task twice: a BiLSTM with attention built from scratch (**75.3%**) and a fine-tuned
DistilBERT (**80.6%**), on an identical split so the comparison holds. The gain is largest on the
rarest class — exactly what transfer learning is supposed to buy.
`pytorch` · `transformers` · NLP

<sub>Also: [Document Clustering — TF-IDF vs Word2Vec](https://github.com/mpozz98/document-clustering) ·
unsupervised topic grouping where the better representation reverses between datasets.</sub>

---

## Toolkit

**Data & BI** · SQL · Excel · Power BI · Tableau
**Python** · pandas · NumPy · scikit-learn · XGBoost · PyTorch · Transformers
**Methods** · regression · classification · clustering · recommender systems · NLP
**Practice** · cross-validation · leakage detection · pipelines · baseline-first evaluation
**Communication** · written analysis reports · matplotlib / seaborn

---

## How I work

**Baselines first.** A dummy model and a linear model go in before anything complex. Without
them a score is a number with nothing to compare it to — and in the churn project, they are what
exposed a result that looked good and was not.

**Preprocessing belongs in the pipeline.** Imputers, scalers and encoders fitted outside the
cross-validation split leak information and inflate scores.

**Report what the data supports.** Two of the projects here end in a negative result. Both say
so and explain why, because a conclusion that will not survive contact with production is worth
less than no conclusion at all.

---

## Background

**AI Data Factory — ML & Data Analysis Bootcamp**, AUEB · Oct 2025 – Apr 2026
**BSc Business Administration** (Accounting & Finance), AUEB
**Real Estate Consultant & Assistant Sales Manager**, Golden Home Real Estate · 2024 – 2025

English — Proficient (Michigan ECPE)
