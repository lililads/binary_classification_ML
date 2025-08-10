# Binary Classification - Pumpkin Seeds

<p>Este proyecto consiste en la clasificación binaria de semillas de calabaza utilizando el dataset Pumpkin Seeds de Kaggle. El objetivo es predecir el tipo de semilla entre las variedades Çerçevelik y Ürgüp Sivrisi a partir de sus características físicas.</p>
<p>This project involves binary classification of pumpkin seeds using the Pumpkin Seeds dataset from Kaggle. The objective is to predict the seed type between the varieties Çerçevelik and Ürgüp Sivrisi based on their physical characteristics.</p>

<p>Dataset: https://www.kaggle.com/datasets/muratkokludataset/pumpkin-seeds-dataset</p>


## 1 - Library Import

<img width="745" height="192" alt="image" src="https://github.com/user-attachments/assets/d3ba4326-107e-4b6e-8aa3-898f14c2a388" />

## 2 - Dataset Loading

<img width="1115" height="487" alt="image" src="https://github.com/user-attachments/assets/004a1680-b959-4ad7-8c8f-8c8044434305" />

## 3 - Initial Dataset Exploration

<img width="1117" height="763" alt="image" src="https://github.com/user-attachments/assets/f987c38a-00d8-460c-92c3-bc5a4bb698ad" />

<img width="470" height="325" alt="image" src="https://github.com/user-attachments/assets/16b38fb0-602e-4261-bb82-0207e51aa95e" />

## 4 - Visualization

<p>Este gráfico de barras muestra la cantidad de registros para cada tipo de semilla en el dataset (Çerçevelik y Ürgüp Sivrisi).</p>
<p>This bar chart shows the number of records for each seed type in the dataset (Çerçevelik and Ürgüp Sivrisi).</p>

<img width="587" height="592" alt="image" src="https://github.com/user-attachments/assets/0f5a64c9-afa4-422e-b443-4d2bf43cfe51" />

<p>Este conjunto de histogramas muestra la distribución de todas las variables numéricas del dataset, permitiendo identificar la forma de los datos, la presencia de asimetrías y posibles valores atípicos.</p>
<p>This set of histograms shows the distribution of all numerical variables in the dataset, allowing identification of data shape, presence of skewness, and possible outliers.</p>

<img width="1110" height="777" alt="image" src="https://github.com/user-attachments/assets/0adcd896-3f5d-4bf3-aa34-a82deca057c7" />

<p>Este mapa de calor muestra la correlación entre las variables numéricas del dataset. Los valores cercanos a 1 o -1 indican relaciones lineales fuertes, mientras que los valores cercanos a 0 sugieren poca o ninguna relación.</p>
<p>This heatmap shows the correlation between the numerical variables in the dataset. Values close to 1 or -1 indicate strong linear relationships, while values close to 0 suggest little or no relationship.</p>

<img width="873" height="857" alt="image" src="https://github.com/user-attachments/assets/ed291195-4d66-4692-b3f2-5363a2361a10" />

## 5 - Class Encoding

<p>Convierte la columna <code>Class</code> en valores binarios, asignando 1 a la clase "Çerçevelik" y 0 a la clase "Ürgüp Sivrisi", lo cual es necesario para que los algoritmos de machine learning puedan procesarla.</p>
<p>Convert the <code>Class</code> column into binary values, assigning 1 to the "Çerçevelik" class and 0 to the "Ürgüp Sivrisi" class, which is necessary for machine learning algorithms to process it.</p>

<img width="50" height="357" alt="image" src="https://github.com/user-attachments/assets/6ec1febe-81f1-4995-995c-40e2e7cf4578" />

## 6 - Variable Separation and Dataset Splitting

<p>Se seleccionan las características predictoras (<code>X</code>) y la variable objetivo (<code>y</code>), y luego se divide el conjunto de datos en conjuntos de entrenamiento y prueba con una proporción del 80% y 20% respectivamente. Esto es fundamental para evaluar el rendimiento de los modelos de manera objetiva.</p>
<p>The predictor features (<code>X</code>) and the target variable (<code>y</code>) are selected, and then the dataset is split into training and testing sets with an 80% and 20% proportion respectively. This is essential to objectively evaluate the performance of the models.</p>

<img width="177" height="54" alt="image" src="https://github.com/user-attachments/assets/9688a072-fe89-4d9e-92eb-cd5f2eb92dbf" />

<img width="670" height="26" alt="image" src="https://github.com/user-attachments/assets/3fbcd77e-8417-4690-a45b-cf4839dc2c47" />

## 7 - ML Models

### Logistic Regression

<img width="982" height="531" alt="image" src="https://github.com/user-attachments/assets/657235e2-8bf0-49e6-9d41-1f20196609b5" />

### SVM

<img width="958" height="535" alt="image" src="https://github.com/user-attachments/assets/a357fb88-387f-4333-8eff-3e7de36aea44" />

### Decision Tree

<img width="938" height="533" alt="image" src="https://github.com/user-attachments/assets/c46074f2-e2ea-4e9c-a4f6-0f6dcdb9ae70" />

### Random Forest

<img width="997" height="529" alt="image" src="https://github.com/user-attachments/assets/03e4a632-5773-4cab-9e4b-60763e6b258c" />

## 8 - ROC Curve - AUC
<p>Los modelos <strong>Random Forest</strong> y <strong>Regresión Logística</strong> presentan los mejores valores de <em>AUC</em> (alrededor de 0.93), seguidos por <strong>SVM</strong> y luego <strong>Árbol de Decisión</strong>.</p>
<p>The <strong>Random Forest</strong> and <strong>Logistic Regression</strong> models show the best <em>AUC</em> values (around 0.93), followed by <strong>SVM</strong> and then <strong>Decision Tree</strong>.</p>

<img width="890" height="821" alt="image" src="https://github.com/user-attachments/assets/d082a2dc-e279-4182-b4f7-afdc4d0b19b2" />


<strong>Thanks for reading!</strong>








