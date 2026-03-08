# challenger-3-alura-store-data-sciece
Challenger telecomxlatam part 2
# Telecom X – Predicción de Cancelación de Clientes (Churn)

##  Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar modelos de **Machine Learning capaces de predecir la cancelación de clientes (Churn)** en Telecom X.

A través del análisis de datos y la construcción de modelos predictivos, se busca identificar los **factores que influyen en la cancelación** y generar **insights estratégicos que ayuden a mejorar la retención de clientes**.

El proyecto forma parte del desafío **Telecom X – Parte 2: Predicción de Cancelación** del programa de formación en Data Science.

---

#  Objetivos

- Preparar los datos para modelos de Machine Learning.
- Analizar correlaciones entre variables y cancelación de clientes.
- Entrenar modelos de clasificación para predecir churn.
- Evaluar el rendimiento de los modelos con diferentes métricas.
- Identificar las variables más importantes en la predicción.
- Proponer estrategias de retención basadas en los resultados.

---

# Estructura del Proyecto
telecomx-churn-prediction

TelecomX_ML.ipynb # Notebook principal con el análisis y modelado
README.md # Documentación del proyecto
TelecomX_clean.csv # Dataset limpio proveniente del Challenger 2

---

# Modelos Utilizados

Se entrenaron dos modelos de clasificación:

##  Regresión Logística

- Modelo lineal interpretativo
- Requiere **normalización de datos**
- Permite analizar **coeficientes de las variables**

##  Random Forest

- Modelo basado en árboles de decisión
- No requiere normalización
- Permite analizar **importancia de variables**

---

# 📊 Métricas de Evaluación

Los modelos fueron evaluados utilizando:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Matriz de confusión**

### Resultados

| Modelo | Accuracy | Precision | Recall | F1-score |
|------|------|------|------|------|
| Regresión Logística | 0.80 | 0.64 | 0.57 | 0.60 |
| Random Forest | 0.78 | 0.61 | 0.50 | 0.55 |

El modelo de **Regresión Logística presentó el mejor desempeño general**.

---

#  Principales Factores de Cancelación

El análisis de variables mostró que los factores más influyentes en el churn son:

- **tenure** (tiempo de permanencia del cliente)
- **Charges.Total**
- **tipo de contrato**
- **InternetService_Fiber optic**
- **PaymentMethod_Electronic check**
- **Charges.Monthly**

Los clientes con **menor tiempo en la empresa y contratos mensuales** presentan mayor probabilidad de cancelar.

---

#  Insights Estratégicos

Los resultados del modelo sugieren que Telecom X podría reducir la cancelación mediante:

- Incentivos para **contratos de largo plazo**
- Estrategias de fidelización para **clientes nuevos**
- Revisión de la experiencia del servicio **Fiber Optic**
- Optimización de procesos asociados a **Electronic check**

---

#  Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

#  Cómo Ejecutar el Proyecto

1. Clonar el repositorio

```bash
git clone https://github.com/JuanCanchi19/telecomx-churn-prediction.git
```

2. Abrir el notebook en Google Colab o Jupyter Notebook

3. Ejecutar las celdas en orden para reproducir:

- preparación de datos

- análisis exploratorio

- entrenamiento de modelos

- evaluación de resultados

## Autor

Juan Canchila

Proyecto desarrollado como parte del desafío de Data Science – Telecom X.
