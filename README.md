# precios_gas

Proyecto de Análisis de Datos basado en precios de gas natural en Argentina en el período enero 2019-junio 2019.

Introducción:

El objetivo principal del proyecto es analizar los datos de precios de gas en Argentina para ver las variaciones de los mismos ya sea por Cuenca o por Segmento, ademas de ver los precios maximos y minimos, y posibles datos 'peculiares'.

Tecnologias utilizadas:

-Python, lenguaje utilizado en el proyecto.
-pandas, bibliotecas para el analisis de los datos
-Power BI, herramienta para hacer graficos de visualizacion de los datos
-Excel, donde se encuentran los datos utilizados para el proyecto

Conjunto de Datos:
El dataset utilizado es 'Precios de Gas Natural - Res 1/2018', este contiene los precios de gas en Argentina en un periodo de 6 meses enero-junio de 2019, precios de diferentes cuencas ubicadas en el pais.

fuente: https://datos.gob.ar/dataset/energia-precios-gas-natural/archivo/energia_956778d7-e3c6-4136-8a74-67dfbb4eb0ef

Dashboard de Power BI:

En el archivo .png se ven los graficos de visualizacion de los datos analizados. Estos graficos son por ejemplo de Precio por Cuenca, Precio promedio por Mes, Precio por Segmento o Evolucion del precio de cada Cuenca por Mes.

Conclusiones:

Gráfico Superior Izquierdo: Precio (USD/MMBTU) por Cuenca

Neuquina lidera los precios: La Cuenca Neuquina presenta el precio promedio más alto significativamente, superando los 400 USD/MMBTU. Esto podría indicar una mayor demanda, costos de producción más elevados o factores geopolíticos específicos de esta cuenca.
Austral Santa Cruz y Golfo San Jorge con precios intermedios: Estas dos cuencas muestran precios similares, alrededor de los 350 USD/MMBTU, sugiriendo condiciones de mercado o costos de producción comparables entre ellas.
Noroeste y Austral Tierra del Fuego con precios más bajos: Estas cuencas tienen los precios promedio más bajos, alrededor de los 300 USD/MMBTU. Esto podría deberse a una menor demanda local, menores costos de extracción o una infraestructura de transporte diferente.

Gráfico Superior Derecho: Precio promedio (USD/MMBTU) por Mes

Variabilidad mensual: El precio promedio muestra fluctuaciones significativas a lo largo de los meses analizados (Enero a Junio).
Punto bajo en Marzo: Se observa un descenso notable en el precio promedio durante el mes de Marzo. Esto podría estar relacionado con factores estacionales, cambios en la demanda o eventos específicos del mercado.
Pico en Junio: El precio promedio alcanza su punto máximo en Junio, superando los 240 USD/MMBTU. Esto podría ser impulsado por una mayor demanda estacional (por ejemplo, para calefacción en el hemisferio sur) o factores de oferta y demanda.

Gráfico Inferior Izquierdo: Precio (USD/MMBTU) por Segmento

Distribuidora e Industria pagan los precios más altos: Estos segmentos registran los precios más elevados, superando los 350 USD/MMBTU. Esto podría reflejar los costos de transporte y distribución que se añaden al precio del gas para estos usuarios finales.
Exportación con precios competitivos: El segmento de Exportación muestra un precio intermedio, lo que sugiere que los precios deben ser competitivos a nivel internacional.
Otros segmentos con precios variables: Los segmentos PPP, Usina, GNC y Otros presentan precios más bajos y variables entre sí, lo que podría reflejar diferentes acuerdos de suministro o volúmenes de consumo.

Gráfico Inferior Derecho: Evolución del precio (USD/MMBTU) de cada cuenca por mes

Tendencias diferenciadas por cuenca: Cada cuenca muestra una evolución de precios distinta a lo largo de los meses.
Neuquina con alta volatilidad: La Cuenca Neuquina, además de tener los precios más altos, también parece experimentar una mayor volatilidad en sus precios mensuales.
Comportamiento similar en algunas cuencas: Algunas cuencas como Austral Santa Cruz y Golfo de San Jorge muestran una evolución de precios más similar entre sí.
Impacto del pico de Junio: Se observa que la mayoría de las cuencas experimentan un aumento en el precio durante el mes de Junio, aunque con magnitudes diferentes.

Conclusiones Generales:

Disparidad de precios por cuenca: Existe una diferencia significativa en los precios del gas natural entre las distintas cuencas productoras. La Cuenca Neuquina se destaca por sus precios más altos.
Influencia de la estacionalidad: El precio promedio del gas natural muestra una clara influencia estacional, con un pico en Junio y un valle en Marzo.
Impacto del segmento de consumo: Los precios varían considerablemente según el segmento de consumo, siendo los usuarios finales (Distribuidora e Industria) quienes pagan los precios más altos.
Dinámicas de precios complejas: La evolución de los precios a lo largo del tiempo difiere entre las cuencas, lo que sugiere que factores específicos de cada región influyen en su mercado.
