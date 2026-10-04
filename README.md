# Dataset

The analysis uses the **Apple AppStore Apps** dataset referenced by the project.

The raw CSV is intentionally not bundled here. Before running the notebook, download the dataset from its original Kaggle source:

- Kaggle: https://www.kaggle.com/datasets/gauthamp10/apple-appstore-apps

Place the downloaded CSV at:

```text
data/raw/apple_data.csv
```

The notebook expects that exact path.

## Dataset snapshot used by the analysis

- Raw records: **1,230,376**
- Records after cleaning: **1,229,263**
- Raw attributes: **21**
- Business questions: **16**

The notebook performs the documented missing-value treatment, duplicate analysis, feature engineering, and exploratory analysis before answering the 16 business questions.
