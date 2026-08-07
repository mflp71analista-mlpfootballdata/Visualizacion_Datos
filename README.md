# 🎨 Football Data Visualization Gallery (Python)

Este repositorio recopila una colección completa de módulos en **Python** enfocados en la representación gráfica, el diseño visual y la analítica táctica avanzada aplicada al fútbol.

El objetivo de este proyecto es transformar métricas complejas e historia de eventos en visualizaciones e informes de alto impacto visual orientados a cuerpos técnicos, analistas y direcciones deportivas.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python
* **Librerías de Visualización Táctica:** Mplsoccer, Matplotlib, Seaborn
* **Procesamiento de Datos:** Pandas, NumPy
* **Fuentes de Datos Utilizadas:** StatsBomb, FBref, Understat

---

## 📊 Módulos y Tipologías de Visualización

### 1. Maquetación y Terreno de Juego
* **Fundamentos de Layout:** Diseño de retículas (*Grid System*), tipografías personalizadas e integración de escudos/imágenes.
* **Representación de Campos:** Generación de pitchs en 2D adaptados a distintas fuentes de datos.

### 2. Análisis de Rendimiento & Perfiles
* **Gráficos de Dispersión (Scatter Plots):** Matriz comparativa para la detección de perfiles destacados e identidades estadísticas (FBref / StatsBomb).
* **Gráficos de Radar (Radar Charts):** Visualización multi-métrica comparativa ajustada por perfil de posición.
* **Distribuciones y Tendencias:** Histogramas, gráficos de barras y mapas de línea/área de evolución temporal (Understat).

### 3. Analítica Táctica Avanzada sobre el Terreno
* **Mapas de Tiros (Shot Maps):** Representación de ocasiones y calidad del remate ($xG$).
* **Mapas de Pases & Redes de Circulación (Pass Maps):** Distribución de envíos sobre el campo.
* **Mapas de Calor (HeatMaps):** Áreas de influencia y ocupación del espacio.
* **Zonificación Espacial:** Análisis táctico por tercios, carriles centrales/laterales y polígonos de ocupación (*Convex Hull*).

---

## 📂 Archivos y Notebooks (`.ipynb`)

* `1.Understanding_The_Grid.ipynb` & `2.Plot_Football_Pitches.ipynb`: Maquetación y dibujado de campos.
* `3.Titles_And_Typography.ipynb` & `4.Plot_Images.ipynb`: Estilo visual, logos y tipografía.
* `5.Histogram_Barchart_Statsbomb.ipynb` & `6.Line_Area_Chart_Understat.ipynb`: Gráficos de tendencias y distribuciones.
* `7.Scatter_Plot_FBREF.ipynb` & `7.ScatterPlot_Statsbomb.ipynb`: Scatter plots multi-proveedor.
* `8.Radar_Chart_FBREF.ipynb` & `8.Radar_Chart_Statsbomb.ipynb`: Gráficos de radar comparativos.
* `9.ShotMap_Understat.ipynb`: Mapas de tiro y $xG$.
* `10.Pass_Map_Statsbomb.ipynb`: Mapas de pases.
* `11.Tercios_Carriles_Statsbomb.ipynb`: Segmentación táctica del campo.
* `12.HeatMap_Statsbomb.ipynb`: Mapas de calor de actividad.
* `13.Convex_Hull_Statsbomb.ipynb`: Polígonos de ocupación de espacio táctico.

---

🔒 *Nota: Los archivos de datos brutos no están incluidos para respetar la propiedad intelectual de los proveedores.*
