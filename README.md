# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## 📋 Descripción del Proyecto

Este proyecto tiene como objetivo predecir si la primera etapa del cohete Falcon 9 de SpaceX aterrizará con éxito. La capacidad de reutilizar la primera etapa reduce significativamente los costos de lanzamiento (de $165M a $62M), lo que permite a SpaceX ofrecer precios más competitivos.

## 📊 Estructura del Proyecto

El proyecto está dividido en las siguientes fases:

### 1. Recolección de Datos
- **API de SpaceX**: Extracción de datos históricos de lanzamientos
- **Web Scraping**: Obtención de información adicional desde Wikipedia

### 2. Análisis Exploratorio de Datos (EDA)
- Visualizaciones con Seaborn y Matplotlib
- Análisis de relaciones entre variables (Flight Number, Payload Mass, Orbit, etc.)
- Consultas SQL para extraer insights clave

### 3. Feature Engineering
- Creación de variables dummy para variables categóricas
- Preparación de datos para modelos de machine learning

### 4. Modelado Predictivo
- Implementación de algoritmos de clasificación:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - K-Nearest Neighbors (KNN)
- Evaluación de modelos con métricas de precisión

### 5. Visualización Interactiva
- Mapa interactivo con Folium mostrando sitios de lanzamiento
- Dashboard con Plotly Dash para análisis en tiempo real

## 📁 Contenido del Repositorio

### Notebooks
| Archivo | Descripción |
|---------|-------------|
| `jupyter-labs-spacex-data-collection-api-v2.ipynb` | Recolección de datos desde la API de SpaceX |
| `jupyter-labs-webscrapping.ipynb` | Web scraping de datos adicionales |
| `jupyter-labs-eda-dataviz-v2.ipynb` | Análisis exploratorio y visualizaciones |
| `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | Análisis con SQL en SQLite |
| `lab-jupyter-launch-site-location-v2.ipynb` | Mapas interactivos con Folium |
| `labs-jupyter-spacex-Data_wrangling-v2.ipynb` | Limpieza y preparación de datos |
| `SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb` | Modelado predictivo y evaluación |

### Datasets
| Archivo | Descripción |
|---------|-------------|
| `dataset_part_1.csv` | Datos recolectados desde la API |
| `dataset_part_3.csv` | Datos con features engineering aplicado |
| `spacex_launch_geo.csv` | Datos geográficos para mapas |
| `my_data1.db` | Base de datos SQLite con datos de SpaceX |

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** - Manipulación de datos
- **NumPy** - Cálculos numéricos
- **Matplotlib & Seaborn** - Visualizaciones
- **SQLite & SQLAlchemy** - Base de datos
- **Scikit-learn** - Machine Learning
- **Folium** - Mapas interactivos
- **Plotly Dash** - Dashboards
- **Requests** - Consumo de APIs
- **BeautifulSoup** - Web scraping

## 📈 Resultados Clave

- **Tasa de éxito**: La tasa de éxito de aterrizajes ha aumentado del 40% (2013) al 85% (2020)
- **Factores críticos**: 
  - Masa de carga útil (Payload Mass)
  - Tipo de órbita (Orbit)
  - Número de vuelos del booster (Flights)
  - Uso de grid fins y patas de aterrizaje
- **Mejor modelo**: El modelo SVM alcanzó una precisión del 83% en la predicción de aterrizajes exitosos

## 🎯 Conclusiones

SpaceX ha demostrado que la reutilización de cohetes es viable económicamente. El análisis predictivo permite estimar con alta precisión si un aterrizaje será exitoso, lo que ayuda a optimizar los costos operativos y planificar futuras misiones.

## 📝 Cómo Ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/martymeco-bit/spacex-falcon9-landing-prediction.git

2. Instalar dependencias:
```bash
pip install -r requirements.txt

3. Ejecutar notebook en orden numerico:
👤 Autor
Marty Meco
GitHub

📄 Licencia
Este proyecto es parte del curso de IBM Data Science Professional Certificate.

⭐ Si te ha sido útil, ¡no olvides darle una estrella al repositorio!
