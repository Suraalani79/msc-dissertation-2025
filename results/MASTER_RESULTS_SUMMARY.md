# Results Summary

This document summarises the key outcomes across all tasks (Credit risk, Bank marketing, Retail segmentation) and provides file references to plots/metrics stored in the repository.

## Key Metrics

- **Credit risk — best model:** `logreg`, **F1:** 0.849

- **Bank marketing — best model:** `rf`, **F1:** 0.572

- **Retail segmentation — best k:** 5, **Silhouette:** 0.608

- **Retail cluster sizes:** Cluster 0: 3840, Cluster 1: 2002, Cluster 2: 35, Cluster 3: 4

## Files & Plots

- Credit metrics CSV: `results/credit_metrics.csv`

- Bank metrics CSV: `results/bank_metrics.csv`

- Silhouette sweep CSV: `results/silhouette_scores.csv`

- Credit confusion matrix: `results/credit_best_cm.png`

- Bank confusion matrix: `results/bank_best_cm.png`

- Retail clusters scatter: `results/retail_clusters_scatter.png`

- Credit ROC curve: `results/credit_roc.png`

- Bank ROC curve: `results/bank_roc.png`
