# Analysis-of-avocado-ripening-with-spectroscopy-using-NIR-and-applying-machine-learning-techniques.-
Este repositorio contiene una serie de notebooks en Python/Google Colab desarrollados como parte de un estudio orientado a predecir el estado de maduración de la palta (Persea americana Mill.), específicamente de las variedades ‘Fuerte’ y ‘Hass’, utilizando espectros NIR obtenidos en cuatro puntos ecuatoriales por fruto, con 100 espectros por punto, para un total de 32 paltas analizadas.

📊 Objetivo del repositorio
Proporcionar el código empleado en el análisis de datos espectrales, así como la aplicación de diferentes técnicas de preprocesamiento y algoritmos de machine learning para evaluar su desempeño en la predicción de la madurez.

🧪 Esquemas aplicados
Se compararon dos flujos de procesamiento:

Esquema 1:

Preprocesamiento: MSC, primera derivada de Savitzky–Golay, y PCA.

Modelos: XGBoost, Random Forest, PLSRegression, MLP y SVR.

Esquema 2:

Preprocesamiento: Primera derivada de Savitzky–Golay y PCA.

Modelos: XGBoost, Random Forest, PLSRegression, MLP y SVR.

💻 Herramientas utilizadas
Python 3.x

Google Colab

Scikit-learn, XGBoost, TensorFlow/Keras, NumPy, Pandas, Matplotlib

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

This repository contains a series of Python/Google Colab notebooks developed as part of a study aimed at predicting the ripeness state of avocado (Persea americana Mill.), specifically for the ‘Fuerte’ and ‘Hass’ varieties. NIR spectra were collected at four equatorial points per fruit, with 100 spectra per point, totaling 32 avocados analyzed.

📊 Repository Objective
To provide the code used for spectral data analysis, including the application of different preprocessing techniques and machine learning algorithms to evaluate their performance in ripeness prediction.

🧪 Processing Schemes
Two processing pipelines were compared:

Scheme 1:

Preprocessing: MSC, first derivative of Savitzky–Golay, and PCA

Models: XGBoost, Random Forest, PLSRegression, MLP, SVR

Scheme 2:

Preprocessing: First derivative of Savitzky–Golay and PCA

Models: Same as in Scheme 1

💻 Tools Used
Python 3.x

Google Colab

Scikit-learn, XGBoost, TensorFlow/Keras, NumPy, Pandas, Matplotlib
