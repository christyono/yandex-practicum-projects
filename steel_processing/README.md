## Data:

The data consists of files obtained from different sources:

- data_arc_en.csv — electrode data
- data_bulk_en.csv — bulk material supply data (volume)
- data_bulk_time_en.csv — bulk material delivery data (time)
- data_gas_en.csv — gas purge data
- data_temp_en.csv — temperature measurement results
- data_wire_en.csv — wire materials data (volume)
- data_wire_time_en.csv — wire materials data (time) 

In each file, the key column contains the batch number. There may be several rows with the same key value in the files. These values correspond to different processing iterations.

## Goal:

Developing a model that predicts the temperature of the metal with the lowest MAE possible.

## Libraries used:

pandas

numpy

sklearn.metrics

sklearn.model_selection

sklearn.preprocessing

sklearn.ensemble

sklearn.linear_model

sklearn.model_selection

lightgbm

