# Task8-Decision_Tree-Bank-_Marketing_Subscription_Prediction



# Decision Tree – Bank Marketing Subscription Prediction

## Task Description

This task focuses on predicting whether a customer will subscribe to a bank term deposit using a **Decision Tree Classifier**. The model is trained on the **Bank Marketing Dataset** and provides clear, interpretable decision rules that help understand customer behavior.



## Objective

To build a machine learning model that predicts customer subscription (`yes` or `no`) based on demographic details and marketing campaign information, while avoiding overfitting.



## Dataset

* **Source:** Kaggle – Bank Marketing Dataset
* **Format:** Whitespace / Tab separated
* **Target Variable:** `y`

  * `yes` → Customer subscribed
  * `no` → Customer did not subscribe



## Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib



##  Data Preprocessing

* Loaded the dataset successfully without specifying a separator as it is whitespace-separated.
* Replaced missing values represented as `"unknown"` with the mode of the respective columns.
* Converted categorical features into numerical values using **Label Encoding**.
* Split the dataset into **80% training data** and **20% testing data**.



##  Model Information

* **Algorithm:** Decision Tree Classifier
* **Criterion:** Gini Impurity
* **Max Depth:** 4

Limiting the depth of the tree helped reduce overfitting and improved generalization.



##  Model Evaluation

* Evaluated using accuracy score and classification report.
* Compared training and testing accuracy to analyze overfitting.
* Training and testing accuracy values were close, indicating good model performance.



##  Key Decision Rules

* Customers with **longer call durations** are more likely to subscribe.
* Customers contacted via **cellular mode** with fewer campaign contacts show higher success rates.
* Short call durations and unsuccessful previous outcomes indicate a low chance of subscription.



##  Outputs

* Trained Decision Tree model
* Decision Tree visualization
* Classification report
* Evaluation Report (PDF)



## How to Run

1. Clone the repository
2. Install required dependencies:

   ```
   pip install pandas numpy scikit-learn matplotlib
   ```
3. Run the Jupyter Notebook or Python script to train and evaluate the model.



##  Conclusion

The Decision Tree model effectively predicts customer subscription outcomes and provides meaningful, interpretable rules. Its simplicity and transparency make it suitable for business and academic applications.





