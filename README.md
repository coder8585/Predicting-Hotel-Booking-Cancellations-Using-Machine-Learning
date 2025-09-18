# mids-207-summer-2025-keck
MIDS 207 Summer Project Group: Kristen, Emily, Karan, Chad

=> Folder Structure:

```text
mids-207-summer-2025-keck/
│
├── data/
│   ├── raw/                # Original, immutable data dumps
│   ├── processed/          # Cleaned and processed data ready for training
│   └── external/           # Data from third-party sources
│
├── notebooks/              # Jupyter notebooks for exploration and prototyping
│   └── 01_data_exploration.ipynb
│
├── src/                    # Core source code
│   ├── __init__.py
│   ├── data/               # Data loading, cleaning, transformation
│   │   ├── load_data.py
│   │   └── preprocess.py
│   ├── features/           # Feature engineering and selection
│   │   └── build_features.py
│   ├── models/             # Training, prediction, evaluation
│   │   ├── train_model.py
│   │   ├── predict_model.py
│   │   └── evaluate_model.py
│   └── visualization/      # Custom plotting functions
│       └── plot_utils.py
│
├── .gitignore              # Files and folders to ignore in version control
└── README.md               # Project overview and instructions
```
