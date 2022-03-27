# Credit Risk Analysis

This project utilizes supervised machine learning methods to distinguish healthy loans from defaulted ones.

---

## Technologies

This project leverages Jupyter notebook and Pandas.

---

## Installation Guide

Before running the application, please install the following libraries

```python

conda install -c conda-forge imbalanced-learn
conda install -c conda-forge pydotplus
```

Then, please import the following libraries and dependencies:

```python

import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```

Then, clone the repository onto your local computer.

---

## Contributors

Initial code is provided by: UC Berkeley Fintech Bootcamp

Code is modified by: Kevin BaRoss [[LinkedIn](https://www.linkedin.com/in/kevin-baross/)]


---
## License
MIT

