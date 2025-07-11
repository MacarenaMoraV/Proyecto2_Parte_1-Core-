# 🧠 Análisis Inicial y Selección de Problema

## 📌 Descripción

Este proyecto tiene como objetivo realizar un análisis exploratorio de distintos conjuntos de datos con el fin de seleccionar un problema de machine learning significativo y con potencial de aplicación práctica. El proceso incluyó limpieza, visualización, transformación y evaluación preliminar de cada dataset para identificar oportunidades analíticas y de modelado.

El valor de esta etapa radica en desarrollar habilidades clave de exploración de datos (EDA), comprensión de los datos, formulación de hipótesis, y evaluación de la factibilidad de un problema antes de entrenar modelos.

---

## 📂 Conjuntos de Datos Analizados

1. **Ventas Globales de Videojuegos (`vgsales.csv`)**  
   Contiene información histórica sobre ventas de videojuegos por plataforma, género y región.

2. **Uso de Aplicación Móvil (`user_app_data.csv`)**  
   Datos sintéticos de usuarios de una app móvil, incluyendo duración de sesiones, feedback, plataforma y país.

3. **Ventas Minoristas (`retail_sales_dataset.csv`)**  
   Dataset sobre ventas en retail que incluye información del producto, cliente y precio por unidad.

4. **Precios de Casas (`house-prices.csv`)**  
   Información estructurada sobre viviendas, incluyendo número de habitaciones, tamaño, barrio y precio de venta.

---

## 📊 Resumen del EDA Inicial

- Se realizaron procesos de limpieza en los cuatro datasets, incluyendo tratamiento de nulos, conversión de tipos de datos y codificación de variables categóricas.
- En **vgsales**, se detectaron valores faltantes en `Year` y `Publisher`, los cuales fueron tratados apropiadamente.
- En **user_app_data**, no hubo valores nulos y se exploraron visualmente patrones por país, plataforma y feedback.
- En **retail_sales_dataset**, se identificaron columnas no representativas y se realizaron operaciones básicas de filtrado y slicing.
- En **house-prices**, el dataset fue completamente limpiado y transformado, eliminando columnas no útiles y codificando las categóricas como `Neighborhood` y `Brick`.

---

## 🎯 Problema Seleccionado

**Predicción del Precio de Venta de Casas** utilizando el dataset `house-prices.csv`.

### Justificación
Este dataset presenta buena calidad, sin valores faltantes, está estructurado, y contiene tanto variables numéricas como categóricas, lo que lo hace ideal para aplicar técnicas de regresión. Además, la predicción del valor de una propiedad es un caso realista, de alto impacto económico y comúnmente abordado en Data Science.

### Objetivos Específicos
- Construir un modelo de regresión para predecir el precio de una vivienda.
- Comparar el rendimiento de distintos algoritmos (Regresión Lineal, Random Forest, XGBoost).
- Evaluar la importancia de las variables predictoras.
- Analizar métricas como RMSE y R² para determinar la precisión del modelo.

---

## ⚙️ Instrucciones para Ejecutar

1. Clonar el repositorio o subir los archivos a tu entorno de trabajo (Google Colab o Jupyter).
2. Asegurarse de tener instaladas las siguientes librerías:  
   `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
3. Ejecutar los notebooks en el orden indicado en los nombres de archivo (si aplica).
4. Seguir los pasos en cada notebook para reproducir el análisis exploratorio y los modelos.

---

## 🧠 Autor

- **Macarena Mora V.** — Analista Químico en transición hacia Data Scientist. Encargada del análisis EDA y selección del problema.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes reutilizar, modificar y distribuir el contenido con la debida atribución.
