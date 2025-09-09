# Master Results Summary

This appendix consolidates the key outcomes across **Credit Risk**, **Bank Marketing**, and **Retail Segmentation** tasks.

## Headline snapshot

| timestamp_utc           | credit_best_model   |   credit_best_f1 | bank_best_model   |   bank_best_f1 |   retail_best_k |   retail_best_silhouette |   drift_fixed_f1 |   drift_rolling_mean_f1 |   credit_best_brier | credit_best_calibration         |   bank_best_brier | bank_best_calibration           |
|:------------------------|:--------------------|-----------------:|:------------------|---------------:|----------------:|-------------------------:|-----------------:|------------------------:|--------------------:|:--------------------------------|------------------:|:--------------------------------|
| 2025-09-09 13:14:15 UTC | logreg              |         0.849315 | rf                |       0.572165 |               4 |                 0.605163 |         0.466012 |                0.538912 |            0.155982 | lr_uncalibrated (ROC_AUC=0.804) |         0.0557258 | rf_uncalibrated (ROC_AUC=0.947) |

### Overview plot

![](results/meta_overview_scores.png)

## Bank Marketing — Concept Drift

| month   |       f1 |   n_test |
|:--------|---------:|---------:|
| aug     | 0.376975 |     6178 |
| sep     | 0.718053 |      570 |
| oct     | 0.489451 |      718 |
| nov     | 0.486702 |     4101 |
| dec     | 0.623377 |      182 |

![](results/bank_drift_rolling_retrain.png)


_Last compiled: 2025-09-09 13:14 UTC_
