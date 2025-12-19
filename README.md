# 🚕 Análisis del Mercado de Taxis en Chicago: Impacto del Clima y Topología Urbana

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-Data_Extraction-orange.svg)](https://en.wikipedia.org/wiki/SQL)
[![Stats](https://img.shields.io/badge/Statistics-Hypothesis_Testing-green.svg)](https://en.wikipedia.org/wiki/Statistics)

## 📌 Resumen Ejecutivo
Este proyecto analiza el comportamiento del mercado de transporte en Chicago mediante la integración de datos extraídos por **SQL** y procesados con **Python**. El objetivo es identificar los distritos con mayor demanda y validar estadísticamente si factores externos como el clima influyen significativamente en la eficiencia del servicio hacia puntos críticos como el Aeropuerto O'Hare.

## 🚀 Competencias Técnicas Demostradas
* **Extracción de Datos:** Recuperación de datos desde bases de datos externas mediante consultas SQL complejas.
* **Análisis Exploratorio de Datos (EDA):** Identificación de líderes del mercado y patrones de destino.
* **Estadística Inferencial:** Diseño y ejecución de pruebas de hipótesis ($t-test$) para validar suposiciones operativas.
* **Visualización de Datos:** Creación de dashboards informativos que facilitan la toma de decisiones empresariales.

## 📊 Hallazgos Principales
* **Concentración de Mercado:** El top 10 de barrios concentra la mayoría de las finalizaciones de viajes, sugiriendo una oportunidad de optimización de flota en zonas específicas.
* **Validación Climática:** Se determinó con rigor estadístico que las condiciones climáticas afectan de manera significativa la duración promedio de los viajes al aeropuerto los sábados lluviosos.

## 🛠️ Stack Tecnológico
- **Lenguaje:** Python
- **Librerías:** Pandas, Matplotlib, Seaborn, Scipy (stats)
- **Gestión de Datos:** SQL (Slices de datos, agrupamientos y uniones)

## 📖 Estructura del Proyecto
1. **Extracción y Limpieza:** Aseguramiento de tipos de datos y manejo de valores ausentes.
2. **Análisis por Barrios:** Identificación de los 10 principales distritos.
3. **Prueba de Hipótesis:** - **$H_0$:** La duración promedio es igual en días lluviosos y despejados.
   - **$H_1$:** Existe una diferencia significativa en la duración promedio.
   - **Resultado:** Rechazo de $H_0$ ($p-value < \alpha$).

---
**¿Interesado en los detalles técnicos?** Revisa el archivo `Proyecto_8.ipynb` para ver el código completo y la lógica analítica.
