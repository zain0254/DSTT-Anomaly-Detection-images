# Figures: Does Robust Adaptive Thresholding Help LSTM Autoencoder Anomaly Detection? A Leakage-Free Evaluation on NAB

Figures from [DSTT-Anomaly-Detection-](https://github.com/zain0254/DSTT-Anomaly-Detection-),
organised by phase, each as PNG (300 dpi) and PDF. The files are written by
`scripts/sync_figures.sh` in the main repository; do not edit them here.
The paper uses print-size versions of four of them (`paper/figures/` in the
main repository).

## Figure index

| File | What it shows | Phase |
|---|---|---|
| figures/phase1_eda/fig01_example_per_category | One example series per NAB category with anomaly windows shaded and the 60/20/20 split boundaries | 1 EDA |
| figures/phase1_eda/fig02_labelled_share | Share of points inside NAB windows, overall and per category | 1 EDA |
| figures/phase1_eda/fig03_value_distributions | Value distribution of every series (min-max scaled per file), grouped by category | 1 EDA |
| figures/phase1_eda/fig04_lengths_and_sampling | Series lengths and median sampling interval per category | 1 EDA |
| figures/phase1_eda/fig05_windows_vs_split | Position of every anomaly window relative to the 60/20/20 split; series without a test window marked | 1 EDA |
| figures/phase1_eda/fig06_windows_per_part_and_contamination | Windows touching train, validation and test per series, and the share of training points inside windows | 1 EDA |
| figures/phase2_model/fig01_loss_curves | Training and early-stopping loss per epoch for four series (seed 15) | 2 Model |
| figures/phase2_model/fig02_reconstruction_error | nyc_taxi (seed 15): series and per-window reconstruction error with windows and split boundaries | 2 Model |
| figures/phase3_thresholds/fig01_tuning_objective | Validation composite F1 against each threshold rule's parameters, selected values circled | 3 Thresholds |
| figures/phase3_thresholds/fig02_test_metrics | Test metrics per rule (composite F1, point F1, event recall, FPR, high-variance FPR, clean-stream false alarms), mean and sd over seeds | 3 Thresholds |
| figures/phase3_thresholds/fig03_paired_per_file | Per-series comparison of P1 with Base and with B3 on composite F1 and FPR | 3 Thresholds |
| figures/phase3_thresholds/fig04_example_trace | nyc_taxi test segment (seed 15): error with the Base, B3 and P1 thresholds and their alarms | 3 Thresholds |
| figures/phase3_thresholds/fig05_category_improvement | Mean improvement of P1 over Base and B3 per NAB category (descriptive) | 3 Thresholds |
| figures/phase3_thresholds/fig06_detection_delay | Relative delay of the first alarm and missed test windows per rule | 3 Thresholds |
