[[Índice - Campo gravitatorio|← Campo gravitatorio]]

## 1) Campo gravitatorio terrestre

Se dice que existe un [[Campo gravitatorio - concepto|campo gravitatorio]] en una región del espacio si una masa colocada en un punto de esa región experimenta una fuerza gravitatoria.

El campo gravitatorio terrestre es un caso particular de la definición anterior, referida a la Tierra, es decir, el campo gravitatorio terrestre es la región del espacio donde una masa experimenta una fuerza gravitatoria debida a la Tierra.

Las características generales del campo gravitatorio ya han sido analizadas en el [[Concepto de campo|tema anterior]] y son aplicables aquí.

## 2) Magnitudes físicas que caracterizan el campo gravitatorio

Un campo gravitatorio queda determinado en cada punto del espacio por dos magnitudes características:

- La intensidad del campo gravitatorio
- El potencial gravitatorio

### 2.1.- Intensidad del campo gravitatorio en un punto

Esta magnitud ya ha sido definida y caracterizada en el [[Intensidad del campo gravitatorio|tema anterior]].

> *La intensidad de campo gravitatorio (g) de una masa M en un punto representa la fuerza que experimentaría la unidad de masa colocada en dicho punto. Su unidad en el S.I. es, por tanto, N·kg⁻¹, o también m·s⁻².*

$$g=G\,\frac{M}{r^2}$$

De lo que aquí se trata es de concretar este concepto al campo gravitatorio terrestre. Así,

$$g=G\,\frac{M_T}{(R_T+h)^2}$$

Donde G es la [[Constante de gravitación|constante de gravitación universal]], G = 6,67428·10⁻¹¹ N·m²·kg⁻²

M<sub>T</sub> es la masa de la Tierra, M<sub>T</sub> = 5,974·10²⁴ kg

R<sub>T</sub> es el radio terrestre, R<sub>T</sub> = 6378 km (radio ecuatorial)

h es la altura sobre la superficie terrestre a la que se esté midiendo g

g es la intensidad del campo gravitatorio terrestre a una altura h sobre su superficie.

Si hacemos h = 0 en la expresión anterior obtenemos la intensidad del campo gravitatorio en la superficie del planeta, g<sub>o</sub>

$$g_o=6{,}67428\cdot10^{-11}\,\frac{5{,}974\cdot10^{24}}{(6378000)^2}=9{,}802\ m\cdot s^{-2}\sim9{,}8\ N\cdot kg^{-1}$$

<u>Consideraciones (aplicadas al campo gravitatorio terrestre)</u>

- La intensidad del campo gravitatorio en un punto bien dada por la aceleración que experimenta un objeto colocado en dicho punto.
- Esta aceleración es independiente de la masa del objeto. Depende de la masa de la Tierra y de la distancia del lugar donde se encuentre al centro del planeta.
- La dirección de la intensidad del campo (aceleración gravitatoria) es la que pasa por el centro de la Tierra y el punto del espacio donde se está considerando el valor del campo.
- El sentido de la intensidad del campo (aceleración gravitatoria) es hacia el centro de la Tierra. Por tanto, según el criterio establecido en la figura para definir el vector unitario, su expresión vectorial será:

![[campo-vector-unitario.png|180]]

$$\vec{g}=-G\,\frac{M_T}{(R_T+h)^2}\,\hat{u}$$

#### Variación de la intensidad de campo gravitatorio con la distancia

El modelo establecido para el estudio de la interacción gravitatoria supone, para la Tierra, que la parte del planeta que genera el campo gravitatorio está concentrada en un punto material situado en el centro. A partir de este punto cualquier coordenada se considera inmersa en el campo gravitatorio terrestre. Debemos considerar pues cómo varía la intensidad del campo gravitatorio desde la superficie del planeta hacia el espacio, pero también desde la superficie del planeta hacia el centro de este.

- *Desde la superficie hacia el espacio exterior*

$$g=G\,\frac{M_T}{(R_T+h)^2}$$

Esta expresión se suele referir al valor de g<sub>o</sub>

$$g_o=G\,\frac{M_T}{R_T^2}$$

Dividiendo ambas expresiones

$$\frac{g}{g_o}=\frac{G\,\dfrac{M_T}{(R_T+h)^2}}{G\,\dfrac{M_T}{R_T^2}}=\frac{R_T^2}{(R_T+h)^2}$$

$$g=g_o\,\frac{R_T^2}{(R_T+h)^2}$$

![[g-con-altura.png|300]]

La representación gráfica de la variación de la intensidad del campo gravitatorio (módulo) en función de la altura en kilómetros se puede observar en la figura adjunta.

- *Desde la superficie hacia el interior del planeta.*

Consideraremos que la Tierra es una esfera sólida y homogénea (aproximación que permite hacer estimaciones de g pero que no es real). Así, el campo gravitatorio será nulo en el centro de la esfera y aumentará conforme aumenta la distancia del centro a un punto interior.

Supongamos que deseamos conocer la intensidad del campo gravitatorio en un punto P situado a una profundidad h. Dicho punto se encuentra a una distancia r del centro del planeta y la masa del planeta que influye como campo gravitatorio sobre P es la masa de la esfera de planeta cuyo radio es precisamente r (véase figura). Por tanto, en el interior del planeta,

![[tierra-interior.png|250]]

$$g=G\,\frac{m}{r^2}$$

Como hemos considerado que la Tierra es una esfera homogénea,

$$m=d\cdot V=\frac{4}{3}\pi r^3d$$

Donde d es la densiad de la Tierra,

$$d=\frac{M_T}{\frac{4}{3}\pi R_T^3}$$

Así,

$$m=\frac{4}{3}\pi r^3\cdot\frac{M_T}{\frac{4}{3}\pi R_T^3}=\frac{M_T\cdot r^3}{R_T^3}$$

La expresión de g en el interior de la Tierra queda,

$$g=G\,\frac{\dfrac{M_T\cdot r^3}{R_T^3}}{r^2}=G\,\frac{M_T\cdot r}{R_T^3}=g_o\,\frac{r}{R_T}$$

$$g=g_o\,\frac{r}{R_T}=g_o\,\frac{R_T-h}{R_T}$$

Vemos que la variación de g en el interior de la Tierra es lineal con la profundidad, h.

$$g=g_o-\frac{g_o}{R_T}\,h$$

En definitiva, una representación aproximada de la variación de la intensidad del campo gravitatorio terrestre desde el centro de la Tierra hasta el infinito, considerando a la Tierra como una esfera homogénea sería:

![[g-centro-infinito.png|450]]

La gravedad también varía con la latitud debido al movimiento de rotación de la Tierra y al achatamiento en los polos.

| Latitud (grados) | g (m/s²) |
| :---: | :---: |
| 0 | 9,7803 |
| 10 | 9,7819 |
| 20 | 9,7864 |
| 30 | 9,7932 |
| 40 | 9,8017 |
| 45 | 9,806 |
| 60 | 9,8191 |
| 80 | 9,8305 |
| 90 | 9,8321 |

### 2.2.- Energía potencial gravitatoria y potencial gravitatorio

Tal como se dijo en el [[Fuerza conservativa|tema anterior]], la fuerza gravitatoria es conservativa, es decir, el trabajo realizado por dicha fuerza entre dos puntos siempre es el mismo, independiente del camino seguido. Las fuerzas conservativas tienen una magnitud característica llamada energía potencial que permite determinar el trabajo que realiza dicha fuerza (teorema de la [[Energía potencial|energía potencial]]),

$$W_1^2=-\Delta E_p=-(Ep_2-Ep_1)$$

La expresión de la energía potencial de una masa m en un punto cualquiera de un campo gravitatorio generado por la masa M es

$$Ep=-G\,\frac{Mm}{r}$$

Donde r es la distancia entre los centros de masas de M y m.

Si sustituimos los parámetros terrestres obtenemos

$$Ep=-G\,\frac{M_Tm}{(R_T+h)}$$

Expresión que representa la energía potenical gravitatoria de un cuerpo de masa m situado a una altura h sobre la superficie de la Tierra.

Aunque lo pueda parecer, la expresión anterior no nos da un valor absoluto de la energía potencial ya que sólo es posible conocer una diferencia entre las energías potenciales de dos puntos del campo gravitatorio (teorema de la energía potenical). Así, la expresión anterior representa el trabajo que realiza el campo gravitatorio cuando la masa m se mueve desde el punto donde se encuentra hasta el infinito.

La energía potencial de un cuerpo en la superficie de la Tierra será entonces

$$Ep=-G\,\frac{M_Tm}{R_T}=-g_o\cdot m\cdot R_T$$

Y respresenta el trabajo que realiza la fuerza gravitatoria cuando m se mueve desde la superficie de la Tierra hasta el infinito, es decir, es la diferencia entre las energías potenciales en la superficie de la Tierra y en el infinito (donde la energía potencial es cero, considerado como origen de energía potencial).

La energía potencial gravitatoria es siempre negativa, indicándose así que para mover la masa m desde donde esté hasta el infinito hay que realizar un trabajo externo en contra del campo cuyo valor es igual al de la energía potencial pero cambiado de signo.

#### Potencial gravitatorio terrestre

Si en lugar de una masa cualquiera se traslada la masa unidad, entonces el trabajo realizado recibe el nombre de **potencial gravitatorio terrestre (J/kg):**

$$V=\frac{Ep}{m}=-G\,\frac{M_T}{R_T+h}$$

El potencial en un punto depende de la distancia desde dicho punto hasta el centro del campo. Todos los puntos que equidisten del centro del campo tendrán, pues, el mismo potencial y forman una superficie equipotencial, que es la superficie de la esfera de radio r que rodea al punto centro del campo. Cada punto de un campo gravitatorio está definido por un potencial, que es una magnitud escalar, por tanto, el campo gravitatorio lleva asociado un campo escalar.

## Ejercicios PAU

**Cuestiones:** [[Ejercicios - Campo gravitatorio terrestre#G-19|G-19]] · [[Ejercicios - Campo gravitatorio terrestre#G-22|G-22]] · [[Ejercicios - Campo gravitatorio terrestre#G-23|G-23]] · [[Ejercicios - Campo gravitatorio terrestre#G-58|G-58]] · [[Ejercicios - Campo gravitatorio terrestre#G-61|G-61]] · [[Ejercicios - Campo gravitatorio terrestre#G-71|G-71]] · [[Ejercicios - Campo gravitatorio terrestre#G-80|G-80]] · [[Ejercicios - Campo gravitatorio terrestre#G-90|G-90]] · [[Ejercicios - Campo gravitatorio terrestre#G-94|G-94]]

**Problemas:** [[Ejercicios - Campo gravitatorio terrestre#G-9|G-9]] · [[Ejercicios - Campo gravitatorio terrestre#G-32|G-32]] · [[Ejercicios - Campo gravitatorio terrestre#G-108|G-108]]

**También relacionados:** [[Ejercicios - Anexo - Mareas, variación de g y Neptuno#G-10|G-10]] · [[Ejercicios - Anexo - Mareas, variación de g y Neptuno#G-11|G-11]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-24|G-24]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-34|G-34]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-42|G-42]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-44|G-44]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-46|G-46]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-49|G-49]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-60|G-60]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-66|G-66]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-73|G-73]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-86|G-86]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-97|G-97]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-112|G-112]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-113|G-113]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-114|G-114]]
