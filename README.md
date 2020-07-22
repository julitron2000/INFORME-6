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
|   ---      |       ---             |      ---           |                    ---                   |              ---                | 
|     220    |        10.6               |     2.33               |                                          |       6.137                          |  
|     470    |        8.98               |     4.22               |                                          |       9.470                          |
|     680    |        7.98               |     5.43               |                                          |       10.82                          |
|     820    |        7.42               |     6.09               |                                          |       11.30                          | 
|     1000   |        6.82               |     6.82               |                                          |       11.62                          |
|     1500   |        5.55               |     8.33               |                                          |       11.56                          | 
|     1800   |        5.00               |     9.00               |                                          |       11.25                          | 
|     2200   |        4.41               |     9.71               |                                          |       10.70                          |
|     3900   |        2.94               |     11.5               |                                          |       8.435                          |
|     4700   |        2.54               |     11.9               |                                          |       7.595                          |


- ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? 
Sí, ya que experimentalmente encontramos que la máxima transferencia de potencia se da cuando la resistencia es de 1000 ohm, y este a su vez es el más cercano a la resistencia de Thévenin = 1200 ohm, lo cual se comprueba haciendo el respectivo cálculo que es el valor con la máxima transferencia de potencia teórica.
-¿Cuál fue la potencia máxima en RL? 
11. 62 mW
 
 - ¿Para qué valor de RL se obtiene la MTP?
 1000 Ω

## 7. CRONOGRAMA
![0067](https://user-images.githubusercontent.com/66037557/87900011-a2592b00-ca18-11ea-9ada-e819dd2c8857.png)


## 8.CONCLUSIONES
- Se comprobó que la potencia maxima es la mas cercana a la resitencia de 1200 ohms, en este caso la de 1000 ohm que nos entrega una potencia de  11.62 mW

- Se concluye que la razón por la que el error es muy pequeño se debe a que el simulador posee una incertidumbre casi nula, a diferencia de la vida real en la que la que las tolerancias de nuestras resistencias pueden variar.

## 9. RECOMENDACIONES
- Si usamos un simulador podemos utilizar un potenciometro ya que podemos variar la resistencia de forma exacta.

- Utilizar las cifras significativas para minimizar el error experimental.

## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
