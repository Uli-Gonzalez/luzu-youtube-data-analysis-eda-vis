
# 📊 Análisis Exploratorio y Visualización

## LUZU TV – Comportamiento de Audiencia 2025

## 📌 Descripción del Proyecto

Este repositorio contiene la segunda etapa del proyecto **“Análisis de datos públicos del canal de streaming LUZU TV”**, enfocada en:

* Exploratory Data Analysis (EDA)
* Visualización de datos
* Generación de insights estratégicos

El objetivo principal es identificar patrones de rendimiento, compromiso y comportamientos extremos de audiencia durante el año **2025**, con foco en variables como vistas normalizadas, crecimiento inicial, formato, interacción y conversación.

Este análisis parte del dataset previamente construido en la etapa de ETL.

---

## 🔁 Relación con el Proyecto ETL

Este trabajo continúa el proyecto:

**ETL – Análisis de datos públicos del canal de streaming LUZU TV**

En la etapa anterior se realizó:

* Extracción de datos públicos (YouTube API)
* Transformación y limpieza
* Normalización de métricas
* Generación de dataset estructurado
* Exportación en formato JSON

---

## ⚙️ Requisito Importante para Ejecutar el Notebook

Antes de comenzar el EDA, es necesario:

1. Descargar el archivo `.json` generado en la etapa de ETL.
2. Colocarlo en la siguiente ruta dentro del proyecto:

```
/content/sample_data/
```

El notebook asume que el archivo se encuentra en esa ubicación para poder cargar correctamente el dataset.

Sin este archivo, el análisis no podrá ejecutarse.

---

## 🎯 Objetivos del Análisis

El notebook se estructura en cuatro grandes preguntas de negocio:

1. **¿Qué programas generan mayor tracción real en la audiencia?**
   Ranking de vistas normalizadas y velocidad de crecimiento.

2. **¿El formato del video influye en el rendimiento?**
   Eficiencia por minuto, volumen y tasa de interacción.

3. **¿Qué tan comprometida está la audiencia más allá de las vistas?**
   Análisis de likes, tasa de comentarios e intensidad conversacional.

4. **¿Qué características presentan los contenidos con comportamientos extremos?**
   Identificación de drivers estructurales de viralidad.

Cada sección incluye:

* Necesidad de negocio
* Visualización
* Insight analítico

Al final del proyecto se incluye:
* Resumen Ejectivo Final
* Recomendación Estratégica Final

---

## 📈 Principales Hallazgos

* La viralidad estructural se concentra en programas con comunidad consolidada.
* Los formatos cortos optimizan captación; los formatos largos consolidan engagement.
* Existen subtipos de contenido breve que disparan reacciones afectivas inmediatas.
* Los comportamientos extremos emergen cuando convergen:

  * Formato largo
  * Comunidad activa
  * Activadores emocionales
  * Eventos catalizadores (celebridades)

---

## 🛠️ Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 🧠 Enfoque Analítico

El análisis combina:

* Métricas normalizadas para comparabilidad temporal
* Análisis de velocidad de crecimiento (primeros 7 días)
* Eficiencia de consumo (views/minuto)
* Engagement rate
* Intensidad y volumen de conversación
* Identificación de patrones temáticos y estructurales

El foco está puesto en comprender el ecosistema del canal como arquitectura editorial y no únicamente como rendimiento de piezas individuales.

---

## 🚀 Cómo Ejecutarlo

1. Clonar el repositorio.
2. Agregar el archivo `.json` generado en la etapa ETL dentro de `/content/sample_data/`.
3. Abrir el notebook en Google Colab o Jupyter.
4. Ejecutar las celdas en orden.

---

## 👤 Autor

Ulises Alberto Gonzalez
Data Analytics Portfolio Project

