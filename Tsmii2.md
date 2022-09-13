#  Practica de documentación en Markdown


| Código | Description |
| ------:| ----------- |
| **TSR-2023-I** | Tarea 01 |


## Contenido

- [Introducción](#introduccion)
- [Desarrollo](#desarrollo)
- [Autor](#autor)
- [Conclusiones](#Conclusiones)
- [Referencias](#referencias)

## Introducción


proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


## Desarrollo

Para consultar el formato a este documento, visitar [Markdown 101](https://github.com/decidim-archive/docs-template/blob/master/es/markdown-101.md).
ver en [texto plano](https://raw.githubusercontent.com/decidim-archive/docs-template/master/es/markdown-101.md)


Bloques de cita

> "If it weren't for my lawyer, I'd still be in prison.
>  It went a lot faster with two people digging."
>
> --- Joe Martin

Bloque de cita con vínculo de referencia. 

> Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
> tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. 
>
> At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
> no sea takimata sanctus est Lorem ipsum dolor sit amet[^1]. ← ***nota al pie insertada*** 

vinculo a otro [documento](/docs/document-template.md) en el repositorio (_ruta relativa_).

Imágenes

![Markdown Guide](/images/markdown-logo.png) Markdown Guide [Basic Syntax](https://www.markdownguide.org/basic-syntax/), [Extended Syntax](https://www.markdownguide.org/extended-syntax/)


***Bloques de código***

Bloques de código "cercados"

```
Texto de ejemplo aquí...
```

De acuerdo a la sintaxis del lenguaje de programación, ver más [información](https://docs.github.com/es/github/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks).

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

**Expresiones Matemáticas**

Para permitir una comunicación clara de expresiones matemáticas, GitHub admite expresiones matemáticas con formato LaTeX dentro de Markdown. Para obtener más información, consulte [LaTeX/Mathematics](http://en.wikibooks.org/wiki/LaTeX/Mathematics) en Wikibooks.

La capacidad de representación matemática de GitHub usa MathJax; un motor de visualización de código abierto basado en JavaScript. MathJax admite una amplia gama de macros LaTeX y varias extensiones de accesibilidad útiles. Para obtener más información, consulte [la documentación de MathJax](http://docs.mathjax.org/en/latest/input/tex/index.html#tex-and-latex-support) y la [documentación de extensiones de accesibilidad de MathJax](https://mathjax.github.io/MathJax-a11y/docs/#reader-guide).

La representación de expresiones matemáticas está disponible en Propuestas de GitHub, discusiones de GitHub, solicitudes de incorporación de cambios, wikis y archivos Markdown.


**Escribir expresiones en línea**
---

Para incluir una expresión matemática en línea con su texto, delimite la expresión con un símbolo de dólar $.

El siguiente ejemplo muestra como se visualiza la expresión `$\sqrt{3x-1}+(1+x)^2$` dentro de una cita:

> Esta oración usa delimitadores `$` para mostrar matemáticas en línea: $\sqrt{3x-1}+(1+x)^2$


**Escribir expresiones como bloque**
---

Para agregar una expresión matemática como un bloque, comience una nueva línea y delimite la expresión con dos símbolos de dólar $$.

```latex
$$ P(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{\frac{-(x-\mu)^2}{2\sigma^2}} $$
```

Se visualiza como:

$$ P(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{\frac{-(x-\mu)^2}{2\sigma^2}} $$


Otros ejemplos:

```latex
$$
\mathbb{R} \ =\ \begin{bmatrix}
n & o & a
\end{bmatrix} \ =\ \begin{bmatrix}
n_{x} & o_{x} & a_{x}\\
n_{y} & o_{y} & a_{y}\\
n_{z} & o_{z} & a_{z}
\end{bmatrix}
$$
```

se visualiza como:

$$
\mathbb{R} \ =\ \begin{bmatrix}
n & o & a
\end{bmatrix} \ =\ \begin{bmatrix}
n_{x} & o_{x} & a_{x}\\
n_{y} & o_{y} & a_{y}\\
n_{z} & o_{z} & a_{z}
\end{bmatrix}
$$

Ejemplo de inserción de **expresiones matemáticas** dentro del **texto de una cita** con **nota al pie**:

**Convertir un cuaternión en una matriz de rotación**

> Dado un cuaternión $q=(q_{0}, q_{1} i, q_{2} j, q_{3} k)$, puede encontrar la matriz de rotación tridimensional correspondiente utilizando la siguiente fórmula[^2]. ← ***nota al pie insertada***
>
> $$
> \begin{equation}
> \mathbb{R}( Q) =\begin{bmatrix}
> 2\left( q_{0}^{2} +q_{1}^{2}\right) -1 & 2( q_{1} q_{2} -q_{0} q_{3}) & 2( q_{1} q_{3} +q_{0} q_{2})\\
> 2( q_{1} q_{2} +q_{0} q_{3}) & 2\left( q_{0}^{2} +q_{2}^{2}\right) -1 & 2( q_{2} q_{3} -q_{0} q_{1})\\
> 2( q_{1} q_{3} -q_{0} q_{2}) & 2( q_{2} q_{3} +q_{0} q_{1}) & 2\left( q_{0}^{2} +q_{3}^{2}\right) -1
> \end{bmatrix}
> \end{equation}
> $$
>

**Youtube videos**

[![Markdown, Curso Práctico para principiantes y desarrolladores](https://img.youtube.com/vi/oxaH9CFpeEE/0.jpg)](https://www.youtube.com/watch?v=oxaH9CFpeEE)

## Conclusiones

Conclusiones o cierre al trabajo realizado.

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
no sea takimata sanctus est Lorem ipsum dolor sit amet[^3]. ← ***nota al pie insertada en el párrafo***. 

## Autor

***[Nombre del autor o listado de los integrantes del equipo]***

**Autor**  Sanchez Espinosa Miguel Angel [GitHub profile](https://github.com/rivascf)


## Referencias

Se pueden agregar notas al pie (cómo pudiste notar en las líneas marcadas como *"nota al pie insertada"*) en este documento, utilizando la siguiente sintaxis de corchetes:

```text
Esta es una nota al pie sencilla[^1].

Una nota al pie también puede tener múltiples líneas multiple lines[^2].  

También puede usar palabras, para adaptarse mejor a su estilo de escritura.[^nota].

[^1]: I.A. Glover and P.M. Grant, Digital Communications, 3rd ed. Harlow: Prentice Hall, 2009.
[^2]: . B. Kuipers, [Quaternions and rotation sequences](https://amzn.to/2RY2lwI). 
  Princeton, NJ: Princeton University Press, 2002. (Chapter 5,  Section 5.14 “Quaternions to Matrices”, pg. 125)

Tome en cuenta que cada línea nueva debe ir precedida de 2 espacios, permitiendo tener una nota al pie con varias líneas.

[^nota]:
	Las notas al pie de página identificadas con nombre aún se representarán con números en lugar del texto pero, permitirán una identificación y vinculación más sencillas.
	Esta nota al pie también se ha realizado con una sintaxis diferente, usando 4 espacios en lugar de 2 para cada línea nueva.
```

**Notas**

Para el desarrollo de documentos dentro del grupo y la asignatura, se usa el formato **IEEE**.[^nota] ← ***insertada al pie del documento con el no. 4***

**Nota simple** insertada en la posición del texto dónde se introdujo.

> **_Nota:_** La posición de una nota al pie en el archivo de markdown no influencia el cómo se interpretará la nota al pie. 
> Se puede escribir una nota al pie inmediatamente después de insertar la referenciarla y aún así **se mostrará en la parte inferior del archivo**.

Para conocer más acerca del formato de **Markdown** con la personalización de GitHub se pude consultar la [documentación de GitHub](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github).

[^nota]:
    Listado de referencias documentales consultadas para realizar el trabajo, consultar el siguiente [vínculo](https://www.bath.ac.uk/publications/library-guides-to-citing-referencing/attachments/ieee-style-guide.pdf) para el formato de referencia estilo **IEEE**.
    > `[^Num Ref]` Iniciales del autor. Apellido del autor, Título del libro, edicion (si no es la primera).
	>
    > Lugar de publicación: Publicador, Año.

[^1]: I.A. Glover and P.M. Grant, Digital Communications, 3rd ed. Harlow: Prentice Hall, 2009. 

[^2]: J. B. Kuipers, [Quaternions and rotation sequences](https://amzn.to/2RY2lwI). 
  Princeton, NJ: Princeton University Press, 2002. (Chapter 5,  Section 5.14 “Quaternions to Matrices”, pg. 125)

[^3]: H.-L. Pham, V. Perdereau, B. Adorno, en P. Fraisse, 
  “Position and Orientation Control of Robot Manipulators Using Dual Quaternion Feedback”, 11 2010, bll 658–663. 
  <https://www.researchgate.net/publication/224200087_Position_and_Orientation_Control_of_Robot_Manipulators_Using_Dual_Quaternion_Feedback>