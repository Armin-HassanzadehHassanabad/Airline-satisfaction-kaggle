Repository Structure

airline-satisfaction-prediction/
├── README.md
├── notebooks/
│   └── airline_satisfaction.ipynb
├── data/
│   └── .gitkeep
├── results/
│   └── .gitkeep
├── requirements.txt
└── .gitignore

Directory Description

notebooks/ — Contains the end-to-end Jupyter notebook, including data preprocessing, feature engineering, leakage-aware target encoding, model development, cross-validation, out-of-fold prediction analysis, and ensemble blending.

data/ — Reserved for the competition dataset. Raw data files are excluded from version control and should be obtained from Kaggle.

results/ — Reserved for evaluation outputs, performance summaries, and visualizations.

requirements.txt — Lists the Python dependencies required to reproduce the workflow.

.gitignore — Specifies files and directories that should not be tracked by Git.

README.md — Documents the project objectives, methodology, dataset, and execution instructions.

Reproducibility

The notebook was developed in the Kaggle environment. Reproducing the workflow elsewhere may require adapting dataset paths and installing compatible versions of the required dependencies.

The competition dataset is available from the Kaggle Playground Series.
