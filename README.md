# Sentiment Analysis with Machine Learning 🧠

This project implements text processing and classification to perform sentiment analysis using Machine Learning techniques. The main approach is to take comments and automatically classify whether the expressed sentiment is positive or negative.

---

## Project Description
The purpose of this project is to develop a system capable of identifying and classifying the sentiment present in short texts. To achieve this, the process includes cleaning and structuring the data, transforming it through vectorization techniques, and training a supervised model that learns to distinguish linguistic patterns associated with positive or negative sentiments. The text is converted into numerical vectors, and a Logistic Regression model is used as the main classifier. Additionally, the project incorporates model performance evaluation using metrics, visualization of confusion matrices, and analysis of the words with the greatest influence on the classification. Finally, it allows manual testing where the user enters new phrases to predict their sentiment.

---

## Technologies Used  
- **Python 3.12**  
**NumPy - Pandas - Matplotlib - Seaborn - Scikit-learn**  

---

## Code Workflow  
The project starts with the import of facial images, followed by face detection using the Haar Cascade classifier. Detected faces are cropped, resized, and processed with a Gaussian filter to reduce noise and enhance key features. The processed images are then split into training and testing sets, standardized, and used to train several **Machine Learning** models. Performance metrics and confusion matrices are computed to compare model results. Finally, visualizations and performance analyses are presented for each algorithm.  

---

## Expected Results  
The project produces a model capable of classifying new comments as positive or negative with an accuracy level suitable for basic sentiment analysis tasks. The results include performance measurements such as the normalized confusion matrix and lists of the words with the greatest weight for positive and negative classification. These tools help interpret the model’s behavior, understand the patterns it uses to make decisions, and assess its reliability in real-world contexts. Additionally, the testing function allows any user to interact directly with the system to evaluate new phrases.
---

## Author  
**Joshua Arango Fabbri**  
Electronic Engineer  
Cali, Colombia  
[Email](mailto:joshuaarango82@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/joshua-arango-295589326/)  


---


# Análisis de Sentimientos con Machine Learning 🧠

Este proyecto implementa procesamiento de texto y clasificación para realizar análisis de sentimientos utilizando técnicas de Machine Learning. El enfoque principal es tomar comentarios para clasificar automáticamente si el sentimiento expresado es positivo o negativo.

---

## Descripción del proyecto  
El propósito de este proyecto es desarrollar un sistema capaz de identificar y clasificar el sentimiento presente en textos cortos. Para esto, se realiza un proceso que incluye la limpieza y estructuración de los datos, su transformación mediante técnicas de vectorización y el entrenamiento de un modelo supervisado que aprende a distinguir patrones lingüísticos asociados con sentimientos positivos o negativos. Se convierte el texto en vectores numéricos y un modelo de Regresión Logística como clasificador principal. Además, el proyecto incorpora la evaluación del desempeño del modelo mediante métricas, la visualización de las matrices de confusión y el análisis de las palabras con mayor peso en la clasificación. Finalmente, permite realizar pruebas manuales donde el usuario ingresa frases nuevas para predecir su sentimiento.

---

## Tecnologías utilizadas  
- **Python 3.12**  
**NumPy - Pandas - Matplotlib - Seaborn - Scikit-learn**  

---

## Flujo del código  
El flujo del proyecto inicia con la carga del archivo Excel que contiene una colección de reseñas y su clasificación asociada. Posteriormente, se seleccionan y limpian las columnas necesarias, convirtiendo el sentimiento en valores numéricos para facilitar su procesamiento. El siguiente paso consiste en dividir el dataset en conjuntos de entrenamiento y prueba para evaluar el rendimiento real del modelo. Luego, se transforma cada comentario en un vector que representa la importancia de sus palabras. Con estos vectores, se entrena un modelo de Regresión Logística que aprende a distinguir sentimientos. Una vez entrenado, se calculan métricas de exactitud y se genera una matriz de confusión para analizar la calidad de las predicciones. También se identifican las palabras que más influyen positiva y negativamente en el modelo, y se implementa una función que permite predecir el sentimiento de frases nuevas.

---

## Resultados esperados  
El proyecto genera un modelo capaz de clasificar comentarios nuevos en positivos o negativos con un nivel de exactitud adecuado para tareas básicas de análisis de sentimientos. Los resultados incluyen mediciones del rendimiento, como la matriz de confusión normalizada, y listas de palabras con mayor peso para la clasificación positiva y negativa. Estas herramientas permiten interpretar el comportamiento del modelo, comprender los patrones que utiliza para decidir y evaluar su confiabilidad en contextos reales. Además, la función de prueba permite que cualquier usuario interactúe directamente con el sistema para evaluar nuevas frases.

---

## Autor  
**Joshua Arango Fabbri**  
Ingeniero Electrónico  
Cali, Colombia  
[Email](mailto:joshuaarango82@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/joshua-arango-295589326/)
