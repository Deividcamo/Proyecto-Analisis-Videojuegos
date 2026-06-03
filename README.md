# Análisis del Mercado de Videojuegos y Comportamiento de Usuarios

## 🎯 Objetivo del Proyecto
Este proyecto combina el Análisis Exploratorio de Datos (EDA) y la Estadística Inferencial en Python para identificar patrones de consumo globales en la industria de los videojuegos. El objetivo principal es descubrir qué factores (plataformas, géneros o regiones) impulsan el éxito comercial de un título para optimizar las campañas de marketing y la gestión de inventario.

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** Python 3
* **Librerías de Datos:** Pandas, NumPy
* **Estadística:** SciPy (Stats)
* **Entorno:** Jupyter Notebook / JupyterLab

## 📊 Principales Hallazgos (EDA)
* **Discrepancia Regional:** Mientras que los mercados de Norteamérica (NA) y Europa (EU) muestran comportamientos de compra casi idénticos (priorizando consolas de sobremesa potentes como PS4 y géneros de Acción/Disparos), el mercado de Japón (JP) opera bajo una dinámica cultural opuesta, coronando a las consolas portátiles (Nintendo 3DS) y al género de Rol (RPG).

## 🔬 Pruebas de Hipótesis Estadísticas

### 1. Calificaciones de Usuarios: Xbox One vs. PC
* **H0:** El promedio de las calificaciones de los usuarios para Xbox One y PC es igual.
* **Resultado:** No se rechazó la hipótesis nula ($p\text{-value} \approx 0.147$). 
* **Conclusión:** Estadísticamente, los usuarios evalúan de igual manera los juegos en ambas plataformas; la diferencia observada se debe puramente al azar.

### 2. Calificaciones de Usuarios: Género Acción vs. Deportes
* **H0:** El promedio de las calificaciones de los usuarios para Acción y Deportes es igual.
* **Resultado:** Se rechazó rotundamente la hipótesis nula ($p\text{-value} = 1.44 \times 10^{-20}$).
* **Conclusión:** Existe una diferencia estadística muy significativa. Las comunidades evalúan estos géneros bajo criterios y expectativas de satisfacción completamente distintos.

## 🚀 Conclusión de Negocio
Las estrategias comerciales y de distribución no deben ser genéricas. Para maximizar el retorno de inversión (ROI), el catálogo de juegos de deportes requiere campañas de fidelización y retención segmentadas, mientras que los esfuerzos de marketing transatlánticos deben pivotar drásticamente al intentar posicionar productos en el mercado japonés en comparación con el occidental.
