---
tags:
  - definicion
  - estructura
---
## Definición
Sea el subconjunto $A$ del grupo $G$. Definimos el conjunto.
$$
gAg^{-1} = \{ gag^{-1} \mid a \in A \}
$$Entonces llamamos el **Normalizador**, $N_{G}(A)$, al conjunto.
$$
\begin{aligned}
N_{G}(A) &= \{ g \in G \mid gAg^{-1} = A \} \\
&= \{ g \in G \mid gA = Ag \}
\end{aligned}
$$
Es decir todos los elementos $g$ que mantienen el conjunto $A$.
## Observaciones
1. Notamos que si $g \in G_{G}(A)$ entonces $gag^{-1} = a \in A$ para todo $a \in A$ luego $C_{G}(A) \leq N_{G}(A)$. 
## Propiedades
- [[El Normalizador De G sobre A Es El Mayor Subgrupo Si A Es Un Subgrupo Normal De G]]
- [[El Normalizador De G Sobre A Es Subgrupo De G]]
- [[El Normalizador De G Sobre A Tiene El Un Subgrupo Normal A Mas Grande Del Normalizador]]
## Ejemplos

1. **El grupo simétrico $S_3$.**
   Consideremos el grupo simétrico de permutaciones de 3 elementos expresado en notación de ciclos: $$G = S_3 = \{\text{id}, (1\ 2), (1\ 3), (2\ 3), (1\ 2\ 3), (1\ 3\ 2)\}$$Tomemos el subconjunto $H$ (que de hecho es un subgrupo) generado por la transposición $(2\ 3)$:$$H = \{\text{id}, (2\ 3)\}$$El normalizador de $H$ en $S_3$, denotado $N_{S_3}(H)$, está formado por todos los elementos $g \in S_3$ tales que al conjugar $H$ obtenemos nuevamente $H$ (es decir, $gHg^{-1} = H$). Dado que la identidad siempre conjuga a la identidad, basta con analizar la conjugación del elemento $(2\ 3)$ por cada $g \in S_3$:

   - Si $g = \text{id}$: $\text{id} \cdot H \cdot \text{id}^{-1} = H$. Por lo tanto, $\text{id} \in N_{S_3}(H)$. 
   - Si $g = (2\ 3)$: $(2\ 3)H(2\ 3)^{-1} = H$. Por lo tanto, $(2\ 3) \in N_{S_3}(H)$. ($(2\ 3)$ tiene orden $2$).
   - Si $g = (1\ 2)$: $(1\ 2)(2\ 3)(1\ 2)^{-1} = (1\ 2)(2\ 3)(1\ 2) = (1\ 3) \notin H$. No está en el normalizador. 
   - Si $g = (1\ 3)$: $(1\ 3)(2\ 3)(1\ 3)^{-1} = (1\ 3)(2\ 3)(1\ 3) = (1\ 2) \notin H$. No está en el normalizador. 
   - Si $g = (1\ 2\ 3)$: $(1\ 2\ 3)(2\ 3)(1\ 3\ 2) = (1\ 2) \notin H$. No está en el normalizador. 
   - Si $g = (1\ 3\ 2)$: $(1\ 3\ 2)(2\ 3)(1\ 2\ 3) = (1\ 3) \notin H$. No está en el normalizador.
   
   Por lo tanto, el normalizador es exactamente el propio conjunto:$$N_{S_3}(H) = \{\text{id}, (2\ 3)\} = H$$***Nota sobre el centralizador:*** El centralizador $C_{S_3}(H)$ es el conjunto de elementos que conmutan con cada elemento de $H$. En este caso específico, al ser un grupo tan pequeño, los únicos elementos que conmutan con $(2\ 3)$ son la identidad y el propio $(2\ 3)$. Así, en este ejemplo, $N_{S_3}(H) = C_{S_3}(H) = H$.