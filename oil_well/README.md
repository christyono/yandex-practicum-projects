## Data:

`geo_data_0.csv`, `geo_data_1.csv`, `geo_data_2.csv`:

- *id* — unique oil well identifier
- *f0, f1, f2* — three features of points (their specific meaning is unimportant, but the features themselves are significant)
- *product* — volume of reserves in the oil well (thousand barrels).

## Goal:

1. Developing a model using the provided data on each oil well region
2. Creating an algorithm that calculates the volume of reserves sufficient for developing a new well without losses
3. Writing a function to calculate net revenue generated using selected oil wells and model predictions as parameters
4. Calculating risks and profit for each oil well region.

## Libraries used:

pandas

numpy.random

sklearn.linear_model

sklearn.metrics

sklearn.model_selection

sklearn.preprocessing