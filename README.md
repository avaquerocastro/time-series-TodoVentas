# Predicción de Ventas con Series Temporales - TodoVentas S.A.
### 📝 Descripción del Proyecto

TodoVentas S.A., una empresa de comercio retail online, busca expandir su capital y necesita una estimación precisa de sus ventas futuras. Este proyecto aplica técnicas de series temporales para predecir el nivel de ventas totales durante el próximo mes, utilizando datos históricos de ventas diarias por producto en los principales mercados.

Se evaluaron varios modelos de predicción, destacando XGBoost como el más eficiente, con un error significativamente menor que otras alternativas como Prophet. Este repositorio contiene el código, los datos y la documentación utilizada en el desarrollo del modelo.


### 🎯 Objetivos

- Predecir el nivel de ventas totales del próximo mes.
- Analizar patrones estacionales y tendencias en las ventas.
- Comparar diferentes modelos de predicción y seleccionar el más eficiente.


### 🛠️ Metodología

1️⃣ Análisis Exploratorio y Preprocesamiento:
- Transformación de variables y tratamiento de datos.
- Evaluación de estacionalidad, tendencias y correlaciones.

2️⃣ Modelado y Evaluación:
- Comparación entre Prophet y XGBoost.
- Métricas de evaluación: MAE, RMSE y MAPE.

3️⃣ Selección del Mejor Modelo:
- XGBoost mostró mejor rendimiento con un MAPE de 11,9%, mientras que Prophet alcanzó 25,3%.

---

## 📂 Estructura del Repositorio

📜 `code/`: Contiene el Notebook con el código Python.<br>
📊 `datasets/`: Almacena los datos de ventas originales y los datos de la predicción.<br>
🖼️ `img/`: Contiene gráficos generados en el análisis exploratorio y evaluación de modelos.<br>
📄 `Resumen-de-proyecto_Time-series-TodoVentas.pdf`: Informe técnico con detalles del proyecto.<br>

---

### 👩🏻‍💻 Proyecto elaborado por Alejandra Vaquero durante el [Máster en Data Science & AI](https://nuclio.school/master-data-science/) de [Nuclio Digital School](https://nuclio.school/).
