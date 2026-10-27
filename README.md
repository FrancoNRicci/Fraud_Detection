# Detección de Fraude Bancario 
*Trabajo Final Integrador — Diplomatura en Ciencia de Datos y Análisis Avanzado (UTN)*

## Descripción del Proyecto
Sistema desarrollado para la detección de transacciones bancarias fraudulentas mediante técnicas de **Machine Learning** y **Deep Learning**. Se utilizó el dataset sintético **BankSim**, con el objetivo de identificar operaciones potencialmente fraudulentas, priorizar las investigaciones y minimizar las falsas alarmas.

---

## Metodología
El desarrollo del proyecto incluyó las siguientes etapas:
- Análisis exploratorio y limpieza de datos (EDA).
- Ingeniería de variables históricas de clientes, comercios y categorías.
- División temporal de los datos en conjuntos de entrenamiento, validación y prueba.
- Comparación de modelos evaluando el impacto de la ingeniería de variables.
- Evaluación de rendimiento mediante **Average Precision**, **ROC-AUC** y **Card Precision@20**.

---

## Modelos Evaluados
- Regresión Logística
- Random Forest
- XGBoost
- Red Neuronal Feedforward (Keras / TensorFlow)

---

## Resultados Principales
El mejor desempeño se obtuvo con la **Red Neuronal Feedforward** utilizando ingeniería de variables. Los resultados obtenidos sobre el conjunto de prueba fueron:

| Métrica | Resultado |
| :--- | :--- |
| **Average Precision** | 0.8800 |
| **ROC-AUC** | 0.9993 |
| **Card Precision@20** | 0.2239 |

---

## Tecnologías Utilizadas
- **Lenguaje:** Python
- **Manipulación de datos:** Pandas, NumPy
- **Machine Learning:** Scikit-learn, XGBoost
- **Deep Learning:** TensorFlow / Keras
- **Visualización:** Matplotlib, Seaborn

---

## Instrucciones de Ejecución
1. Instalar las dependencias del proyecto.
2. Descargar el dataset **BankSim** y ubicarlo en la carpeta `Dataset/`.
3. Abrir y ejecutar el notebook `Trabajo_final.ipynb`.

---

## Dataset y Referencias
- [BankSim — Kaggle](https://www.kaggle.com/datasets/ealaxi/banksim1)
- [Fraud Detection Handbook](https://fraud-detection-handbook.github.io/fraud-detection-handbook/)

> **Nota:** Este proyecto utiliza datos sintéticos y sus resultados no representan una validación sobre transacciones bancarias reales.
