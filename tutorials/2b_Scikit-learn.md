# Scikit-learn

## Cel

Celem tego zadanie jest przygotowanie kodu, który wykona zadanie klasyfikacji binarnej za pomocą algorytmów uczenia maszynowego. kNN jest modelem prostym, dlatego bardziej należy się skupić na wykonaniu poprawnie pipelinu danych oraz dogłębnym zrozumieniu stosowanych metod.

## Pipeline

### Podział na zbiór testowy i treningowy

Najważniejszy etap, zawsze wykonywany na początku pracy z danymi. \
[train_test_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)

### Preprocessing danych

Należy pamiętać, że wszystkie metody powinny być fit'owane na zbiorze treningowym, a zbiór testowy powinien być tylko przez nie transformowany. \
[Preprocessing](https://scikit-learn.org/stable/modules/preprocessing.html)

### Wyuczenie modelu i obliczenie miar

Wyuczenie modelu kNN na zbiorze treningowym oraz sprawdzenie jego dokładności na zbiorze testowym. \
[KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html) \
[KNN](https://www.youtube.com/watch?v=HVXime0nQeI) \
[Analytics Vidhya Guide](https://www.analyticsvidhya.com/blog/2018/03/introduction-k-neighbours-algorithm-clustering/) \
[Classification Metrics](https://scikit-learn.org/stable/modules/model_evaluation.html#classification-metrics)

Celem tego zadania jest eksploracja rozwiązań, które umożliwia nam paczka scikit-learn. Dojrzalszy wybór modelów, metody przeszukań przestrzeni hiperparametrów, tworzenia zespołów klasyfikatorów.

## Poradniki

Modele, które według mnie są warte uwagi i przetestowania: \
[Drzewo decyzyjne](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier) \
[Support Vector Machine](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html#sklearn.svm.SVC) \
[Naive Bayes](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html#sklearn.naive_bayes.GaussianNB)

- [Dokumentacja scikit-learn: KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)

Reszta: \
[Cross-validation (warto też przejrzeć Hyper-parameter optimizers)](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.model_selection) \
[Zespół klasyfikatorów](https://scikit-learn.org/stable/modules/classes.html#module-sklearn.ensemble)

- [KNN](https://www.youtube.com/watch?v=HVXime0nQeI)
- [Random Forest](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ&pp=ygUXc3RhdHF1ZXN0IHJhbmRvbSBmb3Jlc3Q%3D)
- [SVM](https://www.youtube.com/watch?v=efR1C6CvhmE&pp=ygUNc3ZtIHN0YXRxdWVzdA%3D%3D)
- [Drzewo Decyzyjne](https://www.youtube.com/watch?v=_L39rN6gz7Y&pp=ygUYRGVjaXNpb24gdHJlZXMgc3RhdHF1ZXN0)
- [Naive bayes](https://www.youtube.com/watch?v=O2L2Uv9pdDA&pp=ygUUbmFpdmUgYmF5ZXNzdGF0cXVlc3Q%3D)
