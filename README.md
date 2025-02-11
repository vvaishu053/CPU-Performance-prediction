# CPU-Performance-Prediction


This project involves predicting the performance class (High, Medium, Low) of a CPU based on features such as clock speed, cache size, and power consumption. The goal is to evaluate and compare different machine learning models to predict the performance of a CPU.

## Dataset

The dataset used for this project contains features like:

- **Clock Speed**: The speed of the CPU in GHz.
- **Cache Size**: The size of the CPU's cache in MB.
- **Power Consumption**: The power consumed by the CPU in watts.

The target variable is the **Performance Class**, which can be one of the following classes:

- **High**
- **Medium**
- **Low**

The dataset is stored in `cpu_performance.csv`.

## Machine Learning Models

The following machine learning models were implemented and evaluated:

1. **Support Vector Machine (SVM)** with a linear kernel.
2. **Random Forest Classifier** with 100 estimators.
3. **K-Nearest Neighbors (KNN)** with 5 neighbors.

## Evaluation Metrics

The performance of the models was evaluated using:

- **Accuracy**
- **Confusion Matrix**
- **Classification Report**

### Results

- **SVM** achieved an accuracy of `XX.XX%`.
- **Random Forest** achieved an accuracy of `XX.XX%`.
- **KNN** achieved an accuracy of `XX.XX%`.

## Code Execution

To run the project, ensure you have the required libraries installed. You can install the dependencies using `pip`:

bash
pip install pandas numpy scikit-learn matplotlib seaborn

run: 
python cpu_performance.py

## Output

The output includes:

- **Accuracy Comparison Plot**: A bar plot comparing the accuracies of SVM, Random Forest, and KNN models.
- **Confusion Matrix Plots**: Confusion matrices for each model (SVM, Random Forest, and KNN), showing how well the models performed on the test set.

### Classification Report

Below is the classification report for each model, which includes precision, recall, and F1-score for each class:
![classification report](img2.png)

## Example Output

Below are the confusion matrices and accuracy comparison for the models:

### Accuracy Comparison of Classifiers
![Accuracy Comparison](img3.png)

### Confusion Matrix - SVM
![SVM Confusion Matrix](svm.png)

### Confusion Matrix - Random Forest
![Random Forest Confusion Matrix](random.png)

### Confusion Matrix - KNN
![KNN Confusion Matrix](knn.png)
