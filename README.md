Análisis de Eficiencia Logística y Predicción de Retrasos

Este proyecto aplica técnicas de Data Science para identificar y predecir riesgos de retraso en una cadena de suministro global. El objetivo principal es transformar una gestión logística reactiva en una proactiva mediante el uso de aprendizaje automático.

Problemática
La empresa presenta una falla sistémica en la estimación de tiempos de entrega, con un 54.83% de entregas tardías. Esto afecta la confianza del cliente y genera costos operativos adicionales.

Metodología Aplicada
Para este análisis se siguieron los pasos metodológicos requeridos en el curso:


Selección de Datos: Se utilizó un dataset con 180,519 registros y 53 variables.

Limpieza y Preprocesamiento (EDA):
Tratamiento de valores nulos e imputación de códigos postales.
Eliminación de variables irrelevantes o sensibles para optimizar el rendimiento.


Modelado: Implementación de un algoritmo de Random Forest Classifier.
### Evaluación del Modelo
El modelo alcanzó una precisión (Accuracy) de **0.69**. A continuación, se presenta la Matriz de Confusión que detalla el desempeño del algoritmo:

![Matriz de Confusión](matriz_confusion.png)



Tecnologías Utilizadas
Lenguaje: Python.
Librerías: Pandas, Scikit-learn, Matplotlib y Seaborn.
Entorno: Google Colab.

Conclusiones y Propuestas Administrativas
Basado en los hallazgos, se proponen las siguientes acciones para la administración de la empresa:
Alertas Preventivas: Priorizar pedidos detectados con alto riesgo de retraso.
Sinceramiento de SLA: Ajustar promesas de entrega en regiones críticas según los datos reales.
Optimización de Costos: Reducir gastos por reclamos y devoluciones.
