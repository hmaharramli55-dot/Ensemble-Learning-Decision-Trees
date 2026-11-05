# Ensemble Learning with Decision Trees

Machine Learning (CSCI4734) assignment at ADA University, Fall 2026.

A decision tree classifier is tuned with grid search, then 1,000 small trees are trained on random 100-sample subsets of the data and combined by majority vote, similar to a random forest.

## Results

| Model | Test accuracy |
|---|---|
| Single tuned decision tree | 85.95% |
| Average of 1,000 trees (100 samples each) | 80.6% |
| Majority vote of the 1,000 trees | 87.3% |

## Files

- `CSCI4734_2026F_10551_A2_HUSEYN_MAHARRAMLI.ipynb`: notebook with all code, outputs and answers
- `data.csv`: dataset (10,000 samples, 2 features, 2 classes)

## How to run

```
pip install numpy pandas matplotlib scipy scikit-learn
```

Open the notebook in Jupyter or VS Code and run all cells.
