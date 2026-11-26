[[Índice - Campo gravitatorio|← Campo gravitatorio]]

## 1) Leyes de Kepler

Las leyes de Kepler fueron enunciadas por Johannes Kepler (principios siglo XVII) para describir matemáticamente el movimiento de los planetas en sus órbitas alrededor del Sol.

Se trata de tres leyes empíricas, es decir, son resultado del descubrimiento de regularidades en una serie de datos empíricos, concretamente en los datos de observación de la posición de los planetas realizados por Tycho Brahe.

Todos los cuerpos en órbita alrededor de otro cuerpo cumplen las leyes, es decir, no solamente se pueden aplicar a los planetas del sistema solar sino a otros sistemas planetarios, estrellas orbitando a otras estrellas, satélites orbitando sobre planetas, etc.

Aunque Kepler no enunció sus leyes en el mismo orden, en la actualidad las leyes se numeran como sigue a continuación.

### Primera ley: ley de las órbitas

> *Los planetas giran alrededor del Sol describiendo órbitas elípticas en uno de cuyos focos se encuentra el Sol.*

![[kepler-orbita.png|350]]

![[kepler-perihelio-afelio.png|350]]

#### Excentricidad

El parámetro que da una idea del mayor o menor alejamiento de una elipse dada respecto de la circunferencia es la excentricidad (*e*). Para una elipse viene dada por la expresión

![[kepler-elipse.png|300]]

$$e=\sqrt{1-\frac{b^2}{a^2}}$$

Donde *b* es el semieje menor de la elipse y *a* el semieje mayor.

- En la circunferencia $a=b$, entonces $e=0$
- En la elipse $b<a$, entonces $0<e<1$

Las excentricidades de las órbitas de los planetas del sistema solar son

| Planetas | Planetas enanos |
| :---: | :---: |
| Mercurio 0,206 | Ceres 0,080 |
| Venus 0,007 | Plutón 0,249 |
| Tierra 0,017 | Eris 0,442 |
| Marte 0,093 | Makemake 0,159 |
| Júpiter 0,048 | Haumea, ¿? |
| Saturno 0,0541 | |
| Urano 0,047 | |
| Neptuno 0,009 | |

### Segunda ley: ley de las áreas

> *Las áreas barridas por el radio vector que une el Sol con un planeta son directamente proporcionales a los tiempos empleados en barrerlas.*
>
> --------
>
> *El radio vector que une un planeta y el Sol barre áreas iguales en tiempos iguales*

![[kepler-areas.png|450]]

Consecuencia: la velocidad de un cuerpo en órbita no es constante, es mayor cuando se encuentra en el perihelio que cuando está en el afelio. Por tanto, cuando se considere constante la velocidad de un objeto en órbita –movimiento circular uniforme– se está haciendo una aproximación si su órbita es elíptica. Esta aproximación será tanto mejor cuanto menor sea la [[Excentricidad|excentricidad]] de la órbita. Solamente en una órbita circular se puede considera como constante la velocidad orbital.

### Tercera ley: ley de los periodos

> *Los cuadrados de los periodos de revolución son directamente proporcionales a los cubos de los semiejes mayores de las respectivas órbitas*

![[kepler-periodos.png|350]]

Supongamos dos planetas, P<sub>1</sub> y P<sub>2</sub> que describen dos órbitas con periodos respectivos T<sub>1</sub> y T<sub>2</sub> (figura adjunta). Según la tercera ley de Kepler se cumple que:

$$\frac{T_1^2}{r_1^3}=\frac{T_2^2}{r_2^3}$$

La principal consecuencia en el siglo XVII de esta ley es que permitió dar dimensiones al sistema solar. En efecto, si consideramos como 1 la distancia entre la Tierra y el Sol (1 unidad astronómica, aproximadamente igual a 150 millones de kilómetros, valor no conocido en el siglo XVII), dado que se conoce el periodo de revolución de la Tierra, podemos conocer la distancia de cualquier planeta al Sol en unidades astronómicas sin más que conocer el periodo de revolución de dicho planeta, valor que se conoce de la observación astronómica del mismo. Por ejemplo, si el periodo de revolución aproximado del planeta Júpiter es de 11 años y 315 días,

$$11\text{ años},315\text{ días}=11+\frac{315}{365{,}25}=11{,}86\text{ años}$$

$$\frac{1^2}{1^3}=\frac{11{,}86^2}{r_{\text{Júpiter}}^3}$$

$$r_{\text{Júpiter}}=\sqrt[3]{11{,}86^2}=5{,}2\text{ unidades astronómicas}$$

## 2) Ley de la gravitación universal

① A partir de las [[Leyes de Kepler|leyes enunciadas por Kepler]], Isaac Newton dedujo la ley de gravitación universal. Se trata pues de una ley deductiva.

② La ley de gravitación de Newton puede enunciarse así:

> *Toda partícula material atrae a cualquier otra partícula material con una fuerza directamente proporcional al producto de las masas de ambas e inversamente proporcional al cuadrado de la distancia que las separa.*

$$F=G\,\frac{m_1m_2}{r^2}$$

Siendo m<sub>1</sub> y m<sub>2</sub> sus masas; r la distancia entre ellas y G una constante universal que recibe el nombre de **[[Constante de gravitación|constante de gravitación]].**

![[gravitacion-fuerzas.png|350]]

Su expresión en forma vectorial es:

$$\vec{F}=-G\,\frac{m_1\,m_2}{r^2}\,\overrightarrow{u_r}$$

Siendo $\overrightarrow{u_r}$ un vector unitario cuya dirección es la recta que une los centros de las dos partículas que se atraen y cuyo sentido va dirigido desde la partícula que origina la fuerza hacia fuera. Este sentido dado al vector unitario es el que explica la aparición del signo negativo en la expresión vectorial ya que el sentido de la fuerza gravitatoria será contrario al vector unitario que le corresponda.

En la figura anterior se puede observar que las fuerzas gravitatorias que actúan sobre cada una de las partículas son fuerzas de acción y reacción (tercer principio de la Dinámica) y, por tanto, tienen el mismo valor, son de sentidos contrarios y sus líneas de acción coinciden con la recta que las une.

### La constante de gravitación, G

Se trata de una constante universal, es decir, su valor es el mismo en cualquier parte del universo (conocido) e independiente del medio en el que se encuentren los cuerpos.

Newton no determinó el valor de esta constante ya que la formulación de la ley tal como lo hizo difiere de la formulación que se hace actualmente y que se está viendo aquí. El valor de G es

$$G=6{,}670\cdot10^{-11}\ \frac{N\cdot m^2}{kg^2}$$

El sentido físico de este valor: es la fuerza con que se atraen dos masas de 1 kg situadas a una distancia de un metro.

### Dos problemas resueltos

#### Problema: Masa de la Tierra

> [!question] Enunciado
> Calcula la masa de la Tierra a partir del peso de los cuerpos en su superficie. El radio de la Tierra es de 6380 kilómetros.

El peso de un cuerpo de masa m situado en la superficie del planeta es la fuerza con que la Tierra lo atrae. En módulo su valor es, según la [[Ley de la gravitación universal|ley de gravitación universal]]

$$F=G\,\frac{M_T\,m}{R_T^2}$$

Donde M<sub>T</sub> es la masa de la Tierra y R<sub>T</sub> es el radio del planeta.

Por otra parte, podemos aplicar la segunda ley de Newton teniendo en cuenta que la aceleración de caída de los cuerpos en la superficie de la Tierra es g.

$$F=m\cdot a=mg$$

Como ambas fuerzas son iguales,

$$mg=G\,\frac{M_T\,m}{R_T^2}$$

Despejando la masa de la Tierra

$$M_T=\frac{g\,R_T^2}{G}=\frac{9{,}8\cdot6{,}38\cdot10^{6}}{6.67\cdot10^{-11}}=5{,}98\cdot10^{24}\ kg$$

#### Problema: Masa del Sol

> [!question] Enunciado
> Calcula la masa del Sol a partir del periodo de traslación de la Tierra. Distancia entre la Tierra y el Sol, 149 millones de kilómetros.

![[gravitacion-orbita-tierra.png|250]]

La fuerza que ejerce el Sol sobre la Tierra es, según la [[Ley de la gravitación universal|ley de la gravitación universal]] (en módulo)

$$F=G\,\frac{M_T\,M_s}{R^2}$$

Donde M<sub>T</sub> es la masa de la Tierra, M<sub>s</sub> es la masa del Sol y R es la distancia entre la Tierra y el Sol.

Por otra parte, el movimiento de la Tierra alrededor de Sol es un movimiento circular resultado de una fuerza central o centrípeta cuya expresión es según la segunda ley de Newton

$$F=M_T\cdot a_c$$

Donde la aceleración centrípeta es

$$a_c=\frac{v^2}{R}$$

En esta expresión v representa la velocidad en de la Tierra en órbita alrededor del Sol. Suponiendo, como venimos haciendo, que se trata de un movimiento circular uniforme,

$$a_c=\frac{v^2}{R}=\frac{\omega^2R^2}{R}=\omega^2R=\left(\frac{2\pi}{T}\right)^2R=\frac{4\pi^2R}{T^2}$$

Por tanto,

$$F=M_T\cdot\frac{4\pi^2R}{T^2}$$

Como ambas fuerzas son iguales

$$G\,\frac{M_T\,M_s}{R^2}=M_T\cdot\frac{4\pi^2R}{T^2}$$

Despejando la masa del Sol,

$$M_s=\frac{4\pi^2R^3}{GT^2}=\frac{4\pi^2\cdot(1{,}49\cdot10^{11})^3}{6{,}67\cdot10^{-11}\cdot(3{,}156\cdot10^{7})^2}=1.99\cdot10^{30}kg$$

Este procedimiento se puede utilizar para calcular la masa de cualquier planeta con satélites sin más que conocer su periodo de revolución de alguno de esos satélites alrededor del planeta (dato que se obtiene de la observación).

## Ejercicios PAU

**Cuestiones:** [[Ejercicios - Leyes de Kepler y gravitación universal#G-15|G-15]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-25|G-25]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-28|G-28]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-30|G-30]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-38|G-38]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-50|G-50]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-54|G-54]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-63|G-63]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-68|G-68]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-79|G-79]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-88|G-88]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-98|G-98]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-103|G-103]]

**Problemas:** [[Ejercicios - Leyes de Kepler y gravitación universal#G-3|G-3]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-8|G-8]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-42|G-42]] · [[Ejercicios - Leyes de Kepler y gravitación universal#G-60|G-60]]

**También relacionados:** [[Ejercicios - Satélites, órbitas y velocidad de escape#G-2|G-2]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-12|G-12]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-17|G-17]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-20|G-20]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-31|G-31]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-53|G-53]] · [[Ejercicios - Campo e intensidad gravitatoria#G-64|G-64]] · [[Ejercicios - Satélites, órbitas y velocidad de escape#G-69|G-69]] · [[Ejercicios - Campo e intensidad gravitatoria#G-82|G-82]]
