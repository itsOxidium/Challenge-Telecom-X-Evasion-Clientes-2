# Challenge-Telecom-X-Evasion-Clientes-2
# 📦 Churn Prediction para Telecom X Part 2


Este proyecto aplica técnicas de Machine Learning para predecir la cancelación de clientes en una empresa de telecomunicaciones. Se construyó un pipeline robusto y reproducible, con visualizaciones claras y recomendaciones accionables para stakeholders.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10Xpa066vNH16a2OF4JLPOtnVoTDC5ICL?usp=sharing)


https://colab.research.google.com/drive/1akkxoBnClEG4ZcsJdhxSSZas5S6Ym2xY?usp=sharing
## 📚 Índice

- [🔍 Introducción](#introducción)
- [🎯 Objetivos](#objetivos)
- [🧪 Metodología](#metodología)
- [📊 Resultados](#resultados)
- [📈 Visualizaciones](#visualizaciones)
- [🧠 Conclusiones](#conclusiones)
- [🚀 Recomendaciones](#recomendaciones)
- [📁 Estructura del repositorio](#estructura-del-repositorio)

---

## 🔍 Introducción

La cancelación de clientes (churn) representa una pérdida significativa para empresas de telecomunicaciones. Este proyecto busca identificar los factores clave que influyen en la decisión de cancelar y construir modelos predictivos que permitan anticipar este comportamiento.

---

## 🎯 Objetivos

- Construir un pipeline reproducible para predecir churn.
- Identificar variables clave que influyen en la cancelación.
- Evaluar múltiples modelos de clasificación.
- Comunicar resultados de forma clara y accionable.

---

## 🧪 Metodología


1. **Preprocesamiento**: limpieza, codificación, balanceo (SMOTE), normalización.
2. **EDA**: visualización de distribuciones, correlaciones y outliers.
3. **Modelado**: Regresión Logística, Random Forest, SVM, KNN, XGBoost.
4. **Evaluación**: Accuracy, ROC AUC, matriz de confusión.
5. **Interpretación**: análisis de importancia de variables y recomendaciones.

---

## 📊 Resultados

- XGBoost y Random Forest ofrecieron el mejor rendimiento predictivo.
- Regresión Logística y SVM facilitaron la interpretación.
- Variables como `Contract`, `tenure`, y `MonthlyCharges` fueron clave para predecir churn.

---

## 📈 Visualizaciones


- 🔥 Heatmaps de correlación
- 🎻 Violinplots por tipo de contrato
- 📦 Boxplots de cargos mensuales
- 📉 Curvas ROC comparativas

Todas las visualizaciones están integradas en el notebook y explicadas paso a paso.

---

## 🧠 Conclusiones

- Clientes con contratos mensuales y baja antigüedad tienen mayor probabilidad de cancelar.
- Cargos mensuales elevados y falta de servicios como `TechSupport` aumentan el riesgo.
- Los modelos permiten segmentar clientes en riesgo y diseñar estrategias de retención.

---

## 🚀 Recomendaciones

- Incentivar contratos anuales y automatización de pagos.
- Ofrecer paquetes personalizados para clientes con cargos altos.
- Promover servicios de seguridad y soporte técnico.
- Implementar dashboards interactivos para monitoreo en tiempo real.

---

