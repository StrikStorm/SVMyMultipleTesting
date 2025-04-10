
# SVM y Selección de Características usando Pruebas Múltiples

Este proyecto aplica técnicas de análisis estadístico y modelos de clasificación utilizando Máquinas de Vectores de Soporte (SVM) sobre un conjunto de datos con múltiples clases. Se realiza una selección de características usando análisis de varianza (ANOVA) y pruebas de hipótesis, enfocándose en identificar los atributos más relevantes para la clasificación.

## Contenido del Notebook

1. **Carga y limpieza de datos:**  
   Se importa la base de datos y se verifica la presencia de valores nulos.

2. **Selección de características:**  
   - Comparación de promedios entre clases específicas.
   - Evaluación de p-values y estadísticas t.
   - Análisis de varianza (ANOVA) entre las 4 clases del dataset.
   - Filtrado de características con p-value < 0.05.

3. **Modelado con SVM:**  
   Se entrenan y comparan tres modelos:
   - SVM Lineal  
   - SVM con kernel Polinomial (grado 3)  
   - SVM con kernel RBF (Radial)

4. **Evaluación de modelos:**  
   Se analizan las métricas de precisión y desempeño de cada modelo sobre los datos de entrenamiento y prueba.


Si quieres analizar el [NoteBook](./SVMyMultipleTesting.ipynb), si no lo quieres descargar aqui en [HTML](./SVMyMultipleTesting.html) y la [Base de datos](./Khan.csv) que se utilizo.
