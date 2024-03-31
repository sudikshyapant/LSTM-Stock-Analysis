# Time Series Analysis with LSTM Model

## Overview
This repository contains Python code for time series analysis using an LSTM (Long Short-Term Memory) model. The code demonstrates how to preprocess time series data, train an LSTM model, and make predictions.

## Dependencies
- pandas
- datetime
- matplotlib
- numpy
- TensorFlow (for the LSTM model)
- copy (for recursive predictions)

## Usage
1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Download the dataset 'MSFT.csv' and place it in the same directory as the code.
4. Run the main script `time_series_analysis.py` to perform the analysis.

## Contents
- `time_series_analysis.py`: Python script for time series analysis.
- `MSFT.csv`: Sample dataset for Microsoft stock prices.

## How to Run
1. Import necessary libraries:
```python
import pandas as pd
import datetime
import matplotlib.pyplot as plt
import numpy as np
from tensorflow.keras.models import Sequential
from tensorflow.keras.optimizers import Adam
from tensorflow.keras import layers
from copy import deepcopy
