# 📊 Análisis de Clustering de Clientes - Mall Customer Segmentation

Este proyecto implementa dos técnicas de *clustering* (agrupamiento no supervisado) sobre el dataset **Mall Customer Segmentation** usando Python:

- **K-means**
- **Clustering Jerárquico (Hierarchical Clustering)**

El objetivo es segmentar clientes de un centro comercial en grupos con características similares, facilitando decisiones de marketing, promociones personalizadas y análisis de comportamiento.

---

## 📁 Archivos incluidos

- `Clustering_Mall_Customers.ipynb`: Notebook Jupyter con todo el análisis, visualizaciones y métricas de desempeño.
- `Mall_Customers.csv`: Dataset original (debes descargarlo desde Kaggle, enlace abajo).

---

## 📌 Dataset

**Mall Customer Segmentation Data**  
🔗 [Descargar desde Kaggle](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

Contiene información de 200 clientes con variables como:
- Género
- Edad
- Ingreso anual
- Puntaje de gasto

---

## 🛠️ Tecnologías utilizadas

- Python
- Jupyter Notebooks
- Scikit-learn
- Scipy
- Pandas
- Matplotlib & Seaborn

---

## 🔍 Análisis realizado

1. **Análisis exploratorio** de datos
2. **Preprocesamiento**: limpieza y escalado
3. Aplicación de **K-means clustering**
4. Aplicación de **Clustering jerárquico**
5. Evaluación con métricas:
   - Silhouette Score
   - Calinski-Harabasz Index
   - Davies-Bouldin Index
6. Visualizaciones: *scatterplots* y *dendrogramas*
7. Interpretación de resultados

---

## ✅ Cómo ejecutar

1. Clona este repositorio
2. Descarga el archivo `Mall_Customers.csv` desde Kaggle
3. Asegúrate de tener instaladas las librerías:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```
4. Abre y ejecuta el notebook `Clustering_Mall_Customers.ipynb` en Jupyter o Google Colab
