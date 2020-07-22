# Informe N°6 TEOREMA DE LA MÁXIMA TRANSFERENCIA DE ENERGÍA

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA

En el diseño de circuitos, hay ocasiones en que se busca obtener la mayor potencia que se pueda suministrar a una carga especifica, por ello es necesario conocer el teorema de la máxima transferencia de potencia que, esto a su vez requiere un previo conocimiento del teorema de Thevenin.

## 2. OBJETIVOS

### GENERAL

Comprobar experimentalmente el Teorema de la Máxima Transferencia de Potencia.

### ESPECÍFICOS

- Determinar la potencia transferida a cada resistencia propuesta en la guía de laboratorio experimentalmente.

- Determinar la potencia transferida a cada resistencia propuesta en la guía de laboratorio teoricamente.

- Determinar la potencia máxima que se pueda obtener y la resistencia con la que se obtiene.

- Determinar el error experimental.

## 3. MARCO TEÓRICO 

El teorema de la máxima transferencia es utilizado para determinar la mayor potencia que se puede suminstrar a una carga, por ello es importante conocer previamente el equivalente de Thevenin de un circuito. Si tenemos el circuito equivalente de Thevenin podemos decir que la potencia máxima se calcula utilizando la siguiente fórmula

![image](https://user-images.githubusercontent.com/64505672/87900613-8191d500-ca1a-11ea-9635-93fb1671e1ae.png)

Donde RL es la resistencia que varia su carga, RTh es la resistencia de Thevenin y VTH es el voltaje de Thevenin.

El circuito equivalente de Thevenin es el siguiente.

![image](https://user-images.githubusercontent.com/64505672/87901055-9d49ab00-ca1b-11ea-81b1-25c03cac7c4f.png)


Con respecto a este tema Sadiku (2004) afirma "La máxima potencia se transfiere a la carga cuando la resistencia de la carga es igual a la resistencia de Thevenin vista desde la carga (RL = RTh)."

Graficamente se puede observar que efectivamente la potencia máxima se consigue cuando Rh=RL

![image](https://user-images.githubusercontent.com/64505672/87901146-deda5600-ca1b-11ea-8f4c-22a40d6adc8f.png)

## 4. DIAGRAMAS


## 5. LISTA DE COMPONENTES
A. Fuente de Voltaje de C.D. (15 v)


![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)


B. Multímetros Digitales 

![chrome_1E7H2m0GOE](https://user-images.githubusercontent.com/66037763/84236069-a6f6ff00-aabc-11ea-90f8-49d128847e17.png)


C. Resistor de 1.2 kΩ


![chrome_H59RekD0Sn](https://user-images.githubusercontent.com/66037763/84236097-b4ac8480-aabc-11ea-88e9-0930cd8a6151.png)


D. Potenciómetro


![chrome_xygSoFbiG6](https://user-images.githubusercontent.com/66037763/87902277-cc155080-ca1e-11ea-9a3c-274ab920ae10.png)


E. Protoboard

![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)


## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION


|   RL       | Corriente medida (mA) | Voltaje medido (V) | Potencia calculada experimentalmente (mW) | Potencia calculada teóricamente (mW)| 
|   ---      |       ---             |      ---           |                    ---                   |              ---                        | 
|     220    |        10.6               |     2.33       |                24.70                        |       24.5487                        |  
|     470    |        8.98               |     4.22       |                37.90                        |       37.9182                        |
|     680    |        7.98               |     5.43       |                43.33                        |       43.2888                        |
|     820    |        7.42               |     6.09       |                45.19                        |       45.2161                        | 
|     1000   |        6.82               |     6.82       |                46.51                        |       46.4876                        |
|     1500   |        5.55               |     8.33       |                46.23                        |       46.2962                        | 
|     1800   |        5.00               |     9.00       |                45.00                        |       45.0000                        | 
|     2200   |        4.41               |     9.71       |                42.82                        |       42.8200                        |
|     3900   |        2.94               |     11.5       |                33.81                        |       33.7370                        |
|     4700   |        2.54               |     11.9       |                30.23                        |       30.3792                        |


- ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? 
Sí, ya que experimentalmente encontramos que la máxima transferencia de potencia se da cuando la resistencia es de 1000 ohm, y este a su vez es el más cercano a la resistencia de Thévenin = 1200 ohm, lo cual se comprueba haciendo el respectivo cálculo que es el valor con la máxima transferencia de potencia teórica.
-¿Cuál fue la potencia máxima en RL? 
11. 62 mW
 
 - ¿Para qué valor de RL se obtiene la MTP?
 1000 Ω

## 7. CRONOGRAMA
![0077](https://user-images.githubusercontent.com/66037557/88135847-9bafec80-cbad-11ea-8ab6-2c567083c35e.png)



## 8.CONCLUSIONES
- Se  comprobó el teorema de potencia máxima transferida que nos dice que la máxima potencia se transfiere a la carga cuando la resistencia de la carga es igual a la resistencia de Thevenin vista desde la carga. En este caso la resistencia que presento la potencia mas cercana a 1200 ohms es la resistencia  1000 ohm, a la que se le transfiere una potencia de  46.4876 mW.

- Se comprobó que el  experimento se cumple con un error experimental de la potencia máxima transferida es 0.048%, la razon por la que este valor es tan bajo se debe a que los simuladores poseen tolerancias mas ajustadas, a las que se presentan en la vida real. 

- Se comprobó que las resistencia que se alejan en valor a la resistencia de thevenin poseen las potencias mas bajas por ejemplos la resitencia mas pequeña de 220ohm se le transfiere una potencia de 24.5487 mW, y a la resistencia mas alta de 4700 ohm se le transfiriere una potencia de 30.3792 mW.

## 9. RECOMENDACIONES
- Si usamos un simulador podemos utilizar un potenciometro ya que podemos variar la resistencia de forma exacta.

- Considerar mas cifras significativas para hallar un error experimental mas preciso.

- Para hallar la potencia experimental en cada resistencia primero debemos hallar el voltaje y la resistencia en el circuito, o la intensidad y luego utilizar la formula de potencia es igual a intensidad al cuadrado por la resistencia.

## 10. BIBLIOGRAFÍA

- M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

- Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
