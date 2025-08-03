# ANN_Bank_Customer_Retention

This project builds an **Artificial Neural Network (ANN)** to predict customer churn in a bank. By analyzing various customer features, the model classifies whether a customer is likely to leave the bank or not.

## 📌 Project Objective

Predict whether a bank customer will leave the bank, using historical data and a fully connected ANN model built using **Keras** and **TensorFlow**.

## 📂 Dataset

- The dataset includes features such as credit score, geography, gender, age, tenure, balance, number of products, credit card activity, and estimated salary.
- Target variable: `Exited` (1 if the customer left the bank, 0 otherwise).

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn
- TensorFlow, Keras (for building the ANN)

## ⚙️ Data Preprocessing

- Handled categorical features using **Label Encoding** and **One-Hot Encoding**
- Feature Scaling using **StandardScaler**
- Train-test split with 80:20 ratio

## 🧠 Model Architecture

A **Sequential Artificial Neural Network** with the following structure:

| Layer        | Units | Activation Function |
|--------------|-------|---------------------|
| Input Layer  | 11    | -                   |
| Hidden Layer 1 | 6     | ReLU                |
| Hidden Layer 2 | 6     | ReLU                |
| Output Layer | 1     | Sigmoid             |

- Optimizer: **Adam**
- Loss Function: **Binary Crossentropy**
- Evaluation Metric: **Accuracy**

## 🔁 Model Training

- **Epochs:** 100  
- **Batch Size:** 32  
- Trained using `model.fit()` on the training dataset.

## 📊 Evaluation

- Accuracy, Confusion Matrix, and Classification Report were used to evaluate the model.
- The model achieved competitive accuracy in predicting customer churn.

## 🔍 Key Insights

- ANN performs well in binary classification of churned customers.
- Feature scaling and categorical encoding significantly affect model performance.

## 📈 Results

- The model was able to predict customer retention with high accuracy on unseen data.
- Demonstrated effective use of ANN for a business classification problem.

---
## Thank You
---

