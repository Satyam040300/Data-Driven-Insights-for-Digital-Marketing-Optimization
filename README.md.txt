Data-Driven Insights for Digital Marketing Optimization
📌 Project Overview
This project analyzes a digital marketing campaign dataset to optimize lead conversion, identify funnel bottlenecks, and predict customer lifetime value (CLV). By leveraging machine learning models, A/B testing, and funnel analysis, this project provides actionable insights for data-driven marketing decisions.

📊 Key Features
Lead Conversion Prediction: Trained a Random Forest Classifier to predict conversion likelihood based on campaign attributes.
A/B Testing Simulation: Simulated two funnel variations (A & B) and used statistical analysis to measure performance differences.
Funnel Bottleneck Analysis: Simulated a 5-stage funnel, visualized drop-off rates, and calculated the overall conversion rate.
Customer Lifetime Value (CLV) Prediction: Built a Linear Regression model to predict CLV and identify high-value leads.
Feature Importance Analysis: Identified key features influencing lead conversion using feature importance from the Random Forest model.
🛠️ Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SciPy)
Machine Learning Models: Random Forest Classifier, Linear Regression
Statistical Analysis: A/B Testing with t-tests
Data Visualization: Seaborn & Matplotlib for heatmaps, bar plots, and scatter plots
📂 Project Structure
├── data/ # Dataset files
│ ├── satyam_digital_marketing_campaign_dataset.csv
├── notebooks/ # Jupyter notebooks for EDA & modeling
├── src/ # Source code for modeling & analysis
│ ├── data_preprocessing.py # Data cleaning & preprocessing scripts
│ ├── model_training.py # ML models (Random Forest, Linear Regression)
│ ├── ab_testing.py # A/B test simulation
│ ├── funnel_analysis.py # Funnel stage drop-off calculations
│ ├── clv_prediction.py # Customer Lifetime Value analysis
├── README.md # Project documentation
├── requirements.txt # Python dependencies
🚀 Installation & Usage
Clone the repository
git clone https://github.com/yourusername/digital-marketing-analytics.git
cd digital-marketing-analytics
Create a virtual environment & install dependencies
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
Run the scripts
python src/model_training.py
📈 Results & Insights
Lead Conversion Model: Achieved accurate classification of potential conversions.
A/B Testing: Funnel B showed a higher conversion rate, validated by a statistical test.
Bottleneck Analysis: Identified major drop-offs in specific funnel stages.
CLV Prediction: Determined high-value customers for optimized marketing spend.
💡 Future Enhancements
Implement hyperparameter tuning for model performance improvement.
Explore alternative CLV models (e.g., Gamma-Gamma Model, RFM Segmentation).
Integrate real-world marketing campaign data for further validation.
🤝 Contributing
Feel free to fork the repo, submit PRs, or open issues for discussion!

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.


🔗 Connect with Me
📧 Email: your.email@example.com
💼 LinkedIn: Your LinkedIn Profile