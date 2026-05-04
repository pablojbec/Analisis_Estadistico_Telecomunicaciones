# Analysis_ConnectaTel
Este repositorio contiene el análisis realizado para evaluar el comportamiento del uso de las llamadas y los textos, de los usuarios de la empresa latinoamericana de telecomunicaciones ConnectaTel en fechas anteriores al 2024.

El dataset `plans` contiene las características de los dos tipos de planes ofrecidos por la empresa: Básico y Premium.

El dataset `users_latam` contiene la información relevante de los usuarios que tiene la empresa a fecha de 2024, como su nombre, edad, ciudad, fecha de registro y plan adquirido.

El dataset `usage` contiene el detalle del uso que hace cada uno de los usuarios de las llamadas (duración) y mensajes (longitud).



## 📂 Contenido del repositorio

- `/Project_connectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.
- →Links a datasets trabajados

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/everpeak_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Realizar la limpieza de los datasets
- Analizar las distribuciones de duración de llamadas individuales, longitud de mensajes  y duración total de llamadas. 
- Identificar patrones de uso en los outliers
- Generar insights para el equipo de Estrategia e Integración de Connectatel
-Proporcionar recomendaciones de acuerdo con el análisis realizado 

##🧩Etapas de análisis realizadas

- Se realizó la limpieza y validación de los datos

- Graficación de las distribuciones de las variables relevantes para su análisis 

Se segmentaron los clientes según su edad y uso 
Se elaboraron gráficos (histogramas, boxplots y countplots comparativos)
