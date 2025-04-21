# 📊 Digital Marketing Campaign Analysis

A comprehensive end-to-end project for analyzing, modeling, and visualizing a digital marketing campaign using synthetic and real-world inspired data. This includes A/B testing, conversion funnel analysis, customer segmentation, channel attribution, and predictive modeling.

---

## 🔧 Project Structure

This project covers:

- **Synthetic Data Generation**
- **Exploratory Data Analysis (EDA)**
- **A/B Testing**
- **Conversion Funnel Drop-off Analysis**
- **Customer Lifetime Value (CLV) Analysis**
- **Segmentation (CLV, Engagement, Loyalty)**
- **Attribution Modeling**
- **Machine Learning (Random Forest Classifier)**
- **Feature Importance**
- **Evaluation Metrics**

---

## 🧾 Dataset

The dataset `digital_marketing_campaign_dataset.csv` includes fields such as:

- Customer demographics
- Ad performance metrics
- Engagement behaviors
- Campaign metadata
- Conversion status

Additional synthetic columns were added:
- `Funnel Variant` (A/B Test)
- `Stage 1-5 Conversion`
- `CLV (Customer Lifetime Value)`

---

## 🚀 Getting Started

## Results & Insights
Overall Accuracy: ~87.6%

No statistically significant difference between Funnel A and B

Drop-off rates increase sharply by funnel stage

Behavioral metrics (e.g., ClickThroughRate, TimeOnSite) are most predictive

AUC score of 0.82 from Random Forest Classifier

Strong CLV segmentation: High/Medium/Low Value Customers

Attribution shows SocialShares are the most influential channel

Engagement & Loyalty segmentation allows hyper-targete

## Machine Learning Model
Model: Random Forest Classifier
Input Features: All customer and campaign-related features

Target: Conversion

Evaluation:

Accuracy: ~88%

AUC Score: 0.82

Confusion matrix highlights class imbalance

Feature Importance: PagesPerVisit, TimeOnSite, and ClickThroughRate ranked high

## Visualizations
Conversion funnel drop-off chart

Conversion rate comparisons (Funnel A vs B)

CLV & engagement segment distributions

Channel attribution bar chart

Feature importance plot

Confusion matrix & ROC curve

## Potential Enhancements
Address class imbalance using SMOTE or other techniques

Apply advanced attribution modeling (e.g., Markov Chains, Uplift Modeling)

Predict CLV using regression models

Implement behavioral clustering (K-Means, DBSCAN)

Develop Streamlit or Dash dashboard for stakeholders

##  🤝 Contributing
Feel free to fork the repo, submit PRs, or open issues for discussion!


🔗 Connect with Me
📧 Email: satyam@buffalo.edu
💼 LinkedIn: https://www.linkedin.com/in/sattytough17/

