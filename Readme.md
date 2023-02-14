
**Análisis de la esperanza de vida en relación a la renta per cápita, con pandas y matplotlib**

Generar un gráfico en el que se pueda ver la correlación entre la esperanza de vida frente a la renta per cápita de diferentes países. Para ello se ha de utilizar el dataset **Info\_pais.csv**


**1.**: Usar la librería **pandas** para leer el dataset y obtener una tabla con una cabecera de 15 filas en la que los datos aparezcan en orden descendente (de mayor a menor) según los valores de la columna “*Poblacion*”.

**2**: Usar la librería **matplotlib** para crear un gráfico. En el eje x hay que representar los datos de la columna “*Renta per capita*” y en el eje y los datos de la columna “*Esperanza de vida*”, y añadir un título y etiquetas a los ejes x e y.

**3**: Configurar el gráfico para que los puntos sean proporcionales tanto en tamaño como en color para cada país. Para ello hay que crear una nueva columna llamada “*df\_order['Poblacion\_normalizada']*” que normalice frente al máximo de población. Existen grandes diferencias en el número de habitantes entre países, para evitar la inundación del gráfico es recomendable que en vez de dividir la población de cada país entre el máximo de población, hacer la división del máximo entre 10000, para no tener un factor tan elevado.

**4**: Asignar al gráfico un tamaño de *14.5* x *10* pulgadas

**5**: Añadir colores a los países en función de los valores de la columna “*Poblacion\_normalizada*” 

**6**: Añadir la etiqueta del nombre del país dentro de cada burbuja, solo a los 10 primeros países ordenados de mayor a menor por la columna “*Poblacion*”.

**7**: Conclusiones 


