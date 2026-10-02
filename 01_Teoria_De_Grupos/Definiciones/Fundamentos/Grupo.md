---
tags:
  - definicion
  - estructura
  - fundamental
fecha_creacion:
ultima_edicion:
estudiado: true
---
## Definición
Un grupo es un par ordenado $(G, *)$ donde $G \neq \emptyset$ y
$$
G \times G \to G, (a,b) \mapsto a \circ b
$$
es una operación que cumple.
1. $(a \circ b) \circ c = a \circ (b \circ c), \forall a,b,c \in G$
2. existe un elemento $e \in G$ llamado elemento neutro tal que.$$a \circ e = e \circ a = a, \forall a \in G,$$
3. Para cada $a \in G$ existe un elemento $a^{-1} \in G$, elemento inverso tal que$$a \circ a^{-1} = a^{-1} \circ a = e.$$
Donde se dice que el grupo es abeliano si $a \circ b = b \circ a, \; \forall a, b \in G$.
### Orden de un elemento
Sea $G$ un grupo. El orden de $a \in G$, denotado por$|a|$, es el mínimo entero $n > 0$ tal que $a^{n} = e$. Si tal $n$ no existe, se dice que a tiene orden infinito.
## Proposiciones
- [[El Elemento Neutro Es Unico]]
- [[Cada elemento tiene un único inverso]]
- [[Se cumple la ley de cancelación]]
## Ejemplos
- $(Z, +)$, $(Q, +)$, $(R, +)$, $(C, +)$ son grupos abelianos infinitos.
- $(Q^*, \cdot)$, $(R^*, \cdot)$, $(C^*, \cdot)$ son grupos abelianos infinitos.
- $(Z/nZ, +)$ y $(Z/pZ - \{0\}, \cdot)$ ($p$ primo) son grupos abelianos finitos.
- $(GL(n, R), \cdot)$ es un grupo no abeliano infinito.