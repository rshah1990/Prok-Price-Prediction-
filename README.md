# Prok-Price-Prediction-

Problem Statement

Predict the Year over Year (YOY %) percent change in the index for the period of 12 months (June 2017 – May 2018) for all the 3 subcategories of Pork.


Business Rules:


While modeling for any of the Pork Sub category, you can use at max one subcategory from beef as an input feature and nothing from remaining pork subcategories (e.g. while modeling for Pork Chops: participants cannot use Bacon or Ham as input to the model and can use only one (at max) of the three columns for beef subcategory: Beef Steak, Beef Round or Ground Beef.


Evaluation


The evaluation metric for the competition is the mean arctangent absolute percentage error (MAAPE) on YOY:

Mean(Arctan(Abs((Actual_YOY – Predicted_YOY)/Actual_YOY)))
Refer to the sample_evaluation.xlsx file provided with the data to see an example of MAAPE calculation on the sample submission.

