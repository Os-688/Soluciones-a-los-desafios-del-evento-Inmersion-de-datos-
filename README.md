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

## Cuarta Clase:

**Mis respuestas de la clase 4 son:**

   Desafios:
    
    Probar con otros modelos de ML;
    Trabajar más con los datos y crear nuevas variables;
    Probar predicciones para casos reales;

   *Solucion: probar con otros modelos de ML:*
   
Aqui se encuentran el resumen y conclusiones a los que llegue despues de usar un modelo svc, compararlo con el modelo de regresion y probar/entender el tipo de datos con los que trabajan.
   
   ![Resumen del codigo y comparacion de datos, modelos](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/daaccbcd2c88503d3d57de9f5c5cd199a4bef59e/Assets/soluci%C3%B3n_1/CapturaV4.1.PNG)

Inicie probando el modelo svc pero utilice los mismos datos que los profesores, lo cual fue un error. La razon de ello la explico en las conclusiones, pero seria porque el tipo flotante no es el dato por el cual fueron diseñados los modelos de clasificacion. 
   
 ![Prueba del modelo SVC con datos del tipo flotante o continuous](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/daaccbcd2c88503d3d57de9f5c5cd199a4bef59e/Assets/soluci%C3%B3n_1/CapturaV4.2.PNG)

En esta parte se hizo un modelo SVC entrenandolo y probandolo con los datos de precio por millon, para poder hacer esto se usaron funciones de la biblioteca scikit-learn para transformar estos datos continuous (de regresion) a multiclass y poder usarlos en este modelo de clasificacion, se puede observar en la variable code.
Por lo demas se aprovecho la funcion train_test_split para dividir los datos de entrenamiento y de prueba, despues se escalaron. Por ultimo se usaron los datos para entrenar y probar el modelo con una funcion para mostrar la precision. En esta ultima parte se uso accuracy para lograrlo.

  ![Prueba del modelo SVC con datos del tipo flotante o continuous](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/daaccbcd2c88503d3d57de9f5c5cd199a4bef59e/Assets/soluci%C3%B3n_1/CapturaV4.3.PNG)

Use un dummyClassifier para crear una baseline para comparar el accuracy con estas predicciones, esto se repetira en cada prueba del modelo SVC. 

  ![Base line con dummy ](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/3f809c147388dfde9055b360c1c0ced8ff068121/Assets/soluci%C3%B3n_1/CapturaV4.4.PNG)

  Este es el inicio de la siguiente prueba con datos Multiclass, pero con un dato basado en Precio millon (Este dato es division precio y puede ser agrupado) y sus conclusiones. Que resultaron ser en resumen que los datos multiclass se reserven para estos modelos clasificatorios u otros y  los datos continuous como los tipo double para modelos de regresion, porque tienen un mayor indice de precision. Esto tiene mucho sentido por que tiene relacion con el objetivo por el que fueron diseñados.

 ![ conclusiones con datos Multiclass](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/3f809c147388dfde9055b360c1c0ced8ff068121/Assets/soluci%C3%B3n_1/CapturaV4.5.PNG)

Es el mismo modelo que se presento arriba pero con la distinción de que no se necesitan transformar los datos a multiclass. Se utiliza la variable division precio, porque es una variable hecha a partir de precio millones. Este modelo sirve de comparacion con el anterior, para probar la eficacia del modelo con estos dos tipos de datos. En las conclusiones esta el desenlace al respecto.

  ![Modelo SVC con datos division precio](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/3f809c147388dfde9055b360c1c0ced8ff068121/Assets/soluci%C3%B3n_1/CapturaV4.6.PNG)

La baseline de este modelo:
  
   ![Dummy classifier de division precio](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/3f809c147388dfde9055b360c1c0ced8ff068121/Assets/soluci%C3%B3n_1/CapturaV4.7.PNG)

Realizo un mapa de calor para poder distinguir las variables que usare para los datos del nuevo modelo. Este nuevo modelo lo hago con la intencion de poder decidir los datos que tendra ya que no pude hacerlo con division precio. La razón de ello es que el mapa de calor no la detecta. Los datos estan elegidos para habitaciones y tienen la mayor correlacion.

   ![Mapa de calor](https://github.com/Os-688/Soluciones-a-los-desafios-del-evento-Inmersion-de-datos-/blob/3f809c147388dfde9055b360c1c0ced8ff068121/Assets/soluci%C3%B3n_1/CapturaV4.8.PNG)
