# 🎨 Visualización de datos (Python)

Colección de scripts y desarrollos en **Python** enfocados en la representación gráfica, el diseño visual de perfiles individuales, el análisis espacial de eventos y la generación de informes comparativos para scouting técnico y análisis táctico.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python
* **Librerías de Visualización & Tácticas:** PyPizza (mplsoccer), Matplotlib, Seaborn
* **Análisis Espacial & Geometría:** SciPy (ConvexHull / Spatial)
* **Procesamiento de Datos:** Pandas, NumPy
* **Fuentes de Datos:** Wyscout, FBref, StatsBomb

---

## 📊 Tipologías de Visualización Incluidas

### 1. Gráficos de Radar & Perfiles
* **Radares Comparativos:** Análisis bidireccional de futbolistas en formato clásico y estilo *Pizza Chart* con desglose por bloques de métricas (Defensivas, Pases, Ataque).
* **Normalización en Percentiles:** Representación del rendimiento del jugador en relación con su grupo de pares y competición.

### 2. Grids de Percentiles & Barras
* **Perfiles Visuales por Jugador:** Paneles estructurados (*Grids*) de métricas avanzadas por 90 minutos en formato de barras.
* **Evaluación de Rendimiento:** Desglose visual directo para informes rápidos de scouting.

### 3. Análisis Espacial & Mapas de Eventos
* **Mapas de Calor (Heatmaps):** Densidad espacial de acciones y ocupación de zonas sobre el terreno de juego.
* **Mapas de Pases y Tiros (Shot/Pass Maps):** Representación geométrica de trayectorias, origen/destino de pases y mapa de remates.
* **Zonificación por Tercios y Carriles:** Desglose de intervención y volumen de juego segmentado por carriles (bandas/interior) y tercios de campo (iniciación, creación, finalización).
* **Convex Hull (Amplitud y Profundidad):** Envolvente convexa geométrica para medir la superficie de influencia, despliegue espacial, amplitud y profundidad de un jugador o bloque colectivo.

### 4. Análisis Estadístico y Distribuciones
* **Diagramas de Dispersión (Scatter Plots):** Matriz bidimensional para la identificación de *outliers* y correlación entre métricas clave (volumen vs. eficacia).
* **Histogramas & Distribuciones:** Análisis de la dispersión de datos, sesgos de rendimiento y métricas de frecuencia en la competición.

---

## 📂 Contenido del Repositorio (`.ipynb`)

* `WYSCOUT_RadarPyPizza_Comparativa.ipynb`: Generación de gráficos de radar estilo PyPizza.
* `WYSCOUT_RadarClasicoComparativo.ipynb`: Radar clásico comparativo para cara a cara entre jugadores.
* `WYSCOUT_Percentiles_Grids_jugador.ipynb`: Paneles y grids de percentiles individuales.
* `SPATIAL_Heatmaps_Pass_Shot_Maps.ipynb`: Mapas de calor, mapas de pases, tiros y zonificación por tercios/carriles.
* `SPATIAL_Convex_Hull_Analysis.ipynb`: Cálculo visual de amplitud, profundidad y envolventes geométricas (*Convex Hull*).
* `STATISTICS_Scatter_Histograms.ipynb`: Matrices de dispersión para scouting y análisis de distribución de métricas.

---

🔒 *Nota: Los datos brutos y archivos de datos (.csv/.json) no se incluyen en este repositorio público para proteger la propiedad intelectual de las fuentes de datos comerciales.*
