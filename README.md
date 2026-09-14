# 📱 Análisis de Clientes ConnectaTel

## 📌 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel a partir de información demográfica y datos de uso del servicio.

El análisis busca identificar patrones de consumo, segmentar a los clientes según su edad y nivel de uso, detectar posibles valores atípicos y generar recomendaciones comerciales que permitan mejorar la oferta de planes de la compañía.

## 📂 Datasets utilizados

El proyecto utiliza tres datasets:

- `plans.csv`: información relacionada con los planes disponibles.
- `users_latam.csv`: información demográfica y características de los usuarios.
- `usage.csv`: registros relacionados con llamadas y mensajes realizados por los usuarios.

## 🔎 Etapas del análisis

El análisis se desarrolló en las siguientes etapas:

1. Carga y exploración inicial de los datos.
2. Identificación de valores nulos.
3. Detección y tratamiento de valores inválidos y sentinels.
4. Conversión y validación de fechas.
5. Análisis de valores faltantes.
6. Agregación de llamadas, mensajes y minutos por usuario.
7. Integración de los datos en un perfil consolidado de clientes.
8. Análisis estadístico y visualización de variables.
9. Detección de outliers mediante boxplots y el método IQR.
10. Segmentación de clientes por edad y nivel de uso.
11. Elaboración de insights y recomendaciones para el negocio.

## 📊 Segmentación de clientes

Los clientes fueron clasificados por nivel de uso en:

- **Bajo uso**
- **Uso medio**
- **Alto uso**

También fueron segmentados por edad en:

- **Joven:** menores de 30 años.
- **Adulto:** entre 30 y 59 años.
- **Adulto Mayor:** 60 años o más.

## 💡 Principales conclusiones

La mayor parte de los clientes se concentra en un nivel de uso medio. También se identificó un grupo más pequeño de usuarios con consumo elevado, que podría representar una oportunidad para ofrecer planes con mayores beneficios o capacidad.

Los valores extremos encontrados en llamadas, mensajes y minutos fueron considerados comportamientos plausibles de usuarios con mayor actividad, por lo que se conservaron para el análisis.

Los resultados sugieren que ConnectaTel puede complementar su oferta actual con planes y promociones adaptados a los diferentes niveles de consumo.

## ▶️ Cómo ejecutar el proyecto

El análisis completo se encuentra en el notebook:

`connectatel_analysis.ipynb`

Para ejecutarlo:

1. Abrir el notebook en Google Colab o Jupyter Notebook.
2. Cargar los datasets utilizados en el proyecto.
3. Instalar las librerías necesarias si no están disponibles.
4. Ejecutar las celdas en orden desde el inicio hasta el final.

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab
- GitHub

## 🔄 Guía de reproducción

Para reproducir el análisis se necesitan los tres datasets originales y las librerías indicadas anteriormente.

El notebook contiene el proceso completo de carga, limpieza, transformación, análisis exploratorio, visualización, detección de outliers y segmentación de clientes.
