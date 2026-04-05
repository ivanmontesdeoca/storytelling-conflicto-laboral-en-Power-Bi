# Dashboard Power BI – Conflictividad laboral en plataformas de reparto

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un dashboard interactivo en Power BI para analizar la conflictividad laboral en el sector de mensajería urbana y reparto de alimentos en Argentina (2006–2023).

El objetivo es evaluar cómo la expansión de plataformas digitales impactó en:

- Nivel de conflictividad  
- Demandas laborales  
- Formas de organización  
- Repertorios de protesta  

---

## Objetivo analítico

Analizar si la llegada de plataformas digitales modificó los patrones de conflictividad laboral en el sector, comparando dos periodos:

- 2006–2017 (pre-plataformas)  
- 2018–2023 (con plataformas)  

---

## Dataset

El análisis se basa en una base de datos de conflictos laborales elaborada por la Secretaría de Trabajo, Empleo y Seguridad Social.

- Cobertura: nacional  
- Periodo: 2006–2023  
- Estructura: múltiples variables sobre demandas, acciones y organizaciones  

(Como se describe en la presentación :contentReference[oaicite:1]{index=1}, la base incluye información detallada sobre eventos conflictivos en todo el país)

---

## Estructura del dashboard (Storytelling)

El dashboard está diseñado en tres niveles de análisis:

### 1. Indicadores generales
- Total de conflictos  
- Año más conflictivo  
- Demandas predominantes  
- Tipos de acción y organización  

Insight destacado:
La principal demanda es **seguridad**, no salarial :contentReference[oaicite:2]{index=2}  

---

### 2.  Análisis espacial y temporal
- Evolución de la conflictividad (2006–2023)  
- Mapa de conflictos por provincia  
- Segmentación por tipo de acción, demanda y organización  

Permite analizar dinámicas regionales y evolución en el tiempo  

---

### 3. Comparación estructural
- Comparación entre periodo pre y post plataformas  
- Cambios en:
  - demandas  
  - formas de protesta  
  - organización colectiva  

 Permite identificar continuidades y rupturas en el conflicto  

---

## Funcionalidades del dashboard

- Filtros dinámicos por año  
- Interacción entre gráficos (cross-filtering)  
- Segmentación por variables clave  
- Navegación guiada (storytelling)  

Ejemplo:  
Seleccionar “paro” permite visualizar qué organizaciones lo utilizan y qué demandas están asociadas :contentReference[oaicite:3]{index=3}  

---

## Tecnologías utilizadas

- Power BI  
- Modelado de datos  
- DAX (medidas y columnas calculadas)  
- Tablas calendario  

---

## Principales insights

- Predominan demandas vinculadas a **seguridad laboral**  
- La movilización es la forma de protesta más frecuente  
- Persistencia del rol de sindicatos tradicionales  
- Incremento de conflictividad en el periodo de plataformas  

---

## Posibles mejoras

- Integración con SQL/Python para pipeline automatizado  
- Incorporación de nuevas fuentes de datos  
- Análisis predictivo de conflictividad  

---

##  Autor
Iván Montes de Oca  
https://github.com/ivanmontesdeoca
