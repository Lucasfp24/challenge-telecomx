# 📊 TelecomX LATAM - Análisis de Churn y Estrategia de Retención

Este proyecto forma parte de un desafío técnico centrado en la industria de las telecomunicaciones. El objetivo principal es analizar el comportamiento de los clientes de TelecomX en la región LATAM para identificar patrones de abandono (Churn) y proponer estrategias basadas en datos para mejorar la retención.

---

## 📋 Descripción del Proyecto
El análisis se centra en un conjunto de datos que incluye información demográfica, servicios contratados, historial de facturación y estado de permanencia de los clientes. A través de este notebook, se realiza un proceso completo de Data Science, desde la limpieza inicial hasta la visualización de hallazgos clave.

---

## 🎯 Objetivos del Proyecto
El análisis se diseñó para cumplir con los siguientes pilares estratégicos:

**Identificar Factores de Fuga:** Determinar cuáles son las variables demográficas y de servicio (tipo de contrato, internet, soporte técnico) que tienen mayor correlación con el abandono de clientes.

**Segmentación de Perfiles:** Clasificar a los usuarios según su comportamiento de consumo y lealtad para entender qué grupos son más vulnerables.

**Limpieza y Curación de Datos:** Transformar un dataset crudo en una fuente de información confiable, gestionando valores nulos y tipos de datos inconsistentes.

**Generar Insights de Negocio:** Proveer recomendaciones accionables, como la promoción de contratos a largo plazo o la mejora en servicios de valor agregado, para reducir la tasa de Churn.

---

## 🛠️ Tecnologías Utilizadas
Lenguaje: Python 3

Entorno: Jupyter Notebook

Librerías Principales:

Pandas: Manipulación y limpieza de datos.

NumPy: Operaciones numéricas.

Matplotlib & Seaborn: Visualización de datos y análisis estadístico gráfico.

---

## 📊 Estructura del Análisis
El notebook está organizado en las siguientes secciones:

- Carga y Exploración Inicial: Inspección de la estructura del dataset, tipos de variables y detección de valores nulos.

- Limpieza de Datos: Tratamiento de datos faltantes, corrección de tipos de datos (como la conversión de TotalCharges a numérico) y eliminación de duplicados.

- Análisis Exploratorio de Datos (EDA):

- Distribución de la variable objetivo (Churn).

- Relación entre el tipo de contrato y la fuga de clientes.

- Impacto de los métodos de pago y servicios adicionales (Streaming, Seguridad Online, etc.).

- Insights Clave: Identificación de los segmentos de clientes con mayor riesgo de abandono.

---

## 📈 Hallazgos Principales

El riesgo de abandono es crítico durante los primeros 6 meses y disminuye drásticamente a medida que el cliente gana antigüedad.

La volatilidad de los planes mensuales genera un churn mucho mayor que la estabilidad de los contratos a 1 o 2 años.

La fibra óptica y la facturación digital presentan un riesgo mas alto de desercion a pesar de ser opciones modernas.

El cheque electrónico se destaca como un método de pago asociado a una alta tasa de cancelación.

---

Autor: **Lucas Pruya**
Proyecto desarrollado como parte del *Challenge Telecom X Latam*  
📅 Año: 2025
