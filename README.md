# proyecto_2_Alejandro-Cantero

Buenas tardes, aquí les presento el proyecto a analizar: se trata de un **dataset de microcréditos para personas con bajos recursos**.  
A continuación dejo el enlace, junto con los programas y librerías utilizadas:

[Enlace al dataset y materiales del proyecto](https://drive.google.com/drive/folders/1unRq4vd8b8x8NiWDlspHIcPHc0V-ljTp?usp=drive_link)

## Materiales utilizados  

**Dataset principal:**  
- `kiva_loans.csv` (dataset de préstamos de Kiva, procedente de la iniciativa “Data Science for Good”).  

**Entorno de trabajo:**  
- Notebook de **Jupyter / Google Colab** (`kiva.ipynb`).  
- Lenguaje de programación: **Python 3**.  

**Ficheros auxiliares (implícitos):**  
- Archivos comprimidos `.zip` con los datos.  
- Capas y datasets geográficos para los mapas (a través de `geodatasets` / `geopandas`).  

---

## Librerías utilizadas en el proyecto  

Estas son todas las librerías que se importan en el notebook, agrupadas por función:

### 1. Manipulación y análisis de datos  

- **pandas** (`import pandas as pd`)  
  Para la carga del CSV, manejo de dataframes, filtrado, selección de columnas, conversión de tipos, etc.

- **numpy** (`import numpy as np`)  
  Para operaciones numéricas y de apoyo a algunos cálculos.

### 2. Visualización de datos (gráficos y dashboards)  

- **matplotlib.pyplot** (`import matplotlib.pyplot as plt`)  
  Librería base para gráficos (histogramas, barras, etc.).

- **seaborn** (`import seaborn as sns`)  
  Librería de gráficos estadísticos de alto nivel basada en matplotlib, para obtener visualizaciones más elaboradas.

- **missingno** (`import missingno as msno`)  
  Especializada en la visualización de valores faltantes: matrices de nulos, gráficos de barras, etc.

- **plotly** (`import plotly as pl`)  
  Para visualizaciones interactivas (gráficos dinámicos que permiten hacer zoom, pasar el ratón, etc.).

### 3. Datos y visualización geográfica  

- **geopandas** (`import geopandas as gpd`)  
  Extiende pandas para trabajar con datos geoespaciales (shapefiles, geometrías, mapas).

- **geodatasets** (`import geodatasets`)  
  Proporciona datasets geográficos de referencia (por ejemplo, capas de países) para cruzarlos con los datos de Kiva.

- **folium** (`import folium`)  
  Permite crear mapas interactivos basados en Leaflet, añadiendo capas y marcadores con la información de los préstamos.

---

## Conclusion

En este proyecto hemos cogido el archivo `kiva_loans.csv` y lo hemos dejado “arreglado” para poder trabajar con él sin caos. Primero vimos cómo eran los datos (cuántos había, qué columnas, si faltaban cosas, etc.) y quitamos algunas columnas que casi no aportaban nada o tenían demasiados huecos.

Después cambiamos los tipos de datos para que todo tuviera el formato correcto (fechas como fechas, textos como texto, nombres escritos igual, sin espacios raros…) y revisamos que los países y regiones coincidieran con los mapas que queríamos usar.

Al final nos quedamos con un dataset más pequeño pero mucho más limpio y ordenado, listo para poder hacer gráficos, mapas y futuros análisis sin tener que volver a pelearse con datos sucios.

---

## Opinión personal:

Aunque me está siendo muy complicado, ya que estoy viendo muchos conceptos nuevos e intento ponerme al día con todo y se me hace cuesta arriba, estoy aprendiendo mucho, aunque la sintaxis es muy extensa y abrumadora en algunos momentos.

"Cuando el camino se hace duro, solo los duros siguen caminando".






















2
