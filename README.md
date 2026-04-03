# Network Intrusion Detection (KNN)

## Overview
This project classifies network traffic as normal or intrusion using a K-Nearest Neighbors (KNN) classifier.

## Files
- `network-intrusion-detection-knn.ipynb`: main notebook
- `network_intrusion_dataset.csv`: raw dataset
- `prepared_network_intrusion_dataset.csv`: cleaned dataset used for modeling
- `knn_pred_comparison.csv`: sample actual vs predicted output

## Workflow
1. Load and inspect the network intrusion dataset
2. Visualize traffic and attack type distributions
3. Clean features and export a prepared dataset
4. Split data into training and test sets
5. Train a baseline KNN model
6. Evaluate using classification report, confusion matrix, and ROC
7. Tune hyperparameters (manual K analysis + GridSearchCV)

## Results
The notebook reports:
- Classification metrics (precision, recall, F1-score)
- Confusion matrices
- ROC visualization
- Best KNN parameters from grid search

## Setup
Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:
- Open `network-intrusion-detection-knn.ipynb`
- Run all cells from top to bottom

## Notes
- All file paths are relative for portability.
- Large prediction tables are trimmed to `.head()` in outputs.
