# CO2-Emissions
Visualizaciones interactivas y exploratorias sobre emisiones de CO₂, energía y variables económicas desde 1950 hasta 2022.   Incluye análisis por país, evolución histórica, sectores contaminantes y mapas temáticos.

# 🌍 Exploración Visual de Emisiones de CO₂ (1950–2022)

Proyecto de análisis y visualización de datos históricos sobre emisiones de dióxido de carbono, variables económicas, energéticas y climáticas a nivel mundial.

## 📦 Dataset

Fuente utilizada: *Global Carbon Project* + datos enriquecidos  
Rango de años: **1950–2022**  
Cobertura: +190 países, +70 variables  
Filtros aplicados para análisis confiable (`df_util`):
- Años ≥ 1950
- Países reales (códigos `iso_code` de 3 letras)

---

## 📊 Visualizaciones incluidas

- ✅ **Top 10 países por emisiones totales de CO₂ (2021)**
- ✅ **Top 10 países por emisiones per cápita (2021)**
- ✅ **Evolución de emisiones por país (2000–2022)**
- ✅ **Cobertura de columnas con más del 90% de datos**
- ⏳ (Próximo) Mapas, radars y treemaps sectoriales

---

## 🔧 Librerías utilizadas

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import matplotlib.cm as cm

