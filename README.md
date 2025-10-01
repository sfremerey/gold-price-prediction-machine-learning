# Machine learning for "Gold Price Prediction Dataset"
Using the ["Gold Price Prediction Dataset"](https://www.kaggle.com/datasets/sid321axn/gold-price-prediction-dataset) to apply different machine learning algorithms in the further education course ["Machine Learning"](https://www.alfatraining.de/kurse/weiterbildung-machine-learning).

The aim is to examine how well the direction of the gold price can be predicted using machine learning.
The specific question is: **Can a machine learning model reliably distinguish between "long" (price increase), "flat" (sideways) and "short" (price decrease)?**
This shifts the focus from a pure regression task to a classification task, in which the correct prediction of the direction of movement is crucial.

In `MLP_KNeighbors_Beyes.ipynb`, three different machine learning methods are explored in more detail: MLPClassifier, KNeighborsClassifier, RadiusNeighborsClassifier (all using GridSearch) and GaussianNB reflecting a rather simple method.
In `VotingStacking.ipynb`, different top-performing machine learning models are combined to an ensemble model using voting and stacking.

## License
The contents of this repository follow the [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0) license.
