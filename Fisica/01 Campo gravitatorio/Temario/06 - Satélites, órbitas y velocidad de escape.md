[[Índice - Campo gravitatorio|← Campo gravitatorio]]

## 3) Aplicaciones

### 3.1.- Periodo de revolución y velocidad orbital

En general un satélite es un cuerpo que orbita alrededor de otro mayor que se considera como el generador del campo gravitatorio.

![[satelite-orbita.png|320]]

Para simplificar consideraremos una orbita circular. Cuando un satélite describe una órbita experimenta una aceleración centrípeta debido a que se encuentra sometido a una fuerza central (F<sub>c</sub>), que en el caso de la Tierra viene suministrada por la atracción gravitatoria que ejerce la Tierra sobre el satélite.

Por tanto, los módulos de la fuerza centrípeta y la fuerza gravitatoria son iguales,

$$F_c=F_g$$

Para los parámetros fijados en la figura,

$$m\,\frac{v^2}{R_T+h}=G\,\frac{M_Tm}{(R_T+h)^2}$$

Donde m es la masa del satélite que, al simplificarse, indica que la velocidad orbital es independiente de la masa del cuerpo que esté girando.

$$v=\sqrt{G\,\frac{M_T}{R_T+h}}$$

Esta expresión nos dice que la velocidad orbital es inversamente proporcional a la raiz cuadrada de la altura sobre la superficie a la que se encuentre el satélite. La expresión se puede modificar para introducir la [[Intensidad del campo gravitatorio terrestre|intensidad del campo gravitatorio]],

$$v=\sqrt{G\,\frac{M_T}{(R_T+h)^2}\,(R_T+h)}=\sqrt{g(R_T+h)}$$

$$v=\sqrt{g(R_T+h)}$$

Expresión que se también se conoce como primera velocidad cósmica.

Otros parámetros que se pueden conocer son la aceleración centrípeta del satélite,

$$a_c=\frac{v^2}{R_T+h}$$

y el periodo de revolución,

$$\omega=\frac{2\pi}{T}\ \rightarrow\ T=\frac{2\pi}{\omega}=\frac{2\pi}{\dfrac{v}{R_T+h}}=\frac{2\pi(R_T+h)}{v}$$

$$T=\frac{2\pi(R_T+h)}{\sqrt{G\,\dfrac{M_T}{R_T+h}}}\ \rightarrow\ T^2=\frac{4\pi^2(R_T+h)^2}{G\,\dfrac{M_T}{R_T+h}}=\frac{4\pi^2(R_T+h)^3}{GM_T}$$

Se puede observar que

$$T^2=\frac{4\pi^2}{GM_T}(R_T+h)^3=K(R_T+h)^3$$

que es la expresión de la [[Tercera ley de Kepler|tercera ley de Kepler]].

Todas las expresiones anteriores son válidas para cualquier planeta que gira en torno al Sol, para cualquier satélite que gire en torno a otro planeta o para cualquier cuerpo que gire en torno a otro por la fuerza de la gravedad. Simplemente hay que cambiar la masa de la Tierra, M<sub>T</sub>, y el radio de la Tierra, R<sub>T</sub>, por los valores correspondientes al cuerpo central. Para cuerpos muy alejados en comparación con su tamaño es más conveniente sustituir el término *R<sub>T</sub>+h* por la distancia *(r)* entre sus centros de masa.

Si la órbita es elíptica, la distancia entre los centros de los cuerpos (el central y el satélite) es variable. En esta situación la energía potencial del satélite (o planeta) también es variable

$$Ep=-G\,\frac{Mm}{r}$$

![[orbita-eliptica-energia.png|280]]

Ahora bien, como sólo actúa una fuerza conservativa, la energía permanece constante. Así, entre dos puntos diferentes de la órbita elíptica (puntos 1 y 2 en la figura adjunta) se cumple que

$$\Delta Em=0\ \rightarrow\ Em_2=Em_1\ \rightarrow\ Ec_2+Ep_2=Ec_1+Ep_1$$

En el punto 2 la distancia es mayor y la energía potencial es menor menos negativa que en el punto 1. Entonces, para mantener la igualdad, la energía cinética en 2 es menor que en 1, es decir, la velocidad del cuerpo en órbita elíptica es menor cuando está más alejado del foco y viceversa.

### 3.2.- Velocidad de escape de un proyectil

Para conseguir que un cuerpo lanzado desde la superficie terrestre salga del campo gravitatorio habrá que comunicarle una gran velocidad. Se denomina ***velocidad de escape*** a la velocidad que debe adquirir un cuerpo para que se escape de la atracción terrestre.

Supongamos un cuerpo que se lanza desde la superficie de la Tierra. Supondremos también que no hay resistencia del aire. En estas condiciones

$$\Delta Em=0\ \rightarrow\ Em_2=Em_1\ \rightarrow\ Ec_2+Ep_2=Ec_1+Ep_1$$

Si el punto 2 es el infinito podremos considerar que el cuerpo ha escapado del campo gravitatorio terrestre. Si el cuerpo se para en dicho punto,

$$Ec_2=0$$

$$Ep_2=0$$

Por tanto,

$$Ec_1+Ep_1=0$$

$$\frac{1}{2}mv_1^2-G\,\frac{M_Tm}{R_T}=0$$

Despejando la velocidad, que denotaremos como v<sub>e</sub>,

$$v_e=\sqrt{\frac{2GM_T}{R_T}}=\sqrt{2g_oR_T}$$

Exprexión que recibe el nombre de segunda velocidad cósmica.

<u>Consideraciones</u>:

- La velocidad de escape es independiente de la masa del objeto que quiere escapar (un proyectil necesita la misma velocidad de escape que una molécula).
- Según se ha visto en el desarrollo,

$$Ec_1+Ep_1=0\qquad Ec_2=0\qquad Ep_2=0$$

Es decir, un objeto al que se le ha comunicado la velocidad de escape tiene energía mecánica cero. A medida que el proyectil se aleja de la Tierra su energía potencial va aumentando (se va haciendo menos negativa) a costa de su energía cinética de manera que la energía mecánica se conserva.

- Si sustituimos los valores terrestre obtenemos una velocidad de escape desde la superficie de la Tierra de 11,2 Km/s. La expresión es válida para objetos lanzados desde cualquier planeta o satélite, así las velocidades de escape de los planetas del sistema solar (y la Luna) son, en km/s

| Astro | km/s | Astro | km/s |
| --- | :---: | --- | :---: |
| Mercurio | 4,3 | Júpiter | 60 |
| Venus | 10,3 | Saturno | 36 |
| Tierra | 11,2 | Urano | 22 |
| Luna | 2,3 | Neptuno | 24 |
| Marte | 5,0 | | |

<small>Los valores de los planetas gigantes gaseosos corresponden a la velocidad de escape desde la superficie visible de nubes.</small>

- La velocidad de escape es aplicable tan solo a objetos que dependan únicamente de su impulso inicial (proyectiles) para vencer la atracción gravitatoria; obviamente, no es aplicable a los cohetes, lanzaderas espaciales u otros artefactos con propulsión propia.
- Si el cuerpo se sube primero a una altura que se pueda considerar no despreciable y desde este lugar se lanza, la velocidad de escape es, evidentemente, menor:

$$v_e=\sqrt{\frac{2GM_T}{R_T+h}}=\sqrt{2g(R_T+h)}$$

Siendo g la intensidad del campo gravitatorio terrestre a la altura h.

### 3.3.- Lanzamiento de satélites. Energía y órbitas

Generalmente el lanzamiento de un satélite artificial se realiza en dos fases:

Fase 1: Se lleva el satélite a una altura h (este problema se considera en [[Puesta en órbita de un satélite|pág. 11]]).

Fase 2: Desde esa altura se lanza el satélite con una velocidad horizontal. El tipo de trayectoria que adquiera dependerá de la velocidad con que se lance desde dicha altura.

Supongamos que el cuerpo ya se encuentra a una altura h sobre la superficie terrestre, en ese momento el cuerpo se orienta y se lanza horizontalmente con una velocidad v<sub>o</sub>. La energía mecánica del cuerpo será en ese instante:

$$Ec+Ep=Em$$

$$\frac{1}{2}mv_o^2-G\,\frac{M_Tm}{R_T+h}=Em$$

![[lanzamiento-casos.png|280]]

Dependiento del valor de v<sub>o</sub> se pueden dar los siguientes casos (véase figura):

·) Casos A y B. Son lanzamientos que comportan caídas, es decir, son aquellos en los que la velocidad del lanzamiento es inferior a la velocidad orbital correspondiente a la altura de lanzamiento (h). La trayectoria hasta la superficie es una rama de parábola (tiro horizontal).

·) Casos C y D. Son lanzamientos que ponen el objeto en órbita. En estos casos la velocidad del lanzamiento es igual o superior a la velocidad orbital correspondiente a la altura h. Las órbitas pueden ser circulares (C) o elípticas (D).

En los dos casos, tanto para órbitas circulares como para órbitas elípticas, la energía mecánica del cuerpo es negativa, es decir,

$$\frac{1}{2}mv_o^2-G\,\frac{M_Tm}{R_T+h}<0\quad\rightarrow\quad\frac{1}{2}mv_o^2<G\,\frac{M_Tm}{R_T+h}$$

El caso C (órbita circular) se consigue si el lanzamiento tiene una velocidad igual a la velocidad orbital (primera velocidad cósmica), deducida en [[Velocidad orbital|págs. 6-7]].

$$v_o=velocidad\ orbital=\sqrt{G\,\frac{M_T}{R_T+h}}=\sqrt{g(R_T+h)}$$

Si v<sub>o</sub> supera este valor entonces la órbita se hace elíptica, tanto más excentrica cuanto más se aleje v<sub>o</sub> de la velocidad orbital. Pero hay un límite: el caso siguiente.

·) Caso E. Corresponde a un lanzamiento con una velocidad igual a la velocidad de escape del cuerpo situado a la altura h.

$$v_o=v_e=\sqrt{\frac{2GM_T}{R_T+h}}=\sqrt{2g(R_T+h)}$$

La trayectoria que sigue el cuerpo es parabólica y sería como si la órbita elíptica del caso D se abriera cada vez más, de forma que su eje mayor se hace infinito y el satélite sale del campo gravitatorio siguiendo una parábola. Tal como se ha dicho en el [[Velocidad de escape|apartado 3.2.]], en este caso la energía mecánica del cuerpo es cero.

·) Si la velocidad de lanzamiento es superior a la velocidad de escape a la altura h, la curva trazada es una hipérbola. En este caso la energía mecánica del cuerpo (en el instante en que es lanzado) es positiva,

$$\frac{1}{2}mv_o^2-G\,\frac{M_Tm}{R_T+h}>0\quad\rightarrow\quad\frac{1}{2}mv_o^2>G\,\frac{M_Tm}{R_T+h}$$

El que la energía mecánica sea mayor que cero significa que el cuerpo llega al infinito con una velocidad mayor que cero.

La figura anterior también se suele conocer como esquema de Newton pues Fue Isaac Newton quien lo ideó en “Sobre el sistema del mundo”, libro III de los Principia.

![[esquema-newton.png|220]]

#### Puesta en órbita de un satélite

En todas las consideraciones anteriores el cuerpo que se pone en órbita ya se encuentra a la altura deseada. Ante la cuestión de determinar la energía necesaria para poner un satélite en una determinada órbita desde la superficie de la Tierra debemos tener en cuenta que al estar en un campo conservativo, se debe cumplir que la energía que le comunicamos al satélite sea igual a la suma del incremento de su energía cinética y de su energía potencial,

$$W_{F_{exterior}}=E_{comunicada}=\Delta Ec+\Delta Ep$$

Al lanzar un satélite se suele hacer desde una latitud ecuatorial y hacia el este para aprovechar al máximo el impulso que le proporciona la Tierra pues el satélite lleva la velocidad del punto de lanzamiento. Así, si $\Delta Em=0$

$$Ep_{superficie}+Ec_{ayuda\ Tierra}+E_{comunicada}=Ep_{órbita}+Ec_{órbita}$$

Veamos miembro a miembro y término a término. Para ello tendremos en cuenta que,

- M<sub>T</sub> es la masa de la Tierra
- R<sub>T</sub> es el radio de la Tierra
- h la altura sobre la superficie terrestre a la que se encuentra el satélite
- m es la masa del satélite
- v<sub>T</sub> es la velocidad de rotación de la Tierra
- v<sub>o</sub> es la velocidad orbital del satélite a la altura h

$$Ep_{superficie}=-G\,\frac{M_T\,m}{R_T}$$

$$Ep_{órbita}=-G\,\frac{M_Tm}{R_T+h}$$

$$Ec_{órbita}=\frac{1}{2}\,m\,v_o^2=\frac{1}{2}\,m\,\frac{GM_T}{R_T+h}$$

Este valor se hace cero si sólo se desea conocer la energía necesaria para que un cuerpo alcance una altura h.

$$Ec_{ayuda\ Tierra}=\frac{1}{2}\,m\,v_T^2$$

El cuerpo se lanza desde el ecuador pues en donde la velocidad de la Tierra (rotación) es máxima (radio máximo).

$$v_T=\frac{2\pi R_T}{T}=\frac{2\pi\cdot6{,}38\cdot10^{6}}{24\cdot3600}=465\ m/s$$

La energía cinética que corresponde a este valor de velocidad es, por ejemplo, para un satélite de 65 kg de masa que hay que situar a una altura de dos radios terrestres desde la superficie, de el 0,2 % de toda la energía necesaria. Es un valor pequeño y en algunos problemas ni se tiene en cuenta (por ejemplo, en el análisis de la velocidad de escape no se ha tenido en cuenta).

Con todas estas expresiones se puede determinar la energía comunicada al satélite,

$$E_{comunicada}=-G\,\frac{M_Tm}{R_T+h}+\frac{1}{2}\,m\,\frac{GM_T}{R_T+h}+G\,\frac{M_T\,m}{R_T}-\frac{1}{2}\,m\,v_T^2$$

$$E_{comunicada}=G\,\frac{M_T\,m}{R_T}-\frac{1}{2}G\,\frac{M_Tm}{R_T+h}-\frac{1}{2}\,m\,v_T^2$$

A partir de esta energía comunicada se puede determinar la velocidad con que debe ser lanzado un satélite para alcanzar una determinada altura, asumiendo que toda esta energía es energía cinética (y se considera que Ec<sub>órbita</sub> = 0, como se ha mencionado antes).

### 3.4.- Energía mecánica de un satélite en órbita cerrada

La energía mecánica que debe tener u.n satélite para mantenerse en una orbita estacionaria a una altura sobre la superficie terrestre suele llamarse también energía de enlace.

Si el satélite describe una órbita circular

$$Em=Ec+Ep$$

$$Em=\frac{1}{2}mv^2-G\,\frac{M_Tm}{R_T+h}$$

Como v es la velocidad orbital,

$$Em=\frac{1}{2}m\,G\,\frac{M_T}{R_T+h}-G\,\frac{M_Tm}{R_T+h}$$

$$Em=-\frac{1}{2}\,G\,\frac{M_Tm}{R_T+h}=-G\,\frac{M_Tm}{2R_o}$$

Siendo R<sub>o</sub> la distancia desde el satélite al centro de la Tierra. Se puede observar que mientras que el satélite se mantenga en órbita la energía mecánica del mismo permanece constante.

Si la órbita fuese elíptica la expresión de la energía mecánica sería,

$$Em=-G\,\frac{M_Tm}{2a}$$

donde “a” es el semieje mayor de la órbita elíptica.

Un objeto libre, que no esté ligado a la atracción terrestre no tiene energía potencial, su energía mecánica (positiva) será la correspondiente a su energía cinética. Por tanto, un satélite tiene menos energía que si estuviera libre.

### 3.5.- Cambio de órbita de un satélite

Para hacer que un satélite cambie de una órbita situada a una distancia r<sub>i</sub> del centro de la Tierra a otra órbita cuya distancia es r<sub>f</sub>, podemos conocer el trabajo que se debe realizar pues equivale a la diferencia entre las energías de enlace correspondientes

$$W_i^f=Em_f-Em_i$$

Al utilizar esta expresión tenemos en cuenta no solo la energía potencial del satélite a la altura a la que se encuentre sino también su velocidad orbital correspondiente.

Importante: esta expresión no es el trabajo que realiza el campo gravitatorio sino que se trata del trabajo externo que se debe realizar para conseguir el cambio de órbita.

$$W_i^f=-G\,\frac{M_Tm}{2r_f}+G\,\frac{M_Tm}{2r_i}$$

$$W_i^f=\frac{GM_Tm}{2}\left(\frac{1}{r_i}-\frac{1}{r_f}\right)$$

Si se trata de acercar el satélite a la Tierra,

$$r_i>r_f\ \rightarrow\ \frac{1}{r_i}<\frac{1}{r_f}\ \rightarrow\ \frac{1}{r_i}-\frac{1}{r_f}<0\ \rightarrow\ W_i^f<0$$

es decir, se trata de un trabajo negativo. El proceso no requierirá del consumo de energía ya que en realidad se trata de una caída.

Si se trata de alejar el satélite de la Tierra,

$$r_i<r_f\ \rightarrow\ \frac{1}{r_i}>\frac{1}{r_f}\ \rightarrow\ \frac{1}{r_i}-\frac{1}{r_f}>0\ \rightarrow\ W_i^f>0$$

es decir, se trata de un trabajo positivo. El proceso requiere del consumo de energía ya que en realidad se trata de un “lanzamiento hacia arriba”.

## Ejercicios PAU

**Cuestiones:** [[Ejercicios - Satélites, órbitas y velocidad de escape#G-2|G-2]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-7|G-7]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-16|G-16]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-20|G-20]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-29|G-29]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-31|G-31]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-34|G-34]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-35|G-35]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-36|G-36]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-45|G-45]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-51|G-51]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-55|G-55]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-65|G-65]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-72|G-72]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-74|G-74]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-81|G-81]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-83|G-83]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-85|G-85]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-89|G-89]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-91|G-91]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-93|G-93]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-95|G-95]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-101|G-101]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-111|G-111]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-113bis|G-113bis]]

**Problemas:** [[Ejercicios - Satélites, órbitas y velocidad de escape#G-1|G-1]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-4|G-4]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-12|G-12]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-13|G-13]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-17|G-17]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-21|G-21]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-26|G-26]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-33|G-33]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-40|G-40]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-43|G-43]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-48|G-48]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-49|G-49]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-53|G-53]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-56|G-56]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-66|G-66]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-67|G-67]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-69|G-69]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-73|G-73]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-75|G-75]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-86|G-86]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-97|G-97]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-100|G-100]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-104|G-104]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-106|G-106]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-110|G-110]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-112|G-112]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-114|G-114]]

**También relacionados:** [[Ejercicios - Leyes de Kepler y gravitación universal#G-3|G-3]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-79|G-79]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-88|G-88]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-98|G-98]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-105|G-105]] · [[Ejercicios - Campo gravitatorio terrestre#G-108|G-108]]
