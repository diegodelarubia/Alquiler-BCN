# Análisis del precio del alquiler en Barcelona

## Descripción del proyecto
Este proyecto analiza la evolución del precio del alquiler de viviendas en Barcelona y su relación con la renta media de los hogares. El objetivo es evaluar cómo ha cambiado el acceso a la vivienda en los últimos años y si el crecimiento del alquiler ha ido acompañado por un aumento proporcional de la renta.

El análisis se centra principalmente en el nivel urbano (barrios y distritos), ya que es el nivel más adecuado para estudiar el esfuerzo económico real de los hogares.

---

## Fuentes de datos
Los datos utilizados provienen del portal **Barcelona Data (Open Data BCN)**:

- Precio medio del alquiler de vivienda en Barcelona, desagregado por territorio y año.
- Renta disponible media de los hogares, desagregada por barrio y distrito (2015–2021).

Los datasets han sido limpiados y transformados para su análisis, unificando formatos y corrigiendo inconsistencias en la clasificación territorial.

---

## Preparación y limpieza de los datos
Durante la fase de preparación de datos se realizaron las siguientes tareas:

- Transformación de los datos de alquiler a formato largo (una fila por territorio y año).
- Corrección de la columna *Tipus de territori*, trasladando correctamente las categorías de “Barri” y “Districte” que aparecían entre paréntesis en el nombre del territorio.
- Separación entre niveles urbanos (barrios, distritos y municipio) y niveles agregados (ámbito funcional territorial y comunidad autónoma).
- Unión de los datos de alquiler con los datos de renta mediante territorio y año.

---

## 1.Evolución temporal del precio del alquiler
Se analiza la evolución del precio medio del alquiler en Barcelona a lo largo del tiempo. Este análisis permite identificar una tendencia general al alza en el precio del alquiler, con incrementos especialmente relevantes en los últimos años.

---

## 2.Precio medio del alquiler por tipo de territorio
Se comparan los precios medios del alquiler según el tipo de territorio:

- Barrios  
- Distritos  
- Municipio de Barcelona  

De forma separada, se analizan los niveles agregados (comunidad autónoma y ámbito funcional territorial) únicamente como referencia contextual. Los resultados muestran diferencias significativas de precio según el nivel territorial, siendo los barrios el nivel con mayor variabilidad.

---

## 3.Precio medio del alquiler por territorio
Se realiza un análisis comparativo entre los territorios con precios de alquiler más altos y más bajos.  
Este análisis permite identificar barrios con alquileres muy elevados frente a otros tradicionalmente más asequibles, evidenciando la desigualdad territorial existente dentro de la ciudad.

---

## 4.Evolución de la renta per cápita
Se analiza la evolución temporal de la renta disponible media per cápita en Barcelona a partir de los datos desagregados por barrio y distrito.  
Este análisis permite observar la tendencia general de los ingresos de los hogares a lo largo del tiempo y sirve como base para comparar posteriormente con la evolución del precio del alquiler.

---

## 5.Relación entre renta y precio del alquiler
Se estudia la relación entre la renta media y el precio medio del alquiler a nivel de barrio, con el objetivo de identificar si los territorios con mayor renta presentan también precios de alquiler más elevados.

El análisis muestra una relación positiva entre ambas variables, aunque existen barrios donde el precio del alquiler es elevado en relación con la renta media, lo que sugiere la influencia de factores adicionales como la localización o la presión de la demanda.

---

## 6.Evolución comparada de la renta y del alquiler
Se compara la evolución temporal de la renta media y del precio medio del alquiler en Barcelona utilizando un índice base 100, lo que permite analizar el crecimiento relativo de ambas variables de forma comparable.

Los resultados muestran que el precio del alquiler ha crecido a un ritmo superior al de la renta media, lo que indica una pérdida de poder adquisitivo de los hogares en relación al acceso a la vivienda.

---

## 7.Esfuerzo económico del alquiler
Se calcula el esfuerzo económico como el porcentaje de la renta anual destinado al pago del alquiler, convirtiendo el precio medio mensual del alquiler a valor anual para garantizar la coherencia temporal de las magnitudes analizadas.

El análisis evidencia un aumento progresivo del esfuerzo económico de los hogares en Barcelona, lo que refleja una creciente presión del mercado del alquiler sobre la renta disponible.

---

## 8. Barrios extremos

Se identificaron los barrios con los precios de alquiler más altos y más bajos y se comparó su renta media:

- Pedralbes: barrio más caro, renta media más alta.  
- Can Peguera: barrio más barato, renta media más baja.  

Se calculó el **esfuerzo económico**, que indica qué porcentaje de la renta anual se destina al alquiler.  
Los resultados muestran que, aunque Pedralbes es caro y con renta alta, el esfuerzo económico sigue siendo muy elevado. Can Peguera, aunque barato, también puede tener un esfuerzo considerable debido a la renta más baja.

Este análisis permite ejemplificar la desigualdad en el acceso a la vivienda y cómo los precios del alquiler y la renta interactúan en los casos extremos.

---

### Conclusión general

En este proyecto se analizó la evolución del precio del alquiler en Barcelona y su relación con la renta media de los barrios.  

 
El proyecto demuestra que los precios del alquiler están fuertemente correlacionados con la renta de los barrios, pero también existen diferencias significativas que generan desigualdad en el acceso a la vivienda. El esfuerzo económico varía entre barrios y refleja cómo algunos hogares destinan una parte muy elevada de su renta a pagar el alquiler, especialmente en los barrios más caros.




