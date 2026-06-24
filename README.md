# Iris Flower Classification using KNN and SVM

This project demonstrates machine learning classification on the Iris dataset using K-Nearest Neighbors (KNN) and Support Vector Machine (SVM). It also includes hyperparameter tuning using GridSearchCV and RandomizedSearchCV to find the best model configuration.

## 📌 Project Overview

The Iris dataset contains measurements of iris flowers and their corresponding species. The goal is to classify flowers into one of three categories:

- Setosa
- Versicolor
- Virginica

The project follows a complete machine learning workflow:
- Data Loading
- Data Exploration
- Train-Test Split
- Model Training
- Model Evaluation
- Hyperparameter Tuning

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## 📊 Dataset

The Iris dataset contains:
- 150 samples
- 4 features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 target classes:
  - Setosa
  - Versicolor
  - Virginica

## 🤖 Models Used

### K-Nearest Neighbors (KNN)
- Number of Neighbors: 13
- Test Accuracy: 100%

### Support Vector Machine (SVM)
- Gamma: auto
- Test Accuracy: 100%

## 🔍 Hyperparameter Tuning

### GridSearchCV
Parameters Tested:
- C = [1, 10, 20, 30]
- Kernel = ['rbf', 'linear']

Best Cross-Validation Score:
- 98%

### RandomizedSearchCV
Randomly selects parameter combinations for faster optimization.

Best Cross-Validation Score:
- 98%

## 📈 Results

| Model | Accuracy |
|---------|----------|
| KNN | 100% |
| SVM | 100% |
| SVM + GridSearchCV | 98% |
| SVM + RandomizedSearchCV | 98% |

## 📚 Learning Outcomes

- Machine Learning Classification
- KNN Algorithm
- Support Vector Machines (SVM)
- Model Evaluation
- Cross Validation
- GridSearchCV
- RandomizedSearchCV
- Hyperparameter Tuning

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/iris-classification-knn-svm.git
```

2. Install dependencies
```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

3. Run the Jupyter Notebook

## 👩‍💻 Author

Sakshi

---

⭐ If you found this project useful, please consider giving it a star.
