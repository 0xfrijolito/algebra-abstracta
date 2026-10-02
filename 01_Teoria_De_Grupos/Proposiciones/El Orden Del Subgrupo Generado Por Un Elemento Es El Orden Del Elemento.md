---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
El orden de $\left<a\right>$ es el orden de $a$.
## Demostración
Por definición del orden de un elemento, $n$ es el menor entero positivo tal que $a^n = e$ (donde $e$ es el elemento neutro de $G$).

Primero, demostraremos que $\langle a \rangle = \{ e, a, a^2, \dots, a^{n-1} \}$.

Sea $x \in \langle a \rangle$. Por definición, existe un $k \in \mathbb{Z}$ tal que $x = a^k$. Aplicando el Algoritmo de la División para los enteros $k$ y $n$, existen enteros $q$ (cociente) y $r$ (resto) tales que:

$$k = qn + r \quad \text{donde} \quad 0 \le r < n$$

Sustituyendo en la expresión del elemento:

$$x = a^k = a^{qn + r} = (a^n)^q \cdot a^r = e^q \cdot a^r = e \cdot a^r = a^r$$

Como $0 \le r < n$, todo elemento de $\langle a \rangle$ es de la forma $a^r$ con $r \in \{0, 1, \dots, n-1\}$. Esto demuestra que $\vert{}\langle a \rangle\vert{} \le n$.

Segundo, demostraremos que los $n$ elementos del conjunto $\{ e, a, a^2, \dots, a^{n-1} \}$ son **todos distintos**.

Supongamos, por contradicción, que existen dos exponentes $i, j$ con $0 \le j < i < n$ tales que $a^i = a^j$. Multiplicando a la derecha por $a^{-j}$ (el inverso de $a^j$), obtenemos:

$$a^{i-j} = e$$

Dado que $0 \le j < i < n$, se cumple que $0 < i - j < n$. Esto significa que habríamos encontrado un entero positivo $m = i-j$ estrictamente menor que $n$ tal que $a^m = e$. Esto **contradice la minimalidad de $n$** como el orden del elemento $a$.

Por lo tanto, no hay repeticiones, los $n$ elementos son distintos, y se concluye que:

$$\vert{}\langle a \rangle\vert{} = n = \vert{}a\vert{}$$

Por otro lado si el elemento $a$ tiene orden infinito podemos definir la biyeccion.
$$
f: \mathbb{Z} \to \left<a\right>, \; n \mapsto a^{n}
$$
Por lo tanto $|\left<a\right>| = |\mathbb{Z}| = \infty$.

Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)