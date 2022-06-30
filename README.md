# Informe_Tarea4
Resolución de ejercicios Capitulo 7 y 8 del Libro de Floyd (Octava edición)

### Circuitos en Serie-Paralelo (Capitulo 7)
### Teoremas de Circuitos y Conversiones (Capitulo 8)

### 1. OBJETIVOS


#### Objetivos Generales

Combinar el circuito en Serie y en Paralelo dentro del mismo circuito y aplicar los métodos de análisis aprendidos para circuitos en serie y circuitos en paralelo, además incluir el divisor de voltaje con carga resistiva, la red en escalera, y el puente Wheatstone.


#### Objetivos Específicos


- Analizar circuitos en serie-paralelo

- Identificar las relaciones serie-paralelo

- Analizar divisores de voltaje con carga 

- Determinar el efecto de carga de un voltímetro en un circuito 

### 2. MARCO TEORICO

## Circuitos en Serie-Paralelo (Capitulo 7)

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20231006.png)

#### REDES EN ESCALERA

Una red resistiva en escalera es un tipo especial de circuito en serie-paralelo. La red en escalera R/2R se utiliza comúnmente para reducir voltajes a ciertos valores ponderados para conversión de digital a analógica.
Se simplificar escalón por escalón, comenzando en el lado más alejado de la fuente. De este modo, se puede determinar la corriente en cualquier rama o el voltaje en cualquier nodo, como en el ejemplo:

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20231705.png)

#### PUENTE DE WHEATSTONE

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20233454.png)

#### PUENTE WHEATSTONE EQUILIBRADO

El puente Wheatstone se encuentra en la condición de puente equilibrado cuando el voltaje de salida (VSALIDA) entre las terminales A y B es igual a cero.

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20233841.png)

Cuando el puente está equilibrado, los voltajes entre los extremos de R1 y R2 son iguales (V1=V2) y los voltajes entre los extremos de R3 y R4 son iguales (V3=V4)

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20233925.png)

Sustituyendo V por IR de acuerdo con la ley de Ohm se obtiene

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20234628.png)

Como I1=I3 e I2 = I4, todos los términos de corriente se cancelan, y permanecen las relaciones de resistor

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20234641.png)

Se obtiene la siguiente fórmula que permite encontrar el valor del resistor R1 en función de los demás valores de resistor cuando el puente está equilibrado. También se puede encontrar el valor de cualquier otro resistor del mismo modo

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20234656.png)

#### PUENTE WHEATSTONE DESEQUILIBRADO

![image](https://user-images.githubusercontent.com/105259381/176609759-308addb3-9151-4a8c-9e82-23675db2cef4.png)

#### Un circuito puente para medir temperatura

Si se va a medir temperatura, el transductor puede ser un termistor, el cual es sensible a la temperatura. La resistencia del termistor cambia de manera predecible a medida que cambia la temperatura. Un cambio de temperatura cambia la resistencia del termistor, lo que provoca un cambio correspondiente en el voltaje de salida del puente a medida que se desequilibra. El voltaje de salida es proporcional a la temperatura; por consiguiente, o un voltímetro conectado entre la salida puede ser calibrado para mostrar la temperatura o el voltaje de salida puede ser amplificado y convertido a forma digital para controlar en pantalla la visualización de la temperatura.

##  Teoremas de Circuitos y Conversiones (Capitulo 8)

Fuente de voltaje de CD

La fuente de voltaje de cd idealmente proporciona un voltaje constante a una carga, incluso cuando la resistencia de ésta varía.

La siguiente figura es el muy conocido símbolo empleado para identificar una fuente de voltaje de cd ideal.

![image](https://user-images.githubusercontent.com/105259381/176596588-78d7f4fd-cf11-4ab3-863a-af2412d709d9.png)

En realidad, ninguna fuente de voltaje es ideal; sin embargo, las fuentes de potencia regulada se aproximan a la situación ideal cuando funcionan dentro de la corriente de salida especificada.

#### Carga de la fuente de voltaje

Si RS es muy pequeño comparado con RL, la fuente se aproxima a la situación ideal porque casi todo el voltaje de fuente, VS, aparece entre los extremos de la resistencia más grande, RL. Muy poco voltaje actúa entre los extremos de la resistencia interna, RS. Si RL cambia, la mayor parte del voltaje de fuente permanece entre las terminales de salida en tanto RL sea mucho más grande que RS. Por consiguiente, ocurre un cambio muy pequeño en el voltaje de salida. Mientras más grande es RL, en comparación con RS, menos cambio ocurre en el voltaje de salida.

El voltaje de salida disminuye significativamente conforme la resistencia de la carga se reduce en comparación con la resistencia interna de la fuente.

#### Coversiones de Fuente

![image](https://user-images.githubusercontent.com/105259381/176599543-3fe6bd5b-95a2-4e26-9c3c-ce4043efc597.png)

#### Teorema de Superposicón

En cualquier rama dada de un circuito con múltiples fuentes, la corriente puede calcularse al determinar en esa rama particular las corrientes producidas por cada fuente que actúa sola, con todas las demás fuentes reemplazadas por sus resistencias internas. La corriente total en la rama es la suma algebraica de las corrientes individuales presentes en dicha rama. 

![image](https://user-images.githubusercontent.com/105259381/176600566-207a1b15-4df5-4e58-9481-91b777419f1b.png)


![image](https://user-images.githubusercontent.com/105259381/176601225-24c17faf-f663-415b-a7ba-59c4f3a7a011.png)

![image](https://user-images.githubusercontent.com/105259381/176601542-d16276ae-9107-4ce4-9cfc-17d025a13409.png)

#### Teorema de Thevenin

El teorema de Thevenin proporciona un método para simplificar un circuito a una forma equivalente estándar. Se utiliza para hacer más sencillo el análisis de circuitos complejos.

En un circuito eléctrico, el voltaje equivalente de Thevenin (VTH) es el voltaje de circuito abierto (sin carga) presente entre dos terminales de salida. 
Cualquier componente conectado entre estas dos terminales “ve” efectivamente a VTH en seriecon RTH. Como lo define el teorema de Thevenin.

La resistencia equivalente de Thevenin (RTH) es la resistencia total que aparece entre dos terminales en un circuito dado que tiene todas las fuentes reemplazadas por sus resistencias internas.

Ejemplo de la simplificación de un circuito mediante el Teorema de Thevenin

![image](https://user-images.githubusercontent.com/105259381/176601966-003b438c-a7c9-4874-9a44-310a3bc9e66d.png)

![image](https://user-images.githubusercontent.com/105259381/176602002-861f1dbe-cbe6-4855-8095-03088b1d849e.png)

![image](https://user-images.githubusercontent.com/105259381/176602016-f142a259-b784-4a03-a6b3-45294928331b.png)

![image](https://user-images.githubusercontent.com/105259381/176604937-f97054ef-8e3f-4d5d-bd6b-bd632c4ea626.png)

![image](https://user-images.githubusercontent.com/105259381/176605823-3b315125-3a4c-44e9-9239-1bbcf1acbad4.png)

#### Teorema de Norton

Cualquier resistor de carga conectado entre las terminales de salida de un circuito equivalente Norton tendrá la misma corriente a través de él y el mismo voltaje entre sus terminales como si estuviera conectado a las terminales de salida del circuito original.

![image](https://user-images.githubusercontent.com/105259381/176606440-1436283d-1c29-4c8e-a8e4-40d43ea445ea.png)

#### Teorema de transferencia de potencia máxima 

Para una fuente de voltaje dada, la potencia máxima se transfiere desde una fuente hasta una carga cuando la resistencia de la carga es igual a la resistencia interna de la fuente.

#### Conversiones Delta a Y, y Y a Delta

![image](https://user-images.githubusercontent.com/105259381/176608228-847ce084-72d6-4a95-8437-a35d2cc1f7c9.png)


![image](https://user-images.githubusercontent.com/105259381/176607701-c5e5805f-ca9e-454c-8467-99e031158d22.png)


![image](https://user-images.githubusercontent.com/105259381/176609523-24218135-382f-4003-8b8d-6243e574387c.png)


## Resolución de los ejercicios Capítulo 7 

