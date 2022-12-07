# World Happiness Report with School enrollment & CPI

## Data Source
5 row datasets are used in this project:
  1. World Happiness Report 2019: https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2019.csv2Links
  2. School enrollment primary 2019(% gross): https://data.worldbank.org/indicator/SE.PRM.ENRR
  3. School enrollment secondary 2019(% gross): https://data.worldbank.org/indicator/SE.SEC.ENRR
  4. School enrollment tertiary 2019 (% gross): https://data.worldbank.org/indicator/SE.TER.ENRR?view=chartLinks
  5. Inflation, consumer prices 2019 (annual %): https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?view=chartLinks
 

## Methods
To determine the correlation of each independent feature to the happiness score:
  1. Coefficients correlation to show the relationship between country happiness score and indicators.
  2. Divide countries into two parts: happy or unhappy group, and analyze with initial EDA
  3. Create a predictive model with full-established linear regression based on the datasets above.
 

## Model Accuracy Evaluation
Using regression index to evaluate the efficiency of the model including:
  1. R_Square
  2. Mean square error
  3. Pearson’s correlation
  4. Kendal’s Tau
