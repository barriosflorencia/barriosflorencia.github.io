
Detección de Fraude en Seguros de Autos: Optimización de la Siniestralidad.
Sistema de clasificación predictiva diseñado para actuar como primera línea de defensa en la detección de reclamos fraudulentos o irregulares en el sector asegurador.}

Objetivo del proyecto: Automatizar la detección de anomalías para proteger el capital de la compañía y optimizar los recursos operativos, permitiendo que los auditores se enfoquen en los casos de mayor riesgo.
El proyecto detalla el análisis bivariado de patrones de fraude, la experimentación con diversos modelos y la optimización final del clasificador.Dataset utilizado: Dataset "Fraud Oracle", compuesto por 15.420 registros y 33 variables que cubren el perfil del asegurado, detalles del vehículo y contexto del siniestro.
Tecnologías utilizadas: CatBoost (modelo ganador por su manejo eficiente de variables categóricas), Regresión Logística, Random Forest, XGBoost y optimización de sensibilidad (Recall) con Optuna.

Resultados principales: El modelo logra capturar aproximadamente el 77% de los casos de fraude revisando solo el 30% de las reclamaciones totales. Se determinó que la responsabilidad del asegurado (Fault), el tipo de póliza y el retraso en el reporte (Report_Lag) son los indicadores críticos de fraude.
