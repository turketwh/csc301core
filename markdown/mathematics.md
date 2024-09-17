# Writing Mathematics In Markdown Documents

Github supports inclusion of a special language in the *markdown* (`.md`) files that the projects for this course are using. This language provides for clean rendering of potentially complex mathematics. The language is a component of *Latex*, is typeset by *MathJax*, and the browser displays the typeset mathematics.  Other tools you may use, like Google Colab or Jupyter notebooks, offer similar support.

Here is an example: 

$T(n) = 2T(\frac{n}{2}) + n^{2}$

To include Latex in a markdown document, put the latex in between two dollar signs: `$...$`. Don't include the `...` - that is just to show that Latex content goes between the dollar signs.

Key Latex components you may to make use of  in this course are in the table below.

|      Description      | Latex in `$ $`       | Output             |
| :-------------------: | -------------------- | ------------------ |
|      Superscript      | `$x^{n}$`            | $x^{n}$            |
|       Subscript       | `$x_{i}$`            | $x_{i}$            |
|       Fraction        | `$\frac{n}{2}$`      | $\frac{n}{2}$      |
|       Less than       | `$<$`                | $<$                |
|  Less than or equal   | `$\leq$`             | $\leq$             |
|    Much less than     | `$\ll$`              | $\ll$              |
|     Greater than      | `$>$`                | $>$                |
| Greater than or equal | `$\geq$`             | $\geq$             |
|   Much greater than   | `$\gg$`              | $\gg$              |
|    Sum with bounds    | `$\sum_{i=1}^{n} i$` | $\sum_{i=1}^{n} i$ |
