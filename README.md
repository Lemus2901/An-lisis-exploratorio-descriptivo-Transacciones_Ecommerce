# Proyecto de Análisis Exploratorio y Descriptivo de Transacciones de un Ecommerce 📊🛍

Este proyecto transforma datos brutos de transacciones en un ecosistema de insights accionables, apoyándose en la potencia de Python 🐍 y SQL (con DuckDB) para generar una narrativa visual y analítica que facilite la toma de decisiones estratégicas.

## Tabla de Contenidos 📖
1. [Introducción 🌟](#introducción-🌟)
2. [Objetivos 🎯](#objetivos-🎯)
3. [Fuente de Datos 📂](#fuente-de-datos-📂)
4. [Tecnologías Utilizadas 🛠](#tecnologías-utilizadas-🛠)
5. [Metodología 📑](#metodología-📑)
    - [Conexión y Preparación de Datos ⚙](#1-conexión-y-preparación-de-datos-⚙)
    - [Análisis Descriptivo 📋](#2-análisis-descriptivo-📋)
    - [Exploración y Visualización 📊](#3-exploración-y-visualización-📊)
    - [Segmentación y Análisis de Clientes 👥](#4-segmentación-y-análisis-de-clientes-👥)
6. [Conclusiones 🏁](#conclusiones-🏁)
7. [Cómo Ejecutar el Proyecto 💻](#cómo-ejecutar-el-proyecto-💻)
8. [Colaboradores 🤝](#colaboradores-🤝)

## Introducción 🌟

Este repositorio documenta el proceso de análisis de datos aplicados a las transacciones de un ecommerce. Se parte de datos obtenidos mediante la API de Kaggle y se utiliza una combinación de Python 🐍 y SQL (a través de DuckDB) para transformar y analizar la información, extrayendo insights relevantes para la estrategia del negocio.

## Objetivos 🎯

- *Conectar y acceder al dataset*: Utilizar la API de Kaggle para obtener un dataset diverso y robusto.
- *Preparar y depurar los datos*: Cargar, limpiar y transformar tanto variables numéricas como categóricas.
- *Realizar análisis descriptivo*: Calcular medidas de tendencia central y dispersión en variables numéricas, y evaluar frecuencias en variables categóricas.
- *Visualizar datos y patrones*: Utilizar gráficos (histogramas, boxplots, scatter plots, gráficos de barras y pie charts) para identificar tendencias, outliers y relaciones entre variables.
- *Segmentar y analizar clientes*: Explorar la distribución geográfica de los clientes, su actividad de compra y la evolución temporal de las transacciones.
- *Extraer insights accionables*: Integrar los hallazgos para orientar estrategias futuras y abrir la puerta a nuevas investigaciones.

## Fuente de Datos 📂

- *Dataset*: Transacciones de un Ecommerce obtenido a través de la API de Kaggle.
- *Contenido*: Datos que incluyen variables numéricas (Quantity, TotalValue, Price) y categóricas (Region, Category, Product, CustomerName), además de información temporal (TransactionDate, SignupDate).

## Tecnologías Utilizadas 🛠

- *Python*: Para procesamiento, análisis y visualización de datos.
- *SQL con DuckDB*: Para cargar, depurar y transformar la información de manera eficiente.
- *Bibliotecas de Visualización*: (ej. Matplotlib, Seaborn) para la creación de gráficos que faciliten la interpretación de los datos.

## Metodología 📑

### 1. Conexión y Preparación de Datos ⚙
- *Acceso al Dataset*: Conexión a Kaggle mediante su API para obtener un conjunto de datos diverso.
- *Carga y Limpieza*: Uso de Python y SQL (DuckDB) para:
    - Cargar la información.
    - Depurar datos duplicados e inconsistentes.
    - Estandarizar formatos y asegurar la calidad de la base de datos.

### 2. Análisis Descriptivo 📋
*Variables Numéricas*:
- Medidas Calculadas: Media, mediana, mínimo, máximo y desviación estándar para Quantity, TotalValue y Price.
- Visualizaciones: Histogramas y boxplots para detectar asimetrías y outliers.

*Variables Categóricas*:
- Frecuencias y Proporciones: Evaluación de la distribución de datos para Región, Categoría, Producto y CustomerName.
- Gráficos Utilizados: Barras y pie charts para identificar las categorías y clientes más relevantes.

### 3. Exploración y Visualización 📊
- *Relación entre Variables*:
    - Uso de scatter plots e histogramas para analizar la relación entre Quantity y TotalValue.
- *Análisis Temporal*:
    - Gráficos de líneas basados en TransactionDate para identificar patrones estacionales y picos en la actividad.
- *Comparaciones por Categoría*:
    - Diagramas de dispersión y boxplots segmentados por categoría para comparar el precio unitario y el valor total de las transacciones.

### 4. Segmentación y Análisis de Clientes 👥
- *Análisis Geográfico*:
    - Identificación de clientes únicos y estudio de su distribución geográfica, combinando consultas SQL (COUNT DISTINCT) y visualizaciones en Python.
- *Comportamiento de Clientes*:
    - Análisis de la relación entre la fecha de registro (SignupDate) y la actividad de compra a través de gráficos de dispersión y análisis de cohortes.

## Conclusiones 🏁

El proceso analítico ha permitido transformar datos complejos en una narrativa visual y analítica clara, facilitando la identificación de patrones y tendencias clave. Los insights obtenidos no solo responden a las preguntas iniciales del negocio, sino que también abren nuevas perspectivas para investigaciones futuras y estrategias de mejora continua.

## Cómo Ejecutar el Proyecto 💻

1. Clonar este repositorio.
2. Ejecutar el Notebook en Google Colab o Jupyterlab.

## Colaboradores 🤝

- *[Andres Felipe Lemus V](https://www.linkedin.com/in/andres-felipe-lemus-v-7943882a9/)*
- *[Juan Daniel Vergara Nieto](https://www.linkedin.com/in/daniel-vergara-nieto/)* 
