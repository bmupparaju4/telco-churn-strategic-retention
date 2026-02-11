Strategic Retention: Predicting Telecom Customer Churn
📌 Project Overview
In the telecommunications industry, acquisition costs are 5x to 25x higher than retention costs. This project implements a machine learning pipeline to transition from reactive customer service to proactive retention. Using a Random Forest Classifier and SMOTE for class balancing, this model identifies at-risk customers with a 71% recall rate, specifically highlighting a high-value "VIP at Risk" segment for prioritized intervention.

🚀 Key Features
Data Engineering: Automated cleaning of numeric types and one-hot encoding for categorical variables.

Class Imbalance Solution: Implemented SMOTE (Synthetic Minority Over-sampling Technique) to balance the training set, increasing the model's ability to catch churners from 40% to 71%.

Strategic Segmentation: Developed a Risk-Value Quadrant to categorize customers by both churn probability and monthly revenue.

Business Insights: Identified "Payment Friction" (Electronic Checks) and "Bill Fatigue" (Total Charges) as primary psychological drivers of churn.

📊 Results & Metrics
Accuracy: 79.27%

Recall (Churn Class): 71% (High capture rate for at-risk customers)

Top Predictors: Tenure, Total Charges, and Electronic Check Payment Method.

🛠️ Tech Stack
Language: Python 3.x

Libraries: * pandas, numpy (Data Manipulation)

matplotlib, seaborn (Visualization)

scikit-learn (Machine Learning)

imblearn (SMOTE)

📁 Repository Structure
Strategic_Retention_Analysis.py: The complete Python pipeline from data loading to visualization.

WA_Fn-UseC_-Telco-Customer-Churn.csv: The raw dataset (IBM Telco Churn).

White_Paper_Final.pdf: The comprehensive technical and strategic report.

Figures/: Contains the generated Heatmap, Feature Importance, and Risk Quadrant plots.

📉 Strategic Recommendations
Targeted VIP Outreach: Proactive retention for the 400 identified "VIPs at Risk."

Friction Reduction: Incentivize customers to switch from Electronic Checks to Credit Card Autopay.

Contract Migration: Convert high-risk month-to-month users to 1-year contracts to reduce churn probability by ~90%.

📝 How to Use
Clone the repository:

Bash
git clone https://github.com/YOUR_USERNAME/telco-churn-strategic-retention.git
Install dependencies:

Bash
pip install pandas scikit-learn imbalanced-learn seaborn matplotlib
Run the analysis:

Bash
python Strategic_Retention_Analysis.py
👤 Author
Balakrishna Mupparaju DSC680 Applied Data Science
