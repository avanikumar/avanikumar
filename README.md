<div align="center">

# Avani Kumar

**B.tech in Electronics and Communication Engineering | Gujarat Technological University**

<a href="https://linkedin.com/in/avxnikumar"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/avanikumar"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
<a href="mailto:avani.rkumar5@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>

</div>

---

## About

Undergraduate in Electronics and Communication Engineering at **Gujarat Technological University**, focused on machine learning engineering from data preprocessing and model selection to building explainable, deployable ML systems. I care about writing ML code that's structured, interpretable, and ready to ship, not just accurate in a notebook.

Open to **Machine Learning internships**, **Data Science roles**, and **applied AI positions** in predictive analytics and MLOps.

---

## Focus Areas

- Supervised learning: decision trees, random forests, gradient boosting (XGBoost, LightGBM, CatBoost)
- End-to-end ML pipelines: from feature engineering to model deployment
- Model explainability using SHAP for non-technical stakeholder reporting
- Applied AI on Microsoft Azure: cloud fundamentals, administration, and generative AI
- MLOps: experiment tracking, API deployment, and lightweight dashboards

---

## Featured Projects

### <a href="https://github.com/avanikumar/CHURN-REPO-NAME"><u>Customer Churn Intelligence Platform</u></a> &nbsp;<img src="https://img.shields.io/badge/July%202026-f5f5f5?style=flat-square&logoColor=333"/>

End-to-end churn prediction platform that goes beyond prediction to prescriptive retention strategy.

- Architected an end-to-end platform that predicts churn risk using **LightGBM** and **CatBoost**, generates **SHAP-based** explanations, and produces **LLM-driven** recommendations
- Used **SHAP** to identify the key reasons behind each customer's churn risk (e.g. drop in usage, inactivity, support complaints), making results understandable to non-technical users
- Created a simple dashboard/API using **FastAPI** and **Streamlit** to display churn predictions and suggested retention actions

<img src="https://img.shields.io/badge/Python-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/LightGBM-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/CatBoost-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/SHAP-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/FastAPI-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/Streamlit-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/Docker-f5f5f5?style=flat-square&logoColor=333"/>

---

### <a href="https://github.com/avanikumar/sycophancy-eval-mini"><u>Sycophancy and Steering Resistance Replication</u></a> &nbsp;<img src="https://img.shields.io/badge/July%202026%20--%20August%202026-f5f5f5?style=flat-square&logoColor=333"/>

Replication of Anthropic's "are-you-sure" sycophancy test, connecting behavioral results to interpretability research.

- Replicated the test on **22 coding questions** across Claude and ChatGPT, measuring how often models reverse correct answers under social pushback
- Found Claude reversed **1/22** answers and ChatGPT **0/22**, contrasting sharply with the **95%** reversal rate reported for Claude 1.3 in the original 2023 study, suggesting robustness to behavioral pressure has increased substantially
- Connected findings to Anthropic's "Steering Resistance" interpretability work, proposing that mechanistic self-correction circuits may correlate with behavioral robustness to social pressure

<img src="https://img.shields.io/badge/Python-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/OpenAI%20API-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/Anthropic%20API-f5f5f5?style=flat-square&logoColor=333"/>

---

### <a href="https://github.com/avanikumar/minirobust-lm"><u>MiniRobust-LM: Adversarially Robust Compact LLM</u></a> &nbsp;<img src="https://img.shields.io/badge/Sept%202026%20--%20Present-f5f5f5?style=flat-square&logoColor=333"/>

Compact, adversarially hardened language model built to stay small, fast, and resistant to attacks.

- Fine-tuning **Mistral-1B** with **LoRA** on instruction data, applying adversarial robustness training via **PGD** and **TextFooler** attacks to harden the model against prompt injection and jailbreaks
- Applying **GPTQ 4-bit quantization** targeting **<500MB** model size while maintaining **<5% accuracy drop** on MMLU, using bitsandbytes and auto-gptq
- Training a **ResNet-18** classifier from scratch on CIFAR-10 with PGD adversarial training, measuring the clean vs robust accuracy tradeoff and resolving loss spikes, overfitting, and slow convergence, with full experiment tracking via Weights & Biases

<img src="https://img.shields.io/badge/PyTorch-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/HuggingFace%20PEFT-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/bitsandbytes-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/TextAttack-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/Weights%20%26%20Biases-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/lm--evaluation--harness-f5f5f5?style=flat-square&logoColor=333"/>

---

### <a href="https://github.com/avanikumar/backbone-sycophancy-eval"><u>Backbone-Sycophancy Evaluation Toolkit</u></a> &nbsp;<img src="https://img.shields.io/badge/October%202026-f5f5f5?style=flat-square&logoColor=333"/>

Async Python CLI that measures how often LLMs abandon correct answers under user pushback; extends my earlier "are-you-sure" replication.

- Built an **async Python CLI** tracking **flip rate** and accuracy under leading and multi-turn challenges
- Implemented **disk-based response caching** keyed by model, prompt and parameters, **retry with exponential backoff**, and **concurrency limiting** to make experiments fast, cheap and reproducible
- Wrote **unit tests** with a mocked model provider and set up **GitHub Actions CI** to run them on every push
- Ran a 22-question pilot on **gpt-oss-20b**: 1 of 21 correct answers flipped under pushback at baseline vs 0 of 22 with a system-prompt mitigation (within noise); audited graded outputs by hand and fixed a grader bug

<img src="https://img.shields.io/badge/Python-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/Asyncio-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/Pytest-f5f5f5?style=flat-square&logoColor=333"/> <img src="https://img.shields.io/badge/GitHub%20Actions-f5f5f5?style=flat-square&logoColor=333"/>

---

## Tech Stack

**Languages**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white"/>

**ML / DL**

<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/XGBoost-1a1a1a?style=flat-square"/> <img src="https://img.shields.io/badge/LightGBM-2E7D32?style=flat-square"/> <img src="https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square"/> <img src="https://img.shields.io/badge/SHAP-4C1D95?style=flat-square"/>

**Tools and Infrastructure**

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white"/>

---

## Certifications

<img src="https://img.shields.io/badge/Microsoft%20Azure-Cloud%20%26%20AI%20Fundamentals-0089D6?style=flat-square&logo=microsoftazure&logoColor=white"/>



## Contact

<a href="mailto:avani.rkumar5@gmail.com"><img src="https://img.shields.io/badge/Email-avani.rkumar5%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/></a> <a href="https://linkedin.com/in/avxnikumar"><img src="https://img.shields.io/badge/LinkedIn-avxnikumar-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>

---

<div align="center">

*B.tech in Electronics and Communication Engineering | Gujarat Technological University | Batch of 2027*

</div>
