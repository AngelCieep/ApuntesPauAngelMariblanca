[[Índice - Electromagnetismo|← Electromagnetismo]]

## Inducción

En el tema dedicado al electromagnetismo se ha visto que una [[Experiencia de Oersted|corriente eléctrica crea un campo magnético]]. Podríamos preguntarnos si es posible el proceso inverso, esto es: ***crear una corriente eléctrica a partir de un campo magnético.***

***Michael Faraday*** (1791-1867) y ***Joseph Henry*** (1797-1878) llevaron a cabo diversos experimentos (hacia 1830) que permitieron dar respuesta a esta pregunta.

### Experiencia de Faraday

Fue Faraday quien comprobó que al acercar un imán a una espira en ésta se origina una corriente que invierte su sentido cuando el imán se aleja (ver figura).

![[e-faraday.png|250]]

Experiencia de Faraday. Al acercar o alejar un imán a una espira se induce en ésta una corriente eléctrica

Un dato importante es que ***la corriente aparece sólo cuando el imán está en movimiento respecto de la espira (puede moverse el imán o la espira, es igual) y cesa una vez que cesa el movimiento***. El origen de la corriente eléctrica, por tanto, no es la presencia de un campo magnético, ***sino la variación del campo que atraviesa la espira.***

Como se puede ver en la figura las líneas de fuerza del campo del imán están más juntas cerca de los polos (mayor intensidad) , y más separadas (menor intensidad) a medida que nos alejamos de ellos, con lo que al acercar o separar el imán de la espira se produce una variación del campo magnético que la atraviesa.

Otro dato experimental importante es que ***la intensidad de la corriente inducida depende de lo rápido que se mueva el imán respecto de la espira***. Esto indica una dependencia con ***la rapidez de variación del campo magnético.***

### Experiencia de Henry

Henry realizó, de forma simultánea con Faraday, una experiencia que permitió una mejor comprensión del fenómeno de la inducción de una corriente eléctrica a partir de un campo magnético.

La experiencia de Henry consistió en deslizar un conductor móvil sobre otro doblado en forma de U (ver figura), situado en el seno de un campo magnético constante y perpendicular a la dirección del movimiento. Como consecuencia del movimiento (y de la presencia del campo magnético) ***aparece una [[Fuerza de Lorentz|fuerza de Lorenz]] sobre las cargas libres del conductor (electrones)***. Por tanto, las cargas negativas se desplazan hacia el extremo derecho del conductor móvil, mientras que en el izquierdo se acumularán las positivas creándose una diferencia de potencial entre ambos extremos que hará que comience a circular una corriente por el circuito.

En la experiencia de Henry se induce una corriente de forma un tanto diferente a la de Faraday. Ahora el campo magnético es uniforme y lo que varía es el tamaño de "la espira" que forma el circuito.

![[e-henry.png|600]]

Comparando ambas experiencias podemos llegar a la conclusión de que ***lo que varía en ambas es la cantidad de líneas de campo que atraviesan el circuito en el que se induce la corriente.***

## Flujo magnético

Tratemos ahora de dar una formulación matemática a la conclusión que hemos extraído.

- Por convenio ***la intensidad del campo magnético se hace igual al número de líneas de campo que atraviesan la unidad de superficie colocada perpendicularmente a ellas.***
- Si queremos saber el número de líneas que atraviesan la superficie S, perpendicular a las líneas de campo, bastará multiplicar la intensidad por la superficie. Esta nueva magnitud recibe el nombre de ***flujo del campo magnético*** ($\varphi_B$):

$$\boxed{\varphi_B=B\,.\,S}$$

- Si la superficie no está colocada perpendicularmente a las líneas de campo, sino que forma con ellas cierto ángulo, el flujo magnético a través de esa superficie viene dado por:

$$\boxed{\varphi_B=B\,.\,S\,.\cos\alpha}$$

![[e-flujo.png|180]]

El ángulo es el formado por el vector campo magnético y la perpendicular a la superficie.

- ***La unidad S.I. de flujo magnético es el [[Tesla|tesla]] por metro cuadrado (T.m²) y recibe el nombre de weber (Wb)*** *en honor de* ***Wilhem Weber*** *(1804-1891)*
- La rapidez con que varía el flujo magnético a través de una superficie se puede poner en la forma: $\dfrac{\Delta\varphi}{\Delta t}$ En forma diferencial (variación infinitesimal del tiempo): $\dfrac{d\varphi}{dt}$

Utilizando el concepto de flujo, podremos decir:

> **Se induce una corriente eléctrica en un circuito si este es atravesado por un flujo magnético variable.**

## Ley de Lenz

En 1833 ***Heinrich Lenz (1804-1865)*** hizo una nueva contribución para la comprensión del fenómeno al descubrir la regla ***(Ley de Lenz)*** que permite establecer el sentido de la corriente inducida.

> **Ley de Lenz**
> ***El sentido de la corriente inducida es tal que se opone a la causa que la origina***

![[e-lenzfaraday.png|420]]

***En la experiencia de Faraday la causa*** que produce la corriente inducida cuando se acerca el imán es el ***aumento de la intensidad del campo magnético***. En este caso la corriente inducida es tal que tiende a crear ***un campo magnético contrario***, que hace que disminuya el campo inductor.

Cuando alejamos el imán se produce una ***disminución en la intensidad del campo***. La corriente que se induce tiene un sentido tal que ***origina un campo que refuerza al campo inductor.***

![[e-lenzhenry.png|400]]

***En la experiencia de Henry la causa*** que produce la corriente inducida es el ***desplazamiento del conductor*** (hacia la derecha en la figura) . En este caso la corriente inducida es tal que el campo magnético ejerce sobre las cargas que circulan por el conductor móvil u***na fuerza que tiene a dificultar su desplazamiento*** (hacia la izquierda en la figura)

La Ley de Lenz puede reformularse, teniendo en cuenta el concepto de flujo, en la forma siguiente:

> El sentido de la corriente inducida es tal que siempre ***se opone a la variación del flujo que la produce.*** Esto es:
> - Si la corriente se induce debido a ***un aumento del flujo magnético,*** el sentido de la corriente será el que genere ***un campo magnético opuesto al campo inductor*** (produciendo de esta manera un campo más pequeño y una disminución del flujo).
> - Si la corriente se induce debido a ***una disminución del flujo magnético,*** el sentido de la corriente será el que genere ***un campo magnético del mismo sentido que el campo inductor*** (produciendo de esta manera un reforzamiento del campo y un aumento del flujo).

## Ley de Faraday-Henry

La relación matemática entre la fuerza electromotriz inducida y la variación del flujo magnético que atraviesa el circuito se recoge en la ***ley de Faraday-Henry*** :

![[e-espirasale.png|230]]

> **Ley de Faraday-Henry**
> ***La fuerza electromotriz inducida es igual, y de signo contrario, a la rapidez con que varía el flujo magnético.***

$$\boxed{\varepsilon=-\frac{\Delta\varphi}{\Delta t}}$$

> ***Para una variación de flujo no uniforme la fuerza electromotriz viene dada por menos la derivada del flujo respecto del tiempo:***

$$\boxed{\varepsilon=-\frac{d\varphi}{dt}}$$

En el caso del experimento de Henry, suponiendo que el conductor se desplaza con una velocidad constante, v, la variación de flujo podría calcularse de la forma siguiente:

![[e-henryflujo.png|320]]

$$\varphi_1=B\,S_1$$

$$\varphi_2=B\,S_2=B\,\left[S_1-L\,(v\,t)\right]$$

$$\Delta\varphi=\varphi_2-\varphi_1=B\,\left[S_1-L\,(v\,t)\right]-B\,S_1=-B\,L\,(v\,t)$$

$$\frac{\Delta\varphi}{\Delta t}=-\frac{B\,L\,(v\,t)}{t}=-B\,L\,v$$

$$\varepsilon=-\frac{\Delta\varphi}{\Delta t}=B\,L\,v$$

Aplicando la ley de Ohm generalizada podemos obtener la intensidad que circula. Suponiendo que la resistencia del circuito es R:

$$V_A-V_B=\Sigma\,I\,(R+r)-\Sigma\,\varepsilon$$

$$0=IR-\varepsilon$$

$$I=\frac{\varepsilon}{R}=\frac{B\,L\,v}{R}$$

## Alternador

La manera más corriente de producir una corriente eléctrica es haciendo girar una espira (realmente una bobina) en un campo magnético. El flujo variable que atraviesa la espira produce una corriente eléctrica que cambia continuamente su polaridad. El dispositivo recibe el nombre de ***alternador.***

![[e-alternador.png|250]]

En la figura de la derecha se ve una espira que gira con velocidad angular constante en el seno de un campo magnético. El flujo que atraviesa la espira variará en función del ángulo que forme con el campo magnético. Si suponemos que para t =0 la espira está perpendicular al campo ( $\alpha=0$) :

$$\left.\begin{array}{l}\varphi=B\,S\cos\alpha\\\alpha=\omega\,t\end{array}\right\}\ \varphi=B\,S\cos(\omega\,t)=\varphi_{MAX}\cos(\omega\,t)$$

Aplicando la ley de Faraday-Henry la f.e.m. valdrá:

$$\boxed{\varepsilon=-\frac{d\varphi}{dt}=B\,S\,\omega\operatorname{sen}(\omega t)=\varepsilon_{MAX}\operatorname{sen}(\omega t)}$$

La f.e.m. varía senoidalmente desde el valor cero inicial hasta su valor máximo ( $\varepsilon_{MAX}=B\,S\,\omega$ ) para disminuir nuevamente hasta cero, tomar valores negativos y volver a anularse. La intensidad cambia de sentido continuamente ***(corriente alterna)*** siendo su frecuencia (en Hz):

$$\omega=2\pi f\ ;\quad f=\frac{\omega}{2\pi}$$

![[e-senoide.png|600]]

La intensidad que circula por la espira se puede calcular si aplicamos la ley de Ohm generalizada al circuito Si suponemos que la resistencia es R:

$$V_A-V_B=\Sigma\,I(R+r)-\Sigma\,\varepsilon$$

$$0=I\,R-\varepsilon$$

$$\boxed{I=\frac{\varepsilon}{R}}$$

## Dinamo

Un alternador se puede modificar para que la corriente obtenida sea continua, en este caso recibe el nombre de ***dinamo.***

![[e-dinamo.png|420]]

En una dinamo se consigue que la corriente circule siempre en el mismo sentido gracias a dos semianillos partidos llamados ***conmutadores***

<small>Procedencia (FisQuiWeb) · CC BY-NC-SA</small>

## Ejercicios PAU

**Cuestiones:** [[Ejercicios - Inducción electromagnética#E-2|E-2]] · [[Ejercicios - Inducción electromagnética#E-7|E-7]] · [[Ejercicios - Inducción electromagnética#E-17|E-17]] · [[Ejercicios - Inducción electromagnética#E-24|E-24]] · [[Ejercicios - Inducción electromagnética#E-33|E-33]] · [[Ejercicios - Inducción electromagnética#E-34|E-34]] · [[Ejercicios - Inducción electromagnética#E-49|E-49]] · [[Ejercicios - Inducción electromagnética#E-63|E-63]] · [[Ejercicios - Inducción electromagnética#E-67|E-67]] · [[Ejercicios - Inducción electromagnética#E-79|E-79]] · [[Ejercicios - Inducción electromagnética#E-104|E-104]] · [[Ejercicios - Inducción electromagnética#E-108|E-108]] · [[Ejercicios - Inducción electromagnética#E-111|E-111]] · [[Ejercicios - Inducción electromagnética#E-115|E-115]] · [[Ejercicios - Inducción electromagnética#E-118|E-118]] · [[Ejercicios - Inducción electromagnética#E-123|E-123]] · [[Ejercicios - Inducción electromagnética#E-130|E-130]]

**Problemas:** [[Ejercicios - Inducción electromagnética#E-31|E-31]] · [[Ejercicios - Inducción electromagnética#E-37|E-37]] · [[Ejercicios - Inducción electromagnética#E-57|E-57]] · [[Ejercicios - Inducción electromagnética#E-86|E-86]]
