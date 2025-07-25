# Proyecto de Machine Learning – UTN

Este repositorio contiene dos trabajos prácticos desarrollados en el curso de *Machine Learning con Python* (Universidad Tecnológica Nacional, 2025), donde se aplicaron técnicas de regresión, clasificación, clustering, análisis de imágenes y reducción de dimensionalidad.

## 🧠 Herramientas utilizadas

- **Lenguaje:** Python
- **Entorno:** Jupyter Notebook
- **Librerías:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Otros:** Apache Spark, Pillow, BeautifulSoup, Selenium, Django REST Framework

---

## 📊 Trabajo Práctico Intermedio

### 🔹 Ejercicio 1: Regresión Lineal Múltiple
- Dataset: `advertising.csv`
- Objetivo: predecir ventas a partir de inversiones publicitarias en TV, radio y prensa
- Técnicas:
  - División train/test
  - Entrenamiento de regresión lineal
  - Evaluación con MAE, MSE, R², error porcentual
  - Gráficos de dispersión y error

✅ **Resultado:** Modelo con R² > 0.9 y errores porcentuales < 30%

---

### 🔹 Ejercicio 2: Clasificación de vinos (Wine dataset)
- Clasificadores: regresión logística, KNN, SVM
- Comparación entre datos normalizados vs. originales
- Métricas evaluadas: *accuracy* y matriz de confusión

✅ **Resultado:** Modelos normalizados alcanzaron > 95% de precisión

---

## 🧬 Trabajo Práctico Final

### 🔹 Ejercicio 1: Clustering no supervisado + PCA (Wine dataset)
- PCA aplicado para reducir a 2D
- Clustering con KMeans (k=2 a 5) y Affinity Propagation
- Métrica usada: `adjusted_rand_score` sobre test set

✅ **Resultado:** ARI > 90% en clustering con propagación de afinidad

---

### 🔹 Ejercicio 2: Clasificación de rostros humanos (LFW dataset)
- PCA para compresión de imágenes (varianza explicada > 80%)
- Clasificadores: regresión logística, KNN y SVM
- Evaluación con *accuracy* y matrices de confusión

✅ **Resultado:** Dos modelos superaron el 80% de precisión

---

## 📈 Conclusión

Estos trabajos reflejan la aplicación práctica de técnicas de Machine Learning en problemas reales de predicción, clasificación y reducción de dimensionalidad. El enfoque fue técnico, progresivo y orientado a resultados. Ambos trabajos fueron calificados con **más de 9 puntos** sobre 10.
