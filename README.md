# Análisis Estadístico Empresa de Telecomunicaciones
Este repositorio contiene el análisis realizado para evaluar el comportamiento del uso de las llamadas y los textos, de los usuarios de la empresa latinoamericana de telecomunicaciones ConnectaTel en fechas anteriores al 2024.

El dataset `plans` contiene las características de los dos tipos de planes ofrecidos por la empresa: Básico y Premium.

El dataset `users_latam` contiene la información relevante de los usuarios que tiene la empresa a fecha de 2024, como su nombre, edad, ciudad, fecha de registro y plan adquirido.

El dataset `usage` contiene el detalle del uso que hace cada uno de los usuarios de las llamadas (duración) y mensajes (longitud).



## 📂 Contenido del repositorio

- `/Project_connectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.
- →Links a datasets trabajados

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar este notebook de las siguientes formas:

### Opción 1: Abrir en Google Colab
- Ve a Google Colab
- Haz clic en “File” > “Open notebook”
- Selecciona la pestaña “GitHub”
- Pega el enlace de este repositorio
- Abre el archivo .ipynb

### Opción 2: Ejecutar en local

- Clona este repositorio:
git clone [https://github.com/pablojbec/Analysis_ConnectaTel.git]
- Accede a la carpeta del proyecto:
- cd repositorio

- Abre Jupyter Notebook:
  - jupyter notebook
  - Selecciona el archivo .ipynb y ejecútalo

## 🔁 Guía de reproducción
Para reproducir los resultados:

- Instala las dependencias necesarias (recomendado usar entorno virtual o Anaconda):
pip install -r requirements.txt
- Asegúrate de tener los datos en la ruta correcta (ver carpeta /data si aplica)
- Ejecuta las celdas del notebook en orden, desde el inicio
- Verifica que no haya errores y que los outputs coincidan con los esperados

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Realizar la limpieza de los datasets
- Analizar las distribuciones de duración de llamadas individuales, longitud de mensajes  y duración total de llamadas. 
- Identificar patrones de uso en los outliers
- Generar insights para el equipo de Estrategia e Integración de Connectatel
-Proporcionar recomendaciones de acuerdo con el análisis realizado 

## 🧩Etapas de análisis realizadas

- Se realizó la limpieza y validación de los datos
- Graficación de las distribuciones de las variables relevantes para su análisis 
- Se segmentaron los clientes según su edad y uso 
- Se elaboraron gráficos (histogramas, boxplots y countplots comparativos)
