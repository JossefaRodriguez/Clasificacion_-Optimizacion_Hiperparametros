# 🧠 Clasificación y Optimización de Hiperparámetros (Core)

## 🎯 Objetivo

Implementar un pipeline completo de *machine learning* para un problema de clasificación, utilizando técnicas de preprocesamiento, modelado y optimización de hiperparámetros. El enfoque principal está en la limpieza de datos y la comparación entre **GridSearchCV** y **RandomizedSearchCV** para mejorar el rendimiento de los modelos.

---

## 📊 Dataset: Medical Cost Personal Dataset

Este dataset contiene información sobre factores que influyen en los costos de seguros médicos, como:

- Edad
- Sexo
- Índice de masa corporal (BMI)
- Número de hijos
- Hábito de fumar
- Región geográfica
- Costo del seguro

Es ideal para aplicar técnicas de preprocesamiento y clasificación, ya que incluye variables numéricas y categóricas, además de posibles outliers y datos faltantes.

---

## 🧪 Instrucciones del Proyecto

### 1. 🔍 Carga y Exploración Inicial
- Cargar el dataset desde Kaggle.
- Explorar la estructura y tipos de variables.
- Identificar valores faltantes y outliers.
- Documentar hallazgos iniciales.

### 2. 🧼 Preprocesamiento de Datos
- Imputación de valores faltantes (media, mediana, moda).
- Codificación de variables categóricas con **One-Hot Encoding**.
- Escalado de variables numéricas con **StandardScaler**.
- Separación en conjunto de entrenamiento y prueba.

### 3. 🤖 Implementación de Modelos
- Entrenar tres modelos de clasificación:
  - **Regresión Logística**
  - **K-Nearest Neighbors (KNN)**
  - **Árbol de Decisión**
- Evaluar rendimiento inicial con **validación cruzada (CV)**.

### 4. ⚙️ Optimización de Hiperparámetros
- Aplicar **GridSearchCV** para búsqueda exhaustiva.
- Aplicar **RandomizedSearchCV** como alternativa más eficiente.
- Comparar resultados de ambos métodos para cada modelo.

### 5. 📈 Evaluación Final
- Calcular métricas de rendimiento:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC
- Generar y analizar la **matriz de confusión**.
- Visualizar la **curva ROC** para cada modelo optimizado.

### 6. 📚 Documentación y Entrega
- Documentar todo el proceso en un notebook de Jupyter.
- Justificar cada decisión técnica con explicaciones claras.
- Subir el notebook y resultados al repositorio de GitHub.
- Crear un **tag de liberación `v1.0.0`** para esta versión del proyecto.


