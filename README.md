# Rendimiento de Mbappé y resultados del Real Madrid

## Descripción

Este proyecto realiza un análisis exploratorio sobre la relación entre el rendimiento individual de Mbappé y los resultados del Real Madrid durante la temporada 2025/2026.

El objetivo es estudiar si existen diferencias relevantes en el rendimiento colectivo del equipo según la participación del jugador, su capacidad goleadora y otras variables del partido.

## Objetivo del proyecto

El trabajo busca analizar, desde un enfoque estadístico, si el rendimiento de Mbappé guarda relación con la probabilidad de victoria del Real Madrid.

Para ello se tienen en cuenta variables como:

- Participación de Mbappé en el partido.
- Goles marcados por Mbappé.
- Resultado del partido.
- Goles a favor y en contra del equipo.
- Condición de local o visitante.
- Dificultad estimada del rival.

## Técnicas utilizadas

En el proyecto se aplican distintas técnicas estadísticas:

- Estadística descriptiva.
- Comparación de proporciones.
- Contrastes de hipótesis.
- Pruebas de Poisson para comparar tasas de goles.
- Test exacto de Fisher.
- Prueba Chi-cuadrado.
- Regresión logística binaria.
- Estimación de probabilidades de victoria.

## Herramientas utilizadas

- R.
- Excel.
- PowerPoint.
- Análisis estadístico aplicado.

## Principales resultados

El análisis muestra que las diferencias entre los goles a favor y en contra del Real Madrid con y sin Mbappé no resultan estadísticamente significativas en los contrastes de Poisson.

Sin embargo, al analizar únicamente los partidos en los que Mbappé juega al menos 30 minutos, se observa una diferencia relevante entre los partidos en los que marca y aquellos en los que no consigue anotar.

El test exacto de Fisher muestra una asociación estadísticamente significativa entre marcar o no marcar y el resultado del partido, aunque este resultado debe interpretarse con prudencia.

También se estima un modelo de regresión logística para analizar la probabilidad de victoria del Real Madrid considerando distintas variables del contexto del partido.

## Interpretación

Los resultados sugieren que el impacto colectivo de Mbappé podría estar muy condicionado por su aportación goleadora. No obstante, el análisis no permite establecer una relación causal directa.

La diferencia observada puede estar influida por otros factores no incluidos en el modelo, como:

- Calidad real del rival.
- Estado físico de la plantilla.
- Lesiones.
- Rotaciones.
- Contexto competitivo.
- Minutos exactos jugados.
- Rendimiento defensivo del equipo.
- Variables tácticas.

## Limitaciones

Este proyecto debe entenderse como un análisis exploratorio. La muestra utilizada es reducida y corresponde a una única temporada, por lo que los resultados no deben interpretarse como conclusiones definitivas.

Además, algunas variables relevantes del rendimiento futbolístico no se incorporan al modelo, como expected goals, ocasiones generadas, calidad de los tiros, posesión, presión defensiva o alineaciones completas.

## Posibles mejoras futuras

- Ampliar el análisis a varias temporadas.
- Incluir métricas avanzadas como xG, xA o tiros esperados.
- Incorporar datos de posesión, ocasiones y rendimiento defensivo.
- Comparar el rendimiento con otros jugadores ofensivos.
- Analizar modelos alternativos de clasificación o predicción.
- Mejorar la visualización de los resultados mediante dashboards.

## Archivos del repositorio

- `MBAPPE ANALISIS ESTADISTICO PDF.pdf`: presentación del análisis.
- `README.md`: descripción general del proyecto.
- `mbappe_datos_excel`: Base de datos en Excel utilizada para el proyecto, recogida por mi.
- `Codigo en R`: código escrito en R utilizado para el trabajo.
- `graficos/`: carpeta destinada a las tres principales visualizaciones del proyecto.
- `LICENSE`: licencia (MIT).

## Autor

**Jorge Boullosa Conde**

Proyecto de análisis estadístico aplicado al rendimiento deportivo.
