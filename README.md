## Customer_Behaviour_Prediction
A comprehensive evaluation using Hybrid Models for customer purchase behavior prediction.

### Overview
This project evaluates the performance of hybrid models for predicting customer purchase behavior. It includes:
- Data Visualization
- Data Preprocessing
- Model Implementation:
    - Traditional models: SVM, KNN, and Naive Bayes.
    - Hybrid models: Combining the strengths of multiple algorithms.
- Evaluation:
    - Performance metrics (e.g., accuracy, precision, recall).
    - ROC and AUC curves for model comparison.

### Dataset Description

Dataset: [Predict Customer Purchase Behavior Dataset](https://www.kaggle.com/datasets/rabieelkharoua/predict-customer-purchase-behavior-dataset/code)

The dataset contains 1,500 instances with 9 features, capturing demographic information, purchasing habits, and other customer-related attributes.

- Age - Customer's age. 
- Gender - Customer's gender.
- Annual Income - Annual income of the customer in dollars.
- Number of Purchases - Total number of purchases made by the customer.
- Product Category - Category of the purchased product (0: Electronics, 1: Clothing, 2: Home Goods, 3: Beauty, 4: Sports)
- Time Spent on Website - Time spent by the customer on the website in minutes
- Loyalty Program - Whether the customer is a member of the loyalty program (0: No, 1: Yes)
- Discounts Availed - Number of discounts availed by the customer (range: 0-5)
- Purchase Status (Target Variable) - Likelihood of the customer making a purchase (0: No (48%), 1: Yes (52%))

### Technologies Used
- Python
- Scikit-learn
- Pandas
- Numpy
- Matplotlib/Seaborn

### How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CustomerBehaviorPrediction.git
2. Navigate to the Project Directory:
   ```bash
   cd CustomerBehaviorPrediction
3. Open .ipynb file in Google Colab or Jupyter Notebook.