[[Índice - Electromagnetismo|← Electromagnetismo]]

## Electromagnetismo

### Experiencia de Oersted

La unión electricidad-magnetismo tiene una fecha: 1820. Ese año Oersted realizó su famoso experimento (ver figura) en el cual hacía circular una corriente eléctrica por un conductor cerca del cual se colocaba una aguja imantada. La aguja se desviaba mostrando que ***una corriente eléctrica crea un campo magnético a su alrededor.***

![[e-oersted.png|350]]

Experiencia de Oersted (1820) mostrando como una corriente eléctrica desvía una aguja imantada

![[e-oerstedr.png|180]]

Hans Christian Oersted (1777 - 1851)

## Campo magnético creado por un conductor

El valor del campo magnético creado por un hilo por el que circula una corriente de intensidad I en un punto situado a una distancia r viene dado, por ***(Ley de Biot-Savart)***:

$$\boxed{B=\frac{\mu}{2\pi}\,\frac{I}{r}}$$

- ***Las líneas de campo son circunferencias*** concéntricas al hilo, situadas en un plano perpendicular al mismo.
- ***El sentido de las líneas de campo*** es el de giro de un sacacorchos que avanza en el sentido de la corriente.
- ***El vector campo magnético*** es tangente a las líneas de campo y de su mismo sentido.
- ***La intensidad del campo magnético*** es directamente proporcional a la intensidad que circula e inversamente proporcional a la distancia al conductor.

![[e-hilo.png|450]]

### Permeabilidad magnética

µ es la ***permeabilidad*** magnética del medio. Recoge la mayor o menor facilidad del medio para transmitir el campo magnético. Para el vacío o el aire el valor es el mismo:

$$\mu_0=4\pi\,10^{-7}\,\frac{T\,m}{A}=4\pi\,10^{-7}\,\frac{N}{A^2}$$

Para otros medios es muy frecuente expresar la permeabilidad como ***permeabilidad relativa:***

$$\mu_r=\frac{\mu}{\mu_0}\ ;\qquad\mu=\mu_r\,\mu_0$$

### Clasificación de los materiales magnéticos

Podemos clasificar los distintos materiales de acuerdo con su comportamientos magnético como:

#### Sustancias ferromagnéticas

- Su permeabilidad es muy superior a la del vacío: $\mu_r>>1$
- Son fuertemente atraídas por los imanes.
- Son fácilmente imantables y mantienen sus propiedades magnéticas durante cierto tiempo. A veces (caso del acero) se convierten en imanes permanentes.
- Si se someten a un campo magnético externo el campo en su interior es mayor que el externo.
- Ejemplos: hierro, acero, cobalto, níquel, neodimio...

#### Sustancias paramagnéticas

- Su permeabilidad es algo superior a la del vacío: $\mu_r\geq1$
- Son débilmente atraídas por los imanes.
- Aunque son imantables no mantienen sus propiedades magnéticas una vez que se suprime el campo magnético exterior.
- Si se someten a un campo magnético externo el campo en su interior es prácticamente igual que el externo
- Ejemplos: aluminio, platino, paladio...

#### Sustancias diamagnéticas

- Su permeabilidad es inferior a la del vacío: $\mu_r\leq1$
- Son débilmente repelidas por los imanes.
- No son imantables.
- Si se someten a un campo magnético externo el campo magnético en su interior es menor que el externo.
- Ejemplos: mercurio, plata, cobre, bismuto, agua...

## Campo magnético creado por un espira

Una espira crea un campo magnético tal como el de la figura. En los puntos situados en el eje de la espira el campo vale:

$$B=\frac{\mu\,I}{2}\,\frac{R^2}{\left(R^2+x^2\right)^{3/2}}$$

Y en su centro (donde x =0):

$$\boxed{B=\frac{\mu}{2}\,\frac{I}{R}}$$

![[e-espira.png|550]]

## Origen del magnetismo natural

El hecho de que una corriente eléctrica genere un campo magnético permite explicar el magnetismo natural como consecuencia de la existencia de diminutos imanes de tamaño atómico.

Si consideramos un único electrón (carga eléctrica negativa) orbitando alrededor del núcleo tendremos el equivalente a una diminuta corriente eléctrica circular (espira) que generará su correspondiente campo magnético.

![[e-electron.png|400]]

Si consideramos átomos más complejos (con varios electrones situados en varias capas) la situación puede ser mucho más complicada y el campo magnético total[^3] sería el resultante de la suma del de todos los electrones, que puede dar un valor nulo. Una situación similar se produce cuando tratamos con moléculas.

**En las *sustancias diamagnéticas*** los átomos o moléculas (debido a su configuración electrónica) no tienen campo magnético neto. Si se someten a la acción de un campo externo ***se induce*** en ellas un campo magnético opuesto. De esta manera el campo aplicado es más débil en su interior y son repelidas por los imanes (Faraday ya observó en 1846 que el bismuto era repelido por un imán).

![[e-dia.png|180]]

**En las *sustancias paramagnéticas*** los átomos o moléculas individuales sí que pueden ser considerados como diminutos imanes, pero como resultado de la agitación molecular (energía cinética) están orientados al azar dando un campo magnético resultante nulo. Si se someten a la acción de un campo magnético externo se orientan en parte y presentan propiedades magnéticas mientras actúe el campo. Si éste cesa, los imanes microscópicos vuelven a desordenarse. La magnetización no es permanente.

![[e-para.png|180]]

De todo lo dicho se desprende que la magnetización será mayor cuanto más intenso sea el campo magnético externo o más baja la temperatura. Esta dependencia con la temperatura fue observada por Pierre Curie. La ***ley de Curie*** relaciona la magnetización de una sustancia con el campo magnético aplicado y la temperatura absoluta, aunque deja de ser válida para campos magnéticos muy grandes o temperaturas muy bajas.

**En las *sustancias ferromagnéticas*** se observa una magnetización permanente. A nivel microscópico se pueden distinguir zonas, denominadas ***dominios***, en las cuales los imanes atómicos están orientados en una dirección determinada, aun en ausencia de campos externos. Si se aplica un campo magnético externo aquellos dominios que están orientados según el campo aplicado crecen a expensas de los que no poseen esa orientación, a la vez que se produce una rotación en la orientación de los dominios en la dirección del campo magnético externo. Todo ello hace que se produzca un refuerzo considerable del campo magnético en el interior de la sustancia.

![[e-ferro.png|180]]

La agitación térmica tiende a desordenar los dominios, por eso existe una temperatura ***(temperatura de Curie***) por encima de la cual la sustancia pierde sus propiedades ferromagnéticas y se convierte en paramagnética.

![[e-dominios.png|550]]

[^3]: Realmente se habla de ***momento magnético***, un vector definido en la forma siguiente: El vector unitario se define como perpendicular a la superficie (órbita) y sentido el del sacacorchos que gire en el mismo sentido que el de la intensidad. $\vec{\mu}=I\,S\,\vec{u}$

## Campo magnético creado por un solenoide

Un solenoide de longitud L crea un campo resultante de la suma del de las N espiras que lo componen. En el interior del solenoide y para puntos situados sobre su eje:

$$\boxed{B=\frac{N\,\mu\,I}{L}}$$

Para el centro del solenoide y en sus extremos:

$$\boxed{B=\frac{N\,\mu\,I}{2\,L}}$$

![[e-solenoide.png|550]]

Si consideramos un solenoide largo y con las espiras lo suficientemente juntas, podemos considerar que el campo en el exterior es nulo y uniforme en su interior:

$$\boxed{B=\frac{N\,\mu\,I}{L}\qquad B=n\,\mu\,I\ \left(\text{Donde }n=\frac{N}{L}\right)}$$

![[e-solenoidelargo.png|550]]

## Ejercicios PAU

**Cuestiones:** [[Ejercicios - Fuentes del campo magnético y materiales#E-9|E-9]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-87|E-87]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-98|E-98]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-99|E-99]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-110|E-110]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-119|E-119]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-127|E-127]]

**Problemas:** [[Ejercicios - Fuentes del campo magnético y materiales#E-6|E-6]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-54|E-54]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-66|E-66]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-77|E-77]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-80|E-80]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-95|E-95]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-102|E-102]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-106|E-106]] · [[Ejercicios - Fuentes del campo magnético y materiales#E-116|E-116]]

**También relacionados:** [[Ejercicios - Campo magnético y fuerza sobre cargas#E-18|E-18]] · [[Ejercicios - Campo magnético y fuerza sobre cargas#E-29|E-29]] · [[Ejercicios - Campo magnético y fuerza sobre cargas#E-40|E-40]]
