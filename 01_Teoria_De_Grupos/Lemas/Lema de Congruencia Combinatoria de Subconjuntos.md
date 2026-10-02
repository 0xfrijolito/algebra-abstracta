---
tags:
  - lema
fecha_creacion:
ultima_edicion:
estudiado:
---
## Definición
Sea $A$ un conjunto de cardinalidad $p^{n}k$, donde $p$ es un primo, $n \ge 1$ un entero y $k \ge 1$ un entero que no se divide por $p$. El numero de subconjuntos de $A$ de cardinalidad $p^{n}$  es congruente a $k$ modulo $p$. Es decir si $m = \text{ Numeros de subconjuntos de orden }p^{n}$ entonces $m \equiv k\ (mod\ p)$ 
## Demostración
El numero busca es el coeficiente de $n^{p^{n}}$ en la expansión del binomio
$$
(1 + x)^{p^{n}k}= ((1+x)^{p^{n}})^{k}
$$
Sin embargo
$$
(1 + x)^{p^{n}k} \equiv (1+x)^{p^{n}}\;\text{mod}\;p 
$$
Porque todos los demás coeficientes se dividen por $p$. Entonces el coeficiente buscado es congruente al coeficiente de $x^{p^{n}}$ en $(1 + x^{p^{n}})^{k}$, que es $k$.
Q.E.D