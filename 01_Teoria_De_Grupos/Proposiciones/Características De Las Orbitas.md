---
tags:
  - proposicion
---
## Proposición
Sean $G$ un grupo y $X$ un $G$-conjunto. Entonces
1. $\text{orb}(x) \neq \emptyset$ para toda $x \in X$;
2. Sean $x, y \in X$. Si $\text{orb}(x) \cap \text{orb}(y) \neq \emptyset$, entonces $\text{orb}(x) = \text{orb}(y)$;
3. $X = \bigcup_{x \in X} \text{orb}(x)$.
### Demostración 1
Sea $x \in X$. Por los axiomas de la acción de un grupo sobre un conjunto, el elemento neutro $e \in G$ actúa sobre $x$ de tal forma que $e \cdot x = x$. Dado que la órbita se define como $\text{orb}(x) = \{g \cdot x \mid g \in G\}$, y sabiendo que $e \in G$, se deduce que $x \in \text{orb}(x)$. Al contener al menos al propio elemento $x$, concluimos inequívocamente que $\text{orb}(x) \neq \emptyset$.
### Demostración 2
Supongamos que $\text{orb}(x) \cap \text{orb}(y) \neq \emptyset$. Esto significa que existe al menos un elemento $z \in X$ tal que $z \in \text{orb}(x)$ y $z \in \text{orb}(y)$. Por la definición de órbita, existen elementos $g_1, g_2 \in G$ tales que: $$\begin{aligned} z &= g_1 \cdot x \\ z &= g_2 \cdot y \end{aligned}$$Igualando ambas expresiones, obtenemos $g_1 \cdot x = g_2 \cdot y$.
 - Para demostrar que $\text{orb}(x) \subseteq \text{orb}(y)$: Multiplicando la ecuación anterior por $g_1^{-1}$ a la izquierda, obtenemos $x = g_1^{-1} \cdot (g_2 \cdot y) = (g_1^{-1} g_2) \cdot y$. Sea $w \in \text{orb}(x)$ un elemento arbitrario. Entonces, $w = g_3 \cdot x$ para algún $g_3 \in G$. Sustituyendo $x$ en esta expresión: $$
 w = g_3 \cdot ((g_1^{-1} g_2) \cdot y) = (g_3 g_1^{-1} g_2) \cdot y$$Como $G$ es cerrado bajo su operación, el elemento $(g_3 g_1^{-1} g_2) \in G$. Por lo tanto, $w \in \text{orb}(y)$, lo que demuestra que $\text{orb}(x) \subseteq \text{orb}(y)$. 
 
 - Para demostrar que $\text{orb}(y) \subseteq \text{orb}(x)$: Siguiendo un razonamiento simétrico desde $g_1 \cdot x = g_2 \cdot y$, multiplicamos por $g_2^{-1}$ a la izquierda para obtener $y = (g_2^{-1} g_1) \cdot x$. De manera análoga al paso anterior, cualquier elemento generado a partir de $y$ también puede ser generado a partir de $x$.

Al cumplirse ambas contenciones de conjuntos, demostramos que $\text{orb}(x) = \text{orb}(y)$.
### Demostración 3
Demostraremos la igualdad de conjuntos a través de la doble contención: 
- **$\bigcup_{x \in X} \text{orb}(x) \subseteq X$:** Por definición de la acción del grupo, para cualquier $x \in X$ y $g \in G$, el elemento resultante $g \cdot x$ siempre pertenece a $X$. Por lo tanto, cada subconjunto $\text{orb}(x) \subseteq X$. Una unión arbitraria de subconjuntos de $X$ es, por definición, un subconjunto de $X$.

- **$X \subseteq \bigcup_{x \in X} \text{orb}(x)$:** Sea $y \in X$ un elemento arbitrario. Como demostramos en el punto 1, todo elemento pertenece a su propia órbita ($y \in \text{orb}(y)$). Puesto que $\text{orb}(y)$ es uno de los conjuntos indexados que conforman la unión total $\bigcup_{x \in X} \text{orb}(x)$, es evidente que $y \in \bigcup_{x \in X} \text{orb}(x)$.

Habiendo demostrado ambas contenciones, concluimos que $X = \bigcup_{x \in X} \text{orb}(x)$.