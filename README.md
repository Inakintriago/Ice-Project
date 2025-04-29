# 🎮 Tienda Online Ice: Análisis de Ventas de Videojuegos

## 📝 Contexto
Tienda Online Ice es una plataforma global de ventas de videojuegos que opera a través de diferentes regiones: América del Norte (NA), Europa (EU) y Japón (JP). El objetivo de este proyecto es analizar los datos históricos de ventas, calificaciones de usuarios y expertos, géneros de juegos y plataformas, para identificar patrones que predigan el éxito de los videojuegos y ayudar a planificar campañas publicitarias más efectivas para 2017. A partir de los datos de 2016, se busca optimizar las estrategias de marketing y seleccionar los títulos más prometedores.

## 🛠️ Herramientas Utilizadas
- **Python**: Análisis de datos y modelado estadístico.
- **Pandas**: Limpieza, transformación y análisis de datos.
- **Matplotlib** y **Seaborn**: Visualización de patrones y tendencias en las ventas y características de los juegos.
- **SciPy**: Pruebas estadísticas para validar las hipótesis de diferencias en calificaciones y ventas.
- **Jupyter Notebook**: Documentación interactiva y detallada del análisis.

## 📈 Análisis de Resultados
El proyecto se estructuró en varias fases:

1. **Preprocesamiento de Datos**:
   - Limpieza de columnas y tratamiento de valores nulos, como la sustitución de "TBD" en las clasificaciones de ESRB.
   - Conversión de datos de ventas en diferentes regiones a un formato unificado.
   - Cálculo de ventas totales por juego.

2. **Análisis Descriptivo**:
   - Análisis de las ventas de videojuegos a lo largo de los años, observando las plataformas más rentables.
   - Comparación de ventas por plataformas, identificando las que han desaparecido y las que emergen con éxito.

3. **Pruebas de Hipótesis**:
   - Evaluación de las diferencias de calificación promedio entre plataformas y géneros.
   - Confirmación de diferencias significativas en las calificaciones de plataformas como Xbox One y PC, así como entre géneros de Acción y Deportes.

4. **Análisis Regional**:
   - Identificación de las principales plataformas y géneros en distintas regiones, y cómo las calificaciones ESRB afectan las ventas.

## 📋 Conclusiones
- Los géneros más rentables, como **Acción** y **Deportes**, mostraron una mayor audiencia, con ventas consistentes a través de varias plataformas.
- Las plataformas más populares, como **PlayStation** y **Xbox**, tuvieron un rendimiento superior en Norteamérica, mientras que las ventas en Japón fueron dominadas por plataformas más locales.
- Las reseñas tanto de usuarios como de críticos influyen en las ventas, pero el impacto varía según la región y la plataforma, lo que destaca la importancia de adaptar las estrategias de marketing a las preferencias locales.
- La clasificación ESRB mostró que los juegos con clasificación **“E”** (Apto para Todos) y aquellos sin clasificación son los más vendidos en todas las regiones, especialmente en Norteamérica y Japón, lo que sugiere que los consumidores prefieren juegos accesibles a audiencias más amplias.

Este análisis proporciona una visión integral del mercado de videojuegos, ayudando a la tienda Online Ice a tomar decisiones basadas en datos para mejorar sus campañas publicitarias y maximizar su rentabilidad en 2017.
