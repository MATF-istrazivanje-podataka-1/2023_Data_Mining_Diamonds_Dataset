# Project - University of Belgrade, Faculty of Mathematics  

Dataset: https://www.tensorflow.org/datasets/catalog/diamonds  

Ucitavanje iz **tensorflow_datasets** biblioteke: 

->ds = tfds.load('diamonds', split='all')  
->assert isinstance(ds, tf.data.Dataset)  
->data = tfds.as_dataframe(ds)  

***
Models:  
1. Clasification: DecisionTreeClassifier, KNeighborsClassifier, MLPClassifier, CategoricalNB, RandomForestClassifier and XGBClassifier  
2. Clustering: KMeans, AgglomerativeClustering, DBSCAN, SpectralClustering
3. Association rules: Apriori 


Autor: Luka Arambasic 169/2020  
Profesor: prof. dr Nenad Mitic  
Asistent: Stefan Kapunac
