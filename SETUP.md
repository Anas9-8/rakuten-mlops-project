# Project Setup Guide

## Environment Setup (Completed ✅)

### 1. Virtual Environment
```bash
python3.12 -m venv rakuten_env
source rakuten_env/bin/activate
```

### 2. Libraries Installed
- TensorFlow 2.20.0
- NumPy 2.4.1
- Pandas 2.0.3
- Scikit-learn 1.3.0
- Matplotlib, Seaborn
- NLTK, Pillow
- Jupyter

### 3. Data Download (Completed ✅)
Data downloaded from: https://challengedata.ens.fr/challenges/35

Files:
- X_train.csv (52 MB) - 84,916 products
- Y_train.csv (886 KB) - Labels
- X_test.csv (8.5 MB) - 13,812 products
- images.zip (2.4 GB) - Product images

**Note:** Data files are NOT tracked by Git (see .gitignore)

### 4. Data Structure
```
data/
├── X_train.csv
├── Y_train.csv
├── X_test.csv
└── images/
    ├── image_train/
    └── image_test/
```

### 5. Dataset Info
- Total products: 99,000 (train: 84,916, test: 13,812)
- Categories: 27 product type codes
- Modalities: Text (designation, description) + Images
- Metric: Weighted F1-score

## Next Steps
- Explore data
- Run baseline model
- Create API
