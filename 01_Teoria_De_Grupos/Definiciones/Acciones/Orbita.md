---
tags:
  - definicion
---
## Definición
Sean $G$ un Grupo y una [[Acción De Grupos]] sobre $X$ . Para cada $x \in X$, **la orbita de x** es.
$$
\text{orb}(x) = \{g \cdot x \mid g \in G\}
$$
Es decir, todos los objetos que podemos obtener haciendo actuar $G$ sobre x.
## Observaciones 
1. Sean $G$ un grupo y $X$ un [[Acción De Grupos]]. Tenemos que $\text{orb}(x)$ es la clase de equivalencia de $x$ con respecto a la relación inducida por la acción de $G$ en $X$.$$ \begin{aligned} \; [x] &= \{y \in X \mid x \sim y\} \\ &= \{y \in X \mid \exists g \in G \;\text{con}\; g\cdot x = y\} \\ &= \{ g \cdot x \mid g \in G \} = \text{orb}(x) \end{aligned}$$
## Proposiciones
1. [[Características De Las Orbitas]]
## Ejemplos
1. **Grupos De Permutaciones 1**
   Consideremos la permutación $\alpha = (1\ 2\ 3\ 4\ ) \in S_{6}$. Sea $G= \left<\alpha\right>$ y $X = \{ 1, 2,3,4,5,6\}$ con la acción de $G$ sobre $X$ dada por $\alpha^{k} \cdot i = \alpha^{k}(i)$ para toda $k \in \mathbb{Z}$ , $i \in X$. 

   Sean las [[Orbita]]s de los elementos.$$\begin{aligned} \text{orb}(1) &= \{1,2,3,4\} \\ &= \text{orb}(2) = \text{orb}(3) = \text{orb}(4) \\ \text{orb}(5) &= \{5\} \\ \text{orb}(6) &= \{6\}. \end{aligned}$$Observando que las orbitas de $1, 2, 3, 4$ son iguales porque $\alpha$ es una permutación cíclica que mueve los elementos, pero como $\alpha$ deja fijo a $5$ y a $6$ sus orbitas son distintas.
   
   Ahora, podemos describir mejor $G= \left<\alpha\right>$. Como $\alpha$ tiene orden $4$. $G$ quedaría$$ G = \{ e, \alpha^{1}, \alpha^{2}, \alpha^{3} \}$$Por ultimo, describamos los estabilizadores. De acuerdo a la definición de la entrada previa el estabilizador de un objeto son los elementos del grupo que fijan al objeto, en este caso las potencias de $\alpha$ que dejan fijo al objeto. En el caso del $1$ la única potencia de $\alpha$ que lo fija es la identidad y análogamente para $2,3$ y $4$ Por otro lado en el caso de $5$ y $6$ como $\alpha$ no los mueve en absoluto, cualquier potencia de $\alpha$ forma parte de sus respectivos estabilizadores. Esto quedaría escrito de la siguiente manera:$$\begin{aligned}
   G_{1} &= \{ \alpha^{k} \in G \mid \alpha^{k} \cdot 1 \} = \{ e \} \\
   &= G_2 = G_3 = G_4.\\ \\ 
   
   G_{5} &= \{ \alpha^{k} \in G \mid \alpha^{k} \cdot 5 \} = G = \{ e, \alpha^{1}, \alpha^{2}, \alpha^{3} \}\\
   &= \{ \alpha^{k} \in G \mid \alpha^{k} \cdot 6 \} \\ 
   &= G_{6}.
   \end{aligned}
   $$
   