---
tags:
  - definicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Definición
Sea $N$ un [[Subgrupo Normal]] de un grupo G. Consideramos el conjunto de las [[Clases Laterales]] izquierdas de $N$ en $G$.
$$
G/N = \{ aN \mid a \in G \}
$$
Donde la operación es
$$
aN \cdot bN := abN
$$
Es el grupo cociente de $G$ modulo $N$.
## Teoremas 
1. [[El Conjunto De Clases Laterales Forman Un Grupo]]
2. [[Si El Grupo Cociente Formado Por Centro Es Cíclico Entonces G Es Abeliano]]
## Observaciones

## Ejemplos
1. **Dummit 1**
   Sea $G = \mathbb{Z}$ y $H = \mathbb{Z}n = \left<x\right>$ un grupo cíclico de orden $n$ y definimos $\varphi: \mathbb{Z} \to \mathbb{Z}n$ como $\varphi(a) = x^{a}$. Ya que
   $$ \varphi(a + b) = x^{a + b} = x^{a}x^{b} = \varphi(a)\varphi(b)$$
   Por lo tanto es un homomorfismo. Notar que también es sobreyectiva, entonces las fibras (o mas bien preimagen) de $x^{a}$ es
   $$
\begin{aligned}
\varphi^{-1}(x^{a}) &= \{ m \in \mathbb{Z} \mid x^{m} = x^{a} \} = \{ m \in \mathbb{Z} \mid x^{m-a} = 1 \} \\
&= \{ m \in \mathbb{Z} \mid n \; \text{divide}\; m-a \} \\
&= \{ m \in Z \mid m \equiv a \;(\text{mod}\; n) \}.
\end{aligned}
$$
2. 

***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)