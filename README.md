**Guía 3: Análisis de Accidentes en Nueva York**

Introducción

Este proyecto tiene como objetivo analizar el creciente número de accidentes en la ciudad de Nueva York y proporcionar visualizaciones que ayuden a identificar patrones. Con estos análisis, las autoridades pueden tomar decisiones informadas para reducir la cantidad de accidentes en el futuro.

**Dataset**

- Nombre del archivo: accidents-1.csv

- Periodo de datos: Enero de 2018 - Agosto de 2019

- Campos principales: Municipio, hora del día, motivo del accidente, entre otros.

**Enfoque y soluciones**

- Carga y limpieza de datos:

- Eliminación de delimitadores erróneos (;;).

- Identificación de valores nulos en las columnas.

**Imputación de valores faltantes:**

- Uso de la moda para completar ZIP CODE.

- Exploración de datos:

- Cálculo de estadísticas descriptivas.

- Creación de visualizaciones para detectar patrones.

**Funciones implementadas**

- Carga de datos desde Google Drive.

- Limpieza y formateo de datos.

- Identificación e imputación de valores nulos.

- Exploración de patrones en accidentes mediante visualización de datos.

**Uso**

- Para ejecutar el análisis, sigue estos pasos:

- Montar Google Drive.

- Cargar el dataset.

- Ejecutar las funciones de limpieza y exploración.

- Interpretar los resultados y visualizaciones generadas.

**Conclusión**

El análisis de datos de accidentes se puede abordar utilizando diversas librerías y herramientas de ciencia de datos. En este proyecto, se han empleado pandas para la manipulación de datos, matplotlib y seaborn para visualización, y técnicas de imputación simples para el tratamiento de valores faltantes. Alternativamente, se podrían utilizar enfoques más avanzados como scikit-learn para imputación basada en modelos o TensorFlow/PyTorch para análisis predictivo. La elección de herramientas depende de la complejidad del análisis requerido y del volumen de datos disponibles. Con este enfoque, se pueden generar insights valiosos que faciliten la toma de decisiones estratégicas para mejorar la seguridad vial en Nueva York.

