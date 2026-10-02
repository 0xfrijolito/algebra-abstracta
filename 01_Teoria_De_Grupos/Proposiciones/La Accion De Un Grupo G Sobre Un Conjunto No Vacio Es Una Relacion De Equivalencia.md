---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo y $A$ un conjunto no vacío, la accion de $G$ sobre $A$ definido por
$$
a \thicksim b \; \text{si y solo si}\; a = g \cdot b \; \text{para algun} \; g \in G
$$
Es una clase de equivalencia. Para cada $a \in A$, el numero de elementos en la clase de equivalencia de $a$ es $| G : G_{a} |$ llamado el índice del [[Estabilizador]].
## Demostración
Para que lo anterior sea una clase de equivalencia se tiene que cumplir 3 cosas.
1. **Reflexividad**, Es decir que todo elemento $g$ esta relacionado consigo mismo. Para eso notamos que por definición de la accion de grupos se cumple $a = e \cdot a$ para todo $a \in A$, entonces
$$ 
e \cdot a = a \Rightarrow a \thicksim a
$$
2. **Simetría**, Es decir que para cualquier sea $a, b$ se cumple que $a \thicksim b$ tal que $a = g \cdot b$. Entonces notar 
$$ 
g^{-1} \cdot a = g^{-1} \cdot (g \cdot b) = (g^{-1}g) \cdot b = b
$$
   Entonces $b \thicksim a$.
3. **Transitividad**, Si $a \thicksim b$ y $b \thicksim c$, sea $a = g \cdot b$ y $b = h \cdot c$ para algún $g, h \in G$ entonces
$$ 
a = g \cdot b = g \cdot (h \cdot c) = (gh) \cdot c 
$$
   Entonces $a \thicksim c$.
Entonces las acciones son clases de equivalencia. Por ultimo queremos encontrar una biyeccion entre las [[Clases Laterales]] y elementos de la clase de equivalencias de $a$.

Sea $\text{orb}(a)$ la [[Orbita]] de $a$, entonces
$$
\text{orb}(a) = \{ g \cdot a \mid g \in G \}
$$
Suponemos que $b = g \cdot a \in \text{orb}(a)$. Entonces $gG_{a}$ es la clase lateral de $G_{a}$ en $G$ por el mapeo
$$
b = g \cdot a \mapsto gG_{a}
$$
Es un mapeo de $\mathcal{C}_{a}$ a las clases laterales de $G_{a}$ en $G$. Este mapeo es sobreyectivo ya que para todo $g \in G$ el elemento $g \cdot a$ es un elemento de $\mathcal{C}_{a}$. Como $g \cdot a = h \cdot a$ si y solo si $h^{-1}g \in G_{a}$ si y solo si $gG_{a} = hG_{a}$, el mapeo inyectivo, por lo tanto es biyectivo.

Q.E.D.
***