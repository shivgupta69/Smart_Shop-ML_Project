Smart Shop ML

Customer Purchase Prediction using Machine Learning

Python 3.9+ | Scikit-Learn | Status: Completed | License: MIT

⸻

Overview

Smart Shop ML is a machine learning project that predicts whether a user will make a purchase based on their online browsing behavior.

By analyzing session-level data such as page visits, time spent, and user attributes, this model helps identify high-intent customers, enabling businesses to improve conversion rates and optimize marketing strategies.

⸻

Problem Statement

In e-commerce, most users browse but do not complete a purchase. This creates a key challenge: identifying users who are most likely to convert.

This project addresses the problem by building a binary classification model that predicts whether a user session will result in a purchase (Revenue = True or False).

⸻

Business Impact
	•	Helps target high-value customers
	•	Improves conversion rates
	•	Optimizes marketing spend
	•	Supports data-driven decision making

⸻

Dataset Overview

The dataset contains user session data from an online shopping platform. It includes both numerical and categorical features such as:
	•	Page interaction metrics including administrative, informational, and product-related visits
	•	Time spent on different types of pages
	•	Bounce rates and exit rates
	•	Traffic source and visitor type
	•	Weekend or session-based indicators

The target variable is Revenue, which indicates whether a session resulted in a purchase.

⸻

Project Workflow

Data Exploration

Initial analysis was conducted to understand the dataset, including structure, distributions, and target variable balance. This step helped identify patterns and potential issues in the data.

Data Preprocessing

Numerical features were scaled to normalize distributions, while categorical features were encoded for compatibility with machine learning models. A pipeline was built using a ColumnTransformer to ensure a clean and reproducible workflow.

Model Building

A Decision Tree model was trained to classify whether a session would generate revenue. The dataset was split into training and testing sets to evaluate model performance on unseen data.

Model Evaluation

The model was evaluated using F1 score, precision, recall, and a classification report. These metrics were chosen to balance false positives and false negatives, which is important for business decision-making.

Hyperparameter Tuning

Grid search was applied to optimize model parameters and improve performance. This step helped enhance the model’s ability to generalize to new data.

⸻

Results

The model successfully captures patterns in user behavior and predicts purchase intent with reasonable accuracy. It demonstrates practical value for applications such as targeted marketing and customer segmentation.

⸻

Key Learnings
	•	Importance of structured data preprocessing and pipelines
	•	Handling mixed data types effectively
	•	Understanding evaluation metrics and trade-offs
	•	Applying machine learning to real-world business problems

⸻

Future Improvements
	•	Use advanced models such as Random Forest, XGBoost, or LightGBM
	•	Perform deeper feature engineering
	•	Address class imbalance using techniques like SMOTE or class weighting
	•	Deploy the model as a web application for real-time predictions

⸻

How to Run

Clone the repository, install dependencies using the requirements file, and run the Jupyter notebook to reproduce the results.

⸻

⸻

Why This Project Stands Out
	•	Uses an industry-standard machine learning pipeline
	•	Focuses on a real-world business problem
	•	Maintains a clean and scalable project structure
	•	Demonstrates an end-to-end machine learning workflow

⸻

Conclusion

This project demonstrates how machine learning can be applied to predict customer purchase behavior and drive business decisions. It reflects a structured and practical approach to solving real-world problems using data.

⸻
