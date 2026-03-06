# Modelado predictivo de la deserción universitaria

---

## Resumen del Proyecto
Este proyecto utiliza técnicas de **Machine Learning** para predecir la deserción estudiantil a partir de una caracterización de ingreso. El objetivo es proporcionar una herramienta de decisión estratégica que optimice los recursos institucionales para generar una focalización más eficiente.

## 📑 Índice del cuadernillo
El desarrollo técnico paso a paso se encuentra en el archivo Jupyter Notebook principal, estructurado de la siguiente manera:

* Reporte de cambios efectuados frente a la configuración base
* Importación de librerías y dependencias
* Lectura de la base de datos
* Definición de X y Y
* Eliminación de variable problema
* División en train y test
* Identificación de variables a escalar
* Definición de preprocesamiento y pipeline
* Definición de modelos base
* Definición de grids de hiperparámetros
* Validación cruzada
* Entrenamiento con GridSearchCV (Optimizado para F1)
* Matrices de confusión
* Comparación de curvas ROC
* Comparación de curvas precision-recall
* Curvas de aprendizaje
* Interpretación conjunta de métricas y gráficas
* Coeficientes del modelo de regresión logística con penalización LASSO
* Generación de Score Card completo con el conjunto de prueba (deciles de probabilidad) 
* Resumen por decil
* Curva de ganancia
* Sensibilidad y precisión del modelo tras usar Score Card
* Matriz de confusión tras usar Score Card
* Exportar datos a Excel

## Hallazgos principales
El modelo LASSO permitió identificar variables críticas que aumentan la probabilidad de abandono, tales como el origen territorial, el género y el capital económico y educativo familiar. 

## Evaluación de deciles de probabilidad
Se validó una estrategia de intervención limitada al **30% de la muestra** con mayor probabilidad de riesgo, obteniendo los siguientes resultados:

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** Pandas, Scikit-Learn, Matplotlib, Seaborn.
* **Algoritmo:** Regresión Logística con penalización L1 (LASSO).

---
