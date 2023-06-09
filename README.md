# Individual Project for ML Course
This repository contains the individual project assigned in the course of Mathematical Modelling for Machine Learning, held in the second semester of my second year at university.

## Assignment
This dataset is composed of 1300 samples with 35 features each. The first column is the sample id. The second column in the dataset represents the label. There are 3 possible values for the labels. The remaining columns are numeric features.

Notice that the classes are unbalanced: some labels are more frequent than others. You need to decide whether to take this into account, and if so how.

Your task is the following: you should compare the performance of Logistic Regression (implemented by sklearn.linear_model.LogisticRegression) with that of
a Random Forest (implemented by sklearn.ensemble.RandomForestClassifier). Try to optimize both algorithms' parameters and determine which one is best for this dataset. At the end of the analysis, you should have chosen an algorithm and its optimal set of parameters: write this choice explicitly in the conclusions of your notebook.

Your notebook should detail the procedure you have used to choose the optimal parameters (graphs are a good idea when possible/sensible).

The notebook will be evaluated not only based on the final results, but also on the procedure employed, which should balance practical considerations (one may not be able to exhaustively explore all possible combinations of the parameters) with the desire for achieving the best possible performance in the least amount of time.

Bonus points may be assigned for particularly clean/nifty code and/or well-presented results.

You are also free to attempt other strategies beyond the one in the assignment (which however is mandatory!).

## Notes

- Feel free to check out the [syllabus](https://didattica.unibocconi.it/ts/tsn_anteprima.php?cod_ins=30554&anno=2023&IdPag=6896) of the course.
- The data used for the project is randomly generated and is available only upon request.
