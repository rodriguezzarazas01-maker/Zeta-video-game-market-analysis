# Ζ Proyecto Zeta | Análisis del Mercado Global de Videojuegos

## Descripción

Ice es una tienda online dedicada a la comercialización de videojuegos en diferentes mercados internacionales. La empresa dispone de información histórica sobre ventas, plataformas, géneros, reseñas de usuarios y críticos profesionales, así como clasificaciones ESRB.

El objetivo de este proyecto fue identificar los factores asociados al éxito comercial de un videojuego y detectar patrones que puedan utilizarse para planificar campañas publicitarias más efectivas. Para ello, se analizaron datos históricos hasta 2016 con el fin de generar recomendaciones orientadas a la toma de decisiones para 2017.

## Objetivos

- Evaluar la calidad y consistencia de los datos.
- Analizar la evolución histórica de las ventas de videojuegos.
- Identificar las plataformas con mejor desempeño comercial.
- Estudiar el ciclo de vida de las plataformas de videojuegos.
- Analizar la relación entre reseñas y ventas.
- Identificar los géneros más rentables.
- Construir perfiles de consumo para diferentes regiones.
- Evaluar el impacto de las clasificaciones ESRB sobre las ventas.
- Validar hipótesis mediante pruebas estadísticas.
- Generar recomendaciones de negocio para futuras campañas de marketing.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Análisis Exploratorio de Datos (EDA)
- Estadística descriptiva
- Pruebas de hipótesis

## Fuente de datos

El proyecto utiliza información histórica de videojuegos comercializados en distintas plataformas y mercados.

Archivo utilizado:

- `games.csv`

Variables principales:

- `name`
- `platform`
- `year_of_release`
- `genre`
- `na_sales`
- `eu_sales`
- `jp_sales`
- `other_sales`
- `critic_score`
- `user_score`
- `rating`

## Metodología

### 1. Preparación de los datos

- Revisión general del conjunto de datos.
- Estandarización de nombres de columnas.
- Conversión de tipos de datos.
- Tratamiento de valores ausentes.
- Análisis de valores duplicados.
- Creación de la variable `total_sales`.

### 2. Análisis exploratorio

Se estudiaron:

- Ventas globales por año.
- Evolución del mercado de videojuegos.
- Plataformas con mayores ventas.
- Ciclo de vida de las plataformas.
- Tendencias recientes del mercado.

### 3. Análisis de plataformas

- Identificación de plataformas líderes.
- Evolución anual de ventas.
- Comparación de medias y medianas.
- Diagramas de caja para ventas por plataforma.
- Identificación de plataformas con potencial para 2017.

### 4. Influencia de las reseñas

Se evaluó la relación entre:

- Calificaciones de críticos y ventas.
- Calificaciones de usuarios y ventas.

Mediante:

- Diagramas de dispersión.
- Correlaciones estadísticas.

### 5. Análisis de géneros

- Distribución de videojuegos por género.
- Géneros más rentables.
- Comparación de ventas entre categorías.

### 6. Perfil de usuario por región

Para cada mercado:

- Norteamérica (NA)
- Europa (EU)
- Japón (JP)

se analizaron:

- Plataformas más populares.
- Géneros predominantes.
- Impacto de las clasificaciones ESRB.

### 7. Pruebas estadísticas

Se evaluaron las siguientes hipótesis:

1. Las calificaciones promedio de usuarios para Xbox One y PC son iguales.
2. Las calificaciones promedio de usuarios para los géneros Acción y Deportes son diferentes.

## Principales hallazgos

### Evolución del mercado

- La industria mostró un crecimiento sostenido desde mediados de los años noventa.
- El pico de ventas se alcanzó entre 2008 y 2009.
- Después de 2010 se observa una disminución gradual del mercado.
- Los datos recientes son más representativos para proyectar tendencias futuras.

### Plataformas líderes

Las plataformas con mayores ventas durante el período relevante fueron:

1. PS4
2. PS3
3. Xbox 360
4. Nintendo 3DS
5. Xbox One

### Ciclo de vida de plataformas

- PS3 y Xbox 360 mostraron una clara fase de declive.
- PS4 y Xbox One representaron la nueva generación con mayor potencial.
- Nintendo 3DS mantuvo una posición sólida, aunque con crecimiento limitado.
- Las plataformas antiguas como PSP y DS presentaron niveles de ventas significativamente menores.

### Reseñas y ventas

#### Críticos

- Se observó una relación positiva entre las reseñas de críticos y las ventas.
- Los títulos mejor valorados tendieron a registrar mejores resultados comerciales.

#### Usuarios

- La correlación entre las reseñas de usuarios y las ventas fue prácticamente nula.

Correlación obtenida:

```text
-0.032
```

Esto indica que las valoraciones de los usuarios no permiten predecir de forma confiable el éxito comercial de un videojuego.

### Comparación de plataformas

- PS4 y Xbox One presentaron algunas de las distribuciones de ventas más favorables.
- El éxito comercial depende tanto de la calidad del videojuego como de la plataforma en la que se comercializa.
- Las diferencias entre plataformas resultaron significativas.

## Análisis regional

### Norteamérica

- Predominio de PlayStation y Xbox.
- Preferencia por géneros de Acción y Deportes.

### Europa

- Comportamiento similar al mercado norteamericano.
- Alta participación de PlayStation.

### Japón

- Preferencia por plataformas portátiles.
- Mayor relevancia de géneros asociados al mercado japonés.
- Diferencias importantes respecto a Occidente.

## Visualizaciones desarrolladas

- Ventas globales por año.
- Evolución de ventas por plataforma.
- Comparación de plataformas líderes.
- Diagramas de caja por plataforma.
- Distribución de ventas por videojuego.
- Relación entre críticas y ventas.
- Relación entre reseñas de usuarios y ventas.
- Comparaciones regionales.
- Distribución de géneros.

## Archivos principales

- `zeta_video_game_market_analysis.ipynb`
- `games.csv`

## Conclusión

El análisis permitió identificar patrones relevantes en la industria global de videojuegos y detectar los factores más asociados al éxito comercial de un título.

Los resultados muestran que el mercado experimentó una importante transición generacional durante el período estudiado. Mientras plataformas como PS3 y Xbox 360 entraban en una fase de declive, PS4 y Xbox One se consolidaban como las opciones más atractivas para la nueva generación de jugadores.

Las reseñas de los críticos mostraron una relación positiva con las ventas, mientras que las valoraciones de los usuarios tuvieron una influencia muy limitada sobre el desempeño comercial. Asimismo, se encontraron diferencias significativas entre regiones, tanto en preferencias de plataformas como de géneros.

Desde la perspectiva de negocio, las evidencias sugieren que las mejores oportunidades para una campaña publicitaria orientada a 2017 se encuentran en:

- PlayStation 4 (PS4).
- Xbox One.
- Nintendo 3DS.
- PC.

En conjunto, los hallazgos permiten identificar plataformas y segmentos con mayor potencial comercial, proporcionando información valiosa para optimizar decisiones de marketing y selección de productos.
