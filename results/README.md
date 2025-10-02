# Project README

---
## 📊 Latest Results Summary (Auto-updated)

| artefact_profile_csv                    | artefact_scatter_png                      | artefact_val_plot_png             | artefact_val_sweep_csv         |   bank_best_f1 |   credit_best_f1 | model      |   retail_best_k_val |   retail_best_silhouette |   retail_test_silhouette |   retail_val_silhouette | task                  |    test_AP |   test_ROC_AUC |   test_f1@thr |   test_precision@thr |   test_recall@thr |   tuned_threshold(val) |
|:----------------------------------------|:------------------------------------------|:----------------------------------|:-------------------------------|---------------:|-----------------:|:-----------|--------------------:|-------------------------:|-------------------------:|------------------------:|:----------------------|-----------:|---------------:|--------------:|---------------------:|------------------:|-----------------------:|
| nan                                     | nan                                       | nan                               | nan                            |       0.572165 |         0.849315 | nan        |                 nan |                 0.607787 |               nan        |              nan        | nan                   | nan        |     nan        |    nan        |           nan        |        nan        |              nan       |
| nan                                     | nan                                       | nan                               | nan                            |     nan        |       nan        | logreg_bal |                 nan |               nan        |               nan        |              nan        | Bank Marketing (TEST) |   0.621576 |       0.943622 |      0.639897 |             0.530078 |          0.807112 |                0.66856 |
| nan                                     | nan                                       | nan                               | nan                            |     nan        |       nan        | rf_bal     |                 nan |               nan        |               nan        |              nan        | Bank Marketing (TEST) |   0.673553 |       0.947821 |      0.650195 |             0.543872 |          0.80819  |                0.26088 |
| results/retail_cluster_profile_test.csv | results/retail_clusters_scatter_final.png | results/retail_val_silhouette.png | results/retail_k_sweep_val.csv |     nan        |       nan        | nan        |                   4 |               nan        |                 0.582043 |                0.605163 | Retail (TEST)         | nan        |     nan        |    nan        |           nan        |        nan        |              nan       |

### Plots
**Credit — Confusion Matrix**  
![](results/credit_best_cm.png)

**Bank — Confusion Matrix**  
![](results/bank_best_cm.png)

**Credit — ROC Curve**  
![](results/credit_roc.png)

**Bank — ROC Curve (TRAIN)**  
![](results/bank_roc.png)

**Retail — Cluster Scatter (early)**  
![](results/retail_clusters_scatter.png)

**Bank — PR Curves (TRAIN)**  
![](results/bank_pr_curves.png)

**Bank — PR Curve (TEST)**  
![](results/bank_pr_test.png)

**Bank — ROC Curve (TEST)**  
![](results/bank_roc_test.png)

**Bank — Confusion Matrix (TEST, Logistic Reg)**  
![](results/bank_cm_test_logreg_bal.png)

**Bank — Confusion Matrix (TEST, Random Forest)**  
![](results/bank_cm_test_rf_bal.png)

**Retail — Validation Silhouette vs k**  
![](results/retail_val_silhouette.png)

**Retail — Cluster Scatter (final model)**  
![](results/retail_clusters_scatter_final.png)

**Credit — Permutation Importance (AGG)**  
![](results/credit_perm_importance_AGG.png)

**Credit — Permutation Importance (EXP)**  
![](results/credit_perm_importance_EXP.png)

**Bank — Permutation Importance (AGG)**  
![](results/bank_perm_importance_AGG.png)

**Bank — Permutation Importance (EXP)**  
![](results/bank_perm_importance_EXP.png)


_Last updated: 2025-10-02 15:14 UTC_
