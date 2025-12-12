# Policy Optimization for Financial Decision Making – LendingClub Project

## 📌 Overview

This project applies Machine Learning and Offline Reinforcement Learning (RL) to improve the loan approval strategy for a fintech company using LendingClub accepted loan data (2007–2018).

We build and compare two approaches:

1. **Supervised Deep Learning Model** (PyTorch MLP predicting default probability)
2. **Offline RL-Style Policy** (profit-based policy + fallback behavior cloning)

Goal: **maximize expected financial return** while reducing loan default risk.

---

## 📂 Project Structure
📦 ShodhAI_Loan_Policy_Project  
├── 📓 notebooks  
│   └── 📘 01_data_and_first_model.ipynb  
│  
├── 📊 results  
│   └── 📄 disagreement_examples_top200.csv  
│  
├── 📄 requirements.txt  
├── 📄 README.md  
├── 🧹 .gitignore  
└── 📂 data  (dataset stored locally, not uploaded)
