pandas-learning-journey/
├── .gitignore                    # Ignore data files, venv, etc.
├── requirements.txt              # Python dependencies
├── README.md                     # Project overview & setup instructions
│
├── data/                         # Raw datasets (git-ignored)
│   ├── kaggle_dataset_1/
│   │   ├── train.csv
│   │   └── test.csv
│   └── kaggle_dataset_2/
│       └── data.csv
│
├── notebooks/                    # Jupyter notebooks (organized by topic)
│   ├── 01_basics/
│   │   ├── data_loading.ipynb    # Loading datasets from Kaggle
│   │   ├── data_inspection.ipynb
│   │   └── data_cleaning.ipynb
│   │
│   ├── 02_manipulation/
│   │   ├── filtering.ipynb
│   │   ├── grouping.ipynb
│   │   └── merging.ipynb
│   │
│   ├── 03_analysis/
│   │   ├── time_series.ipynb
│   │   ├── aggregation.ipynb
│   │   └── visualization.ipynb
│   │
│   └── 04_projects/              # End-to-end projects with Kaggle data
│       ├── titanic_analysis.ipynb
│       ├── sales_forecasting.ipynb
│       └── customer_segmentation.ipynb
│
├── scripts/                      # Reusable utility functions
│   ├── data_loader.py            # Custom data loading functions
│   └── visualizations.py         # Plotting helpers
│
├── resources/                    # Learning materials
│   ├── pandas_cheatsheet.pdf
│   ├── kaggle_dataset_links.md   # Sources of datasets used
│   └── learning_notes.md         # Personal notes/tips
│
└── tests/                        # Unit tests for functions (optional)
    └── test_data_loader.py