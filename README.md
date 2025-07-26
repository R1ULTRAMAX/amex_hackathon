# 🏦 Amex Campus Challenge 2025 – Offer Personalization

This repository contains the complete solution for the **American Express Campus Challenge 2025**. The task was to build a predictive model that ranks offers shown to customers, estimating the probability that they will click on an offer once it is shown.

> 📎 Kaggle Notebook: [View Solution](https://www.kaggle.com/code/rudrakshkawde/main-amex-main)  
> 📁 Dataset Folder: [Download Data](https://drive.google.com/drive/folders/1c9jFRR5eWorz6JbXQ5RQIa9uFk5o7_lD?usp=sharing)

---

## 🧠 Problem Statement

Given a customer, an offer, and a placement date — predict the **probability of click** conditional on impression (`P(click | impression)`). The goal is to **rank relevant offers higher** to increase customer engagement.

- Evaluation Metric: **MAP@7 (Mean Average Precision at 7)**
- Final submission requires predicting **top 7 ranked offers** for each customer per day.
