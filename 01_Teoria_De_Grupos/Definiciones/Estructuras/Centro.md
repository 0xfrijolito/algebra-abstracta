---
tags:
  - definicion
  - estructura
---
## Definición
Definimos el **Centro De G**, $Z(G)$ como el conjunto de elementos que conmutan con todos los elementos del grupo $G$. 
$$
\begin{aligned}
Z(G) &= \{ g\in G \mid gx = xg \;\;\text{Para todo } x \in G \} \\
&= \{ g\in G \mid gxg^{-1} = x \;\;\text{Para todo } x \in G \}
\end{aligned}
$$
## Observaciones
1. Notar que el Centro de G es igual al centralizador de $G$ sobre $G$.
## Proposiciones
1. [[El Centro De G es un Subgrupo Normal Abeliano]]
2. [[El Centro De G de un Grupo Abeliano es Igual Al Grupo]]
3. [[El Centro De G Es Un Subgrupo Característico]]
4. [[El Centro de G Es La Intersección De Los Centralizador De Todos Los Elementos]]
5. [[Si El Grupo Cociente Formado Por Centro Es Cíclico Entonces G Es Abeliano]]
6. [[El Centro De Un P Grupo Es Siempre No Trivial]]
## Ejemplos
1. **El centro del grupo lineal general $GL(2, \mathbb{R})$**
   Por ejemplo, sea $G$ el grupo $GL(2, \mathbb{R})$ de las matrices invertibles de orden $2 \times 2$ con coeficientes reales:$$A = \begin{bmatrix} a & b \\ c & d \end{bmatrix}$$Las matrices invertibles son aquellas cuyo determinante $\det(A) = ad - bc$ es diferente de $0$.

   Un cálculo directo muestra que el centro de $G$ consiste en las matrices escalares:$$\lambda I = \begin{bmatrix} \lambda & 0 \\ 0 & \lambda \end{bmatrix}$$donde $\lambda$ es cualquier número real distinto de cero.
   Este es un caso particular del resultado siguiente: el centro del grupo general lineal $GL(n, \mathbb{R})$ —compuesto por las matrices invertibles de orden $n \times n$ con coeficientes reales— lo forman las matrices escalares, es decir, aquellas que son un múltiplo no nulo de la matriz identidad de orden $n$.

3. **El centro del grupo de los cuaterniones**
   Para otro ejemplo, sea $G = Q_8$ el grupo de los cuaterniones.
   Es fácil verificar que el centro de este grupo es $\langle -1 \rangle = \{-1, 1\}$, pues son los únicos elementos que conmutan con el resto del grupo.
