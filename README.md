# Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-
Alura creo un evento en donde se enseña ciencia de datos llamado inmersion de datos. En cada sesión se dan desafios para resolver y aqui mostrare mis soluciones de cada uno de los desafios.

## Primera Clase:

**Mis respuestas de la clase 1 son:**


   Desafios:
   
    Promedio de área de todos los inmuebles en los barrios en el dataset. El top 10.

    Consultar otros datos estadísticos, conteo, mediana, valores mínimo y máximo.


Primero revise los datos, para consecuentemente realizar una agrupacion por barrios. Después se ordenan de mayor a menor y se obtienen solo los primeros 10. Por ultimo realice una grafica de barras.
Anteriormente habia realizado otra grafica con todos los barrios pero la respuesta era muy poco entendible.

![Grafico de barras](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV1.1.PNG)

Ahora lo que hice para terminar con los desafios de esta clase fue realizar 4 funciones para obtener 4 datos que se usan para realizar medidas estadisticas.

![Funciones estadisticas](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV1.2.PNG)


## Segunda Clase:

**Mis respuestas de la clase 2 son:**


   Desafios:
    
    Estudiar mejor el histograma de valores, seleccionar 3 tipos de inmuebles (Refinar el gráfico: Títulos, aumentar el tamaño de labels, colores, conclusión de la información)

    Precio del m2 por barrio y hacer el gráfico más adecuado para esta nueva variable.


Primeramente cree una nueva variable con precio millon. Esta nueva variables son los rangos de precio, los hice concorde la media, los cuartiles y la frecuencia de un grafico boxplot. Use lambda para crear estos rangos de valores.

![Creando columna con rangos de valores](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV2.1.PNG)

Ahora lo que hice fue crear un booleano de cada uno de los inmuebles y use estas condicionales para obtener un dataframe de solo estos tres inmuebles.

![obteniendo dataframe con solo tres inmuebles](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV2.2.PNG)

Con el uso de la nueva variable creo la grafica y en la grafica se ve la incedencia de los inmuebles por el rango de valores. Se edito el fondo, el tamaño de las labels y se uso una paleta de colores. Tambien se modificaron las labels de los dos ejes. 

![grafica de frecuencia por tres tipos de inmuebles](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV2.3.PNG)

Por ultimo realice mis conclusiones de la grafica. Con esto el primer desafio esta terminado. 

![Conclusiones de la grafica](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV2.4.PNG)

En este segundo desafio cree la variable m2 (Nota: Esta variable no la dividi por millon, despues fue hecha una nueva con esta caracteristica) y con esto obtuve la media agrupada por barrio de m2. Por lo demás consigue los 10 valores mas altos y los plasme en una grafica de barras. Viendo que este no era el mejor grafico para esta variable, hice el grafico boxplot. Para ser honesto no comprendia que el grafico boxplot daba tantos datos funcionales hasta la instruccion de los maestros.

![Primera grafica de m2 barrio](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV2.5.PNG)

Con esta nueva grafica utilice valor m2 millon y respete los demas datos de la anterior. Use la paleta de Colores Mako y agregue color a los fondos para resaltar la informacion y mejorar el visual. Las labels estan inclinadas de una forma un poco distinta a como me enseñaron en esta aula. Hubiera querido modificar los colores de la media y los cuartiles pero no logre un codigo funcional, por eso priorice la paleta de colores. Con esto termina los desafios del aula 2.

![Grafica box plot](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/b68ccd95d50810918f097a80b95697cb433c4131/Assets/soluci%C3%B3n_1/CapturaV2.6.PNG)



## Tercera Clase:

**Mis respuestas de la clase 3 son:**

   Desafios:
    
    Dar un vistazo a la base de datos del DANE, entender estas variables conceptualmente para entender mejor el contexto de esta base.
    Organizar tu notebook para que tu proyecto quede mejor presentado.

Resumen:

![Resumen de los dos desafios](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/c32dcd084574f1252d18f68dc84499680609ff5a/Assets/soluci%C3%B3n_1/CapturaV3.1.PNG)
