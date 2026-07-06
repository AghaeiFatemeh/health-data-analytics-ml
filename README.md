# Health Data Analytics — ML pipeline (clinical + RNA-seq)

An end-to-end supervised machine-learning pipeline built for the MSc Bioinformatics
*Health Data Analytics* module (University of Birmingham). It takes clinical and
gene-expression (FPKM) data and runs the full workflow: data joining, exploration,
imputation, normalisation, variance thresholding, PCA / K-means, cross-validated
feature selection, GridSearchCV hyper-parameter tuning (SVM, Random Forest) and
model evaluation (ROC/AUC, precision-recall).

## Stack
Python · pandas · NumPy · scikit-learn · matplotlib · seaborn

## Running it
The raw datasets are course-provided and are **not** included here. To run end to
end, create a local `data/` folder and place the clinical and FPKM CSVs inside it,
then run the notebook top to bottom.

## Note
This is coursework, shared to demonstrate a complete Python ML workflow. Datasets
are excluded for size and licensing reasons.
