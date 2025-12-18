# 💗 Chasslayy Luxe — Customer Purchase Propensity Using IBM Watson AutoAI

## 📌 Project Overview

This project explores how **Responsible AI** can be applied to a real-world beauty and lifestyle business, **Chasslayy Luxe**, to better understand customer behavior and support data-informed decision making.

Using **IBM Watson Studio and AutoAI**, this project builds a **binary classification model** that predicts whether a customer interaction is likely to result in a purchase. The project prioritizes **privacy, fairness, transparency, and explainability** by intentionally avoiding personal or sensitive information.

---

## 🎯 Business Problem

Small beauty brands often rely on intuition when deciding how to market products, design content strategies, and allocate promotional resources. This project investigates whether machine learning can help answer the following question:

> **Which customer interactions are most likely to result in a purchase—without using personal or sensitive data?**

---

## 🧠 AI Task

- **Prediction Type:** Binary Classification  
- **Target Variable:** `purchase_made`  
  - `1` → Purchase made  
  - `0` → No purchase  

IBM **AutoAI** is used to automatically:
- perform feature engineering  
- train multiple algorithms  
- evaluate performance  
- select the best-performing model  

---

## 📊 Dataset Description

The dataset represents **anonymized and behavior-based customer interactions**.  
No personal information (PI) or sensitive personal information (SPI) is included.

### Features Used
- `sessions_last_30d` — Number of sessions in the last 30 days  
- `engagement_level` — Low / Medium / High engagement  
- `product_category_viewed` — Wig / Beauty / Digital  
- `discount_used` — Whether a discount was used (0/1)  
- `days_since_last_interaction` — Time since last interaction  
- `prior_purchases` — Number of previous purchases  
- `avg_order_value_bucket` — Low / Medium / High  
- `traffic_source` — Instagram, TikTok, Pinterest, Direct, Other  

### Label
- `purchase_made` — Whether a purchase occurred (0/1)

> ⚠️ **Note:**  
> For portfolio purposes, a **synthetic dataset** was generated to simulate realistic business behavior. This ensures privacy while still demonstrating an end-to-end AI workflow.

---

## 🛠️ Tools & Technologies

- **IBM Watson Studio**
- **IBM AutoAI**
- **Python**
- **Pandas / NumPy**
- **Scikit-learn**
- **Google Colab**

---

## ▶️ Project Workflow

1. Design a **privacy-safe dataset schema**
2. Generate or load anonymized interaction data
3. Upload dataset to **IBM Watson Studio**
4. Create an **AutoAI experiment**
5. Train multiple models automatically
6. Evaluate using:
   - Accuracy
   - Confusion Matrix
   - Feature Importance
7. Analyze results through a **Responsible AI lens**

---

## 🛡️ Responsible AI Considerations

This project explicitly applies Responsible AI principles:

- **Privacy**  
  - No personal or sensitive attributes collected  
  - Data minimization applied  

- **Fairness**  
  - Model performance evaluated across non-protected segments  

- **Explainability**  
  - Feature importance used to understand predictions  

- **Transparency**  
  - Clear documentation of data sources, assumptions, and limitations  

---

## 📦 Repository Structure


---
You simply say:

“Although IBM AutoAI was initially considered, model training and evaluation were conducted locally using scikit-learn due to access constraints. This approach allowed full transparency and control over model selection and evaluation metrics.”

## 📈 Key Takeaways

- Behavior-based features can meaningfully predict purchase likelihood  
- AutoAI accelerates experimentation and model comparison  
- Responsible AI practices can be applied without sacrificing business value  

---

## 👩🏽‍💻 Author

**Chastity Lewis**  
Founder, Chasslayy Luxe  
Graduate Student — Computer Vision & Machine Learning  

🔗 GitHub: https://github.com/chasslayy  
🔗 LinkedIn: https://www.linkedin.com/in/chasslayy  

---

## 📜 License

This project is for **educational and portfolio purposes**.  
No real customer data was used.
