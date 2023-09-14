# Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-
Alura creo un evento en donde se enseña ciencia de datos llamado inmersion de datos. En cada sesión se dan desafios para resolver y aqui mostrare mis soluciones en el area.

## Primera Clase:
**Mis respuestas a la clase 1 son.**
Primero revise que los datos, después cree un nuevo dataframe con solo los datos de Barrio y area.

![Primera imagen de solucion 1, la antelacion contiene mas informacion](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/c950c5e334fdd2bd459fd18b47436caf31fae5a9/Assets/soluci%C3%B3n_1/CapturaV1.1.PNG)

En esta parte realice un nuevo Dataframe de agrupaciones con la funcion group by agrupando por barrios. También revise de que se realizara el proceso correcto con el uso de value counts, esto tambien para compararlo con el mismo dataframe pero con la funcion de media .mean.

![Segunda imagen de solucion 1, la antelacion contiene mas informacion](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/d03975b527203f4c9b4089e986dd6cc66c13f995/Assets/soluci%C3%B3n_1/CapturaV1.2.PNG)

En esta parte se creo una nueva series usando la funcion .mean sobre el anterior dataframe. La funcion .mean devuelve la media de valores, pero use el atributo numeric_only para que solo utilizara los valores numericos, pero realmente no es necesario. Devuelve una series con indices como barrios y con la unica columna area como la media de area. Cuando se realiza un group by cualquier tipo de funcion como mean, max, min se realizara por cada columna por la cual fue agrupada.

Por ultimo se uso plot.bar para crear la grafica de los barrios y sus promedios.
![Tercera imagen de solucion 1, la antelacion contiene mas informacion](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/ebb0c40cf619558bcb42c0f33e938a2f94142b9c/Assets/soluci%C3%B3n_1/CapturaV1.3.PNG)

En esta imagen de abajo se realizaron busquedas como baños min, baños mean, banos len(Para obtener el total de filas de baños), Habitaciones max(Para obtener el numero maximo de habitaciones). Tambien se podria haber usado sum sobre baños para obtener el total de baños. Hice promedio_area value counts para asegurarme que estan correctos los datos.

![Image text](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/2faf30b878405e33d6d02ecfd19a1a490f60ea26/Assets/soluci%C3%B3n_1/CapturaV1.4.PNG)
