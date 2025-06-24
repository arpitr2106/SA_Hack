## DataHack-Hackathon-by-GFG

<div align="center">
<img alt="output" src="pictures/gfg.jpeg" width="400" />
</div>

This repository contains the solution for the Hackathon by GeeksforGeeks(GFG) conducted during Summer Analysis, Consulting & Analytics Club, IIT Guwahati. It features an exploratory analysis notebook, a trained model, and the required submission files.

## 📁 Repository Contents

- `practice.ipynb` – Jupyter notebook showcasing:
  - Data loading and exploration of feature distributions
  - Handling missing values
  - Feature engineering (if any)
  - Model development and evaluation (Random Forest Classifier)
  - Cross-validation and performance insights

- `training_set_features.csv` & `training_set_labels.csv` – Labeled data used for training.

- `test_set_features.csv` – Unlabeled data used for generating predictions.

- `submission_format.csv` – Template defining submission structure.

- `submit_final_RFC.csv` – Final predictions on the test set using the Random Forest model.

- `Problem description.pdf` – Hackathon problem statement and evaluation criteria.

## 🧪 Methodology

- Exploratory Data Analysis
  - Inspected distributions, null values, and feature correlations
  - Visualized key variables to guide feature engineering

- Preprocessing
  - Addressed missing values (mean/median/imputation)
  - Scaled or encoded features where necessary

- Model Selection
  - Evaluated multiple classifiers via cross-validation
  - Selected Random Forest Classifier based on performance, robustness, and interpretability

- Submission
  - Trained on full dataset
  - Generated final predictions and exported to submit_final_RFC.csv

---
