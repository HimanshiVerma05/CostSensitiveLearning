### Project Overview:
This repository contains the code and analysis for Assignment 4 of the course CSCI 4146/6409 - Process of Data Science. The assignment is divided into two parts, focusing on:
- **Part A:** Cost-Sensitive Learning on the Statlog (Heart) dataset.
- **Part B:** Handling Class Imbalance in Credit Card Fraud Detection.

### Technologies and Libraries:
The project uses the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `imbalanced-learn`

### Contents:
- **Part A: Cost-Sensitive Learning on Statlog (Heart) Dataset**
  - Data preprocessing and encoding of categorical variables.
  - Implementation of models such as Random Forest, SVC, and Naive Bayes.
  - Application of a custom cost matrix and evaluation based on misclassification costs.
  - Calibration of model probabilities using Isotonic Regression and evaluation using Bayes Minimum Risk Classifier.

- **Part B: Handling Class Imbalance in Credit Card Fraud Detection**
  - Data scaling and analysis of class distribution (fraud vs. non-fraud transactions).
  - Implementation of resampling techniques like SMOTE (oversampling) and NearMiss (undersampling).
  - Evaluation of models using Precision-Recall and ROC curves, focusing on the performance of Random Forest, SVC, and Naive Bayes.
  - Application of the Easy Ensemble Method for further performance improvement.

### Key Results:
- **Part A:**
  - The SVC model had the lowest misclassification cost before calibration.
  - The Naive Bayes model showed the most significant cost improvement after applying the Bayes Minimum Risk Classifier.

- **Part B:**
  - SMOTE improved recall for the minority class (fraud), while NearMiss improved recall but reduced overall model performance.
  - The Easy Ensemble method yielded the best performance in handling class imbalance with strong Precision-Recall and ROC curves.

### Usage:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/assignment4_cost_sensitive_learning.git
    cd assignment4_cost_sensitive_learning
    ```

2. Install the necessary Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook to execute the models and visualize the results.

### File Structure:
- `A4-HimanshiVerma.ipynb`: The Jupyter notebook containing the code for both parts of the assignment.
- `A4-HimanshiVerma.pdf`: The detailed report for Assignment 4.
- `requirements.txt`: Python dependencies required to run the notebook.

### Insights and Conclusion:
The excercies highlights the importance of cost-sensitive learning and methods to handle imbalanced datasets. Techniques like Bayes Minimum Risk Classifier and Easy Ensemble can significantly reduce misclassification costs and improve minority class detection.


