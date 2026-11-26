[[Índice - Campo gravitatorio|← Campo gravitatorio]]

## 5) Estudio energético de la interacción gravitatoria

La interacción gravitatoria también se puede describir en términos energéticos, teniendo en cuenta los conceptos de **[[Fuerza conservativa|fuerza conservativa]]** y de **[[Energía potencial|energía potencial]].** Una de las formas de transmitir la energía desde un cuerpo a otro cuerpo es mediante una fuerza de interacción. Esta fuerza de interacción provoca en el cuerpo sobre el que se ejerce un desplazamiento y, por tanto, produce un trabajo. Este trabajo es la energía transmitida.

### Fuerza conservativa

Centrémonos en el caso que nos ocupa, la interacción gravitatoria. Supongamos que se lanza un objeto hacia arriba. El objeto alcanza una altura máxima y luego cae. Vamos a calcular el trabajo total realizado por la fuerza gravitatoria, que está actuando sobre el cuerpo continuamente. En estas consideraciones se está despreciando cualquier resistencia del aire al movimiento.

![[trabajo-lanzamiento.png|200]]

En la figura adjunta, a es el punto de partida, situado a una altura y<sub>a</sub> respecto de la superficie, b es el punto más alto que alcanza el objeto, situado a una altura y<sub>b</sub>. Vamos a determinar el trabajo que realiza la fuerza gravitatoria (peso) mientras el cuerpo sube y cuando el cuerpo baja.

- Cuerpo subiendo:

$$W_a^b=\vec{P}\cdot\Delta\vec{r}=P\cdot\Delta r\cdot\cos180=-mg(y_b-y_a)$$

- Cuerpo bajando:

$$W_b^a=\vec{P}\cdot\Delta\vec{r}=P\cdot\Delta r\cdot\cos0=mg(y_b-y_a)$$

Hacer notar que en los dos casos Δr es (y<sub>b</sub> − ya) ya que es el módulo del desplazamiento (siempre positivo).

- El trabajo total será:

$$W_T=W_a^b+W_b^a=0$$

Como vemos, el trabajo realizado a través de una línea cerrada (trayectoria cerrada que empieza y termina en el mismo punto) es cero.

> *Una **fuerza es conservativa** si el trabajo realizado por dicha fuerza a través de una línea cerrada es nulo o, lo que es lo mismo, el trabajo realizado entre por dicha fuerza entre dos puntos siempre es el mismo independientemente del camino seguido.*

![[trabajo-caminos.png|250]]

La fuerza que interviene para mover un cuerpo desde A hasta B por los caminos 1, 2 ó 3 es conservativa si:

$$(W_a^b)_1=(W_a^b)_2=(W_a^b)_3$$

Además, por ejemplo,

$$(W_a^b)_1+(W_b^a)_2=0$$

$$(W_a^b)_2+(W_b^a)_2=0\,,\qquad etc.$$

La [[Ley de la gravitación universal|fuerza gravitatoria]] y la fuerza elástica son fuerzas conservativas. También es conservativa la fuerza eléctrica. La fuerza de rozamiento no es conservativa (es una fuerza que siempre se opone al movimiento y, por tanto, siempre formará un ángulo de 180º con el desplazamiento). Tampoco es conservativa la fuerza magnética.

### Energía potencial asociada a una fuerza conservativa

La energía potencial es una magnitud característica de las fuerzas conservativas. Se representa por U o por Ep.

La variación de la energía potencial viene definida por el llamado *Teorema de la Energía Potencial*. En general, el trabajo realizado por una fuerza conservativa (F) cuando desplaza su punto de aplicación desde la posición 1 hasta la posición 2 viene dado por:

$$W_1^2=\int_1^2\vec{F}\,d\vec{r}=-(U_2-U_1)=-\Delta U\qquad(=-\Delta E_p)$$

> *El trabajo realizado por una fuerza conservativa es igual a la variación de la energía potencial del cuerpo sobre el que actúa, tomando como minuendo la energía potencial del punto de partida.*

<u>Consideraciones:</u>

① La expresión anterior solo puede utilizarse si F es conservativa.

② En el ejemplo anterior de un cuerpo lanzado verticalmente desde un punto del campo gravitatorio, no se ha integrado la expresión del trabajo porque se considera que la variación en altura es pequeña y la [[Intensidad del campo gravitatorio|intensidad del campo gravitatorio]] permanece prácticamente constante.

Aplicamos el teorema a dicho ejemplo. Primero cuando el cuerpo sube:

$$W_a^b=\vec{P}\cdot\Delta\vec{r}=P\cdot\Delta r\cdot\cos180=-mg(y_b-y_a)=-\Delta E_p$$

Como y<sub>b</sub> > y<sub>a</sub>, entonces, $W_a^b=-\Delta E_p<0$.

*Cuando el trabajo que realiza una fuerza conservativa es negativo*, para mover el cuerpo desde el punto *a* hasta el punto *b* hay que realizar un trabajo en contra del campo gravitatorio (el cuerpo no va a subir solo). Es un trabajo que debemos realizar nosotros, cuyo valor será igual al que realiza la fuerza conservativa pero cambiado de signo.

Cuando el cuerpo cae,

$$W_b^a=\vec{P}\cdot\Delta\vec{r}=P\cdot\Delta r\cdot\cos0=mg(y_b-y_a)=-\Delta E_p$$

Como y<sub>b</sub> > y<sub>a</sub>, entonces, $W_a^b=-\Delta E_p>0$.

*Cuando el trabajo que realiza una fuerza conservativa es positivo*, para mover el cuerpo desde el punto *b* hasta el punto *a*, el trabajo lo realiza el campo gravitatorio.

#### ③ Teorema de las fuerzas vivas

En mecánica del sólido rígido, el trabajo realizado por una fuerza al desplazarse su punto de aplicación entre dos posiciones es igual al incremento que experimenta la energía cinética del cuerpo sobre la que actúa:

$$W_a^b=\Delta E_c$$

④ Diferencia entre el teorema de la energía potencial y el teorema de las fuerzas vivas: el teorema de la energía potencial sólo es válido para fuerzas conservativas, mientras que el teorema de las fuerzas vivas es válido para todo tipo de fuerzas, conservativas y no conservativas.

Por ejemplo, el teorema de las fuerzas vivas puede aplicarse aunque existan fuerzas disipativas, como la fuerza de rozamiento. Así, se puede utilizar para calcular el trabajo que realizan los frenos de un coche en una frenada (sin embargo, en el caso de la caída de un cuerpo se ha dicho desde el principio que se desprecia la resistencia del aire).

## 6) Energía potencial gravitatoria

La fuerza gravitatoria es [[Fuerza conservativa|conservativa]]. Por consiguiente lleva asociada una energía potencial cuya expresión será deducida en este apartado, así como un análisis de las consecuencias de aplicación de dicha expresión.

① <u>Situación de partida</u>: dos masas cualesquiera M<sub>1</sub> y m<sub>2</sub> (M<sub>1</sub> >> m<sub>2</sub>). La masa m<sub>2</sub> se encuentra inmersa en el campo gravitatorio que genera M<sub>1</sub> en un punto P, situado a una distancia r del centro de M<sub>1</sub>, y se mueve desde dicho punto hasta el infinito (es decir, se aleja del campo gravitatorio de M<sub>1</sub>).

![[ep-hasta-infinito.png|450]]

Se puede tratar, por ejemplo, de un lanzamiento vertical de una masa en un planeta, o de una salida de órbita de un satélite.

② Cálculo del trabajo que realiza la fuerza gravitatoria en este desplazamiento.

$$W_P^\infty=\vec{F}\cdot\Delta\vec{r}$$

Aquí $\vec{F}$ es la fuerza gravitatoria que se establece en m<sub>2</sub> y que es ejercida por M<sub>1</sub>. Por otra parte, $\Delta\vec{r}$ es el vector desplazamiento con origen en P y extremo en el infinito. $\vec{F}$ es una fuerza variable que depende de la distancia que hay entre las masas. Esta circunstancia impide un cálculo del trabajo con la expresión anterior, hay que recurrir a calcular dicho trabajo ($dW$) en desplazamientos infinitesimales ($d\vec{r}$):

$$dW=\vec{F}\cdot d\vec{r}=F\,dr\cos180=-G\,\frac{M_1m_2}{r^2}\,dr$$

y “sumar” (integral) todos los trabajos calculados al final:

$$W_P^\infty=\int_r^\infty-G\,\frac{M_1m_2}{r^2}\,dr=-GM_1m_2\int_r^\infty\frac{dr}{r^2}=-GM_1m_2\left[\frac{-1}{r}\right]_r^\infty$$

$$W_P^\infty=-GM_1m_2\left[\frac{1}{r}-\frac{1}{\infty}\right]=-G\,\frac{M_1m_2}{r}$$

③ La expresión anterior representa la energía potencial gravitatoria de m<sub>2</sub> en un punto cualquiera P del campo gravitatorio creado por M<sub>1</sub>.

$$Ep=-G\,\frac{M_1m_2}{r}$$

*¿Qué representa dicha energía potencial gravitatoria?*

*Es el trabajo necesario para llevar, en presencia de M<sub>1</sub>, la masa m<sub>2</sub> desde el punto donde se encuentra hasta el infinito.*

La energía potencial no se puede conocer de forma absoluta. Sólo se puede conocer la diferencia de energía potencial, pero al poner el punto final en el infinito se asume que en dicho punto la energía potencial es cero.

④ Valoración del signo de Ep.

Como vemos la energía potencial es negativa, es decir, el trabajo necesario para alejar una masa de la influencia de otra lo debemos “hacer nosotros” en contra del campo. Dado que se ha calculado el trabajo que realiza la fuerza gravitatoria, el que teóricamente debemos “hacer nosotros” al aplicar una fuerza sobre m<sub>2</sub> es el mismo pero cambiado de signo.

⑤ Si la posición final no es el infinito sino que es otra cualquiera.

![[ep-de-a-a-b.png|450]]

Aplicando el teorema de la energía potencial y sustituyendo ésta por la expresión recién encontrada

$$W_A^B=-\Delta Ep=-(Ep_B-Ep_A)=-\left(-G\,\frac{M_1m_2}{r_B}+G\,\frac{M_1m_2}{r_A}\right)$$

$$W_A^B=\left(G\,\frac{M_1m_2}{r_B}-G\,\frac{M_1m_2}{r_A}\right)$$

Pueden darse dos posibilidades:

1) r<sub>A</sub> < r<sub>B</sub> , situación dibujada anteriormente que corresponde a un alejamiento de las dos masas. En estas condiciones,

$$\frac{1}{r_B}<\frac{1}{r_A}\ \rightarrow\ W_A^B<0$$

es decir, el trabajo necesario para alejar una masa de la influencia de otra lo debemos “hacer nosotros” en contra del campo. Dado que se ha calculado el trabajo que realiza la fuerza gravitatoria, el que teóricamente debemos “hacer nosotros” al aplicar una fuerza sobre m<sub>2</sub> es el mismo pero cambiado de signo.

2) r<sub>A</sub> > r<sub>B</sub> , situación que corresponde a un acercamiento entre las dos masas. En estas condiciones

$$\frac{1}{r_B}>\frac{1}{r_A}\ \rightarrow\ W_A^B>0$$

es decir, el trabajo necesario para acercar una masa a otra lo realiza el campo gravitatorio.

### ⑥ Energía potencial terrestre y su relación con la expresión Ep = mgh

Hemos visto que la energía potencial gravitatoria de una masa m<sub>2</sub> debido a la interacción gravitatoria con otra masa M<sub>1</sub> viene dada por la expresión:

$$Ep=-G\,\frac{M_1m_2}{r}$$

Donde r es la distancia entre los centros de masa de M<sub>1</sub> y m<sub>2</sub>. También hemos visto que su valor representa el trabajo que hay que realizar para mover m<sub>2</sub> desde su posición hasta el infinito.

Si M<sub>1</sub> representa la masa de la Tierra todo lo dicho es válido y entonces Ep representa la energía potencial gravitatoria terrestre. En esta situación se pueden hacer algunas consideraciones:

![[ep-terrestre.png|250]]

1) *r* como mínimo vale el radio de la Tierra, R<sub>T</sub>. Si m<sub>2</sub> se encuentra en la superficie de la Tierra,

$$Ep=-G\,\frac{M_1m_2}{R_T}$$

Este valor es negativo, distinto de cero. Cambiado de signo representa el trabajo que debemos realizar en contra del campo gravitatorio terrestre para desplazar m<sub>2</sub> desde la superficie de la Tierra hasta el infinito.

2) Cuando m<sub>2</sub> se encuentra a una altura h sobre la superficie terrestre, su energía potencial será

$$Ep=-G\,\frac{M_1m_2}{(R_T+h)}$$

Este valor también es negativo, menos negativo que el caso anterior. Cambiado de signo representa el trabajo que debemos realizar en contra del campo gravitatorio terrestre para desplazar m<sub>2</sub> desde una altura h de la Tierra hasta el infinito.

¿Cuándo se puede utilizar entonces la expresión Ep = mgh? ¿Por qué si utilizamos la expresión Ep = mgh la energía potencial es cero en la superficie de la Tierra contradiciendo lo que se ha mencionado anteriormente?

![[ep-mgh.png|180]]

Volvamos a la siguiente situación: un cuerpo se lanza desde un punto r<sub>a</sub> hasta otro punto r<sub>b</sub>:

$$W_a^b=-\Delta Ep=-(Ep_b-Ep_a)=-\left(-G\,\frac{M_Tm}{r_b}+G\,\frac{M_Tm}{r_a}\right)$$

Si r<sub>a</sub> es la superficie de la Tierra,

$$-\Delta Ep=-GM_Tm\left(\frac{1}{R_T}-\frac{1}{R_T+h}\right)$$

$$-\Delta Ep=-GM_Tm\left(\frac{R_T+h-R_T}{R_T(R_T+h)}\right)=GM_Tm\left(\frac{h}{R_T(R_T+h)}\right)$$

Como $R_T\gg h$, la expresión $R_T(R_T+h)$ es aproximadamente igual a $R_T^2$. Entonces la variación de energía potencial en esta caída es

$$\Delta Ep=GM_Tm\left(\frac{h}{R_T^2}\right)=m_2\cdot G\,\frac{M_T}{R_T^2}\cdot h=mgh$$

Por otra parte, si hacemos Ep<sub>a</sub> = 0 ya que al encontrarse en la superficie de la Tierra su altura sobre esta es cero,

$$\Delta Ep=Ep_b-Ep_a=Ep_b-0$$

Entonces podemos asimilar la energía potencial a una cierta altura sobre la superficie como

$$Ep_b=mgh$$

La expresión Ep = mgh sólo es válida, por tanto, cuando $R_T\gg h$ pues en estas condiciones la intensidad del campo gravitatorio, g, se mantiene prácticamente constante.

## 7) Principio de conservación de la energía mecánica

Se llama energía mecánica de un sistema a la suma de la energía cinética y la energía potencial

$$Em=Ec+Ep$$

El principio de conservación de la energía mecánica dice:

> *Si sobre un sistema sólo actúan [[Fuerza conservativa|fuerzas conservativas]], la energía mecánica del sistema se mantiene constante*

<u>Deducción:</u>

Tenemos dos teoremas que se pueden aplicar cuando un cuerpo se mueve desde un punto a otro gracias a la acción de una fuerza conservativa:

-[[Teorema de las fuerzas vivas|Teorema de la energía cinética]], $W_1^2=\Delta Ec$

-[[Energía potencial|Teorema de la energía potencial]], $W_1^2=-\Delta Ep$

Si ambas expresiones representan el mismo trabajo,

$$\Delta Ec=-\Delta Ep$$

$$\Delta Ec+\Delta Ep=0$$

$$Ec_2-Ec_1+Ep_2-Ep_1=0$$

$$Ec_2+Ep_2-(Ec_1+Ep_1)=0$$

$$Em_2-Em_1=0$$

$$\Delta Em=0$$

Este principio sólo se puede utilizar si en el sistema no intervienen fuerzas no conservativas. Sin embargo las fuerzas no conservativas, a menudo llamadas fuerzas disipativas (disipan energía en forma de calor) son de lo más habitual (fuerza de rozamiento). Cuando en un sistema se tengan en cuenta estas fuerzas disipativas, el principio de conservación de la energía mecánica debe ser modificado.

Como el trabajo que se realiza sobre un cuerpo es igual a la suma de los trabajos que realizan cada una de las fuerzas que actúan sobre él, podemos poner,

$$W_T=W_c+W_{nc}$$

Donde $W_c$ es el trabajo que realiza todas las fuerzas conservativas (gravitatoria, elástica, etc.) y $W_{nc}$ es trabajo que realizan las fuerzas no conservativas (fundamentalmente la fuerza de rozamiento). Los teoremas de la energía cinética y energía potencial se aplican de la siguiente forma:

$$W_c=-\Delta Ep$$

$$W_T=\Delta Ec$$

Por tanto,

$$\Delta Ec=-\Delta Ep+W_{nc}$$

$$\Delta Ec+\Delta Ep=W_{nc}$$

$$\Delta Em=W_{nc}$$

> *El trabajo realizado por las fuerzas no conservativas es igual a la variación de la energía mecánica. Es decir, la energía mecánica no se mantiene constante.*

## 8) Potencial gravitatorio

En la determinación de la [[Energía potencial gravitatoria|energía potencial]] de una masa m<sub>2</sub> inmersa en el campo gravitatorio de M<sub>1</sub>, si m<sub>2</sub> fuese la unidad de masa, entonces el trabajo necesario para mover la unidad de masa desde donde se encuentre hasta el infinito recibe el nombre de potencial gravitatorio (V). Por tanto,

$$Ep=-G\,\frac{M_1m_2}{r}\ \xrightarrow{\ si\ m_2=1\,kg\ }\ V=-G\,\frac{M_1}{r}$$

El potencial gravitatorio se mide en J/kg.

Se puede encontrar una expresión que permita calcular el trabajo necesario para mover una masa m<sub>2</sub> entre dos puntos del campo gravitatorio generado por M<sub>1</sub> en función de los potenciales gravitatorios de dichos puntos:

$$W_a^b=-\Delta Ep=-\left(-G\,\frac{M_1m_2}{r_b}+G\,\frac{M_1m_2}{r_a}\right)=-m_2\left(-G\,\frac{M_1}{r_b}+G\,\frac{M_1}{r_a}\right)$$

$$W_a^b=-\Delta Ep=-m_2\Delta V$$

## Ejercicios PAU

**Cuestiones:** [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-6|G-6]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-44|G-44]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-76|G-76]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-77|G-77]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-92|G-92]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-99|G-99]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-105|G-105]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-107|G-107]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-109|G-109]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-113|G-113]]

**Problemas:** [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-24|G-24]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-46|G-46]] · [[Ejercicios - Trabajo, energía potencial, conservación y potencial#G-47|G-47]]

**También relacionados:** [[Ejercicios - Satélites, órbitas y velocidad de escape#G-1|G-1]] · [[Ejercicios - Campo e intensidad gravitatoria#G-27|G-27]] · [[Ejercicios - Campo e intensidad gravitatoria#G-39|G-39]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-40|G-40]] · [[Ejercicios - Campo e intensidad gravitatoria#G-41|G-41]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-45|G-45]] · [[Ejercicios - Campo e intensidad gravitatoria#G-52|G-52]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-55|G-55]] · [[Ejercicios - Campo e intensidad gravitatoria#G-57|G-57]] · [[Ejercicios - Campo e intensidad gravitatoria#G-59|G-59]] · [[Ejercicios - Campo e intensidad gravitatoria#G-62|G-62]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-72|G-72]] · [[Ejercicios - Campo e intensidad gravitatoria#G-78|G-78]] · [[Ejercicios - Campo e intensidad gravitatoria#G-87|G-87]] · [[Ejercicios - Campo e intensidad gravitatoria#G-102|G-102]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-104|G-104]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-110|G-110]]
