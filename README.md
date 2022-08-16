# Laboratorio-Extra

## Corrección del Exámen 
### 1.	OBJETIVOS

**Principales**

 - Experimentar La superposición
 - Experimentar el teorema de Thévenin
 - Construir un circuito.

**Específicos**

- Diferenciar las partes de una herramienta eléctrica
- Apreciar la diferencia de voltaje y corriente cuando se apaga una fuente
- Consultar la nomenclatura de colores y valores parar las resistencias.
- Apreciar la diferencia de voltaje y corriente cuando se cambia la resistencia RL.
- Diferenciar las partes de un vatímetro.


### 2.	MARCO TEÓRICO
##Principios de Superposición 
Cualquier circuito resistivo se puede modelar mediante la combinación lineal de variables en un sistema de ecuaciones. Como se mostró en linealidad y proporcionalidad.
Las ecuaciones que describen a un circuito se obtienes a partir de fórmulas como las de las leyes de Kirchhoff, en cada caso se tendrán ecuaciones como las que se relacionan a continuación. 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/1.png)
 
 ###### _FIGURA 1_
Las primeras ecuaciones se refieren a la sumatoria de corriente, donde los coeficientes de cada variable son valores de resistencias o conductancias, y el valor (C) denota la suma de corrientes conocida en un nodo, generalmente debida a fuentes independientes de corriente. La segunda muestra la suma de tensiones alrededor de un lazo cerrado; en este caso, los coeficientes de las variables son nuevamente resistencias o conductancias, mientras que (C) es la suma de las tensiones conocidas, o de las producidas por fuentes independientes de tensión.

Al tomar la primera ecuación y utilizamos una fuente de corriente de valor Ca, esta producirá tensiones acordes con la magnitud de la corriente.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/2.png)

 ###### _FIGURA 2_
Ahora si se toma un valor diferente para la fuente de corriente Cd, este producirá tensiones acordes con la magnitud de la corriente.

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/3.png)
 
 ###### _FIGURA 3_
Si se toman valores apropiados para Ca y Cd, de manera que la suma de ellos se constituya en el valor de C original, se tendrá que:

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/4.png)

 ###### _FIGURA 4_
 
Es de esta forma que se la tensión particular producida sobre una resistencia o una conductancia, por ejemplo (K1), se puede ver como la suma de dos tensiones particulares, cada uno de ellos producido por una fuente de tensión diferente.
 
![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/5.png)
 
 ###### _FIGURA 5_
Este es el principio de superposición y se puede extender a un número cualquiera   de combinaciones. La consecuencia más importante de la linealidad es la superposición. Es esencial desde el punto de vista conceptual y como método de cálculo. El principio de superposición como: La respuesta (una corriente o tensión) en un circuito lineal que tiene más de una fuente independiente se obtiene sumando las respuestas ocasionadas por las fuentes independientes separadas que actúan solas. Esto es, la respuesta a la acción   simultánea de varios estímulos es igual a la suma algebraica de las respuestas de cada estímulo individual. 

![](https://github.com/SanchezMaiAndresSebastian/Laboratorio-3/blob/main/Foto/6.png)

 ###### _FIGURA 6_ 
 
 ##TEOREMA DE THEVENIN

![](https://github.com/SanchezMaiAndresSebastian/Tarea-4-/blob/main/Fotos/3.png)

###### _FIGURA 7_
![](https://github.com/SanchezMaiAndresSebastian/Tarea-4-/blob/main/Fotos/4.png)


###### _FIGURA 8_


 
### 3.	EXPLICACIÓN DEL PROCEDIMIENTO
- Diagramas eléctricos
![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/5.png)

###### _FIGURA 9_

![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/6.png)

###### _FIGURA 10_
![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/7.png)

###### _FIGURA 11_


####	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- | 
| 1 |Fuente de voltaje de C.D. | 
| 1 |Multímetro |  
|1 |Resistor de 2 Ω|
|2 |Resistor de 3 Ω|
|1 |Resistor de 4 Ω|
|1 |Resistor de 5 Ω|
|1 |Resistor de 6 Ω|
|1 |Resistor de 12 Ω|
|1 |Resistor de 9.1 kΩ|
|1 |Resistor de 7.5 kΩ|
|1 |Resistor de 6.8 kΩ|
|1 |Resistor de 3.3 kΩ|
|1 |Potencioemtro de 1.0 kΩ|
|1 |Protoboard|
 
> (Herramientas utilizadas en simulación) 
> Simulador thinkercad


#### SIMULACIÓN

Se tiene que preparar los componentes antes de la construcción del circuito

![](https://github.com/SanchezMaiAndresSebastian/Lab4-2022/blob/main/Fotos/3.png)

###### _FIGURA 12_

Se hace los circuitos y se mide las resistencias con el multímetro 


 
### 4.	RESPUESTAS A INTERROGANTES
#### 4.1 Empleando el circuito de Thevenin determine la potencia suinisrada de la resistencia R3

![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/1.png)
###### _FIGURA 13_

#### 4.2 Calcular la intensidad I que pasará la resistencia de 5 Ω utilizando thevenin
![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/2.png)
###### _FIGURA 14_

#### 4.3 Encontrar la corriente y el voltaje a través de la resistencia de 12 mediante el teorema de superposición

##### Encontrar corriente 
![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/3.png)
###### _FIGURA 15_
##### Encontrar el voltaje
![](https://github.com/SanchezMaiAndresSebastian/Lab-extra/blob/main/Fotos/4.png)
###### _FIGURA 16_

### 5. VIDEOS

https://youtu.be/Y-3tUByS7xI

### 6.	CONCLUSIONES

 - Al momento de construir el circuito se debe tener en cuenta que tiene que conectarse correctamente los cables en el positivo y negativo de todos los instrumentos eléctricos los cuales si no se hacen correctamente pueden sufrir una disminución de la vida útil.
 - El vatímetro se usa con cuatro pines el cual Dos de ellas son fijas y se conectan en serie a un circuito eléctrico, se denominan bobinas amperimétricas. Además, tiene otra móvil, también llamada «bobina voltimétrica, la cual se instala en paralelo con el circuito.
 - Cuando en un resistor se encuentra aplicado con el multímetro la medición de su corriente cambia el voltaje de los demás resistores que se tienen midiendo con las demás herramientas.
 - Siempre tener la guía del sentido para poder resolver las mallas y cambia totalmente si se apaga una fuente o no, debido a que eso genera una corriente que pasa por los componentes.
 

### 7.	BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. México: Pearson Educacion. Serway,

R. (2001). Física II. México: Pearson Educacion.

A. (2021, 5 agosto). El. La fisica y quimica. Recuperado 14 de julio de 2022, de https://lafisicayquimica.com/teorema-de-transferencia-de-potencia-maxima/

