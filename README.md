# 📊 Dashboard Ejecutivo para el Análisis de Ventas y Rentabilidad

## 📌 Descripción

Este proyecto consiste en el desarrollo de un dashboard interactivo en **Power BI** para analizar el desempeño comercial de una empresa utilizando un conjunto de datos de ventas.

El objetivo es transformar datos en información útil mediante indicadores clave (KPIs), visualizaciones interactivas y análisis de rentabilidad que faciliten la toma de decisiones.



## 🎯 Objetivos

- Analizar el comportamiento de las ventas y ganancias.
- Identificar las categorías y regiones con mejor desempeño.
- Evaluar el impacto de los descuentos sobre la rentabilidad.
- Proporcionar indicadores ejecutivos que apoyen la toma de decisiones.



## 📁 Dataset

El análisis se realizó utilizando el dataset público **Sample Superstore**, que contiene información relacionada con:

- Ventas
- Categorías y subcategorías de productos
- Regiones y estados
- Descuentos
- Ganancias
- Cantidad de productos vendidos



## 🛠️ Tecnologías utilizadas

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel (fuente de datos)



## 🔄 Preparación de los datos

Antes del desarrollo del dashboard se realizó un proceso de revisión y transformación de datos mediante **Power Query**, incluyendo:

- Validación de tipos de datos.
- Verificación de registros nulos o erróneos.
- Eliminación de columnas sin valor analítico.
- Preparación del modelo para el análisis.

---

## 📈 Indicadores (KPIs)

El dashboard incorpora los siguientes indicadores:

- 💰 Ventas Totales
- 📈 Ganancia Total
- 📦 Cantidad Vendida
- 🛒 Ticket Promedio
- 📊 Margen de Ganancia (%)


## 📊 Visualizaciones

### Página 1 — Resumen Ejecutivo

- Ventas por Categoría
- Ganancia por Región
- Ventas por Subcategoría
- KPIs principales
- Segmentadores para exploración interactiva

### Página 2 — Rentabilidad y descuentos

- Relación entre descuentos y ganancias (gráfico de dispersión)
- Ganancia por Categoría
- Top Estados por Ganancia
- Distribución de ventas rentables y con pérdida
- Hallazgos principales


## 🧮 Medidas DAX desarrolladas

Durante el proyecto se desarrollaron medidas utilizando DAX para calcular indicadores como:

- Ventas Totales
- Ganancia Total
- Cantidad Vendida
- Ticket Promedio
- Margen de Ganancia
- Venta Promedio
- Ganancia Promedio
- Ventas con Pérdida

Además, se implementaron columnas calculadas para clasificar la rentabilidad de las ventas y segmentar los niveles de descuento.

---

## 🔍 Principales hallazgos

El análisis permitió identificar diversos patrones de comportamiento comercial, entre ellos:

- La categoría **Technology** concentra el mayor volumen de ventas, representando una de las principales fuentes de ingresos.
- La región **West** presenta el mejor desempeño en términos de rentabilidad.
- Existen subcategorías con altos niveles de ventas que no necesariamente generan las mayores ganancias.
- Los descuentos elevados no garantizan un incremento en la rentabilidad y, en algunos casos, están asociados a ventas con baja ganancia o pérdidas.
- El dashboard facilita la identificación de oportunidades para optimizar estrategias comerciales mediante el análisis interactivo de los datos.



## 💡 Recomendaciones

A partir del análisis realizado, se proponen las siguientes acciones:

- Evaluar la estrategia de descuentos aplicada a productos con baja rentabilidad.
- Priorizar categorías y regiones con mejor desempeño financiero.
- Complementar el análisis con información temporal para evaluar tendencias de ventas.
- Incorporar nuevos indicadores para monitorear el desempeño comercial de forma periódica.

---

## 📷 Capturas

### Resumen Ejecutivo

<img width="1307" height="841" alt="image" src="https://github.com/user-attachments/assets/809c72c7-088f-446d-8227-018fa45764b8" />

### Rentabilidad y Descuentos

<img width="1278" height="831" alt="image" src="https://github.com/user-attachments/assets/9de4ab88-4134-4a48-aa2f-c9c138f782eb" />

---

## 📂 Estructura del proyecto

```
Dashboard-Ejecutivo-Ventas/

│── Dashboard.pbix
│── SampleSuperstore.csv
│── README.md
│── images/
│     ├── resumen-ejecutivo.png
│     └── rentabilidad-descuentos.png
```

---

## 👩‍💻 Autora

**Daniela Fernanda Ojeda Arrelucea**

Estudiante de Ingeniería de Software interesada en análisis de datos, Business Intelligence y desarrollo de software.
