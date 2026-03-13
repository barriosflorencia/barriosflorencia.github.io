
BankShield: Detección de Phishing Bancario con Deep Learning

Sistema de filtrado inteligente en tiempo real que utiliza el análisis semántico para bloquear ataques de Smishing bancario antes de que lleguen al usuario.

Objetivo del proyecto: Desarrollar un modelo capaz de entender el contexto y la intención detrás de los mensajes, superando las limitaciones de los filtros tradicionales basados solo en reglas rígidas o palabras clave.

Incluye el proceso de tokenización preservando señales críticas, la arquitectura de la red neuronal y una demo de predicción con mensajes reales.

Dataset utilizado: Dataset SMS Spam Collection (5,572 mensajes), procesado para mantener señales de urgencia, puntuación y errores gramaticales críticos para la detección de phishing.

Tecnologías utilizadas: Deep Learning con arquitectura de Transformers (DistilBERT), Transfer Learning, Fine-Tuning especializado y mecanismos de atención para el análisis semántico.

Resultados principales: * Accuracy: 0.99 .F1-Score: 0.96. Desempeño en testeo: Sobre 131 ataques, el modelo solo omitió 6 (sensibilidad del 95%), y únicamente generó 4 falsos positivos entre los mensajes legítimos (tasa de error del 0,4%).
