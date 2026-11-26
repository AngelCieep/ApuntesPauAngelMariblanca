# Apuntes de Física PAU

Apuntes de Física (2º de Bachillerato / PAU) organizados como vault de [Obsidian](https://obsidian.md), con estilo wiki: texto seguido por bloques y enlaces a cada concepto.

> Para verlos correctamente, abre la carpeta como vault en Obsidian. GitHub no interpreta los enlaces `[[ ]]` ni las notas incrustadas `![[ ]]`.

## Estructura

```
├── index.md                  ← punto de entrada
├── README.md                 ← directrices y formato
├── _src/                     ← PDF originales
├── .obsidian/snippets/       ← hoja.css
├── 01 Campo gravitatorio/
│   ├── Índice - Campo gravitatorio.md
│   ├── Temario/              ← bloques de teoría
│   ├── Conceptos/            ← accesos a conceptos
│   ├── Problemas/            ← accesos a problemas resueltos
│   └── Imágenes/
└── 02 Electromagnetismo/
    └── (misma estructura)
```

## Directrices de contenido

1. **Mismas palabras que el original.** Se reorganiza el contenido; no se resume ni se reescribe.
2. **Mismo orden que los PDF.**
3. **Toda la teoría vive en el bloque.** Cada texto existe en un solo sitio.
4. **Las notas de concepto y problema no tienen texto propio:** solo incrustan su apartado del bloque.
5. **Sin cadenas de notas:** un bloque no incrusta otras notas.
6. **Enlazar los conceptos** cuando se mencionan, sin cambiar el texto.
7. **Erratas del original:** se conservan y se anotan en [Erratas detectadas](#erratas-detectadas).
8. **Añadidos permitidos:** títulos, enlaces e imágenes necesarios para organizar.

## Nombres de archivo

| Tipo | Formato | Ejemplo |
|---|---|---|
| Índice de tema | `Índice - Tema.md` | `Índice - Campo gravitatorio.md` |
| Bloque | `NN - Nombre.md` | `01 - Leyes de Kepler y gravitación universal.md` |
| Concepto | `Nombre.md` | `Excentricidad.md` |
| Problema | `Problema - Nombre.md` | `Problema - Masa del Sol.md` |
| Imagen | `minusculas-con-guiones.png` | `kepler-areas.png` |

Los nombres no deben repetirse dentro del vault.

## Formato

### Bloque

La primera línea es el enlace de vuelta al índice:

```markdown
[[Índice - Campo gravitatorio|← Campo gravitatorio]]
```

| Elemento | Formato |
|---|---|
| Apartado principal | `## 1) Título` |
| Subapartado | `### Título` |
| Detalle | `#### Título` |
| Ley o definición destacada | `> *texto*` |
| Fórmula en bloque | `$$ ... $$` |
| Fórmula en línea | `$ ... $` |
| Subíndice en el texto | `m<sub>1</sub>` |
| Imagen | `![[nombre.png\|350]]` |
| Decimales en fórmulas | `6{,}67` |

Enunciado de un problema:

```markdown
### Problema: Nombre

> [!question] Enunciado
> Texto del enunciado.
```

Los problemas van bajo un título propio para que no se incluyan al incrustar un concepto de teoría.

### Nota de concepto

Contiene una sola línea:

```markdown
![[01 - Leyes de Kepler y gravitación universal#Excentricidad]]
```

El título debe coincidir con el del bloque. Al incrustar un título se incluyen sus subapartados.

### Enlaces

```markdown
[[Excentricidad|excentricidad]]
```

## Estilo visual

El archivo `.obsidian/snippets/hoja.css` muestra las notas como una hoja, con colores por nivel de título y fondo en las fórmulas.

1. `Ajustes → Apariencia → Fragmentos CSS` → activar `hoja`.
2. `Ajustes → Editor` → activar la longitud de línea legible.
3. Leer en modo lectura (`Ctrl+E`).

## Ejercicios PAU

- Cada tema tiene su carpeta `Ejercicios/`, con un archivo `Ejercicios - <bloque>.md` por bloque.
- Cada ejercicio es un recorte del PDF original (en `Ejercicios/Imágenes/`), con la solución plegada.
- Numeración del PDF: `G-` gravitatorio, `E-` electromagnetismo. El PDF de gravitatorio repite el 113 (`G-113bis`) y el de electromagnetismo no tiene 83.
- Cada bloque termina en `## Ejercicios PAU`, con enlaces a sus ejercicios y a los relacionados.
- La clasificación por bloque es manual y orientativa.

## Estado

| Contenido | Estado |
|---|---|
| Gravitatorio: bloques 01–07 | Hecho |
| Electromagnetismo: bloques 01–07 | Hecho |
| Ejercicios PAU por bloque (245) | Hecho |
| Resúmenes de fórmulas | Pendiente |
| Revisión de las notas contra los PDF | Pendiente |

En electromagnetismo, muchos esquemas con rótulos se han recortado como imagen; su texto no aparece en el buscador de Obsidian.

## Erratas detectadas

Páginas de `Campogravitatorio.pdf`.

| Pág. | Errata |
|---|---|
| 3 | "se puede considera" (en el apartado de la segunda ley) |
| 5 | En la masa de la Tierra falta elevar al cuadrado el radio en la sustitución |
| 5 | "velocidad en de la Tierra" |
| 6 | Con los datos dados, la masa del Sol es ≈ 1,97·10³⁰ kg, no 1,99·10³⁰ |
| 8 | La unidad N·kg se ve sin el signo del exponente; se escribe N·kg⁻¹ |
| 9 | En g₂ aparece r₁ en lugar de r₂ |
| 12 | Llama t²ᵀ al instante; es tᵀ |
| 13 | "ya" en lugar de yₐ, y "entre por dicha fuerza" |
| 14 | Al caer el cuerpo, el último trabajo debería ser de *b* a *a* |
| 18 | Falta un signo menos en la segunda igualdad de −ΔEp y se mezclan m y m₂ |
| 23 | "Tras recorrer 2 mm" en el enunciado; la resolución usa 2 m |
| 24 | "0,98 − 0,34 = 0,2·1" debería ser 0,2·a; "potenical" |
| 25 | "elásica" (elástica); 0,5·9,8·50,08 ≈ 245,4, no 245,5 |
| 26–27 | "de cumple"; vA², vB² y vC² se igualan a la raíz (es v, sin cuadrado) |
| 27 | En la ecuación del punto C aparece EcB en lugar de EcC |
| 30 | "bien dada" (viene dada) |
| 32 | "densiad" |
| 33–34 | "potenical", "respresenta" |
| 35 | "raiz cuadrada de la altura": depende de la distancia al centro (R_T + h); "se también" |
| 36–37 | "menor menos negativa"; "Exprexión" |
| 38–39 | "Dependiento"; "pues Fue" |
| 40–41 | "u.n"; "Em = =" (en las notas se escribe un solo =); "requierirá" |
| 43 | "con es Sol" |

Páginas de `Electromagnetismo.pdf`.

| Pág. | Errata |
|---|---|
| 1 | "alguna cosas"; "Carga de lo cuerpos" |
| 2 | "con un constante" |
| 7 | "es un distribución" |
| 8 | "distancia el eje" |
| 10 | "Ep- 0,6 J" (falta el signo =) |
| 12–13 | "extremos de imán"; "del primen al segundo" |
| 15 | "Si ocurre los contrario" |
| 18–19 | "su comportamientos"; "un espira" |
| 20 | Revisar: en el centro de un solenoide largo B = NμI/L; NμI/2L corresponde a los extremos |
| 22 | "se crearan" |
| 24–26 | "Lorenz" (Lorentz); "Wilhem"; "tiene a dificultar" (tiende) |
| 25–26 | Al convertir las páginas a imagen no se ve la Δ; en las notas se escribe Δφ/Δt |

## Fuentes y créditos

El contenido pertenece a sus autores originales.

| Material | Autoría indicada | Licencia indicada |
|---|---|---|
| `Campogravitatorio.pdf` | Felipe Moreno Romero ([escritoscientificos.es](http://www.escritoscientificos.es)); los anexos finales pueden tener otra procedencia | CC BY-NC-SA 3.0 ES (pág. 28) |
| `Electromagnetismo.pdf` | IES El Clot; procedencia FisQuiWeb | Creative Commons (ver pág. 27) |
| Resúmenes y ejercicios PAU | [www.uv.es/jmarques](http://www.uv.es/jmarques) | Revisar antes de redistribuir |
