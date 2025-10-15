# Predicción de Satisfacción de Pasajeros en Aerolíneas

Este proyecto tiene como objetivo analizar y predecir la **satisfacción de los pasajeros en aerolíneas** utilizando un dataset que contiene información sobre vuelos, pasajeros y servicios ofrecidos. Se aplican **modelos de machine learning** para identificar qué factores influyen en la satisfacción del pasajero.

## Dataset

El dataset incluye variables como:

- Información demográfica del pasajero (edad, género, clase de viaje, etc.)
- Detalles del vuelo (distancia, tiempo de vuelo, tipo de cabina)
- Servicios ofrecidos (comida, entretenimiento, servicio de atención)
- Valoración de la satisfacción del pasajero (target)

## Pasos del Proyecto

1. **Análisis Exploratorio de Datos (EDA)**  
   - Revisión de valores faltantes y outliers.  
   - Histogramas, gráficos de barras y dispersión para entender los patrones en los datos.  

2. **Procesamiento de Datos**  
   - Tratamiento de valores nulos y outliers.  
   - Codificación de variables categóricas (One-Hot Encoding, Label Encoding).  
   - Escalado de variables numéricas según sea necesario.  

3. **Modelado y Predicción**  
   - División de los datos en conjuntos de entrenamiento y prueba.  
   - Entrenamiento de modelos de clasificación para predecir satisfacción.  
   - Evaluación del desempeño con métricas como **accuracy**, **precision**, **recall** y **F1-score**.  

4. **Interpretación y Conclusiones**  
   - Identificación de las variables más importantes que afectan la satisfacción.  
   - Recomendaciones basadas en los hallazgos para mejorar la experiencia del pasajero.

## Librerías Utilizadas

- `pandas`, `numpy` – Manipulación de datos  
- `matplotlib`, `seaborn` – Visualización  
- `scikit-learn` – Preprocesamiento, entrenamiento de modelos y evaluación  

## Cómo usar el proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/tu_usuario/Airline_Passenger_Satisfaction.git
