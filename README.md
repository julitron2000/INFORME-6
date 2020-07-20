# Informe N°6 TEOREMA DE LA MÁXIMA TRANSFERENCIA DE ENERGÍA

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA

Al momento de analizar circuitos, frecuentemente, se presentan casos en los que es indispensable aplicar un análisis por método de nodos , por lo que conocer y saber utilizar este método debe ser un requisito necesario e indispensable para realizar cualquier análisis de un circuito tanto en la práctica como en la teoría.

## 2. OBJETIVOS

### GENERAL

Comprobar experimentalmente el Teorema de la Máxima Transferencia de Potencia.

### ESPECÍFICOS

-Determinar la potencia transferida a cada resistencia propuesta en la guía de laboratorio experimentalmente.

-Determinar la potencia transferida a cada resistencia propuesta en la guía de laboratorio teoricamente.

-Determinar la potencia máxima que se pueda obtener y la resistencia con la que se obtiene.

-Determinar el error experimental.

## 3. MARCO TEÓRICO 
![image](https://user-images.githubusercontent.com/64505672/84841818-10b96080-b009-11ea-8c5f-862ff4ee8891.png)

Un nodo es el punto en donde se conectan diferentes elementos en un circuito, en el cual se puede medir el voltaje que cae en este punto, basándonos en la ley de corrientes Kirchhoff y la ley de Ohm.
### Método de Nodos


El teorema de la maxima transferencia es utilizado para determinar la mayor potencia que se puede suminstrar a una carga, por ello es importante conocer previamente el equivalente de Thevenin de un circuito. Si tenemos el circuito equivalente de Thevenin podemos decir que la potencia maxima se calcula utilizando la siguiente fórmula

![image](https://user-images.githubusercontent.com/64505672/87900613-8191d500-ca1a-11ea-9635-93fb1671e1ae.png)

Donde RL es la resistencia que varia su carga, RTh es la resistencia de Thevenin y VTH es el voltaje de Thevenin.

El circuito equivalente de Thevenin es el siguiente.

![image](https://user-images.githubusercontent.com/64505672/87901055-9d49ab00-ca1b-11ea-81b1-25c03cac7c4f.png)


Con respecto a este tema Sadiku (2004) afirma "La máxima potencia se transfiere a la carga cuando la resistencia de la carga es igual a la resistencia de Thevenin vista desde la carga (RL = RTh)."

Graficamente se puede observar que efectivamente la potencia maxima se consigue cuando Rh=RL

![image](https://user-images.githubusercontent.com/64505672/87901146-deda5600-ca1b-11ea-8f4c-22a40d6adc8f.png)

## 4. DIAGRAMAS
Del circuito base:

![Circuito](https://user-images.githubusercontent.com/66037763/84849909-0785bf00-b01c-11ea-854a-a0eaf524f16f.png)


Se observan las conecciones y se identifican los nodos a los que se debe hacer el respectivo análisis:


![CircuitosNodos](https://user-images.githubusercontent.com/66037763/84850917-8f6cc880-b01e-11ea-9627-a9fe10551303.png)


Los nodos encerrados en rojo son donde tomará lugar el análisis de nodos. El voltaje que entra a cada uno de estos, está representado por las flechas rojas, de igual manera el voltaje saliente que tienen dirección vertical y con sentido hacia tierra. 

## 5. LISTA DE COMPONENTES
A. 2 Fuentes de Voltaje de C.D. (12 y 8 V. respectivamente)


![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)


B. Multímetros Digitales (los que se encuentre necesarios)

![chrome_1E7H2m0GOE](https://user-images.githubusercontent.com/66037763/84236069-a6f6ff00-aabc-11ea-90f8-49d128847e17.png)


C. Resistor de 1.8 kΩ


![chrome_H59RekD0Sn](https://user-images.githubusercontent.com/66037763/84236097-b4ac8480-aabc-11ea-88e9-0930cd8a6151.png)


D. Resistor de 470 Ω


![chrome_nYj42XTcAA](https://user-images.githubusercontent.com/66037763/84236121-bc6c2900-aabc-11ea-9052-20d1e126c649.png)


E. Resistor de 1.5 kΩ


![chrome_jPVmQCB5dn](https://user-images.githubusercontent.com/66037763/84236149-cbeb7200-aabc-11ea-96d9-4b01e8f8ef81.png)


F. Resistor de 3.9 kΩ


![chrome_RgP3H68Ui2](https://user-images.githubusercontent.com/66037763/84236162-d60d7080-aabc-11ea-864d-536485900f86.png)


G. Resistor de 2.2 kΩ

![chrome_u6waqAZiNN](https://user-images.githubusercontent.com/66037763/84236192-e0c80580-aabc-11ea-9767-487481f78259.png)


H. Protoboard

![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)


## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION


|   RL       | Corriente medida (mA) | Voltaje medido (V) | Potencia calculada experimentalmente (W) | Potencia calculada teóricamente | 
|   ---      |       ---             |      ---           |                    ---                   |              ---                | 
|     220    |                       |                    |                                          |                                 |  
|     470    |                       |                    |                                          |                                 |
|     680    |                       |                    |                                          |                                 |
|     820    |                       |                    |                                          |                                 | 
|     1000   |                       |                    |                                          |                                 |
|     1500   |                       |                    |                                          |                                 | 
|     1800   |                       |                    |                                          |                                 | 
|     2200   |                       |                    |                                          |                                 |
|     3900   |                       |                    |                                          |                                 |
|     4700   |                       |                    |                                          |                                 |



Finalmente, el circuito puesto a prueba: 

![Tinker](https://user-images.githubusercontent.com/66037763/84852749-33587300-b023-11ea-8052-10f689380e30.jpg)


## 7. CRONOGRAMA
![0067](https://user-images.githubusercontent.com/66037557/87900011-a2592b00-ca18-11ea-9ada-e819dd2c8857.png)


## 8.CONCLUSIONES
-Se comprobó que la potencia maxima es la mas cercana a la resitencia de 1200 ohms, en este caso la de 1000 ohm que nos entrega una potencia de  11.62 mW

-se concluye que la razón por la que el error es muy pequeño se debe a que el simulador posee una incertidumbre casi nula, a diferencia de la vida real en la que la que las tolerancias de nuestras resistencias pueden variar.

## 9. RECOMENDACIONES
- Si usamos un simulador podemos utilizar un potenciometro ya que podemos variar la resistencia de forma exacta

- Utilizar las cifras significativas para minimizar el error experimental.

## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
