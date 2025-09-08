# Sacrificio_de_Ganado_en_Rastros_Municipales_Anuales-

Se realizó un estudio a la Encuesta de Sacrificio de Ganado en Rastros Municipales Anuales (ESGRM) 2024, que consta de 4484 observaciones; sacado de la base de datos abiertos publicados por el [INEGI](https://www.inegi.org.mx/datosabiertos/) (actualmente ya no se encuentra disponible).

Se busca predecir con modelos lineales y no lineales la variable de Precio Medio, esta nos habla del monto promedio expresado en pesos, medido por toneladas de carne. 

## Variables de la base de datos
PRODUCTO: Nombre del producto estadístico (ESGRM). Categórica.

COBERTURA: Entidad federativa. Categórica.

ANIO: Año de referencia. Numérica.

ID_ENTIDAD: Clave numérica de la entidad federativa (0–32). Numérica.

ESPECIE_GANADERA: Tipo de ganado (bovino, caprino, porcino, ovino). Categórica.

CABEZAS_SACRIFICADAS: Número de animales sacrificados. Numérica.

PRODUCCION_CARNE: Volumen total de carne producida. Numérica.

VALOR_PRODUCCION: Valor monetario de la producción (miles de pesos). Numérica.

PRECIO_MEDIO: Precio promedio de la carne (pesos/tonelada). Numérica.

ESTATUS_DATO_*: Variables de control de calidad del dato (D = disponible, ND = no disponible, NA = no aplicable, NS = no significativo, C = confidencial). Categórica.

ESTATUS: Estatus global de las cifras conforme a INEGI. Categórica.

## Conclusión
El estudio permitió explorar cómo distintos factores productivos y económicos del sacrificio de ganado impactan en el precio medio. Si bien los modelos lineales aportaron información sobre las variables más influyentes, su capacidad predictiva fue limitada. En contraste, los enfoques no lineales como KNN lograron capturar mejor la complejidad de los datos y, con el uso de intervalos de confianza, se consiguió una estimación más confiable y acompañada de márgenes de incertidumbre.

El proyecto tiene los siguientes documentos: 

* [Reporte en formato ipynb](PP1645700.ipynb)
* [Reporte en formato html](PP1645700.html)
* [Base de datos](Sacrificio.csv)
* [Diccionario](diccionario_datos_esgrm_anual_1989_2024.csv)
