# datafun_07_ml

#### This file contains the documentation and commands related to the Module 7 Machine Learning Project

## Instructions for Setting up Virtual Environment
``` bash
python3 -m venv .venv
source .venv/bin/activate
```

## Installing dependencies and freezing requirements
```bash
python3 -m pip install jupyterlab pandas pyarrow matplotlib seaborn
python3 -m pip freeze > requirements.txt
```


## Git Commands
``` bash
git add .
git commit -m ""
git push origin main
```

[Project Requirements](https://nwmissouri.instructure.com/courses/60333/discussion_topics/485822?module_item_id=2106438)

## Project Dependencies
``` bash
import seaborn as sns
import pandas as pd
import matplotlib.pyplot as plt
from scipy import stats
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
```