# ML Portfolio Course — Dataset

This repository contains the e-commerce dataset used in the course 
**"Build Your First ML Portfolio Project: Step by Step"**

## Dataset

`ecommerce_data.csv` — Real e-commerce transaction data containing:
- Customer IDs
- Invoice dates
- Product quantities and unit prices
- Total transaction amounts
- Country information

## How to load it in your notebook
```python
import pandas as pd
df = pd.read_csv('https://raw.githubusercontent.com/mar-antaya/ml-portfolio-course/main/ecommerce_data.csv')
print(df.shape)
df.head()
```

## Course

Full course available at: https://mariana-antaya-s-school.teachable.com/l/pdp/how-to-build-a-predictive-machine-learning-model
