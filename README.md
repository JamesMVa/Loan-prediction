# Loan-prediction
El presente proyecto tiene como objetivo predecir el estado del préstamo de los individuos. Para ello se procederá a explorar, limpiar, separar y generar la predicción con 5 modelos distintos (DecisionTree, LogisticRegression, XGBoost, RandomForestClassifier y GaussianNB).

Para el tratamiento de missings values se imputó datos con métodos no paramétricos. Para ello, se clasificó grupos de observaciones con un modelo no supervisado y se imputaron los datos más cercanos al grupo al cual pertenece. Este método resulta mejorar la calidad de los datos a comparación de si se hubiera reemplazado la moda o la mediana general a los missings values.

Base de datos obtenido de la página Kaggle (https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset).
