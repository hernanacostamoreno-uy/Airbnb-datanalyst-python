# Airbnb-datanalyst-python

Este proyecto forma parte del Desafío Profesional de la Certificación en Data Analyst.

El objetivo es realizar un análisis exploratorio de datos (EDA) sobre un conjunto de datos de Airbnb con el fin de comprender el comportamiento del mercado y detectar posibles oportunidades de inversión.

El trabajo se enfoca en la exploración estructural del dataset, el análisis descriptivo de variables clave y la visualización de relaciones relevantes entre precio, demanda, ubicación y características de las propiedades.

-----------------------------------------------------------------------------------------------------------------------------------------------
Objetivos

Familiarizarse con la estructura y calidad de los datos.

Identificar patrones en la distribución de precios.

Analizar la relación entre precio y variables como tamaño, rating y reviews.

Evaluar diferencias entre barrios y tipos de propiedad.

Extraer conclusiones preliminares orientadas a decisiones de inversión.
-----------------------------------------------------------------------------------------------------------------------------------------------
Dataset Utilizado

El análisis se basa en tres archivos principales:

listings.csv: información general de las propiedades.

calendar.csv: disponibilidad diaria y precios.

reviews.csv: reseñas realizadas por los usuarios.

Estos archivos permiten combinar información de oferta, demanda y disponibilidad.

-----------------------------------------------------------------------------------------------------------------------------------------------

Metodología
1. Exploración inicial

Revisión de dimensiones del dataset.

Análisis de tipos de datos.

Identificación de valores nulos.

Estadísticas descriptivas generales.

2. Limpieza preliminar

Conversión de la variable precio a formato numérico.

Tratamiento de valores extremos para visualización (cap en percentil 99).

Selección de variables relevantes para análisis.

3. Análisis descriptivo y visual

Distribución de precios.

Relación entre precio y tamaño (accommodates, bedrooms, bathrooms).

Relación entre precio y rating.

Análisis de reviews por mes como proxy de demanda.

Segmentación por tipo de propiedad y barrio.

4. Integración con disponibilidad

Cálculo de tasa de disponibilidad anual a partir del dataset de calendario.

Análisis de relación entre precio y disponibilidad.

5. Matriz de correlación simplificada

Evaluación de relaciones entre variables numéricas clave.

Identificación de variables redundantes y relaciones relevantes.

Principales Hallazgos

El precio presenta alta dispersión y asimetría positiva.

El tamaño de la propiedad tiene una relación moderada con el precio.

No se observa una relación significativa entre precio y volumen de reviews.

Existen barrios claramente posicionados como segmentos premium.

La mayoría de las propiedades muestran baja frecuencia de reviews mensuales.

La formación de precios parece responder a múltiples factores y no a una única variable dominante.

-----------------------------------------------------------------------------------------------------------------------------------------------

Conclusión

El análisis exploratorio sugiere que la rentabilidad potencial no depende exclusivamente de fijar precios elevados.

Una estrategia que combine ubicación adecuada, tamaño acorde al mercado, experiencia del huésped y una política de precios competitiva puede resultar más eficiente que enfocarse únicamente en el segmento premium.

Este trabajo constituye la primera etapa del proyecto y sienta las bases para una fase posterior de limpieza avanzada, transformación de datos y construcción de dashboards para visualización ejecutiva.
