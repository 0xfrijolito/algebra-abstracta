---
tags:
  - definicion
  - estructura
fecha_creacion:
ultima_edicion:
estudiado: true
---
## Definición
Definimos el **Centralizador** del subconjunto $A$ de $G$ como
$$
\begin{aligned}
C_{G}(A) &= \{ g \in G \mid gag^{-1} = a \;\;\text{para todo } a \in A\} \\
&= \{ g \in G \mid ga = ag  \;\;\text{para todo } a \in A\ \}
\end{aligned}
$$
Siendo entonces el conjunto de todos los elementos del grupo que conmutan con todo elemento de $A$.

En algunos casos especiales de $A=\{a\}$ entonces simplemente escribimos 
$$
\begin{aligned}
C_{G}(a) &= \{ g \in G \mid gag^{-1} = a \} \\
&= \{ g \in G \mid ga = ag \}
\end{aligned}
$$
Donde en este caso son todos los elementos que conmutan con $a$.
## Propiedades
- [[El Centralizador es un Subgrupo]]
- [[El Centralizador Es El Subgrupo En El Que Conmutan Todos Los Elementos]]
- [[El Centralizador De a Es G Si a Pertenece Al Centro]]
- [[El Centralizador De a Es G Si a Es El Único Elemento De Orden 2]]
## Ejemplos

1. **Grupos abelianos.** 
   Si $G$ es un grupo abeliano, entonces la operación es conmutativa para todos los elementos del grupo. En este caso, para cualquier subconjunto $A \subseteq G$, se cumple que $C_G(A) = G$. Todos los elementos del grupo conmutan con todo subconjunto.

2. **El grupo de los cuaterniones.**
   Consideremos el grupo de los cuaterniones $Q_8 = \{1, -1, i, -i, j, -j, k, -k\}$. Si queremos calcular el centralizador del elemento $i$, buscamos todos los elementos que conmutan con él. Por inspección de las reglas de multiplicación de $Q_8$ (recordando que $ij = k \neq -k = ji$, etc.), podemos verificar que los únicos elementos que conmutan con $i$ son los escalares $\{1, -1\}$ y las potencias del propio elemento $\{i, -i\}$. Por lo tanto: 
   $$C_{Q_8}(i) = \{1, -1, i, -i\}$$
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)