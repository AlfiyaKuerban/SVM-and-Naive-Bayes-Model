# Project Title
Raisin Classification using SVM and Naive Bayes

---

## Short Description
This project analyzes a raisin dataset containing 900 observations and 8 variables to classify raisins into two categories: Kecimen and Besni.

The workflow includes data exploration, visualization, preprocessing, and classification using two machine learning models: Support Vector Machine (SVM) and Gaussian Naive Bayes. The goal is to evaluate which model performs better for this classification task.

---

## Getting Started
This project can be run locally using Python in a Jupyter Notebook or VS Code.

The code demonstrates a complete data analysis pipeline:
- Load dataset
- Perform exploratory data analysis (EDA)
- Visualize relationships
- Train machine learning models
- Evaluate performance

---

## Prerequisites
Install the following libraries before running the project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Installing

1. Download or clone the project files.

2. Place the dataset file in the same directory:
```
raisin_dataset.csv
```

3. Open the notebook or Python file.

4. Run the code step-by-step:

- Load libraries
- Load dataset
- Perform EDA
- Create visualizations
- Train models
- Evaluate results

---

## Running the Tests
The models are evaluated using:

- Confusion Matrix
- Classification Report

These metrics help measure:
- Accuracy
- Precision
- Recall
- F1-score

---

## Breakdown of Tests

### Model 1: Support Vector Machine (SVM)
- Uses RBF kernel
- Requires feature scaling
- Achieved accuracy: **87%**
- Shows balanced performance across both classes

### Model 2: Gaussian Naive Bayes
- Assumes feature independence
- Faster but less accurate
- Achieved accuracy: **83%**

### Key Findings
- SVM performs better than Naive Bayes
- Features like Area, ConvexArea, and Perimeter are highly correlated
- Data scaling improves SVM performance significantly

---

## Deployment
This project is designed for local execution.

It can be extended to:
- Web applications (Streamlit)
- Cloud platforms (AWS, Azure)
- Real-time prediction systems

---

## Author
Alfiya Kuerban

---

## License
This project is for academic purposes only.

---

## Acknowledgement
- Raisin dataset for classification analysis
- Scikit-learn for machine learning models
- Course materials and instructor guidance
