---
tags:
  - definicion
  - accion
---
## Definición
Dado un [[Grupo]] $G$ y un conjunto no vacío $X$, una **acción de grupo** puede comprenderse desde dos enfoques lógicamente equivalentes:
### 1. La Perspectiva Externa (Mapeo)
Es una aplicación $G \times X \to X$, denotada por $(g, x) \mapsto g \cdot x$, que satisface los axiomas de acción:
- **Identidad:** Para cada $x \in X$, $e \cdot x = x$.
- **Compatibilidad:** Para cada $g, h \in G$ y $x \in X$, $(gh) \cdot x = g \cdot (h \cdot x)$.
### 2. La Perspectiva Interna (Representación por Permutaciones)
Para cada elemento fijo $g \in G$, la aplicación $\sigma_g : X \to X$ definida por $\sigma_g(x) = g \cdot x$ es siempre una **biyección** (una permutación de $X$). Por lo tanto, la acción induce un **homomorfismo de grupos** $\Phi: G \to S_X$ definido por:
$$
\Phi(g) = \sigma_g
$$
## Propiedades
1. [[Para Cualquier Grupo G Y Un Conjunto A Existe Una Biyeccion Entre La Accion De G Sobre A Y Un Homomorfismo G Con El Grupo De Permutaciones De A]]
2. [[La Accion De Un Grupo G Sobre Un Conjunto No Vacio Es Una Relacion De Equivalencia]]
3. [[Núcleo de la Acción y Acciones Fieles]]
## Ejemplos

1. **Grupos De Permutaciones 1**
   Consideremos la permutación $\alpha = (1\ 2\ 3\ 4\ ) \in S_{6}$. Sea $G= \left<\alpha\right>$ y $X = \{ 1, 2,3,4,5,6\}$ con la acción de $G$ sobre $X$ dada por $\alpha^{k} \cdot i = \alpha^{k}(i)$ para toda $k \in \mathbb{Z}$ , $i \in X$. 

   Sean las [[Orbita]]s de los elementos.$$\begin{aligned} \text{orb}(1) &= \{1,2,3,4\} \\ &= \text{orb}(2) = \text{orb}(3) = \text{orb}(4) \\ \text{orb}(5) &= \{5\} \\ \text{orb}(6) &= \{6\}. \end{aligned}$$Observando que las orbitas de $1, 2, 3, 4$ son iguales porque $\alpha$ es una permutación cíclica que mueve los elementos, pero como $\alpha$ deja fijo a $5$ y a $6$ sus orbitas son distintas

   Ahora, podemos describir mejor $G= \left<\alpha\right>$. Como $\alpha$ tiene orden $4$. $G$ quedaría$$ G = \{ e, \alpha^{1}, \alpha^{2}, \alpha^{3} \}$$Por ultimo, describamos los estabilizadores. De acuerdo a la definición de la entrada previa el estabilizador de un objeto son los elementos del grupo que fijan al objeto, en este caso las potencias de $\alpha$ que dejan fijo al objeto. En el caso del $1$ la única potencia de $\alpha$ que lo fija es la identidad y análogamente para $2,3$ y $4$ Por otro lado en el caso de $5$ y $6$ como $\alpha$ no los mueve en absoluto, cualquier potencia de $\alpha$ forma parte de sus respectivos estabilizadores. Esto quedaría escrito de la siguiente manera:
$$
   \begin{aligned}
   G_{1} &= \{ \alpha^{k} \in G \mid \alpha^{k} \cdot 1 \} = \{ e \} \\
   &= G_2 = G_3 = G_4.\\ \\ 
   
   G_{5} &= \{ \alpha^{k} \in G \mid \alpha^{k} \cdot 5 \} = G = \{ e, \alpha^{1}, \alpha^{2}, \alpha^{3} \}\\
   &= \{ \alpha^{k} \in G \mid \alpha^{k} \cdot 6 \} \\ 
   &= G_{6}.
   \end{aligned}
   $$
2. **Grupo Permutaciones 2**
   Consideremos ahora la permutación $\beta = (1\ 2\ 3)(4\ 5) \in S_{5}$. Sean $G = \left<\beta\right>$ y $X = \{1,2,3,4,5\}$ Donde la accion de $G$ sobre $X$ esta dada por $\beta^{k} \cdot i = \beta^{k}(i)$ para todo $k \in \mathbb{Z}$ y $i \in X$.

   Luego las [[Orbita]]s nos quedan como$$\begin{aligned} \text{orb}(1) &= \{1,2,3\} = \text{orb}(2) = \text{orb}(3) \\ \text{orb}(4) &= \{4, 5\} = \text{orb}(5) \end{aligned}$$Ahora describimos $G$. Observamos que $\beta$ esta compuesta por dos ciclos disjuntos, uno con orden 3 y otro con orden 2, es decir el producto de los ciclos que conmutan 