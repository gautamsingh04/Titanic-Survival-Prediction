# 🚢 Passenger Survival Prediction using Machine Learning

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster, using data from the famous Kaggle Titanic dataset.

## 📌 Overview

Using Python and popular data science libraries (like pandas, seaborn, and scikit-learn), this notebook walks through:

- Loading and exploring the dataset  
- Handling missing values  
- Feature selection and preprocessing  
- Model training using **Logistic Regression**
- Evaluating model performance

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 📊 Dataset

The dataset used is the Titanic training dataset from Kaggle:  
[https://www.kaggle.com/competitions/titanic](https://www.kaggle.com/competitions/titanic)

Make sure to download `train.csv` and place it in the same directory as the notebook or update the path accordingly.

## 🧪 Model

The project uses **Logistic Regression** to classify whether a passenger survived based on features such as:

- Passenger class (`Pclass`)
- Sex
- Age
- Number of siblings/spouses aboard
- Fare, etc.

## 📈 Accuracy

The model’s accuracy is computed using `accuracy_score` from scikit-learn after testing on a split dataset (training/testing via `train_test_split`).

---

## 🔧 How to Run

## 1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction

```

## 2. Install the required libraries:

```bash
pip install -r requirements.txt
Run the notebook:
```

```bash
jupyter notebook Passenger_Survival_Prediction_using_Machine_Learning.ipynb
```

## 3.📂 Project Structure

```bash
├── Passenger_Survival_Prediction_using_Machine_Learning.ipynb
├── train.csv
└── README.md
```
## 4.🤝 Contributing
Pull requests are welcome! If you'd like to improve the model or visualizations, feel free to fork the repo and submit your suggestions.

## 5.📄 License
This project is open source and available under the MIT License.
