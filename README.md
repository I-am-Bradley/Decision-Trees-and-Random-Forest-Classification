# Decision-Trees-and-Random-Forest-Classification

## 🧭 Project Overview

### Title:
Decision Trees & Random Forest Classification

### Purpose:
This repository implements two supervised machine learning algorithms for classification tasks:

- **C4.5 Decision Tree**
- **Random Forest Ensemble**

The project evaluates both algorithms on two datasets:

- **MNIST Handwritten Digits**
- **UCI Student Performance Dataset**

The implementation includes a corrected C4.5 information gain calculation, hyperparameter experimentation, performance evaluation, and visualization of model accuracy.

### Audience:

- Machine Learning Students
- AI Researchers
- Data Scientists
- Software Engineers
- Cybersecurity Professionals interested in applied ML

---

# 🧱 System Scope and Architecture

## Project Components:

- Data preprocessing and feature engineering
- C4.5 Decision Tree implementation
- Random Forest implementation
- Model evaluation pipeline
- Hyperparameter tuning
- Performance visualization
- Experiment logging

## Datasets:

- MNIST Handwritten Digits
- Student Performance Prediction Dataset

## Modeling Techniques:

- Information Gain
- Entropy-based splitting
- Recursive decision tree construction
- Bootstrap aggregation (Bagging)
- Random feature selection
- Ensemble majority voting
- Cross-validation

---

# 📂 Repository Structure

```text
Decision_Trees_Random_Forest/

├── README.md
├── Decision_Trees_and_Random_Forest.py
├── .gitattributes
├── Data_set/
│   ├── mnist/
│   │   ├── t10k-images-idx3-ubyte
│   │   ├── t10k-labels-idx1-ubyte
│   │   ├── train-images-idx3-ubyte
│   │   └── train-labels-idx1-ubyte
│   └── extra_data_set/
│        └── data.csv
│
├── Results/
│   ├── running_everything_output.txt
│   ├── running_test_output.txt
│   └── Image of 5.png
│
└── Report/
    └── Decision_Trees_and_Random_Forest_Project_Report.pdf
```

---

# 🌲 Algorithm Summary

This repository implements two classical supervised learning algorithms.

### C4.5 Decision Tree

The decision tree recursively partitions the feature space using the attribute with the greatest average information gain.

Features include:

- Entropy-based split selection
- Average information gain calculation
- Recursive tree construction
- Leaf-node classification
- Continuous feature handling
- Performance evaluation

---

### Random Forest

The Random Forest builds an ensemble of decision trees trained on bootstrap samples.

Features include:

- Bootstrap sampling
- Random feature selection
- Ensemble learning
- Majority voting
- Improved generalization
- Reduced overfitting

---

# 🚀 How to Run

Install the required packages:

```bash
pip install numpy pandas matplotlib scikit-learn
```

Run the complete experiment:

```bash
python RF_starter.py
```

The program automatically:

- Loads each dataset
- Trains the Decision Tree
- Trains the Random Forest
- Evaluates classification accuracy
- Performs hyperparameter testing
- Generates figures
- Saves console output to:
  - `running_everything_output.txt`
  - `running_test_output.txt`

---

# 📊 Results Summary

The corrected C4.5 implementation computes **average information gain** across candidate thresholds before selecting the optimal split, resulting in significantly improved classification performance compared to the original implementation.

The Random Forest further improves predictive performance by combining multiple decision trees through ensemble learning.

The repository includes:

- Accuracy comparisons
- Hyperparameter experiments
- Decision tree evaluations
- Random Forest evaluations
- Saved execution logs
- Performance visualizations

---

# 🧠 Skills Demonstrated

- Decision Tree Learning
- C4.5 Algorithm
- Random Forests
- Ensemble Learning
- Information Theory
- Entropy & Information Gain
- Feature Selection
- Hyperparameter Optimization
- Model Evaluation
- Classification Metrics
- Data Preprocessing
- Scientific Visualization
- Python Machine Learning Development

---

# 📈 Future Improvements

- Implement CART decision trees
- Add Gradient Boosting and XGBoost comparisons
- Perform k-fold cross-validation
- Implement feature importance visualization
- Add pruning techniques
- Benchmark additional datasets

---

# 📬 Author

**Bradley Titagwan**
