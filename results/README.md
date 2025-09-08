# 📂 Results Folder
This folder stores **outputs generated from experiments** in the MSc dissertation project.

## 📑 Contents
- **Metrics reports** (accuracy, F1-score, AP/AUC, calibration, silhouette values).
- **Plots and visualisations** (confusion matrices, ROC/PR curves, calibration, segmentation clusters, feature importance).
- **Intermediate artefacts** (CSV summaries).

## 📊 Latest Results Summary (Auto-updated)

|   artefact_profile_csv |   artefact_scatter_png |   artefact_val_plot_png |   artefact_val_sweep_csv |   bank_best_f1 |   credit_best_f1 |   model |   retail_best_k_val |   retail_best_silhouette |   retail_test_silhouette |   retail_val_silhouette |   task |   test_AP |   test_ROC_AUC |   test_f1@thr |   test_precision@thr |   test_recall@thr |   tuned_threshold(val) |
|-----------------------:|-----------------------:|------------------------:|-------------------------:|---------------:|-----------------:|--------:|--------------------:|-------------------------:|-------------------------:|------------------------:|-------:|----------:|---------------:|--------------:|---------------------:|------------------:|-----------------------:|
|                    nan |                    nan |                     nan |                      nan |       0.572165 |         0.849315 |     nan |                 nan |                 0.607787 |                      nan |                     nan |    nan |       nan |            nan |           nan |                  nan |               nan |                    nan |

## Probability Calibration (TEST)

**Credit Risk — metrics**

| dataset     | variant         |    brier |   roc_auc |   avg_precision |
|:------------|:----------------|---------:|----------:|----------------:|
| Credit Risk | lr_uncalibrated | 0.155982 |  0.804267 |        0.650842 |
| Credit Risk | lr_sigmoid      | 0.157097 |  0.805486 |        0.657833 |
| Credit Risk | lr_isotonic     | 0.159576 |  0.800914 |        0.655262 |
| Credit Risk | rf_uncalibrated | 0.16343  |  0.794171 |        0.602718 |

**Bank Marketing — metrics**

| dataset        | variant         |     brier |   roc_auc |   avg_precision |
|:---------------|:----------------|----------:|----------:|----------------:|
| Bank Marketing | rf_uncalibrated | 0.0557258 |  0.946554 |        0.670224 |
| Bank Marketing | lr_isotonic     | 0.0582391 |  0.942258 |        0.622466 |
| Bank Marketing | lr_sigmoid      | 0.0605729 |  0.942251 |        0.623669 |
| Bank Marketing | lr_uncalibrated | 0.0605995 |  0.942253 |        0.623388 |

## Plots

**Credit — Confusion Matrix**  
![](credit_best_cm.png)

**Bank — Confusion Matrix (best on TRAIN)**  
![](bank_best_cm.png)

**Credit — ROC Curve**  
![](credit_roc.png)

**Bank — ROC Curve (TRAIN)**  
![](bank_roc.png)

**Bank — PR Curves (TRAIN)**  
![](bank_pr_curves.png)

**Bank — PR Curve (TEST)**  
![](bank_pr_test.png)

**Bank — ROC Curve (TEST)**  
![](bank_roc_test.png)

**Bank — Confusion Matrix (TEST, Logistic Regression)**  
![](bank_cm_test_logreg_bal.png)

**Bank — Confusion Matrix (TEST, Random Forest)**  
![](bank_cm_test_rf_bal.png)

**Credit — Calibration (TEST)**  
![](credit_calibration.png)

**Bank — Calibration (TEST)**  
![](bank_calibration.png)

**Credit — Permutation Importance**  
![](credit_perm_importance_AGG.png)  
![](credit_perm_importance_EXP.png)

**Bank — Permutation Importance**  
![](bank_perm_importance_AGG.png)  
![](bank_perm_importance_EXP.png)

**Retail — Cluster Scatter (from Step 8)**  
![](retail_clusters_scatter.png)

**Retail — Validation Silhouette vs k (Step 14)**  
![](retail_val_silhouette.png)

**Retail — Cluster Scatter (final model, Step 14)**  
![](retail_clusters_scatter_final.png)


## Key CSV artefacts

- `summary_master.csv`
- `summary.csv`
- `master_results_summary.csv`
- `credit_calibration_metrics.csv`
- `bank_calibration_metrics.csv`
- `bank_threshold_tuning.csv`
- `bank_train_test_eval.csv`
- `silhouette_scores.csv`
- `retail_k_sweep_val.csv`
- `retail_cluster_profile_test.csv`
- `credit_perm_importance_AGG.csv`
- `credit_perm_importance_EXP.csv`
- `bank_perm_importance_AGG.csv`
- `bank_perm_importance_EXP.csv`

_Last updated: 2025-09-08 14:29 UTC_
