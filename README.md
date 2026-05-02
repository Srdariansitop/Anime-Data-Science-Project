# 📊 Anime Data Science Project

Un proyecto completo de **Análisis Exploratorio de Datos (EDA)** y **Machine Learning** aplicado a un dataset de anime, que incluye análisis estadísticos avanzados como ANOVA, regresión lineal y clustering.

---

## 📋 Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo de datos de anime procedentes de **MyAnimeList**. El objetivo es explorar patrones, relaciones y características de series anime mediante técnicas de análisis estadístico y aprendizaje automático no supervisado.

### Contexto Académico
Proyecto realizado como parte de la formación en **Ciencia de Datos** que integra:
- Análisis exploratorio de datos (EDA)
- Pruebas estadísticas (ANOVA)
- Regresión lineal
- Clustering no supervisado
- Visualización de datos

---

## 🗂️ Estructura del Proyecto

```
Anime-Data-Science-Project/
├── README.md                          # Este archivo
├── LICENSE                            # Licencia MIT del proyecto
├── requirements.txt                   # Dependencias del proyecto
├── Jupyter Notebook/
│   ├── data.csv                       # Dataset principal de anime
│   ├── notebook.ipynb                 # EDA: Análisis Exploratorio
│   ├── anova.ipynb                    # Análisis ANOVA
│   ├── regresionlineal.ipynb          # Regresión Lineal
│   └── clustering.ipynb               # Análisis de Clustering
└── Power Point/                       # Presentaciones del proyecto
```

---

## 📁 Descripción de Notebooks

### 1. **notebook.ipynb** - Análisis Exploratorio de Datos (EDA)
**Propósito:** Exploración inicial y comprensión del dataset

**Contenido:**
- Carga y revisión de la estructura del dataset
- Estadísticas descriptivas de variables cuantitativas
- Distribución de variables (Episodes, Duration, Score, etc.)
- Identificación de valores atípicos (outliers)
- Análisis de correlaciones
- Visualizaciones exploratorias

**Variables analizadas:**
- Episodes (Número de episodios)
- Duration_Minutes (Duración en minutos)
- Score (Puntuación promedio)
- Scored_Users (Usuarios que puntuaron)
- Ranked (Ranking)
- Popularity (Popularidad)
- Members (Miembros)

**Herramientas:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

### 2. **anova.ipynb** - Análisis de Varianza (ANOVA)
**Propósito:** Determinar si existen diferencias estadísticamente significativas en las puntuaciones entre tipos de anime

**Pregunta de Investigación:**
¿Existen diferencias estadísticamente significativas en la Puntuación entre distintos tipos de anime (TV, Película, OVA, ONA, Especial, etc.)?

**Contenido:**
- Estadísticas descriptivas por tipo de anime
- Pruebas de normalidad (Shapiro-Wilk)
- Pruebas de homogeneidad de varianza (Levene)
- ANOVA paramétrico (si se cumplen supuestos)
- Pruebas no paramétricas (Kruskal-Wallis)
- Análisis post-hoc (comparaciones pareadas)
- Visualizaciones (boxplots, violinplots)

**Hipótesis:**
- **H₀:** No hay diferencias en la media de puntuación entre tipos de anime
- **H₁:** Sí hay diferencias significativas

**Herramientas:** `scipy.stats`, `matplotlib`, `seaborn`

---

### 3. **regresionlineal.ipynb** - Análisis de Regresión Lineal
**Propósito:** Modelar la relación entre variables y predecir puntuaciones

**Contenido:**
- Selección de variables predictoras
- Construcción de modelo de regresión lineal
- Evaluación de supuestos de regresión
- Interpretación de coeficientes
- Métricas de bondad de ajuste (R², RMSE, MAE)
- Análisis de residuos
- Predicciones

**Herramientas:** `scikit-learn`, `scipy`, `matplotlib`

---

### 4. **clustering.ipynb** - Análisis de Clustering K-Means
**Propósito:** Identificar grupos o patrones naturales en los datos de anime

**Metodología:**
1. **Preprocesamiento:** Limpieza y selección de características
2. **Normalización:** Escalado de datos (StandardScaler)
3. **Selección de K:** Método del Codo (Elbow Method)
4. **Clustering:** Aplicación del algoritmo K-Means
5. **Visualización:** PCA para reducción a 2D
6. **Interpretación:** Análisis de centroides

**Características utilizadas:**
- Episodes
- Duration
- Score
- Popularity
- Members

**Objetivos identificables:**
- Éxitos populares (mainstream)
- Series de nicho
- Películas
- Programas de larga duración

**Herramientas:** `scikit-learn`, `matplotlib`, `seaborn`

---

## 📊 Dataset (data.csv)

**Origen:** MyAnimeList

**Características principales:**
- Type (Tipo de anime: TV, Movie, OVA, ONA, Special, etc.)
- Episodes (Número de episodios)
- Duration_Minutes (Duración)
- Score (Puntuación del usuario)
- Scored_Users (Cantidad de usuarios que puntuaron)
- Ranked (Ranking)
- Popularity (Índice de popularidad)
- Members (Cantidad de miembros)

---

## 🛠️ Instalación y Configuración

### Requisitos previos
- Python 3.7 o superior
- pip o conda

### Instalación de dependencias

```bash
pip install -r requirements.txt
```

### Dependencias principales
```
pandas          # Manipulación de datos
matplotlib      # Visualización
seaborn         # Visualización estadística
scikit-learn    # Machine Learning
ipykernel       # Kernel de Jupyter
numpy           # Computación numérica
scipy           # Análisis estadístico
```

---

## 🚀 Cómo ejecutar

### Opción 1: Jupyter Notebook
```bash
jupyter notebook
```
Luego abre cualquiera de los archivos `.ipynb` en la carpeta `Jupyter Notebook/`

### Opción 2: JupyterLab
```bash
jupyter lab
```

---

## 📈 Resultados y Conclusiones

Este proyecto proporciona insights sobre:

1. **Características del Dataset de Anime**
   - Distribución de puntuaciones
   - Relación entre número de episodios y puntuación
   - Tendencias de popularidad

2. **Diferencias por Tipo de Anime**
   - ANOVA revela si hay diferencias significativas
   - Comparativas entre TV, Películas, OVAs, etc.

3. **Predicción de Puntuaciones**
   - Regresión lineal identifica factores que influyen
   - Modelo para estimar puntuaciones

4. **Segmentación de Anime**
   - Clustering agrupa anime en categorías interpretables
   - Identificación de nichos y tendencias

---

## 👨‍💻 Autor

**Darian** - Proyecto de Ciencia de Datos para la Escuela

---

## 📝 Licencia

Este proyecto está bajo la **Licencia MIT (Massachusetts Institute of Technology)**.
**Detalles completos en:** [LICENSE](LICENSE)


---