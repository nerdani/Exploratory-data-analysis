# Análisis Exploratorio de Datos: Mercado Global de Videojuegos

## Introducción
Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) aplicado a un dataset de la industria de videojuegos. El objetivo principal es transformar datos crudos en información estratégica para el equipo de marketing, identificando patrones de éxito, géneros dominantes y tendencias de ventas globales para apoyar la toma de decisiones directivas.

## Tecnologías Asociadas
Para el desarrollo de este análisis técnico, se utilizaron las siguientes herramientas del ecosistema de Data Science:
* Lenguaje: Python
* Librerías de Análisis: Pandas y NumPy.
* Librerías de Visualización: Seaborn (para relaciones complejas) y Matplotlib (para gráficos personalizados).
* Entorno de desarrollo: Jupyter Notebook.

## Procedimientos (Metodología)
El análisis se estructuró en las siguientes fases técnicas:
* Carga y Exploración Inicial: Lectura del archivo videojuegos.csv y revisión de la estructura de datos.
* Análisis Visual con Seaborn: Implementación de pairplot para observar relaciones entre variables numéricas y heatmap de correlación para identificar vínculos entre ventas y puntuaciones.
* Personalización con Matplotlib: Procesamiento de datos para calcular el promedio de ventas globales por género y creación de visualizaciones pulidas con estándares estéticos profesionales.

## Resultados y Visualizaciones

### Rendimiento de ventas según el género del videojuego

<p align="center">
  <img src="https://github.com/nerdani/Exploratory-data-analysis/blob/main/assets/heatmap.png" alt="Imagen" width="500">
</p>
 
Observaciones.

Lo más llamativo aquí es que las Ventas_NA (Norteamérica) son las que más "empujan" a las ventas globales, mientras que la Critica_Puntaje aparece con colores muy fríos o cercanos a cero. Esto nos confirma visualmente lo que sospechábamos: en este negocio, que a un crítico le guste el juego no garantiza para nada que la gente lo vaya a comprar en masa, ya que la relación es prácticamente nula.

### Promedio de Ventas Globales por Género de Videojuego

<p align="center">
  <img src="https://github.com/nerdani/Exploratory-data-analysis/blob/main/assets/barpromgame.png" alt="Imagen" width="500">
</p>
 
Observaciones 

Se concluye que el género Platform lidera la rentabilidad con un promedio de 0.93 millones de unidades vendidas, seguido por los géneros Shooter y Role-Playing, los cuales demuestran un sólido desempeño comercial por encima de la media de la industria. En contraste, géneros como Adventure y Strategy muestran el alcance más limitado, con promedios inferiores a 0.25 millones. Este hallazgo, presentado mediante una visualización personalizada con etiquetas de datos para facilitar la toma de decisiones ejecutivas, permite identificar que la eficiencia económica reside en los juegos de plataformas y disparos, sugiriendo una focalización estratégica en estos nichos frente a otros más saturados como el de acción

### Conclusiones
* Identificación de Tendencias: El análisis permite visualizar claramente qué géneros lideran el mercado en términos de ventas promedio, facilitando la focalización de campañas de marketing.
* Insights de Correlación: A través del mapa de calor, se identificaron las variables que más impactan en el éxito comercial de un título.
*Impacto de la Visualización: La personalización de gráficos permitió convertir datos complejos en una historia visual clara para niveles ejecutivos.

### Contacto
Si deseas conocer más sobre mi metodología de trabajo o discutir este análisis:
<a title="LinkedIn" href="https://www.linkedin.com/in/danielherreramz/" target="_blank" onclick="window.open('https://www.linkedin.com/in/danielherreramz/', '_blank');"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

