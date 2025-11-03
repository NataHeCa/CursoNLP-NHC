[# Proyecto NLP - Clasificación de Textos en Español

Este proyecto corresponde al **Trabajo Final del Curso de Procesamiento de Lenguaje Natural (NLP)**, desarrollado por **Natalia Herrera** como parte de la **Especialización en Inteligencia de Negocios (UPB)**.

El objetivo principal es **preparar, representar y clasificar textos en español**, aplicando distintas técnicas de limpieza, tokenización, lematización y modelos de Machine Learning.

---

## 🧠 Objetivo del Proyecto
Desarrollar un flujo completo de procesamiento de texto que incluya:
1. Limpieza y preprocesamiento del texto.
2. Tokenización y lematización con SpaCy.
3. Representación vectorial usando TF-IDF.
4. Entrenamiento y evaluación de un modelo de clasificación supervisado.
5. Cálculo de métricas de desempeño: accuracy, precision, recall, f1-score.

---

## ⚙️ Pasos del Proyecto

### 1️⃣ Preparación del texto
- Normalización (minúsculas, eliminación de caracteres especiales).
- Eliminación de acentos (unidecode).
- Eliminación de stopwords.
- Tokenización.

### 2️⃣ Representación
- Lematización con SpaCy (`es_core_news_md`).
- Representación TF-IDF.

### 3️⃣ Entrenamiento del modelo
- División en conjuntos de entrenamiento y prueba.
- Entrenamiento con **Regresión Logística**.
- Evaluación con métricas estándar.

### 4️⃣ Evaluación
- Accuracy, Precision, Recall, F1-score.
- Matriz de confusión y reporte de clasificación.

---

## 🧰 Librerías Usadas
- pandas  
- numpy  
- spacy  
- scikit-learn  
- matplotlib  
- seaborn  
- unidecode  
- watermark  

---

## 🧩 Instalación

```bash
git clone https://github.com/NataHeCa/CursoNLP-NHC.git
cd CursoNLP-NHC
pip install -r requirements.txt
python -m spacy download es_core_news_md
jupyter notebook NLP_trabajo_final_Natalia_Herrera.ipynb
]