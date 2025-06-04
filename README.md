# 🚀 Proyecto de Exploración y Modelado con 🍭 Machine Learning 📊

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

Este repositorio es tu pasaporte a un vibrante viaje por el **universo del Machine Learning** ✨, encapsulado en un solo notebook. Aquí, no solo "codificamos", ¡sino que **creamos magia con datos**! 🧙‍♀️✨ Desarrollado por un equipo de entusiastas (Luis Salamanca, Javier Cerna, Vicente Solorza), este proyecto te guiará a través de un flujo de trabajo de ML completo, desde la curiosidad inicial hasta la evaluación de modelos súper potentes. 💥

## 💖 ¿Qué Dulces Sorpresas Encontrarás? 🍬

Adéntrate en el **`MLY0100_Entrega_2_Base-LuisSalamanca_JavierCerna_VicenteSolorza.ipynb`** y descubre:

### 🔍 **Análisis Exploratorio de Datos (EDA)** - *¡Desentrañando Misterios!* 🕵️‍♀️
Sumérgete en tus datos como si fueran un mapa del tesoro. 🗺️ Descubrirás:
* **Visualizaciones Hipnotizantes** 📊: Gráficos coloridos y dinámicos que revelan patrones ocultos.
    * Histogramas para distribuciones 📈
    * Gráficos de dispersión para relaciones ✨
    * Diagramas de caja para detección de *outliers* 📦
* **Estadísticas Descriptivas** 🔢: Medias, medianas, desviaciones estándar... ¡tus datos no tendrán secretos! 🤫
* **Ingeniería de Características** 👷‍♀️: Creando nuevas variables a partir de las existentes para mejorar el rendimiento del modelo. ¡La creatividad al poder! 💡

### 🧼 **Preprocesamiento de Datos** - *¡Puliendo la Gema!* 💎
Transformamos los datos brutos en una joya lista para el entrenamiento. Aquí verás:
* **Manejo de Valores Atípicos (Outliers)** 🗑️: Técnicas para identificar y gestionar esos puntos de datos rebeldes que pueden desequilibrar tus modelos. ⚖️
* **Escalado de Características** 📏: Normalización y estandarización para que tus algoritmos trabajen de manera óptima. ¡Adiós a los sesgos por escalas! 🥳
* **Codificación de Variables Categóricas** 🏷️: Transformando texto en números para que los modelos puedan entenderlo. ¡Magia numérica! ✨

### 🧠 **Modelado Predictivo Avanzado** - *¡Dando Vida a la IA!* 🤖
Hemos entrenado y comparado un verdadero **ejército de algoritmos de clasificación**. Cada uno con su superpoder:
* **Regresión Logística** 🎯: El clásico que nunca falla, ideal para clasificaciones binarias.
* **Máquinas de Vectores de Soporte (SVC)** 🧲: Encontrando el hiperplano perfecto para separar tus clases. ¡Poderoso y elegante! 💫
* **Árboles de Decisión** 🌳: Como un diagrama de flujo inteligente, fácil de entender y visualizar.
* **Random Forest** 🌲🌲🌲: ¡Un bosque entero de árboles de decisión trabajando juntos! La fuerza de la multitud. 💪
* **Gradient Boosting (¡Potenciando el rendimiento!)** 🚀: Construyendo modelos secuencialmente, corrigiendo errores del anterior. ¡Precisión al máximo! 🌟

### ✅ **Validación Cruzada (K-fold CV)** - *¡La Prueba Definitiva!* 🛡️
No nos conformamos con una sola evaluación. Utilizamos una estrategia de **5-fold Cross-Validation** para garantizar la robustez y generalización de nuestros modelos. ¡Sin trucos, solo ciencia sólida! 🔄

### 📊 **Métricas de Evaluación Clave** - *¡El Juicio de los Modelos!* 💯
Vamos más allá de la simple "precisión". Analizamos métricas cruciales para una comprensión completa del rendimiento de cada modelo:
* **Accuracy** ✅: ¿Cuántas predicciones correctas hizo el modelo en total?
* **Precision** 🎯: De todas las predicciones positivas, ¿cuántas fueron realmente correctas?
* **Recall** 🔍: De todas las instancias positivas reales, ¿cuántas fue capaz de detectar el modelo?
* **F1-score** ⚖️: El equilibrio perfecto entre Precision y Recall. ¡La métrica que lo tiene todo!

## 🎯 **Propósito Brillante** ✨
Este proyecto es una **plantilla viva y respirante** para cualquier entusiasta del Machine Learning. Demuestra un **flujo de trabajo estructurado, reproducible y con las mejores prácticas** para abordar problemas de clasificación. ¡Ideal para aprender, inspirarse y lanzar tus propios proyectos de ML! 🚀

## 🛠️ **El Kit de Herramientas Secreto** 🧰
Construido con el **dream team** de las librerías de Python para Ciencia de Datos:
* **Python** 🐍: El lenguaje de la ciencia de datos.
* **Pandas** 🐼: Para la manipulación y análisis de datos de forma mágica.
* **NumPy** 📏: La base para operaciones numéricas de alto rendimiento.
* **Scikit-learn** 🤖: Tu mejor amigo para construir y evaluar modelos de ML.
* **Jupyter Notebook** 📓: Nuestro laboratorio interactivo para experimentos de código y visualizaciones.

## 🏆 **Resultados y Comparativa** - *¡La Tabla de Honor!* 🏅
Dentro del notebook, encontrarás una **tabla comparativa clara y concisa** con las métricas de rendimiento promedio (5-fold CV) para cada modelo. ¡Podrás ver quién es el campeón! 👑

```python
# Ejemplo de la tabla que verás en el notebook:
# Comparación de modelos (5-fold CV promedio):
#                       Accuracy  Precision  Recall  F1-score
# Model
# Logistic Regression      0.985      0.850   0.720     0.780
# SVC                      0.970      0.750   0.650     0.696
# Decision Tree            0.992      0.880   0.850     0.865
# RandomForest             0.995      0.920   0.890     0.905
# GradientBoosting         0.996      0.930   0.900     0.915
