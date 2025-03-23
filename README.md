# Módulo de Estadística, Álgebra Lineal y Data Mining  

## Descripción  
Este módulo proporciona una introducción a técnicas avanzadas de análisis de datos, combinando herramientas de estadística, álgebra lineal y minería de datos. Se enfoca en la construcción de modelos predictivos utilizando diversas metodologías para la exploración, transformación y modelado de datos.  

## Contenidos  

### Estadística  
El análisis estadístico es fundamental para la toma de decisiones basada en datos. En este módulo, se aplican diversas técnicas estadísticas para describir, inferir y modelar datos de manera efectiva.  

#### Funciones de Probabilidad  
Las funciones de probabilidad permiten modelar fenómenos aleatorios y analizar la distribución de datos. Entre las distribuciones más utilizadas se encuentran:  
- **Distribución Normal**:  
  \[
  f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{(x - \mu)^2}{2\sigma^2}}
  \]
- **Distribución Binomial**:  
  \[
  P(X = k) = \binom{n}{k} p^k (1 - p)^{n - k}
  \]
- **Distribución Poisson**:  
  \[
  P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}
  \]

#### Test Estadísticos  
Se utilizan pruebas estadísticas para evaluar hipótesis y comparar grupos de datos:  
- **Test de Student (t-test)**: Compara la media de dos grupos y evalúa si las diferencias son estadísticamente significativas.  
  \[
  t = \frac{\bar{X}_1 - \bar{X}_2}{\sqrt{\frac{s_1^2}{n_1} + \frac{s_2^2}{n_2}}}
  \]
- **ANOVA (Análisis de Varianza)**: Evalúa si existen diferencias significativas entre más de dos grupos.  
- **Test de Tukey**: Comparación post-hoc tras ANOVA para identificar grupos diferentes.  
- **P-valor**: Indica la probabilidad de obtener los resultados observados si la hipótesis nula es verdadera. Si \( p < 0.05 \), se rechaza la hipótesis nula.  

#### Análisis Multivariable  
Permite analizar la relación entre múltiples variables simultáneamente:  
- **Regresión Múltiple**  
  \[
  Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + ... + \beta_n X_n + \epsilon
  \]
- **Coeficiente de Determinación \( R^2 \)**:  
  \[
  R^2 = 1 - \frac{SS_{res}}{SS_{tot}}
  \]
  Mide la proporción de variabilidad explicada por el modelo.  

### Álgebra Lineal y Transformaciones  
El álgebra lineal es fundamental en la manipulación de datos en machine learning y estadísticas:  
- **Normalización de datos**:  
  \[
  X_{norm} = \frac{X - \mu}{\sigma}
  \]
  Escalar datos para mejorar la estabilidad numérica de los modelos.  

### Regresión Lineal  
Es un método estadístico clave para modelar relaciones entre variables. Se utiliza en predicción, análisis de tendencias y optimización.  

- **Fórmula del Modelo**:  
  \[
  Y = \beta_0 + \beta_1 X + \epsilon
  \]
  Donde:  
  - \( Y \) es la variable dependiente.  
  - \( X \) es la variable independiente.  
  - \( \beta_0 \) es el intercepto.  
  - \( \beta_1 \) es el coeficiente de la variable independiente.  
  - \( \epsilon \) es el error.  

La regresión lineal se usa en múltiples disciplinas como economía, biología, y ciencias sociales para entender relaciones entre variables y hacer predicciones.  

### Minería de Datos  
Incluye técnicas para extraer patrones y conocimiento de grandes volúmenes de datos:  
- **Clustering**: Algoritmos como K-Means y DBSCAN para segmentación de datos.  
- **Reducción de dimensionalidad**: PCA para mejorar la eficiencia del análisis.  
- **Modelos predictivos**: Aplicación de regresión y aprendizaje automático.  

## Herramientas y Tecnologías Utilizadas  
Se emplean herramientas especializadas en análisis de datos y machine learning en **Python** y **R**.  

**Python** es ampliamente utilizado en análisis de datos debido a sus bibliotecas especializadas: 
- **Manipulación de datos**: `pandas`, `numpy`  
- **Estadística y pruebas**: `scipy`, `statsmodels`  
- **Machine Learning**: `scikit-learn`  
- **Visualización**: `matplotlib`, `seaborn`

**R** es una potente herramienta para estadísticas avanzadas.  

## Manipulación de Datos  
- `dplyr`  
- `tidyverse`  

## Modelos Estadísticos  
- `lm()`  
- `aov()`  

## Proceso de Trabajo  

### Exploración de Datos  
- Análisis de variables  
- Detección de valores atípicos  
- Identificación de datos faltantes  

### Preprocesamiento  
- Normalización y transformación de datos para mejorar el rendimiento del modelo  

### Modelado Predictivo  
- Aplicación de algoritmos de regresión y clustering para generar predicciones  

### Evaluación del Modelo  
- Medición del error  
- Coeficiente de determinación \( R^2 \)  
- Validación cruzada  

## Visualización  
- `ggplot2`  

## Conclusión  
Este módulo proporciona una base sólida en análisis de datos, combinando estadística, álgebra lineal y minería de datos para la construcción de modelos predictivos. Se fomenta el uso de herramientas especializadas como **Python** y **R** para la manipulación y análisis de datos en distintos contextos aplicados.



<h3>1 - Práctica de Estadísticas en R, un lenguaje de programación con gran foco en la estadística.</h1>
    <p>Se explora una Dataset de Airbnb.</p>
    <p>Se realizan Análisis estadísticos tales como:</p>
    <ul>
        <li>Funciones de probabilidad.</li>
        <li>Test Estadísticos.</li>
        <li>Análisis Multivariable.</li>
        <li>Regresión lineal.</li>
        <li>Clustering.</li>
        <li>Normalización de datos.</li>
        <li>Coeficiente de determinación.</li>
        <li>P-valor.</li>
        <li>etc.</li>
    </ul>
    <p>Y finalmente se crea un modelo predictivo.</p>
    <h3>2 - Práctica de Álgebra lineal enfocada en Regresión lineal, desarrollado en Python.</h1>
    
    
