# Ciencia de Datos 1: Exploratory Data Analysis (EDA)

Este repositorio contiene el avance práctico, notas de clase y códigos desarrollados durante el curso de Ciencia de Datos 1 enfocado en el Análisis Exploratorio de Datos (EDA), dictado por la Oficina de Tecnologías de la Información de la Universidad Nacional de Ingeniería (OTI-UNI).

El objetivo principal es dominar las técnicas de estadística descriptiva, visualización y preparación de datos necesarias para auditar la calidad de la información antes de la construcción de modelos predictivos.

## Plan de Estudios del Curso

### Sesión 1: Fundamentos del EDA
* Rol del EDA en el ciclo de datos y objetivos.
* Tipos de variables y problemas comunes.
* Herramientas base (Python, pandas, matplotlib).
* Tipos y conversiones "trampa" (fechas, strings numéricos, nulos encubiertos).
* Buenas prácticas de reproducibilidad (semillas, notebooks limpios, control de rutas).
* Caso práctico: Elección del dataset, definición de objetivos y diccionario inicial.

### Sesión 2: Descriptivas, Visualización y Distribución de Clases
* Medidas de tendencia central y dispersión.
* Histogramas, boxplots, KDE y visualización responsable.
* Distribución de clases y diagnóstico de desbalance.
* Segmentación exploratoria (cohortes, región, canal).
* Partición estratificada preliminar.
* Caso práctico: Perfilado descriptivo y análisis de clases.

### Sesión 3: Relaciones y EDA por Tipo de Datos
* Correlaciones (Pearson, Spearman, Kendall).
* Mapas de calor y relaciones numéricas vs. categóricas.
* Series temporales: Estacionalidad, re-sampling, ventanas rodantes.
* Mini-EDA de texto y geodatos.
* Caso práctico: Matriz de correlación y visualizaciones de tiempo/texto.

### Sesión 4: Calidad y Preparación de Datos
* Valores faltantes: MCAR, MAR, MNAR e implicancias.
* Outliers robustos: IQR, MAD, winsorización.
* Duplicados y unicidad de llaves.
* Normalización, estandarización y transformaciones (log, Box-Cox).
* Consolidación de tipos y unidades.
* Caso práctico: Imputación documentada y tratamiento de outliers.

### Sesión 5: Feature Engineering y Selección
* Creación de variables: Ratios, binning, agregaciones.
* Selección por varianza, correlación y redundancia.
* Manejo de categóricas de alta cardinalidad.
* PCA introductorio como puente a modelado.
* Riesgos de fuga de información (data leakage).
* Caso práctico: Generación de nuevas features y PCA exploratorio.

### Sesión 6: Integración y Cierre
* Validación de calidad y linaje de datos.
* Evaluación de desbalance y partición estratificada final.
* Drift preliminar: Comparación train vs. muestra reciente.
* Storytelling de hallazgos y handoff a modelado.
* Reproducibilidad: Notebooks a scripts y control de versiones.
* Caso práctico: Ejecución end-to-end (dataset listo para modelado).

## Entorno de Desarrollo

A diferencia de la propuesta inicial en la nube, el entorno de este repositorio está configurado de manera local utilizando:
* Visual Studio Code (VS Code) como IDE principal.
* Extensión oficial de Jupyter para la ejecución modular de celdas de código.
* Entorno local de Python 3.14 con el paquete ipykernel configurado.

## Requisitos e Instalación

Para ejecutar los notebooks de este repositorio, asegúrate de contar con las librerías necesarias ejecutando el siguiente comando en tu terminal:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---
Curso dictado por el docente Juan Chipoco - OTI UNI.
