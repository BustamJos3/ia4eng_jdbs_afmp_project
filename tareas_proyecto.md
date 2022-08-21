_CONVENCIONES_
```
(iniciales_nombre_completo): encargado a alguien
(***): hecho
(~~): logrado
(--_): falta por revisar
```


# TAREAS_IA

## Objetivos

### macro_tareas
4. encontrar los mejores hiperparámetros para DOS algoritmos predictivos

5. encontrar los mejores hiperparámetros para DOS combinaciones de algoritmo 
no supervisado + algoritmo predictivo

6. realizar las curvas de aprendizaje para cada uno de los cuatro casos anteriores

7. realizar una evaluación diagnóstica que contenga:

7.1 para cada uno de los cuatro casos anteriores un diagnóstico de 
overfitting/bias etc.

7.2 una recomendación justificada de qué pasos a seguir si tuvieras que intentar 
mejorar el desempeño obtenido.

7.3 una evaluación sobre los retos y condiciones para desplegar en producción un 
modelo (como establecerías el nivel de desempeño mínimo para desplegar en producción, 
cómo se desplegaría en producción, cómo serían los procesos de monitoreo del desempeño 
en producción)

### micro_tareas

#### ENTREGA 2
1. realizar material para empezar a hacer video (JDBS, AFMP)
2. crear colabs para trabajo con datasets (JDBS)[exploracion creado***]
3. enlazarlos con repos (JDBS)[exploracion enlazado***]
5. Hacer informe ENTREGA 2 (JDBS, AFMP)
-> Hacer introducción (AFMP)
##### EN PROYECTO (con dataset)
1. División de test en: 1) test_validation, 2)test_test--->***Partirlos de manera que sea representativa
2. Inducción de datos NaN--->Qué datos serán datos NaN
3. Criterio de llenado de datos NaN->(1. investigar critérios a la hora de reemplazar valores nulos o NaN)(AFMP)
4. Evaluacion de correlación entre columnas (variables) a través de la matriz de gráficas de correlación
5. Creación de métrica de ML y pruebas de implementación con datos de control sintéticos
6. ..
7. ..

--->creo que lo mejor es ir viendo datasets y tratar de definir el problema según el contexto
de los datasets

------**que hara c/u**------

# ENLACES INTERÉS
## Misceláneo
- [Git and GitHub Tutorial For Beginners | Full Course [2021]](https://www.youtube.com/watch?v=3fUbBnN_H2c&ab_channel=Amigoscode)
- [Performance Measures for Multi-Class Problems](https://www.datascienceblog.net/post/machine-learning/performance-measures-multi-class-problems/)
- [How To Load Kaggle Dataset In Your Colab/Jupyter Notebook Without Downloading](https://buggyprogrammer.com/load-kaggle-dataset-in-colab-or-jupyter/)
- [Using Google Colab with GitHub: Saving Notebooks To GitHub or Drive](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb#scrollTo=8QAWNjizy_3O)
- [IO tools (text, CSV, HDF5, …): Iterating through files chunk by chunk](https://pandas.pydata.org/docs/user_guide/io.html)
- [Welcome to pytablewriter’s documentation!: python module to write tables in several formats](https://pytablewriter.readthedocs.io/en/latest/index.html#welcome-to-pytablewriter-s-documentation)
### ScikitLearn documentación
- [Para determinar las variables más importantes (columnas, features, etc): 4.2. Permutation feature importance](https://scikit-learn.org/stable/modules/permutation_importance.html)
- [Para seleccionar las variables en función de su grado de importancia: 1.13. Feature selection](https://scikit-learn.org/stable/modules/feature_selection.html)
- [---> Documentación acerca de conducto de transformaciones-Pipeline of transforms-sklearn.pipeline.Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html#sklearn.pipeline.Pipeline)
- [---> Documentación acerca del encadenamiento entre transformaciones y clasificadores: 6.1. Pipelines and composite estimators](https://scikit-learn.org/stable/modules/compose.html#pipeline)
- [(--_)---> Manera rápida de hacer una Pipeline-sklearn.pipeline.make_pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.make_pipeline.html#sklearn.pipeline.make_pipeline)
- [(--_)--->Ejemplo de feature importance con forest of decision tress: Feature importances with a forest of trees](https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html#sphx-glr-auto-examples-ensemble-plot-forest-importances-py)
- [Para plotear variables de manera independiente y ver su comportamiento respecto a la variable objetivo: 4.1. Partial Dependence and Individual Conditional Expectation plots](https://scikit-learn.org/stable/modules/partial_dependence.html)
## Archivos de entregas PDF
- enlace a arhivo PROYECTO_ENTREGA1.tex _**definitivo**_, overleaf : [Forest Cover Type Prediction, use cartographic variables to classify forest categories](https://www.overleaf.com/8579998717zjrrdcgmnpqk)
- enlace a arhivo PROYECTO_ENTREGA1.tex **opcional**, overleaf : [American express](https://www.overleaf.com/5998522951rfchkzvnzxtf)
- enlace a arhivo PROYECTO_ENTREGA2.tex **_definitivo_**, overleaf : [Entrega 2](https://www.overleaf.com/1932649754ffysfmrjxnkk)

## DATASETS
- [incumplimientos de créditos de american express](https://www.kaggle.com/competitions/amex-default-prediction)
- [Forest Cover Type Prediction, use cartographic variables to classify forest categories](https://www.kaggle.com/competitions/forest-cover-type-prediction/data?select=train.csv)
