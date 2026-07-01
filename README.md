📈 Churn = 20,4%

🎯 Mejor modelo: Stacking

📊 ROC-AUC: 0.87

👥 Dataset: 10.000 clientes

🤖 Modelos evaluados: 6

# 🏦 Predicción de Churn Bancario


> Pipeline End-to-End de Machine Learning para predecir el abandono de clientes y generar recomendaciones estratégicas de negocio.

---


## 📌 Descripción del proyecto

La pérdida de clientes (*customer churn*) representa uno de los principales desafíos para las entidades financieras, ya que impacta directamente sobre:

- Customer Lifetime Value (CLV)
- Costos de adquisición y retención
- Estabilidad de los ingresos

En este proyecto se desarrolla un pipeline completo de Ciencia de Datos que combina modelos supervisados y no supervisados para predecir el abandono de clientes, comprender sus principales causas y aportar información útil para la toma de decisiones.

El enfoque no estuvo únicamente en obtener un buen modelo predictivo, sino también en traducir los resultados en recomendaciones accionables para el negocio.

---

# 🎯 Objetivos

- Predecir la probabilidad de abandono de cada cliente.
- Identificar las variables que más influyen en el churn.
- Comparar distintos modelos de Machine Learning.
- Segmentar clientes según su comportamiento.
- Generar recomendaciones para estrategias de retención.

**Variable objetivo**

**Exited**

- 1 → Cliente abandona el banco.
- 0 → Cliente permanece.

---

# 📂 Estructura del repositorio

| Notebook | Descripción |
|-----------|-------------|
| **1_EDA_RegresionLogistica.ipynb** | Análisis exploratorio, limpieza, preprocesamiento y modelo base mediante Regresión Logística. |
| **2_GradientBoosting_Optimizacion.ipynb** | Implementación de Random Forest, XGBoost, LightGBM, CatBoost y Stacking, junto con la optimización de hiperparámetros. |
| **3_AprendizajeNoSupervisado.ipynb** | Segmentación de clientes mediante K-Means y análisis de perfiles. |
| **4_Reporte_Modelos.ipynb** | Comparación de modelos e interpretación de resultados. |
| **4_Reporte_Modelos2.ipynb** | Consolidación del proyecto y recomendaciones estratégicas para el negocio. |

---

# 📊 Fase 1 – Modelo Base

## Trabajo realizado

- Análisis Exploratorio de Datos (EDA)
- Ingeniería de variables
- Escalado
- Codificación de variables categóricas
- Regresión Logística
- Matriz de confusión
- ROC-AUC
- PR-AUC
- Interpretación mediante Odds Ratio

### Principales hallazgos

- La edad incrementa significativamente el riesgo de abandono.
- Los clientes de Alemania presentan mayor probabilidad de churn.
- Un alto balance combinado con baja actividad incrementa el riesgo.
- Ser un cliente activo reduce considerablemente la probabilidad de abandono.

---

# ⚡ Fase 2 – Modelos de Ensamble

## Modelos implementados

- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Stacking Classifier

## Técnicas aplicadas

- Validación cruzada estratificada
- GridSearchCV
- Optimización de hiperparámetros
- Early Stopping
- Regularización
- Feature Importance

### Principales resultados

Los modelos de Gradient Boosting superaron al modelo lineal en capacidad predictiva, mientras que el modelo Stacking permitió combinar las fortalezas de distintos algoritmos.

---

# 🔬 Fase 3 – Aprendizaje No Supervisado

Para complementar la predicción del churn se realizó una segmentación de clientes mediante K-Means.

Esta etapa permitió identificar distintos perfiles de clientes y relacionarlos con el riesgo de abandono, aportando una visión más estratégica para el diseño de campañas de retención.

---

# 📈 Fase 4 – Consolidación

Se realizó una comparación integral de los modelos desarrollados, evaluando:

- ROC-AUC
- PR-AUC
- Precision
- Recall
- Matriz de confusión
- Umbral de decisión

Finalmente se elaboró un reporte ejecutivo con recomendaciones orientadas a negocio.

---

# 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn

---

# 💼 Competencias demostradas

- Machine Learning End-to-End
- Clasificación binaria
- Aprendizaje supervisado
- Aprendizaje no supervisado
- Optimización de hiperparámetros
- Validación cruzada
- Interpretación de modelos
- Segmentación de clientes
- Storytelling con datos
- Traducción de métricas técnicas a impacto de negocio

---

# ⭐ Valor agregado del proyecto

- Combina interpretabilidad y desempeño predictivo.
- Integra modelos supervisados y no supervisados.
- Incorpora métricas relevantes para negocio.
- Presenta recomendaciones accionables para equipos de retención.
- Desarrollado con un enfoque cercano a un caso de uso real en banca.
