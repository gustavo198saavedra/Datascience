[Enlace al Taller de Machine Learning con Dataset Iris](https://github.com/gustavo198saavedra/Datascience?tab=readme-ov-file#taller-de-machine-learning-con-dataset-iris-taller-de-machine-learning-con-dataset-iris)

[Enlace al Taller de Machine Learning: Boston House Prices Dataset](https://github.com/gustavo198saavedra/Datascience?tab=readme-ov-file#taller-de-machine-learning-boston-house-prices-dataset-taller-de-machine-learning-boston-house-prices-dataset)

[Enlace al Proyecto Analisis del mercado de los videojuegos](https://github.com/gustavo198saavedra/Datascience?tab=readme-ov-file#proyecto-analisis-del-mercado-de-los-videojuegos-proyecto-analisis-del-mercado-de-los-videojuegos)


# Taller de Machine Learning con Dataset Iris

Este proyecto es parte de un taller de aprendizaje automático y utiliza el conocido conjunto de datos Iris. El objetivo principal es realizar un análisis detallado de diferentes modelos k-Nearest Neighbors (k-NN) y evaluar su desempeño en la tarea de clasificación de especies de iris.

## Contenido del Proyecto

1. **Visualización de Datos:**
   - Utilización de la función scatter_matrix de Pandas para visualizar las relaciones entre las características del dataset Iris.

2. **Análisis de Complejidad de Modelos KNN:**
   - Implementación de modelos k-NN variando el número de vecinos.
   - Medición del desempeño de cada modelo entrenado.
   - Identificación del mejor modelo y explicación de la elección.

3. **Matriz de Confusión:**
   - Obtención y análisis de la matriz de confusión para el modelo escogido.
   - Visualización de la matriz de confusión para una mejor comprensión.

4. **Métricas de Evaluación:**
   - Investigación y aplicación de métricas como recall, precisión y exactitud.
   - Explicación de qué tan bueno es el modelo para la tarea de predicción.

5. **Comentarios en el Código:**
   - Uso de comentarios para explicar cada línea de código y facilitar la comprensión.

# Taller de Machine Learning: Boston House Prices Dataset 

Este proyecto tiene como objetivo explorar diversas estrategias de ingeniería de características en el contexto de un problema de regresión lineal utilizando el conjunto de datos de precios de casas de Boston. Se utilizará un modelo de regresión lineal estándar y se evaluará su desempeño en diferentes escenarios de preprocesamiento de datos.

## Estrategias de Ingeniería de Características

1. **Características Originales:**
   - Entrenamiento del modelo con las características originales proporcionadas por `sklearn.datasets.load_boston`.

2. **Características Escaladas:**
   - Entrenamiento del modelo con características escaladas utilizando diversos métodos disponibles en `sklearn.preprocessing`.

3. **Características Proyectadas con PCA:**
   - Utilización de PCA para proyectar el conjunto de datos sobre los dos primeros componentes principales.

4. **Binning y Características de Interacción:**
   - Aplicación de binning y generación de características de interacción. Se realizará binning en características continuas.

5. **Características Polinómicas:**
   - Generación de características polinómicas con diferentes grados. Elección del grado que proporciona el mejor desempeño.

## Propósito del Taller

- **Exploración de Estrategias de Preprocesamiento:**
  - Comprender cómo diferentes técnicas de ingeniería de características pueden afectar el rendimiento de un modelo de regresión lineal.

- **Evaluación del Impacto en el Modelo:**
  - Comparar y analizar cómo cada estrategia impacta la capacidad del modelo para realizar predicciones precisas.

- **Toma de Decisiones Informada:**
  - Proporcionar información sobre qué estrategias de ingeniería de características pueden ser más beneficiosas en el contexto de un problema de regresión lineal.

- **Práctica con Herramientas de Machine Learning:**
  - Familiarizarse con el uso de funciones y herramientas de la biblioteca scikit-learn para implementar diferentes estrategias de preprocesamiento.

## Entregable y Repositorio GitHub

Los proyectos han sido desarrollados en la carpeta Notebooks y se encuentra disponible en el siguiente repositorio de GitHub:

[Enlace al Repositorio](https://github.com/gustavo198saavedra/Datascience)

# Proyecto Analisis del mercado de los videojuegos
### Planteamiento del Problema:

El problema se centra en comprender y analizar el mercado de los videojuegos, identificando patrones, tendencias y relaciones entre diferentes variables que puedan influir en el éxito comercial de un juego. Este análisis es crucial tanto para los desarrolladores de videojuegos como para las empresas editoras, ya que les permite tomar decisiones estratégicas informadas en áreas como el desarrollo de juegos, la inversión en marketing y la selección de plataformas de lanzamiento.

### Importancia del Análisis de Datos:

1. **Toma de Decisiones Informadas:** El análisis de datos proporciona información valiosa sobre qué géneros de juegos son más populares, qué características se correlacionan con altas puntuaciones de los críticos y cuáles son las plataformas más rentables. Esto permite a los desarrolladores y editores tomar decisiones informadas sobre qué juegos producir, cómo comercializarlos y dónde lanzarlos.

2. **Optimización de Recursos:** Comprender las preferencias de los jugadores y los factores que influyen en las ventas ayuda a asignar recursos de desarrollo y marketing de manera más eficiente. Esto puede conducir a una mayor rentabilidad y a maximizar el retorno de la inversión en el desarrollo de juegos.

3. **Identificación de Tendencias Emergentes:** El análisis de datos permite identificar tendencias emergentes en la industria de los videojuegos, como cambios en las preferencias de los jugadores o el impacto de nuevas tecnologías. Estar al tanto de estas tendencias puede proporcionar una ventaja competitiva significativa.

### Objetivo del Proyecto:

El objetivo principal del proyecto es analizar los datos relacionados con las ventas y la recepción crítica de los videojuegos para identificar patrones y tendencias clave. Algunos de los objetivos específicos incluyen:

- Identificar los géneros de juegos más populares y lucrativos.
- Analizar la relación entre las puntuaciones de los críticos y las ventas totales.
- Evaluar el desempeño de ventas en diferentes regiones geográficas.
- Investigar la influencia de las plataformas de lanzamiento en las ventas de juegos.

### Solución Propuesta:

La solución propuesta implica realizar un análisis exhaustivo de los datos disponibles para extraer información valiosa que pueda guiar las decisiones comerciales. Esto implica:

1. **Preprocesamiento de Datos:** Limpiar y preparar los datos para su análisis, abordando valores faltantes, duplicados o atípicos.

2. **Análisis Exploratorio de Datos:** Explorar y visualizar los datos para identificar patrones, correlaciones y tendencias.

3. **Modelado Predictivo (Opcional):** Si es necesario, desarrollar modelos predictivos para predecir el desempeño de ventas de futuros juegos en función de diversas características.

4. **Informe y Recomendaciones:** Presentar los hallazgos del análisis en un informe detallado que destaque las principales conclusiones y proporcione recomendaciones prácticas para los desarrolladores y editores de videojuegos.

En resumen, este proyecto busca proporcionar información valiosa sobre el mercado de los videojuegos que pueda utilizarse para optimizar la toma de decisiones comerciales y mejorar el éxito de los juegos en el mercado.

**Informe de Análisis del Mercado de Videojuegos**

**Introducción:**
El presente informe tiene como objetivo analizar el mercado de los videojuegos mediante el estudio de datos relacionados con las ventas y la recepción crítica de los mismos. Se utilizaron técnicas de análisis de datos y modelado predictivo para identificar patrones, tendencias y relaciones clave que puedan influir en el éxito comercial de un juego.

**Metodología:**
Se utilizó un conjunto de datos que incluye información sobre diferentes aspectos de los videojuegos, como su título, género, plataforma, ventas y puntajes de los críticos. Se realizó un análisis exploratorio de datos para comprender la distribución y las relaciones entre las variables. Luego, se aplicaron modelos de regresión para predecir el puntaje de los críticos.

**Resultados:**
1. **Patrones de Ventas:** Se identificaron ciertos géneros de juegos que tienden a tener mayores ventas en comparación con otros. Los juegos de acción y aventura parecen ser los más populares, seguidos de cerca por los juegos de disparos y deportes.

2. **Relación entre Puntajes de Críticos y Ventas:** Se observó una correlación positiva entre los puntajes de los críticos y las ventas totales de los juegos. Esto sugiere que los juegos mejor calificados tienden a vender más unidades.

3. **Desempeño de Plataformas:** Se encontraron diferencias en el desempeño de las ventas de juegos en diferentes regiones geográficas y plataformas de lanzamiento. Algunas plataformas pueden ser más populares en ciertas regiones, lo que puede influir en las estrategias de lanzamiento de los juegos.

**Conclusiones:**
- Los desarrolladores y editores de videojuegos pueden utilizar los hallazgos de este análisis para tomar decisiones informadas sobre qué tipos de juegos producir, cómo comercializarlos y dónde lanzarlos.
- Es importante prestar atención a las opiniones de los críticos, ya que los juegos bien calificados tienden a tener un mejor desempeño en términos de ventas.
- Se recomienda realizar un seguimiento continuo del mercado y adaptar las estrategias comerciales según las tendencias emergentes y los cambios en las preferencias de los jugadores.

**Recomendaciones:**
1. **Diversificar el Catálogo:** Considerar la producción de juegos en una variedad de géneros para satisfacer las diferentes preferencias de los jugadores.
2. **Invertir en Calidad:** Priorizar la calidad en el desarrollo de juegos para obtener mejores puntajes de los críticos y, en última instancia, mayores ventas.
3. **Segmentación del Mercado:** Adaptar las estrategias de lanzamiento y marketing según las preferencias regionales y las plataformas de juego más populares en cada mercado objetivo.

**Próximos Pasos:**
- Realizar un seguimiento continuo del desempeño de los juegos lanzados y ajustar las estrategias según los resultados.
- Explorar el uso de técnicas de aprendizaje automático más avanzadas para mejorar la precisión de las predicciones de ventas y la comprensión del mercado.
