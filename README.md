# G'day, I'm Llani 👋

### Junior Software Engineer with a data and machine-learning focus

Career changer with 8 years’ experience across quantitative finance, credit risk analysis and lending, including banker/relationship manager roles at CBA, NAB and Westpac, plus specialist property finance lenders in London.

I’m now focused on software engineering, with a particular interest in AI/ML and data engineering, underpinned by a BSc in Statistics with distinction-level results.

---

## Core Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/DRF-red?style=flat)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## What I Build

| Area | Focus |
|---|---|
| **Software Engineering** | Full-stack applications, REST APIs, authentication, CRUD workflows, deployment |
| **Data Engineering** | Python API extraction, ETL-style pipelines, data cleaning, validation, schema design |
| **Machine Learning** | pandas, scikit-learn, feature engineering, cross-validation, model comparison |
| **Finance / Analytics** | Credit risk, lending, financial analysis, risk modelling, decision support |

---

## Featured Projects

### CV Generator — Django REST Framework, React, PostgreSQL

Full-stack CV builder with a React frontend, Django REST Framework API, PostgreSQL database, Google OAuth, live preview and PDF export.

**Highlights**
- Built authenticated save/reload workflows with Google OAuth, deployed across Vercel and Render
- Designed a normalised relational model: `CV → Section → Entry → Bullet`
- Implemented nested writable DRF serializers for deeply nested form data
- Used React state management, controlled inputs and live preview rendering
- Built a prompt-based AI import feature to map unstructured CV content into typed JSON and populate the full form

**Tech:** Python · Django REST Framework · React · PostgreSQL · Google OAuth · Vercel · Render

[GitHub](https://github.com/llani-rainey/odin_cv_generator) · [Live Demo](https://odin-cv-generator-iota.vercel.app/)

---

### Retailer API Data Pipeline (GAIA) — Python

Python pipeline extracting, cleaning and normalising product, price, pack-size and nutrition data from major UK grocery retailers.

**Highlights**
- Built API-based extractors for Tesco, Sainsbury’s, Ocado, Morrisons, Iceland and ASDA
- Normalised 150k+ product records into a single structured schema
- Cleaned inconsistent data including units, pack sizes, calories and multipack formats
- Added retries, backoff and structured logging for more reliable extraction
- Produced analysis-ready CSV outputs for downstream querying and comparison

**Tech:** Python · APIs · ETL-style processing · pandas · CSV/JSON · logging

[GitHub](https://github.com/llani-rainey/retailer-api-pipeline-demo)

---

### Titanic Survival Prediction — Python, scikit-learn

End-to-end supervised classification project focused on reproducible ML workflow design, feature engineering and model evaluation.

**Highlights**
- Performed raw data audit, EDA and feature engineering
- Built leakage-safe preprocessing and custom sklearn pipeline components
- Compared Logistic Regression, Random Forest, Gradient Boosting, XGBoost and LightGBM
- Used stratified cross-validation, GridSearchCV and soft-voting ensembles
- Generated a final Kaggle submission from a reproducible workflow

**Tech:** Python · pandas · scikit-learn · XGBoost · LightGBM · Jupyter

[GitHub](https://github.com/llani-rainey/Titanic-Survival-Prediction)

### NeetCode to Prompt — Python Workflow Automator

Cross-platform Python utility that turns a copied NeetCode problem URL into a clean, structured ChatGPT prompt, including the problem statement, examples and starter code.

**Highlights**
- Integrated with NeetCode’s backend API using authenticated POST requests
- Parsed and cleaned problem HTML with BeautifulSoup, removing noisy sections such as hints, topics and company tags
- Normalised starter code so Python prompts remain runnable and correctly formatted
- Automated clipboard input/output with pyperclip for a faster coding-practice workflow
- Added optional hotkey automation using AutoHotkey on Windows and Hammerspoon on macOS

**Tech:** Python · Requests · BeautifulSoup · pyperclip · dotenv · AutoHotkey · Hammerspoon

[GitHub](https://github.com/llani-rainey/Neetcode-to-prompt)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/llanirainey/) · [GitHub](https://github.com/llani-rainey) 
