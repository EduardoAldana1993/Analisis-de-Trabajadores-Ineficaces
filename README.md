# Analisis-de-Trabajadores-Ineficaces
Descripción del Proyecto

Este proyecto analiza el rendimiento de trabajadores de un call center con el objetivo de identificar operadores ineficientes usando métricas operativas clave.
El análisis se realizó a partir de un conjunto de datos simulados (proyecto académico de la plataforma TripleTen) que contiene información de actividad de los operadores.

Objetivo

Detectar qué trabajadores presentan bajo desempeño basándose en su actividad telefónica y métricas de productividad, para entender patrones de ineficiencia y apoyar la toma de decisiones basada en datos.

Datos Utilizados

Los datos representan la actividad de operadores de un call center e incluyen variables como:

⏱ Duración de llamadas
📞 Llamadas entrantes
📲 Llamadas salientes
❌ Llamadas perdidas

Se consideró que una baja cantidad de llamadas gestionadas y ciertos patrones de duración podrían indicar bajo rendimiento.

 Herramientas y Tecnologías

Python (análisis de datos)
Pandas & NumPy (manipulación y procesamiento de datos)
Jupyter Notebook (entorno de trabajo)
SQL (consultas y extracción de métricas)
Tableau (visualización de datos y dashboards)

Proceso de Análisis
El proyecto se desarrolló en varias etapas:

Limpieza de Datos

Revisión de valores faltantes
Corrección de tipos de datos
Preparación de variables para análisis

 Análisis Exploratorio

Distribución de llamadas por operador
Análisis de duración de llamadas
Comparación entre llamadas entrantes y salientes

 Métricas y KPIs

Se construyeron indicadores de desempeño, tales como:
Promedio de duración de llamadas
Número total de llamadas gestionadas
Proporción de llamadas perdidas
Actividad total por operador

Visualización de Datos

Se utilizaron gráficos y dashboards para identificar patrones de comportamiento y detectar operadores con desempeño atípico.

Resultados Principales

El análisis reveló que:
Aproximadamente 2% de los trabajadores mostraban patrones consistentes con bajo rendimiento
La ineficiencia estaba asociada principalmente con:
Bajo volumen de llamadas gestionadas
Alta proporción de llamadas perdidas
A pesar de que el porcentaje es pequeño, el impacto puede ser significativo en operaciones a gran escala (millones de registros)

Estructura del Repositorio
notebook 1 Preparacion.ipynb → Limpieza y preparación de datos
notebook 2 Analisis SQL.ipynb → Consultas SQL y métricas
notebook 3 Analisis.ipynb → Análisis final y visualizaciones
Archivos .csv → Conjuntos de datos utilizados

PDF del proyecto → Presentación final del análisis

Conclusión:
Este proyecto demuestra cómo el análisis de datos puede utilizarse para evaluar el desempeño de empleados, identificar ineficiencias y generar información útil para mejorar procesos operativos.
