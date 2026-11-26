[[Índice - Campo gravitatorio|← Campo gravitatorio]]

## Problemas resueltos de energía

### Problema: Muelle y dos masas

> [!question] Enunciado
> En el dispositivo de la figura, el muelle tiene una constante elástica K = 1000 N/m y el coeficiente de rozamiento de la masa m<sub>2</sub> con la superficie de la mesa vale 0,1. Si, inicialmente, el muelle se encuentra en reposo, calcula la ecuación que proporciona el alargamiento máximo.

![[muelle-dos-masas.png|400]]

*Inicio*

El sistema parte del reposo (v<sub>o</sub> = 0) y, según el enunciado, el muelle no está estirado (x = 0). Con estos datos podemos establecer que inicialmente la energía mecánica del sistema es la energía potencial correspondiente a la altura (h<sub>o</sub>) a la que se encuentre la masa m<sub>1</sub>, es decir,

$$Em_o=Ep_o=m_1gh_o$$

*Final*

La energía potencial de la masa m<sub>1</sub> es la que hace moverse al sistema, que empieza a acelerar y el muelle a estirarse hasta que el sistema se detiene (v = 0) con un estiramiento máximo del muelle (x). En estas condiciones la energía mecánica del sistema corresponde a la energía potencial de m<sub>1</sub> debido a la nueva altura a la que se encuentre (h) y energía potencial elástica del muelle, es decir,

$$Em=Ep_{gravitatoria}+Ep_{elástica}$$

$$Em=m_1gh+\frac{1}{2}Kx^2$$

Por tanto,

$$\Delta Em=Em-Em_o=m_1gh+\frac{1}{2}Kx^2-m_1gh_o$$

$$\Delta Em=m_1g(h-h_o)+\frac{1}{2}Kx^2=-m_1gx+\frac{1}{2}Kx^2$$

Ya que la variación en altura de m<sub>1</sub> es igual al alargamiento que se produce en el muelle, pero su valor es negativo porque h < h<sub>o</sub>.

Entre el instante inicial y el final interviene una fuerza no conservativa (fuerza de rozamiento), por tanto,

$$\Delta Em=W_{nc}$$

Donde $W_{nc}$ es el trabajo realizado por la fuerza de rozamiento, es decir,

$$W_{nc}=F_Rx\cos180=-\mu Nx=-\mu m_2gx$$

Donde la distancia que recorre m<sub>2</sub> en horizontal es igual al alargamiento que se produce en el muelle.

Igualando la variación de energía mecánica con el trabajo no conservativo:

$$-m_1gx+\frac{1}{2}Kx^2=-\mu m_2gx$$

$$-49\cdot x+\frac{1}{2}\,1000\,x^2=-5{,}88\cdot x$$

$$-43{,}12\cdot x+500\,x^2=0\qquad x\,(500x-43{,}12)=0$$

Soluciones:

$$x=0\ (situación\ inicial)$$

$$x=0{,}086\ m\ \ (situación\ final)$$

### Problema: Trineo en una ladera

> [!question] Enunciado
> Un trineo de 100 kg parte del reposo y desliza hacia abajo por una ladera de 30º de inclinación respecto a la horizontal.
> a) Explique las transformaciones energéticas durante el desplazamiento del trineo suponiendo que no existe rozamiento y determine, para un desplazamiento de 20 m, la variación de sus energías cinética y potencial, así como la velocidad del cuerpo.
> b) Explique, sin necesidad de cálculos, cuáles de los resultados del apartado a) se modificarían y cuáles no, si existiera rozamiento.

![[trineo.png|450]]

a) En la figura se representa la situación inicial y final, los datos que da el problema y el origen de alturas.

En la situación inicial el cuerpo está en reposo, luego no posee energía cinética (Ec<sub>o</sub> = 0). En dicha situación el cuerpo se encuentra a una cierta altura sobre el origen de alturas y posee, por tanto, energía potencial gravitatoria cuyo valor es,

$$Ep_o=mgh$$

La energía mecánica del cuerpo en esta situación inicial será:

$$Em_0=Ep_o+Ec_o=mgh$$

En la situación final el cuerpo ha llegado al origen de alturas, ha perdido la energía potencial (Ep = 0) que tenía en la situación inicial transformándose esta en energía cinética, es decir,

$$Ec=\frac{1}{2}mv^2$$

La energía mecánica del cuerpo en esta situación final será:

$$Em=Ep+Ec=\frac{1}{2}mv^2$$

Como el cuerpo cae sin rozamiento, no existen fuerzas disipativas y, por tanto, se cumple el [[Principio de conservación de la energía mecánica|principio de conservación de la energía mecánica]],

$$\Delta Em=0\qquad\qquad Em-Em_o=0$$

$$\frac{1}{2}mv^2-mgh=0$$

Despejando v

$$v=\sqrt{2gh}$$

Donde $h=20\operatorname{sen}30=10\ m$. Por tanto,

$$v=\sqrt{2gh}=\sqrt{2\cdot9{,}8\cdot10}=14\text{ m/s}$$

En cuanto a las variaciones de energía potencial y energía cinética,

$$\Delta Ep=\Delta Ec=mgh=\frac{1}{2}mv^2=9800\text{ J}$$

b) Si existiera rozamiento, una fuerza disipativa, el principio de conservación de la energía mecánica toma la forma

$$\Delta Em=W_{nc}$$

Donde W<sub>nc</sub> es el trabajo que realiza la fuerza de rozamiento. Este trabajo es energía que se pierde en forma de calor, es decir, la energía potencial inicial del cuerpo no se transforma completamente en energía cinética cuando llega al final del plano sino que parte de esta energía se ha disipado en forma de calor por el rozamiento entre el cuerpo y el suelo del plano. Según este razonamiento, la energía potencial inicial no cambia pero si la energía cinética en la situación final, que disminuye respecto del valor calculado. La disminución de esta energía cinética será el valor del trabajo no conservativo.

### Problema: Bloque y resorte en un plano inclinado

> [!question] Enunciado
> Un bloque de 0,2 kg, inicialmente en reposo, se deja deslizar por un plano inclinado que forma un ángulo de 30º con la horizontal. Tras recorrer 2 mm, queda unido al extremo libre de un resorte, de constante elástica 200 N·m⁻¹, paralelo al plano fijo por el otro extremo. El coeficiente de rozamiento del bloque con el plano es 0,2.
> a) Dibuja esquema todas las fuerzas que actúan sobre el bloque cuando comienza el descenso e indica el valor de cada una de ellas. ¿Con qué aceleración desciende el bloque?
> b) Explica los cambios de energía del bloque que inicia el descenso hasta que comprime el resorte, y calcula la máxima compresión de este.

a) El esquema de todas las fuerzas que actúan sobre el bloque cuando comienza el descenso aparece en la figura adjunta.

![[bloque-fuerzas.png|350]]

Se observa que sobre el bloque se ejercen tres fuerzas, la fuerza peso, la reacción normal del plano y la fuerza de rozamiento.

$$P_x=mg\cdot\operatorname{sen}30=0{,}2\cdot9{,}8\cdot\operatorname{sen}30=0{,}98\ N$$

$$N=P_y=mg\cos30=0{,}2\cdot9{,}8\cdot\cos30=1{,}70\ N$$

$$Fr=\mu N=0{,}2\cdot1{,}70=0{,}34\ N$$

Para determinar la aceleración de caída del bloque aplicamos la segunda ley de Newton en la dirección del movimiento,

$$\Sigma F_x=m\cdot a$$

$$P_x-F_r=m\cdot a\qquad0{,}98-0{,}34=0{,}2\cdot1\ \rightarrow\ a=3{,}2\ m/s^2$$

b) Sobre el cuerpo están actuando simultáneamente fuerzas conservativas y la fuerza de rozamiento (disipativa). En estas circunstancias se cumple que el trabajo que realiza la fuerza de rozamiento (W<sub>nc</sub>) es igual a la variación de energía mecánica:

$$W_{nc}=\Delta Em$$

Para desarrollar esta expresión debemos observar la siguiente figura que representa el punto inicial y final de este movimiento.

![[resorte-inicial.png|330]] ![[resorte-final.png|330]]

- Valoración energética de la situación inicial:

$$Em_i=Ep_g=mgh_i$$

En el estado inicial no hay energía cinética pues el móvil parte del reposo. Tampoco hay energía potencial elástica pues el resorte se encuentra en su posición de equilibrio.

- Valoración energética de la situación final:

$$Em_f=Ep_g+Ep_e=mgh_f+\frac{1}{2}Kx^2$$

En el estado final no hay energía cinética pues el móvil está en reposo. Existe en este estado energía potencial gravitatoria debido a que el cuerpo se encuentra a una altura h<sub>f</sub> respecto del origen de alturas. Además hay energía potencial elástica pues el resorte se ha alejado de su posición de equilibrio.

- Variación de energía mecánica:

$$\Delta Em=Em_f-Em_i=mgh_f+\frac{1}{2}Kx^2-mgh_i$$

$$\Delta Em=mg(h_f-h_i)+\frac{1}{2}Kx^2$$

Según se puede observar en la figura,

$$h_i-h_f=(2+x)\cdot\operatorname{sen}30$$

Por tanto,

$$\Delta Em=-mg(2+x)\operatorname{sen}30+\frac{1}{2}Kx^2$$

- Cálculo del trabajo de la fuerza de rozamiento:

$$W_{nc}=\vec{F}_R\cdot\Delta\vec{r}=F_R\,\Delta r\cos180=-F_R\,(2+x)$$

Durante la caída del cuerpo por el plano inclinado la energía potencial gravitatoria inicial del cuerpo se está transformando en energía cinética, el cuerpo va ganando velocidad hasta llegar al resorte donde convierte dicha energía cinética en energía potenical elástica. También parte de la energía potencial inicial se transforma en calor, debido al rozamiento del cuerpo con el plano inclinado. No toda la energía potencial inicial se transforma en energía potencial elásica pues el cuerpo no queda en el origen de alturas, es decir, aún le queda energía potencial gravitatoria.

El principio de conservación de la energía mecánica no se cumple cuando existen fuerzas no conservativas, sino que se cumple que

$$\Delta Em=W_{nc}$$

$$-mg(2+x)\operatorname{sen}30+\frac{1}{2}Kx^2=-F_R\,(2+x)$$

$$-0{,}2\cdot9{,}8\cdot(2+x)\cdot0{,}5+\frac{1}{2}\,200\,x^2=-0{,}34\cdot(2+x)$$

$$-0{,}98\cdot(2+x)+100\,x^2=-0{,}34\cdot(2+x)$$

$$100\,x^2-0{,}64\,x-1{,}28=0$$

Resolviendo esta ecuación cuadrática se obtiene como solución x = 0,12 m = 12 cm

### Problema: Caída y penetración en el suelo

> [!question] Enunciado
> Desde una altura de 50 m se deja caer un cuerpo de 500 g. Si al llegar al suelo penetra en este una distancia de 8 cm, calcula la resistencia media que ha ofrecido el suelo. ¿En qué se ha empleado la energía mecánica que poseía el cuerpo? Se desprecia la resistencia del aire

![[caida-suelo.png|200]]

<u>Inicialmente</u>

El cuerpo tiene energía potencial gravitatoria. No tiene energía cinética pues su velocidad inicial es cero, tal como menciona el enunciado).

$$Em_i=Ep_i=mgh$$

<u>Final</u>

El cuerpo ha transformado su energía potencial inicial en energía calorífica principalmente, es decir, la energía mecánica se ha invertido en vencer la fuerza de rozamiento durante 8 cm.

$$Em_f=0$$

Por tanto, la variación de energía potencial

$$\Delta Em=Em_f-Em_i=-mgh=-0{,}5\cdot9{,}8\cdot50{,}08=-245{,}5\ J$$

Al existir una fuerza no conservativa, la fuerza de resistencia del suelo,

$$\Delta Em=W_{nc}$$

Donde $W_{nc}$ es el trabajo que realiza la fuerza de resistencia,

$$W_{nc}=\vec{F}_R\Delta\vec{r}=F_R\,\Delta r\cos180=-F_R\,\Delta r=-0{,}08\,F_R$$

$$\Delta Em=W_{nc}\quad\rightarrow\quad-245{,}5=-0{,}08\,F_R$$

$$F_R=3067\ N$$

### Problema: Plano inclinado y aro circular

> [!question] Enunciado
> En lo alto de un plano de 2 m de altura y 30º de inclinación se coloca una masa de 0,5 kg. Al final del plano se encuentra un aro circular como indica la figura. En todo el recorrido no existe rozamiento. Calcula:
> a) La velocidad de la masa en los puntos A, B y C.
> b) ¿Desde qué altura sobre el plano se debe dejar caer la masa para que al llegar a C no ejerza ninguna fuerza sobre el aro?

![[plano-aro.png|550]]

Dado que no existe rozamiento, la caída del objeto por el plano se debe exclusivamente a una fuerza conservativa, la gravedad. En estas condiciones de cumple el principio de conservación de la energía mecánica,

$$\Delta Em=0$$

La aplicación de este principio al punto A,

$$Em_A-Em_o=0\quad\rightarrow\quad Ep_A+Ec_A-Ep_o-Ec_o=0$$

La energía cinética inicial (Ec<sub>o</sub>) es en todos los casos cero pues el cuerpo parte del reposo. La energía potencial en A (Ep<sub>A</sub>) es cero si consideramos que la base del plano inclinado es el origen de alturas. Por tanto,

$$Ec_A-Ep_o=0\ \rightarrow\ \frac{1}{2}mv_A^2-mgh_o=0\ \rightarrow\ v_A^2=\sqrt{2gh_o}=6{,}26\ m/s$$

En A toda la energía potencial inicial se ha convertido en energía cinética.

La aplicación del principio de conservación de la energía mecánica a B, teniendo en cuenta lo ya mencionado quedará,

$$Em_B-Em_o=0\quad\rightarrow\quad Ep_B+Ec_B-Ep_o=0$$

En B parte de la energía cinética que el cuerpo tenía en A se ha vuelto a convertir en energía potencial,

$$mgh_B+\frac{1}{2}mv_B^2-mgh_o=0\quad\rightarrow\quad v_B^2=\sqrt{2g(h_o-R)}=4{,}95\ m/s$$

El procedimiento en C es idéntico al caso anterior pero h<sub>C</sub> = 2R, por tanto,

$$v_C^2=\sqrt{2g(h_o-2R)}=3{,}13\ m/s$$

b) “Rizar el rizo”

![[aro-rizo.png|250]]

La velocidad mínima en C para no caer es tal que el cuerpo no “toca” el aro, es decir, no hay una fuerza normal del aro sobre el cuerpo. En estas condiciones, siendo un movimiento circular, la fuerza peso ejerce de fuerza central, es decir,

$$F_c=P\quad\rightarrow\quad ma_c=mg$$

$$\frac{v^2}{R}=g\quad\rightarrow\quad v=\sqrt{gR}=2{,}7\ m/s\ \ (=v_C)$$

Para que llegue al punto C con esa velocidad, haciendo las mismas consideraciones que en el apartado anterior, la altura a la que se debe dejar caer es,

$$Em_C-Em_o=0\quad\rightarrow\quad Ep_C+Ec_B-Ep_o=0$$

$$mgh_C+\frac{1}{2}mv_C^2-mgh_o=0\quad\rightarrow\quad h_o=2R+\frac{v_C^2}{2g}=1{,}87\ m$$

### Problema: Altura máxima de un lanzamiento vertical

> [!question] Enunciado
> Se lanza un cuerpo verticalmente hacia arriba desde la superficie de la Tierra con una velocidad de 4000 m/s. Calcula la altura máxima que alcanzará. (R<sub>T</sub> = 6400 km)

Si se desprecia la resistencia del aire entonces no existen fuerzas no conservativas, se cumple el principio de conservación de la energía mecánica,

$$\Delta Em=0\ \rightarrow\ Em-Em_o=0\ \rightarrow\ Em=Em_o$$

$$Ec+Ep=Ec_o+Ep_o$$

Supondremos que al alcanzar la altura máxima el cuerpo se para, es decir, Ec = 0. Además la velocidad a la que se lanza es elevada y el cuerpo alcanzará una altura considerable, es decir, la expresión de la [[Energía potencial gravitatoria|energía potencial]] del cuerpo será:

$$Ep=-G\,\frac{M_Tm}{r}$$

Donde M<sub>T</sub> representa la masa de la Tierra, m la masa del cuerpo, r la distancia del cuerpo al centro de la Tierra y G es la [[Constante de gravitación|constante de gravitación universal]]. Por tanto,

$$-G\,\frac{M_Tm}{R_T+h}=\frac{1}{2}mv_o^2-G\,\frac{M_Tm}{R_T}$$

La masa del cuerpo se simplifica, h representa la altura sobre la superficie de la Tierra a la que se encuentra el cuerpo (lo que se pide) y R<sub>T</sub> el radio de la Tierra,

$$-G\,\frac{M_T}{R_T+h}=\frac{1}{2}v_o^2-G\,\frac{M_T}{R_T}$$

En esta expresión todo es conocido excepto h, que despejado nos da un valor de

$$h=938900\text{ m}=938{,}9\text{ km}$$
