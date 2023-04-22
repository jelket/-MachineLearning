### Реализованы следующие алгоритмы машинного обучения:

* Logistic Regression
* SVM
* KNN
* Naive Bayes 

Классы наследуются от BaseEstimator и ClassifierMixin. Процесс предобработки и обучения происходит с помощью Pipeline. Гиперпараметры моделей подобраны с помощью кросс валидации GridSearchCV.

Также алгоритмы сравниваются с коробочными решениями SkLearn

### Получены мертрики:

* Confusion Matrix
* Accuracy
* Recall
* Precision
* ROC_AUC
