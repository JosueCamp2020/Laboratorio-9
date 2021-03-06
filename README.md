# Laboratorio-9
# Amplificador Operacional

1. OBJETIVOS

1.1 OBJETIVOS GENERALES

* Diseñar una serie de circuitos que nos permitan determinar el comportamiento de un amplificador operacional dentro de este a través de las mediciones obtenidas a partir del osciloscopio para encontrar la relación entre la práctica y la teoría adquirida en clase.

1.2 OBJETIVOS ESPECIFICOS

* Verificar el principio de funcionamiento de un amplificador operacional.
* Analizar algunas aplicaciones básicas con el amplificador operacional.
* Familiarizarse con el uso de instrumentos de medida.

2. MARCO TEORICO

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/Marco.jpeg)

3. DIAGRAMAS

* Diagramas de los 3 circuitos

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/Circuitos.png)

* Armado Circuito 1 en Multisim Live.

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/Circuito1.1.png)

* Osciloscopio y Medicion de Voltaje de Entrada y Salida

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/1.png)

* Armado Circuito 2 en Multisim Live.

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/Circuito2.1.png)

* Osciloscopio y Medicion de Voltaje de Entrada y Salida

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/2.png)

* Armado Circuito 3 en Multisim Live.

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/Circuito3.1.png)

* Osciloscopio y Medicion de Voltaje de Entrada y Salida

![](https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Imagenes/3.png)

4. LISTA DE COMPONENTES

| CANTIDAD | MATERIAL O EQUIPO |
| ------------- | ------------- |
| 1 | Generador de señales  |
| 1 | Fuente DC |
| 1 | Osciloscopio |
| 1 | Protoboard |
| 1 | Multimetro  |
| 1 | Cables conductores  |
| 1 | Resistencias, Capacitores  |
| 1 | Amplificadores Operacionales  |

5. EXPLICACIÓN / RESOLUCIÓN

* Primer Circuito

* Podemos observar que en este circuito se ha conectado la entrada no inversora a tierra, y también se conecta una resistencia, mientras que el voltaje inversor se ha conectado con una resistencia de retroalimentación Rf. Estos son los requisitos para tener un amplificador inversor, el comportamiento se relaciona directamente con su nombre, ya que este amplificador precisamente se encarga de mostrar una salida de señal inversa a la de entrada, que en nuestro caso es mayor y ha aumentado nuestro voltaje a un factor de 4.2965 V

* Segundo Circuito

* En el comportamiento de un circuito con amplificador integrador, se observa en la gráfica que a la salida hay una onda cuadrada bipolar la cual al pasar a través del amplificador operacional se obtiene en la salida una onda integral, esto se debe a que principalmente la onda rectangular se constituye por valores positivos y negativos y como se conoce, al integrar una constante lo que se obtiene es una recta con su respectiva pendiente, que dependerá de las contantes positivas y negativas que se tenga y también del factor que multiplica a toda la integral, el signo negativo en la integral nos indica que está en fase contraria respecto a la señal de entrada.

* Tercer Circuito

En esta gráfica también tenemos un amplificador inversor por lo que tiene el mismo análisis que el primer diagrama, con la diferencia de que hay dos señales que corresponden a las fuentes de entrada, con ayuda de cálculos se obtiene que este voltaje de entrada tiene un valor de 2V y en el voltaje de salida tenemos 8.33V, por lo que concluimos que el voltaje se ha amplificado a un valor de 6.33V.

- Conclucion en una tabla.

| - | VOLTAJE ENTRADA | VOLTAJE SALIDA |
| - | - | - |
| 1ER CIRCUITO | 0.70711 | 4.2965 |
| 2DO CIRCUITO | 3.53 | -12 |
| 3ER CIRCUITO | 2 | 8.32 |

6. MANUAL DE USUARIO

Link Manual: https://github.com/JosueCamp2020/Laboratorio-9/blob/main/Anexos/Multisim.pdf

7. CONCLUSIONES

* Encontramos un circuito con un amplificador integrado, ya que al tener conectado un capacitor lo que se observa es una señal de entrada, mientras que en la salida vemos una señal ya integrada, razón por la cual las señales se inclinan y nos dan este tipo de gráfica, la cual está en fase contraria respecto a la señal de entrada.
* Se determinó que tanto el primer circuito como el tercer circuito funcionan como amplificadores inversores, ya que como se observó en la gráfica, ambos nos dan una señal de salida inversa a la de entrada que es mayor al valor del voltaje inicial.
* Esta práctica fue realizada con éxito ya que se pudo comprobar mediante la fórmula del amplificador inverso el resultado obtenido del osciloscopio de cada circuito simulado obteniendo pequeños porcentajes de errores, que se pueden considerar ya no existe la máxima precisión al usar un osciloscopio.

8. PREGUNTAS

* 1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

RESPUESTA = Entre los principales parámetros que se deben considerar son:

- Valor del voltaje inversor y no inversor = Es importante a tomar en cuenta estos dos voltajes, ya que de esto dependerá la forma de nuestra señal de salida, ya que dependiendo de esto se observarán diferentes gráficas respecto al voltaje e función del tiempo.

- Componente de retroalimentación = Dependiendo de este componente cambiará el amplificador, por ejemplo si fuese una resistencia podriamos hablar de un amplificador inversor, pero si conectamos un capacitor lo que se obtiene es un amplificador integrador.

- Impedancia de entrada = Son los componentes que se oponen al flujo de corriente como las resistencias.

- Tensión de alimentación = Se refiere a la máxima alimentación que se aplica en los terminales, tomando en cuenta que no exista un flujo excesivo de corriente.

* 2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.

Las características mas importantes de los amplificadores operacionales a tomar en cuenta son:

-Infinita ganancia en lazo abierto.

-Infinita resistencia de entrada.

-Corriente de entrada cero.

-Tensión de desequilibrio de entrada cero.

-Infinito rango de tensión disponible en la salida.

-Infinito ancho de banda con desplazamiento de fase cero.

-Rapidez de variación de tensión infinita.

-Ruido cero.

-Infinito rechazo de modo común (CMRR)

-Infinito factor de rechazo a fuente de alimentación (PSRR).

* 3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.

Algunas aplicaciones más comunes que hay para esos amplificadores son los siguientes:

-Calculadoras digitales

-Filtros

-Preamplificadores y búferes de audio y video

-Reguladores

-Conversores

-Evitar el efecto de carga

-Adaptadores de niveles (por ejemplo CMOS y TTL)

-Rectificadores de precisión

Las aplicaciones más comunes, corresponden a amplificadores sumadores, restadores, diferenciadores, integradores e integradores (que ya fueron usados).

9. BIBLIOGRAFIA

* Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.
* Lifeder, Onda senoidal. Recuperado de: https://www.lifeder.com/onda-senoidal/
* Floyd, T. L. ( 2007). Principios de circuitos eléctricos (Vol. Octava edición). México: Pearson Educación.
