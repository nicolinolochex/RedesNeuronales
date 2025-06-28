# 🏨 Clasificación de Sentimiento en Reseñas de TripAdvisor

Este proyecto incluye dos enfoques complementarios de análisis de sentimiento sobre reseñas de hoteles provenientes de TripAdvisor:

---


## 🔗 Acceso al Notebook en Google Colab
Puedes abrir el proyecto directamente en Google Colab desde este enlace:

[🔗 Abrir en Google Colab](https://colab.research.google.com/drive/1KDo7LIdMGLwkiOSHf1-WW5PVdIrjupS3)

---
## 📘 Proyecto 1 – Procesamiento de Lenguaje Natural Tradicional

**Objetivo:**  
Construir un pipeline de NLP para predecir si una reseña es positiva o negativa.

**Pasos principales:**
- Limpieza y preprocesamiento de texto (tokenización, stopwords, lematización).
- Vectorización con Bag of Words y TF-IDF.
- Modelado de temas (LDA) para identificar tópicos frecuentes.
- Entrenamiento de clasificadores supervisados:
  - Naive Bayes.
  - Logistic Regression (modelo final).
- Evaluación de métricas de desempeño.
- Pruebas de predicción sobre nuevas reseñas.

**Resultados destacados:**
- Accuracy Logistic Regression: ~85%.
- Pipeline listo para clasificación de textos nuevos.

---

## 🤖 Proyecto 2 – Deep Learning con Redes Neuronales

**Objetivo:**  
Aplicar un modelo de Deep Learning sobre las mismas reseñas para comparar enfoques.

**Pasos principales:**
- Tokenización y padding de secuencias.
- Análisis exploratorio del dataset.
- Construcción de dos arquitecturas:
  - Modelo simple: Embedding + capa densa.
  - Modelo extendido: Embedding + múltiples capas densas.
- Entrenamiento y comparación de resultados.

**Resultados destacados:**
- Accuracy validación: ~89% en ambos modelos.
- Ligera reducción de pérdida con el modelo extendido.
- Conclusión: mayor profundidad no incrementó significativamente el desempeño en este caso.

---

## 🚀 Tecnologías utilizadas
- Python
- Pandas
- scikit-learn
- TensorFlow / Keras
- Matplotlib
- spaCy

---

