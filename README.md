# 📊 EDA Dashboard – Análisis de Deuda en Empresa de Servicios

## 🧠 Descripción del Proyecto

Este proyecto consiste en la realización de un **Análisis Exploratorio de Datos (EDA)** sobre la deuda pendiente de una empresa de servicios, con el objetivo de:

- Analizar la distribución de los importes pendientes
- Evaluar los días hasta vencimiento
- Detectar concentración de riesgo financiero
- Diseñar un **dashboard en Excel** orientado a la toma de decisiones

El análisis se ha realizado utilizando **Excel**, aplicando técnicas estadísticas descriptivas y visualización de datos.

---

## 🎯 Objetivos del análisis

- Comprender cómo se distribuye la deuda entre clientes
- Identificar patrones de vencimiento
- Detectar concentración del riesgo (efecto Pareto)
- Evaluar dispersión y presencia de outliers
- Diseñar un dashboard claro y orientado a negocio

---

## 📂 Estructura del repositorio

eda_dashboard_excel/
├── Datos origen
├── Analisis deuda servicio Dashboard_transformacion.xlsx
├── README.md


---

## 📊 Variables Analizadas

### 1️⃣ Días_Hasta_Vencimiento
- Media: -152 días
- Mediana: -11 días
- Asimetría: -6
- Curtosis: 51

**Conclusión:**  
Distribución fuertemente sesgada a la izquierda con presencia de deudas muy antiguas concentradas en pocos clientes.

---

### 2️⃣ Importe_Pendiente
- Media: 6.231 €
- Mediana: 314 €
- Asimetría: 18,84
- Curtosis: 436,39
- Máximo: 1.032.263 €
- Total pendiente: 67,88 M€

**Conclusión:**  
La deuda está altamente concentrada en un pequeño grupo de clientes con importes muy elevados.

---

## 📈 Análisis Estadístico

### 🔹 Distribución
- Alta dispersión
- Presencia de outliers extremos
- Media no representativa
- Mediana como métrica clave

### 🔹 Concentración del riesgo
El análisis sugiere un comportamiento tipo **80/20**, donde:
- Un pequeño porcentaje de clientes concentra la mayor parte del importe pendiente.

### 🔹 Segmentación por tramos
Se han creado tramos de análisis tanto para:
- Importes pendientes
- Días hasta vencimiento

Esto permite priorizar la gestión de cobros.

---

## 📊 Dashboard en Excel

El dashboard incluye:

### 🔢 KPIs principales
- Importe total pendiente
- Mediana del importe
- % deuda vencida
- % deuda crítica (>180 días)
- Máximo importe pendiente

---

### 📊 Gráficos principales

1. **Barras por tramos de importe**
2. **Barras por tramos de vencimiento**
3. **Boxplot del importe pendiente**
4. **Gráfico de Pareto**
5. **Dispersión: Importe vs Días hasta vencimiento**

---

## 🧠 Principales Insights

- La mayoría de clientes presenta importes pequeños.
- El riesgo financiero está concentrado en pocos clientes.
- La media distorsiona la realidad del cliente típico.
- Existen deudas extremadamente antiguas que requieren revisión.
- La segmentación por tramos mejora la priorización operativa.

---

## 🛠 Herramientas utilizadas

- Microsoft Excel
  - Tablas dinámicas
  - Segmentación por tramos
  - Estadísticos descriptivos
  - Gráficos dinámicos
  - Dashboard interactivo

---

## 📌 Conclusión Final

El análisis demuestra que la deuda no está distribuida de manera homogénea.  
El riesgo financiero está altamente concentrado, lo que obliga a una gestión estratégica basada en:

- Priorización por importe
- Priorización por antigüedad
- Identificación de clientes críticos

El dashboard desarrollado permite visualizar esta información de forma clara y orientada a la toma de decisiones.

---

## 🚀 Posibles mejoras futuras

- Integración con SQL o Power BI
- Automatización de actualización de datos
- Modelización predictiva de impagos
- Scoring de riesgo por cliente
- Análisis temporal de evolución de deuda

---

## 👤 Autor

Proyecto desarrollado como parte de un análisis exploratorio de datos enfocado en la gestión financiera y optimización de cobros.
