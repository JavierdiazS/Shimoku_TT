# Shimoku_TT

Algunas consideraciones sobre los datos y el problema, y una breve explicación del proceso de pensamiento presentado como una simple aplicación de datos creada con nuestro SDK.

Usando Python +3.9
    
     pip install shimoku-api-python

Se obtuvo las siguientes graficas:

![bars](https://github.com/JavierdiazS/Shimoku_TT/assets/75210642/397c3277-853c-4805-86df-6de9b7ba9a13)
![line](https://github.com/JavierdiazS/Shimoku_TT/assets/75210642/95136c38-6753-463d-aa57-9bc9873e64d6)


 * La gran mayoria de los clientes potenciales en el DataFrame se encuentran en espera de ser una venta exitosa o no. Los clientes que compraron el servicio son más que los que no lo hicieron, por casi 900 clientes pero preocupa la cantidad tan alta de los que se prevé sean descartados.

![pie](https://github.com/JavierdiazS/Shimoku_TT/assets/75210642/6d84aff3-92e8-482b-b2bb-1eec33565f74)

* Los eventos corporativos son los casos de uso predominantes por un poco más de la mitad de los clientes.
* A pesar de que muchos de los clientes no han definido su caso de uso, una pequeña parte lo desean usar para planificaciones de bodas o conciertos y festivales.

(La siguiente grafica no se hizo con el SDK pero se requiere para dar las consideraciones finales)

![box](https://github.com/JavierdiazS/Shimoku_TT/assets/75210642/0b05bf2b-308e-4319-82af-365b7f57146c)

Para interpretar el grafico de caja, se hará por sus partes principales:

* La altura de las Cajas:

  Hay una mayor variabilidad en la conversión de los clientes para los seminarios de educacaión y conciertos y festivales.

* Mediana o Linea central dentro de la Caja:

  Hay un 40% de probabilidad de conversión para la mayoria de los clientes, exceptuando que tienen caso de uso para conciertos y festivales por el 50%.

* Bigotes o barras laterales y los valores atípicos:

  En la mayoria de los datos hay una distribución amplia y variada de los datos, pero sin observaciones extremadamente inusuales.

  Pero en el caso de uso del servicio que es Planeación de bodas hay una distribución amplia con valores extremadamente inusuales.

**NOTA: La explicación completa de la construcción del DataFrame enriquecido se encuentra en el Jupyter Notebook.**
