
# Classification Model Evaluation with Confusion Matrix

## Project Description

This project demonstrates how to calculate and visualize evaluation metrics for binary classification models using Python:

- Accuracy
- Precision
- Recall
- F1-Score

Additionally, the project shows how to create and visualize the confusion matrix, which is essential to understand the model's errors.

## Technologies Used

- Python 3
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/avaliacao_modelos.git
cd avaliacao_modelos
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Python script:

```bash
python matriz_confusao.py
```

## Code Explanation

The script performs the following steps:

1. Import necessary libraries
2. Create sample data (`y_true` and `y_pred`)
3. Calculate and visualize the normalized confusion matrix
4. Calculate evaluation metrics (Accuracy, Precision, Recall, F1-Score)
5. Display the metrics and the heatmap of the confusion matrix

## Expected Output

- Normalized Confusion Matrix
- Evaluation Metrics, for example:
  - Accuracy: 0.80
  - Precision: 0.86
  - Recall: 0.75
  - F1-Score: 0.80

## Conclusion

The confusion matrix and evaluation metrics provide a clear view of the model's performance and help identify areas for improvement.
