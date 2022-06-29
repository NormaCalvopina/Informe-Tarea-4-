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

![](https://github.com/NormaCalvopina/Informe_Tarea4/blob/main/fotos/Captura%20de%20pantalla%202022-06-28%20235901.png)

#### Un circuito puente para medir temperatura

Si se va a medir temperatura, el transductor puede ser un termistor, el cual es sensible a la temperatura. La resistencia del termistor cambia de manera predecible a medida que cambia la temperatura. Un cambio de temperatura cambia la resistencia del termistor, lo que provoca un cambio correspondiente en el voltaje de salida del puente a medida que se desequilibra. El voltaje de salida es proporcional a la temperatura; por consiguiente, o un voltímetro conectado entre la salida puede ser calibrado para mostrar la temperatura o el voltaje de salida puede ser amplificado y convertido a forma digital para controlar en pantalla la visualización de la temperatura.

##  Teoremas de Circuitos y Conversiones (Capitulo 8)

