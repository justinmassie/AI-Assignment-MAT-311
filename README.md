# AI-Assignment-MAT-311
# Credit Card Fraud Detection — Exploratory Data Analysis (EDA)

## 📄 Overview
This project recreates the exploratory data analysis (EDA) portion of the **Credit Card Fraud Detection** notebook presented in class. The goal was to practice using a **Large Language Model (LLM)** to assist in reproducing the analysis **without directly copying** any code, text, or visuals from the original source.

All work up to, but **not including**, the machine learning section ("Can we predict if a transaction is a fraud?") has been completed.  

## 🎯 Objectives
- Recreate and expand on the in-class EDA using my own questions and AI-assisted reasoning.  
- Explore data relationships and visualize transaction characteristics associated with fraudulent activity.  
- Practice healthy, thoughtful AI use in the data analysis workflow as a Christian and mindful learner.

## 🧠 How AI Was Used
This notebook was developed with the assistance of **ChatGPT (GPT-5)** to help:
- Formulate exploratory data analysis (EDA) questions.  
- Generate Python and visualization code snippets.  
- Interpret data relationships and visualize trends efficiently.  

No text, code, or images were copied from the class notebook; all results were generated from scratch through prompt-based exploration.

## 🧮 Dataset Description
The dataset used is `card_transdata`, containing 977 records and 8 columns:

| Column | Description |
|---------|-------------|
| `distance_from_home` | Distance of the transaction from the cardholder’s home |
| `distance_from_last_transaction` | Distance from the previous transaction |
| `ratio_to_median_purchase_price` | Ratio of the transaction amount to the user’s median purchase price |
| `repeat_retailer` | Whether the transaction occurred at a previously visited retailer |
| `used_chip` | Whether a chip was used during the transaction |
| `used_pin_number` | Whether a PIN was used |
| `online_order` | Whether the purchase was made online |
| `fraud` | Binary indicator of fraud (1 = Fraudulent, 0 = Legitimate) |

## 📊 Key Analyses
- **Data Cleaning:** Checked for and dropped missing values.  
- **Univariate Analysis:** Explored distributions of categorical variables such as chip usage, PIN usage, online orders, and fraud labels.  
- **Bivariate Analysis:** Examined relationships between fraud and transaction characteristics through countplots and percentage plots.  
- **Scatter Plot Analysis:** Visualized fraudulent vs. non-fraudulent transactions by `distance_from_home` and `ratio_to_median_purchase_price`.

## 🧩 Insights
- Fraudulent transactions tend to occur more frequently **further from home** and with **higher purchase price ratios**.  
- **Online orders** and transactions **without PIN or chip verification** show higher proportions of fraud.  
- Fraud cases are a minority class, emphasizing the need for careful model balancing in predictive modeling.

## 💭 Reflection
This assignment demonstrated how AI can serve as a **powerful ally** for accelerating analysis and visualization tasks.  
However, it also reinforced the importance of **critical thinking, verification, and independent reasoning** — skills that remain vital both professionally and spiritually.

---

**Author:** [Your Name]  
**Course:** [Course Name, e.g., BUS/SYS 411 – Data Science Applications]  
**Instructor:** [Professor’s Name]  
**Date:** [Submission Date]  

