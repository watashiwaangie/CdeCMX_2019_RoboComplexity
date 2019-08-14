# MER3: RoboComplexity: Fisiología desde la complejidad y robótica.

# Resumen
En la semana de CdeCMX llevada acabo en la Facultad de Ingeniería, Mérida, Yucatán se realizó un simulador de corazón para el análisis de  este como un sistema complejo.

# Objetivos

- Diseñar y construir un simulador cardíaco utilizando robótica suave.
- Visualizar con un simulador cómo cambia el comportamiento del corazón después de realizar distintas actividades como meditar, correr o asustarse.
- Analizar con Python y R desde el paradigma de sistemas complejos cómo cambia la dinámica de las señales cardíacas.

# Hipótesis

Complejidad:

- Un sistema será complejo si el DFA arroja un valor alrededor a 1.
- Si el valor del DFA es igual a 0.5, el sistema será aleatorio.
- Si el valor del DFA es igual a 2, el sistema es determinista.

Entropía:

A mayor información, menor entropía y viceversa.

# Introducción

## Sistemas

Son un conjunto de elementos que se relacionan e interaccionan entre sí para lograr un objetivo.

###### Simples

Se comportan de manera lineal, por lo que son predecibles. Un ejemplo de sistema simple es el péndulo "simple", comúnmente usado en
clases de física para encontrar sus ecuaciones de movimiento haciendo uso de las leyes de Newton o las ecuaciones de Lagrange o Hamilton.

###### Complicados

Por lo general son un conjunto de sistemas simples interactuando entre sí, por lo tanto son lineales y su comportamiento de igual
forma es predecible. Un ejemplo de un sistema complicado es un avión, es grande y se aplican muchos principios y leyes físicas tanto para su construcción como para su funcionamiento, sin embargo, dedicando el tiempo adecuado a su estudio, hasta usted podría construir uno desde cero.

###### Complejos

Se caracterizan por ser no lineales, no predecibles, ser adaptativos, evolutivos y de propiedades emergentes, es decir, propiedades que son propios del conjunto de elementos que conforman el sistema y que al aislar esos elementos no se tienen. 

Los sistemas complejos se encuentran entre la zona de aleatoriedad y la zona determinista. 

Al analizar los sistemas se toman en cuenta los siguientes indicadores:

**DFA (Detrended Fluctuation Analysis)**

Indica el grado de fractalidad de una señal de acuerdo a lo siguiente:
- Si x = 0.1 el sistema es aleatorio
- Si x = 1 el sistema es complejo
- Si x = 2 el sistema es determinista

**Entropía** 

Indica cuánta información se tiene respecto de un sistema, mientras mayor información se tenga, menor será la entropía.

## Corazón

El corazón es una bomba de perfusión que tiene como principal función realizar contracciones para transportar oxígeno, CO2 y nutrientes al cuerpo. Posee células cardiacas que son especializadas para descargar, y transmitir energía eléctrica que provoca las contracciones musculares (latidos). 
Se considera un sistema complejo ya que se adapta y evoluciona de manera autoorganizada, no se puede predecir y siempre está en un punto de equilibrio entre aleatoriedad y determinismo, es decir, criticalidad. 

## Robótica suave

Parte de la robótica que sustituye el tipo de materal típico (metales), por materiales más elásticos, sensibles, moldeables, con la finalidad de replicar, por ejemplo, órganos humanos. 

# Materiales

Experiento 1: Análisis de las señales de pulso.

- Arduino UNO
- Sensor de pulso

Experimento 2: Análisis de las señales de movimiento.

- Celular con la aplicación 
- Tacones
- Tennis

Experimento 3: Simulador del corazón.

- 1 metro de tubo de plástico de 1/8.
- 1 metro de tubo de plástico de 1/4.
- 25 globos
- 50 cinchos de plástico
- Tela: FHSO - RED 58" 200 D. Heat Sealable Coatd Oxford, color: red.
- RED: 100 ft - 1/2 inch Flexo Pet expandable braided sleeving, black.


# Desarrollo

![Se presenta el flujo de trabajo.]
(https://raw.githubusercontent.com/watashiwaangie/CdeCMX_2019_RoboComplexity/master/Images/FLUJOTRABAJO.png)

Experimento 1: Análisis de las señles de pulso.

Para este primer experimento, se trabajó con la placa Arduino UNO y con un sensor de pulso. 
Primeramente se realizó la configuración necesaria de la placa y se conectó el sensor en el que una persona puso su dedo, se registró el pulso mientras esta se encontraba en un estado normal, sin estímulo alguno.
Posteriormente se alteró el estado de la persona poniéndole música y variando los géneros de esta, se le puso el tráiler de su película favorita y se le invitó a realizar una serie de puntillas.
El pulso sufrió alteraciones que son visibles en las gráficas que se realizaron para cada estímulo.

Experimento 2: Análisis de las señales de movimiento.

Una persona usó tenis y caminó y corrió por lapsos mientras se registraba su pulso con un sensor de movimiento instalado en un celular.
La misma persona realizó las mismas actividades, pero ahora usando tacones.

Experimento 3: 


# Conclusión

# Referencias









 
