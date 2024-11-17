# Classifiers
Comparing Classifiers

**Understanding of the business problem**
Evaluation and comparison of the performance of four classifiers: K-Nearest Neighbors (KNN), Logistic Regression, Decision Trees, and Support Vector Machines (SVM) to predict whether a client subscribes based on marketing campaign data from a Portuguese bank. The dataset includes customer attributes, marketing interaction details, and external socioeconomic factors. Accurate predictions can optimize targeting strategies, improve conversion rates, and reduce marketing costs.

**Interpretation of Descriptive and Inferential Statistics**

Dataset:
- Target Variable: y (yes/no indicating subscription).
- Features: Demographics (e.g., age, job, marital status), campaign details (e.g., last contact duration), and external factors (e.g., economic indicators).
- Distribution: The dataset is imbalanced, with significantly more no responses than yes

Preprocessing:
- Encoding categorical variables (one-hot or label encoding).
- Normalizing numeric features for KNN and SVM
- Splitting into training (80%) and testing (20%)

Model Evaluation and Comparision using Scores:
- Accuracy: Overall performance, though not reliable for imbalanced data.
- Precision, Recall, F1-Score: Focus on yes predictions due to imbalance.
- ROC-AUC: Measures the trade-off between true positive rate and false positive rate.

Results:
- Best Model: Logistic Regression achieved the highest accuracy and ROC-AUC, balancing precision and recall effectively.
- SVM: Performs well with similar scores to Logistic Regression.
- Decision Trees: Prone to overfitting, if no max depth specified.
- KNN: Performance drops likely due to sensitivity to imbalanced data.

Actionable Insights:
- Improve Marketing Campaigns: Focus on high-duration contacts and specific job types as positively correlated with subscriptions
- Resource Allocation: Prioritize customers predicted as yes with high confidence to maximize ROI
- Improvements: Add additional external factors like competitor activity or broader economic indicators.

Next Steps and Recommendations
- Fine-Tune Models
- Deployment
- Continuous Improvement

  ![image](https://github.com/user-attachments/assets/6a167323-b887-4e12-88bd-fc642618001c)

  ![image](https://github.com/user-attachments/assets/ceea934b-dae4-44af-8edd-f09ca9e62c48)

