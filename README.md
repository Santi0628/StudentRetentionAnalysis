StudentRetentionAnalysis
Este repositorio contiene un análisis completo sobre la retención y deserción estudiantil utilizando técnicas de machine learning, con énfasis en modelos de Máquinas de Soporte Vectorial (SVM). El objetivo principal es identificar patrones y factores que influyen en los resultados académicos de los estudiantes.

Contenido del Proyecto

Preprocesamiento de Datos:
Limpieza y manejo de datos atípicos.
Balanceo de clases utilizando técnicas de undersampling.
Selección de características más relevantes mediante SelectKBest.

Modelos Implementados:
SVM con kernel lineal y kernel RBF.
Comparación de modelos para determinar el más efectivo.
Ajuste de hiperparámetros mediante GridSearchCV.

Evaluación del Modelo:
Métricas de evaluación: precisión, recall, F1-score.
Validación cruzada para garantizar la estabilidad del modelo.

Requisitos
Este proyecto utiliza Python y las siguientes bibliotecas:
pandas, numpy
sklearn
seaborn, matplotlib, plotly
imblearn
