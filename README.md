# 🚗 Mobility Economy Analysis with Python

Proyecto de **Data Analytics** desarrollado con **Python** para estudiar la relación entre la movilidad urbana y la productividad económica en ciudades latinoamericanas.

El análisis integra información del **TomTom Traffic Index** y **OECD Cities** para explorar patrones entre congestión vehicular, tiempos de viaje e indicadores económicos y demográficos.

---

## 📌 Resumen ejecutivo

El proyecto parte de una pregunta de negocio: **¿cómo se relaciona la movilidad urbana con el contexto económico de las ciudades?**

Para responderla, se limpiaron y transformaron dos datasets, se filtró la información de tráfico correspondiente a **2024**, se agregaron métricas por ciudad y posteriormente se integraron los datos con información económica y urbana.

## 🎯 Objetivo del proyecto

Evaluar la relación entre la congestión vehicular y variables económicas de distintas ciudades, explorando preguntas como:

- ¿Qué ciudades presentan mayores niveles de congestión?
- ¿Cómo se comportan los indicadores de tráfico entre ciudades?
- ¿Existe una relación clara entre PIB per cápita y congestión?
- ¿Qué variables económicas y urbanas ayudan a complementar el análisis de movilidad?

## 📂 Fuentes de datos

| Fuente | Información |
|---|---|
| **TomTom Traffic Index** | Congestión, retrasos, longitud y cantidad de embotellamientos y tiempos de viaje |
| **OECD Cities** | PIB per cápita, desempleo, población y PM2.5 |

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔎 Metodología

1. Carga y exploración de los datasets.
2. Revisión de estructura, tipos de datos y valores ausentes.
3. Estandarización de nombres de columnas en **snake_case**.
4. Conversión de fechas y variables económicas a formatos adecuados.
5. Creación de la variable de población total.
6. Extracción del año y filtrado de los registros de tráfico de **2024**.
7. Agregación de métricas de tráfico por ciudad.
8. Integración de los datasets mediante `merge`.
9. Análisis exploratorio y visualización de relaciones.

## 📊 Variables analizadas

### Movilidad

- `jams_delay`
- `traffic_index_live`
- `jams_length_kms`
- `jams_count`
- `traffic_index_week_ago`
- `travel_time_live_per_10kms_mins`
- `travel_time_hist_per_10kms_mins`
- `mins_delay`

### Economía y contexto urbano

- `city_gdp_capita`
- `unemployment_pct`
- `population`
- `pm25`

## 💡 Principales hallazgos

- **Ciudad de México** registró el mayor promedio de retraso por congestión entre las ciudades analizadas durante 2024.
- El análisis exploratorio no mostró una relación lineal clara entre el PIB per cápita y la congestión.
- La comparación entre ciudades muestra que la relación entre desempeño económico y movilidad no depende de una única variable.
- La integración de datos de movilidad y economía permite construir una visión comparativa del contexto urbano.

## 📈 Visualizaciones

El notebook incluye visualizaciones orientadas a explorar:

- Distribución de la congestión por ciudad.
- Distribución del PIB per cápita.
- Relación entre PIB per cápita y congestión.
- Comportamiento de variables de movilidad.

## 🚀 Competencias demostradas

- Python para análisis de datos
- Limpieza y transformación con Pandas
- Manejo de fechas y tipos de datos
- Integración de datasets mediante `merge`
- Análisis exploratorio de datos (EDA)
- Visualización con Matplotlib y Seaborn
- Interpretación de relaciones entre variables
- Comunicación de hallazgos

## 🔗 Proyecto

**Repositorio:**  
https://github.com/catalinaduquediaz-svg/--Mobility---Economy-Analysis-with-Python

**Notebook:**  
https://github.com/catalinaduquediaz-svg/--Mobility---Economy-Analysis-with-Python/blob/main/dashboard/S5%20ladb_mobility_economy_project_student%20(1).ipynb

## 🎓 Contexto académico

Proyecto desarrollado durante el **Bootcamp de Análisis de Datos de TripleTen**.

---

## 👩‍💼 Autora

**Catalina Duque**

Business Analyst • Data Analyst • BI Analyst