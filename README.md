## telecom-analysis

Este repositorio contiene el analisis realizado del caso ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.

Tres fuentes principales de información, relacionadas con usuarios, actividad y planes del servicio de telecomunicaciones:
- plans.csv: Catálogo de planes con sus precios y beneficios. 
- users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). 
- usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud. 

## 📂 Contenido del repositorio

- `telecom_analysis.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]((https://colab.research.google.com/github/sofiaduartea/telecom-analysis/blob/c867578a1189baee98b80a220b246fc88035e9d2/Telecom_analysis.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `telecom_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Comprender patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas
- Generar insights, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.
