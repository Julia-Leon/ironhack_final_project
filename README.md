![Header](https://github.com/Julia-Leon/ironhack_final_project/blob/main/images/mer-de-glace-2423521_1280.jpg)
# Time Series for Weather and Glaciers Surface Mass Balance Prediction
## Introduction:
Glaciers represent more than 2% of earth's water volume. They play an important environmental role and climate change accelerates its natural melting process.

Surface Mass Balance (SMB) is the mesure to analyse glaciers mass changes in time, comparing the ice and snow addition (accumulation) and loss (ablation).

The target of this study is to create a predictive model SMB's future changes related to the climate change.

We will use the dataset of Mer de Glace, a glacier placed in Chamonix Valley (French Alps) and the weather dataset of Argentière.
This database is been provided by GLACIOCLIM, the French national glaciers obserbatory, which studies Glaciers in the Alps, Andes and Antártica. 

Glaciers are a dynamic element and to mesure each parameter, stakes in strategical points have been used to mesure parameters such as altitude, speed of glacier movement, width, accumulation and ablation.

## Hypothesis:

Can Time Series models be used to forecasting Mer de Glace SMB changes?

GLACIOCLIM builds predictive ANN models (Artificial neural networks), very complex models. We want to asses the accuracy of predicting glaciers evolution with 
simpler models.

## Method:
We apply the ARIMA model to our weather dataset, dividing it in train and test (the test data used is from Novenber and December 2019), for which we already have the real values. Comparing test and real values will allow us to evaluate the model's acuracy.

## Results:
The prediction and the real values for the period assessed are extremely different, as we can see [here]https://public.tableau.com/app/profile/julia.leon4960/viz/Glaciersmelting/Sheet3

## Conclusion:
Hypothesis rejected.
ARIMA is a model not ready for glaciers behaviour, as its assumptions lead it to stabilize values.
