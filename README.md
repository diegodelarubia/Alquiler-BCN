# 📊 Análisis del Precio del Alquiler en Barcelona

## 📌 Descripción del Proyecto

Este proyecto analiza la evolución del **precio del alquiler de viviendas en Barcelona** y su relación con la **renta media de los hogares**.

El objetivo es estudiar cómo ha cambiado el acceso a la vivienda en los últimos años y evaluar si el crecimiento del alquiler ha estado acompañado por un incremento proporcional de la renta disponible.

El análisis se centra principalmente en el **nivel urbano (barrios y distritos)**, ya que permite entender con mayor precisión el esfuerzo económico real que deben afrontar los hogares para acceder a una vivienda en la ciudad.

---

## 📂 Fuentes de Datos

Los datos utilizados proceden del portal **Open Data BCN (Barcelona Data)** e incluyen:

- Precio medio del alquiler de vivienda en Barcelona, desagregado por territorio y año
- Renta disponible media de los hogares, desagregada por barrio y distrito (2015–2021)

Los datasets fueron **limpiados, transformados y unificados** para facilitar su análisis, corrigiendo inconsistencias y homogeneizando la clasificación territorial.

---

## 🧹 Preparación y Limpieza de los Datos

Durante la fase de preparación se realizaron varias tareas de procesamiento:

- Transformación de los datos de alquiler a **formato largo**, con una fila por territorio y año
- Corrección de la columna **Tipus de territori**, identificando correctamente las categorías *Barri* y *Districte*
- Separación entre **niveles urbanos** (barrios, distritos y municipio) y **niveles agregados** (ámbito funcional territorial y comunidad autónoma)
- Integración de los datasets de **alquiler y renta** mediante las variables de territorio y año

---

# 📈 Análisis de Datos

## 1️⃣ Evolución temporal del precio del alquiler

Se analiza la evolución del precio medio del alquiler en Barcelona a lo largo del tiempo.

Los resultados muestran una **tendencia creciente en el precio del alquiler**, con incrementos especialmente significativos en los últimos años.

---

## 2️⃣ Precio medio del alquiler por tipo de territorio

Se comparan los precios medios del alquiler según el nivel territorial:

- Barrios
- Distritos
- Municipio de Barcelona

De forma adicional, se incluyen los niveles agregados (**comunidad autónoma y ámbito funcional territorial**) como referencia contextual.

El análisis muestra **diferencias relevantes entre niveles territoriales**, siendo el nivel de barrios el que presenta mayor variabilidad en los precios.

---

## 3️⃣ Precio medio del alquiler por territorio

Se realiza una comparación entre los territorios con **precios de alquiler más elevados y más bajos**.

Este análisis permite identificar barrios con alquileres significativamente altos frente a otros tradicionalmente más asequibles, evidenciando la **desigualdad territorial dentro de la ciudad**.

---

## 4️⃣ Evolución de la renta per cápita

Se estudia la evolución temporal de la **renta disponible media per cápita** utilizando datos desagregados por barrio y distrito.

Este análisis permite observar la evolución de los ingresos de los hogares y sirve como base para compararla posteriormente con la evolución del precio del alquiler.

---

## 5️⃣ Relación entre renta y precio del alquiler

Se analiza la relación entre la **renta media y el precio medio del alquiler** a nivel de barrio.

Los resultados muestran una **correlación positiva** entre ambas variables:

- Los barrios con mayor renta tienden a presentar precios de alquiler más elevados.

Sin embargo, también se observan casos donde el precio del alquiler es alto en relación con la renta media, lo que sugiere la influencia de **factores adicionales** como:

- Localización
- Oferta de vivienda
- Presión de la demanda

---

## 6️⃣ Evolución comparada de renta y alquiler

Para comparar el crecimiento relativo de ambas variables se utiliza un **índice base 100**.

Este enfoque permite observar cómo han evolucionado la renta media y el precio del alquiler en términos comparables.

Los resultados indican que **el precio del alquiler ha crecido más rápido que la renta media**, lo que sugiere una pérdida de poder adquisitivo de los hogares en relación con el acceso a la vivienda.

---

## 7️⃣ Esfuerzo económico del alquiler

Se calcula el **esfuerzo económico del alquiler**, definido como el porcentaje de la renta anual destinado al pago del alquiler.

Para ello, el precio mensual del alquiler se convierte a valor anual, permitiendo compararlo con la renta disponible.

El análisis muestra **un aumento progresivo del esfuerzo económico de los hogares**, reflejando una creciente presión del mercado del alquiler en Barcelona.

---

## 8️⃣ Análisis de barrios extremos

Se identificaron los barrios con los precios de alquiler más altos y más bajos y se comparó su renta media.

- **Pedralbes** → barrio con el alquiler más caro y una de las rentas medias más altas  
- **Can Peguera** → barrio con el alquiler más bajo y una renta media considerablemente menor  

Se calculó el **esfuerzo económico del alquiler**, que representa el porcentaje de la renta anual destinado al pago de la vivienda.

Resultados:

- En **Pedralbes**, aunque la renta es alta, el esfuerzo económico sigue siendo elevado debido al precio del alquiler.
- En **Can Peguera**, el alquiler es más bajo, pero el esfuerzo económico puede seguir siendo significativo debido a la menor renta disponible.

Este análisis ilustra cómo la **desigualdad territorial influye en el acceso a la vivienda**.

---

## 🧾 Conclusión

Este proyecto analiza la evolución del **precio del alquiler en Barcelona** y su relación con la **renta media de los barrios**.

Los resultados muestran que:

- Existe una relación clara entre renta y precios del alquiler
- Existen diferencias significativas entre territorios
- El precio del alquiler ha crecido **más rápido que la renta de los hogares**

En conjunto, el análisis sugiere un **aumento del esfuerzo económico necesario para acceder a una vivienda**, evidenciando desigualdades en el acceso a la vivienda dentro de la ciudad.

---

## 🛠 Herramientas Utilizadas

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
