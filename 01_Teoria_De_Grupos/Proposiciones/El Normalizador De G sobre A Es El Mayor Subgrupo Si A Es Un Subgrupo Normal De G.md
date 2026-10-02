---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea un grupo $G$ y un subgrupo normal $A$ cualquiera entonces $N_{G}(A)$ es el subgrupo mas grande de $G$.
## Demostración
El normalizador se define como:
$$
\begin{aligned}
N_{G}(A) &= \{ g \in G \mid gAg^{-1} = A \} \\
&= \{ g \in G \mid gA = Ag \}
\end{aligned}
$$
Donde 
$$
gAg^{-1} = \{ gag^{-1} \mid a \in A \}
$$
Por lo tanto sea un elemento $a \in A$ la idea es mostrar que este elemento se encuentra también en $N_{G}(A)$. Entonces sea, pero como $A$ es un grupo normal de $G$ entonces todo elemento de $A$ se encuentra en $N_{G}(A)$ por lo tanto cualquier grupo normal de $G$ cumple que.
$$
A \subset N_{G}(A)
$$
Ahora sea $K$ el grupo mas grande de $G$ entonces $A \unlhd K$, sea $k \in K$ un elemento cualquier cumple con.
$$
kak^{-1} \in kAk^{-1} \Rightarrow \exists a' \in A \; \text{t.q.}\; kak^{-1} = a' \Rightarrow ka = a'k \Rightarrow Ak \subset kA.
$$
Por lo tanto $kA = Ak$ entonces $kAk^{-1} = A$. De modo que todo elemento $k \in K \Rightarrow k \in N_{g}(A)$.

Q.E.D.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)