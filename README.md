# 🚕 Análisis de Movilidad Urbana en Chicago: Caso Zuber

**Proyecto ID:** 08

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)](https://pandas.pydata.org/)
[![Scipy](https://img.shields.io/badge/Stats-SciPy-red.svg)](https://scipy.org/)

## 📑 Descripción del Proyecto

Este repositorio contiene un análisis estratégico diseñado para el lanzamiento de **Zuber**, una nueva startup de viajes compartidos en Chicago. El proyecto integra la extracción de datos mediante SQL con el análisis estadístico avanzado en Python para identificar patrones de competencia, hotspots de demanda y el impacto de factores externos (clima) en la eficiencia operativa.

## 🎯 Objetivos Estratégicos

1. **Auditoría Competitiva**: Identificar líderes de mercado y distribución de cuota de viajes.
2. **Optimización Geoespacial**: Localizar los barrios con mayor flujo de pasajeros para planificación de flota.
3. **Validación de Hipótesis**: Confirmar estadísticamente si el clima adverso afecta la duración de los viajes hacia el Aeropuerto O'Hare.

## 🛠️ Tecnologías y Metodología

- **Análisis de Datos**: `Pandas`, `NumPy`.
- **Visualización Ejecutiva**: `Seaborn`, `Matplotlib`.
- **Estadística Inferencial**: `SciPy` (Prueba de Levene para Homocedasticidad y T-Test para muestras independientes).
- **Data Sourcing**: SQL (consultas para filtrado de datos climáticos y logs de viajes).

## 📈 Hallazgos Clave

- **Concentración de Mercado**: Flash Cab domina el sector con casi 20,000 viajes mensuales, sugiriendo una oportunidad de disrupción basada en optimización tecnológica.
- **Hotspots de Demanda**: El **Loop** y **River North** representan los nodos críticos de demanda, consolidándose como áreas prioritarias para el despliegue inicial.
- **Impacto Climático**: Se validó con un **p-value de 0.0000** que el clima adverso incrementa significativamente la duración de los viajes.

## 🚀 Conclusiones de Negocio

Se recomienda a Zuber implementar un **Modelo de Predicción Dinámica** que ajuste el ETA (_Estimated Time of Arrival_) y los precios durante días lluviosos, asegurando la fiabilidad del servicio y la satisfacción del usuario frente a la competencia tradicional.
