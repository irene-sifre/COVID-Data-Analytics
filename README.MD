# Análisis de Eventos Adversos de Vacunas COVID-19

Este proyecto analiza los eventos adversos reportados tras la administración de vacunas COVID-19, utilizando datos del sistema VAERS (Vaccine Adverse Event Reporting System). 
El objetivo es identificar patrones y tendencias que puedan mejorar la toma de decisiones en salud pública y optimizar la gestión de efectos adversos de las vacunas.

## Objetivo del Proyecto
El objetivo principal es analizar los reportes de eventos adversos asociados con las vacunas COVID-19 para generar insights accionables 
que respalden decisiones en políticas de vacunación y atención de salud pública.

## Metodología
1. **Fuente de Datos:** 
   - Datos extraídos de VAERS, una base de datos pública que recopila reportes de eventos adversos relacionados con la vacunación en EE.UU.

2. **Limpieza de Datos:**
   - Se eliminaron valores duplicados y nulos irrelevantes.
   - Se normalizaron y estandarizaron columnas clave, incluyendo síntomas y demografía de los pacientes.

3. **Almacenamiento en SQL:**
   - Los datos fueron organizados y gestionados en una base de datos SQL para permitir consultas eficientes y estructuradas.

4. **Consultas y Análisis:**
   - Se realizaron consultas SQL para extraer subconjuntos clave de datos y se utilizó Tableau para el análisis visual de los datos y la creación de dashboards.

## Hipótesis Analizadas
1. **Prevalencia de Síntomas por Género:** Las mujeres tienen una mayor probabilidad de presentar síntomas adversos tras la vacunación en comparación con los hombres.
2. **Mortalidad y Edad:** Los pacientes de mayor edad presentan un mayor riesgo de mortalidad tras la vacunación.
3. **Incidencia en Estados más Poblados:** Los estados con mayor población tienden a reportar un mayor número de eventos adversos.

## Insights Principales
1. **Prevalencia de Síntomas por Género:**
   - Las mujeres reportan un mayor número de síntomas adversos, especialmente en categorías leves.

2. **Mortalidad y Edad:**
   - Se observó que las personas mayores presentan un mayor riesgo de síntomas severos y mortalidad, alineándose con la hipótesis inicial.

3. **Incidencia por Estado y Población:**
   - Los estados con mayor población presentan una mayor cantidad de reportes de eventos adversos, lo que podría estar relacionado con la mayor exposición y distribución de vacunas.

## Recomendaciones
1. **Estandarización en la Recogida de Información y Codificación de Síntomas:**
   - Implementar un método uniforme de codificación de síntomas para asegurar una mayor consistencia en los reportes y mejorar la comparabilidad de datos.

2. **Reducción de Campos Textuales No Estructurados:**
   - Minimizar el uso de texto libre en los reportes para reducir errores y facilitar el análisis automatizado de los datos.

3. **Homogeneización de Datos Demográficos:**
   - Recoger información adicional sobre comorbilidades y antecedentes médicos para permitir un análisis más preciso de los factores de riesgo por grupo poblacional.

4. **Monitoreo de Lotes Específicos:**
   - Realizar un seguimiento adicional a lotes de vacunas con mayores reportes de eventos adversos para asegurar la consistencia en su seguridad y calidad.

## Visualizaciones
El análisis incluyó visualizaciones clave desarrolladas en Tableau:
- **Prevalencia de Síntomas por Género**
- **Mortalidad y Edad**
- **Distribución de Síntomas por Estado**
- **Análisis de Lotes de Vacunas**

Estas visualizaciones ayudan a comprender la relación entre síntomas, género, edad, estado geográfico y lotes de vacunas, proporcionando una visión amplia sobre la distribución y severidad de los efectos adversos.

## Conclusión
Este análisis de eventos adversos asociados con la vacunación contra COVID-19 identifica tendencias clave en síntomas, mortalidad y distribución geográfica. Las recomendaciones resultantes buscan mejorar la calidad de los reportes de eventos adversos y ayudar a reducir riesgos asociados con la vacunación en poblaciones específicas.
