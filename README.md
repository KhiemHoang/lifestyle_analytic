# Lifestyle Tracking Report Overview

This is a personal data analytics project that investigates how lifestyle and sleep patterns relate to stress levels.

The workflow includes:
- Downloading the dataset **[Lifestyle and Sleep Patterns — Minahil Fatima (Kaggle)](https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns)**.
- Performing data preprocessing and building a **Linear Regression** model in Python.
- Creating an interactive **Power BI** report for visualization and stress level estimation.

---

## Repository Structure
```text
├── README.md
├── Lifestyle Tracking Report.pbix        # Power BI report
├── bi_theme/                             # Power BI custom themes (JSON)
├── data/                                 # Dataset storage
├── img/                                  # Images (dashboards, assets, encoded images)
└── notebook/                             # Jupyter notebooks
    ├── data_preprocessing.ipynb
    └── img_encode_base64.ipynb
```
---

## Power BI Report
- **Overview page**: summarizes dataset insights.  
- **How about you? page**: interactive section where users can input *Age, BMI, Sleep Hours, and Sleep Quality* to estimate their stress level.  

---

## Python Environment

### Required Libraries
``` text
kagglehub
os
pandas
seaborn
matplotlib
scikit-learn
numpy
base64
```

### Example Code Snippet
```python
import kagglehub
import os
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LinearRegression
import numpy as np
import base64
```

---

## How to Use
1. Clone this repository.  
2. Open **`Lifestyle Tracking Report.pbix`** in **Power BI Desktop**.  
3. Explore the **Overview** page and try the **How about you?** input to get a stress estimate.  
4. (Optionally) Run notebooks in `notebook/` to re-preprocess data and encode images.  

---

## Attribution
Dataset © **Minahil Fatima** — used under Kaggle terms:  
[https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns](https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns)  

---

## Author
**Khiem Hoang** — personal learning & analytics project.  
