# DataScience_weatherReport
## Dataset Information:
The dataset `weather-data.csv` is obtained from [IOWA Environmental Mesonet - Iowa State University](https://mesonet.agron.iastate.edu/).

Columns for this dataset:
* `station`: Acronym for the place of data capture.
* `valid`: Date and time of capture.
* `tmpc`: Temperature of the environment in celsius.
* `dwpc`: Temperature of the dew point in the environment in celsius.
* `relh`: Relative humidity of the environment in percentage.
* `sknt`: Wind Speed in knots.
* `gust`: Wind Gust in knots.
* `peak_wind_drct`: Peak Wind Gust Direction (from PK WND METAR remark). (deg).

## Getting started:
Install the following libraries as listed in `requirements.txt` 

## Part 1 - Exploratory Data Analysis (EDA):
Numerically:
-  Average.
-  Standard Deviation.
-  Percentile range either:
    -  10th and 90th or
    -  25th and 75th.

Graphically:
-  Correlation Plot.
-  Graphing any Numerical Sections of the dataset.

## Part 2 - Data Preparation:
-  Data deemed useless removed.
-  Dataset converted to a form that a model can use.
-  A train and test dataset for the model made.
-  State a reason for each changes made to the DataFrame.

## Part 3 - Data Modelling:
- Model selected.
- Training dataset fitted.
- Testing dataset scored.
- Another month of the existing dataset predicted.
- Model evaluation in a paragraph.