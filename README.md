# scikit-learn-pipeline
**Pipeline** can be used to chain multiple estimators into one. This is useful as there is often a fixed sequence of steps in processing the data, for example feature selection, normalization and classification. </br>
Pipeline serves multiple purposes here:

Convenience and encapsulation </br>
- You only have to call fit and predict once on your data to fit a whole sequence of estimators.

Joint parameter selection </br>
- You can grid search over parameters of all estimators in the pipeline at once.

Safety</br>
- Pipelines help avoid leaking statistics from your test data into the trained model in cross-validation, by ensuring that the same samples are used to train the transformers and predictors.</br>

[sklearn.pipeline](https://scikit-learn.org/stable/api/sklearn.pipeline.html)
