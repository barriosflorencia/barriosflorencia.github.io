
Análisis predictivo del mercado inmobiliario uruguayo

Herramienta de tasación automatizada para el mercado inmobiliario de Uruguay que busca reducir la asimetría de información y el ruido en los precios.
Objetivo: Construir un motor predictivo capaz de encontrar el valor intrínseco de cada propiedad basándose en sus atributos reales, permitiendo a inversores y compradores identificar oportunidades de forma instantánea.
Cómo están organizados los archivos: El repositorio incluye el ciclo de vida completo del proyecto, desde la limpieza y curaduría de datos masivos hasta la optimización final de los algoritmos.
Dataset utilizado: Base de datos masiva de 550.000 registros recolectados mediante web scraping de los portales Mercado Libre y El Gallito (período 2023-2025).
Tecnologías utilizadas: Machine Learning avanzado, técnicas de Feature Engineering (geolocalización, extracción de atributos y ratios de confort), y optimización de hiperparámetros con Optuna. Se evaluaron modelos como Árboles de Decisión, AdaBoost, XGBoost y CatBoost.
Resultados principales: El modelo Random Forest Optimizado resultó ganador, logrando explicar el 80% de la variabilidad de los precios (R² = 0.80). Se identificó que la superficie es el principal motor del precio (35%), seguida por el confort (baños y dormitorios) (23%).
