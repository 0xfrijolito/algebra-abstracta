---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
El numero de conjugados de un subconjunto $S$ del grupo $G$ es el índice del [[Normalizador]] $[G : N_{G}(S)]$. En particular, el numero de conjugados de un elemento $s$ de $G$ es el índice del [[Centralizador]] $[G : C_{G}(s)]$.
## Demostración
Sea un grupo $G$ y un subconjunto $S \subseteq G$, sabemos que su normalizador esta definido por.
$$
N_{G}(S) = \{ g \in G \mid gSg^{-1} = S \}
$$
Entonces sea $\mathcal{S} = \{gSg^{-1} \mid g \in G \}$ el conjunto de todos los subconjuntos conjugados de $S \subseteq G$ en el cual podemos definir la accion.
$$
\begin{aligned}
	G \times \mathcal{S} &\to \mathcal{S} \\
	(g, A) &\mapsto gAg^{-1}
\end{aligned}
$$
Ahora notamos que $S \in \mathcal{S}$ ya que $eSe^{-1} = S$, entonces podemos ver que el estabilizador de $S$ es nuestro normalizador.
$$
\text{stab}(S) = \{ g \in G \mid gSg^{-1} = S \}
$$
Como sabemos que la accion conjugación crea una partición de $G$ entonces el índice.
$$
\text{Numero De Conjugados Sobre S} = \text{orb}(x) = [G : \text{stab}(S)] = [G : \text{norm}(S)]
$$
Luego sabemos que el centralizador de un elemento $s$ es equivalente a el normalizador del singleton $\{ s \}$ por lo tanto queda demostrado.

Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)