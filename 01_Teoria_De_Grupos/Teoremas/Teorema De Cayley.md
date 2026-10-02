---
tags:
  - teorema
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Todo grupo $G$ es isomorfo a un subgrupo del [[Grupos De Permutaciones]] $S_{n}$. Donde $n$ es el orden de $G$.
## Demostración
Sea la accion de $G$ sobre si mismo definido por 
$$
\begin{aligned}
	G \times G &\to G \\
	(g, a) &\mapsto ga
\end{aligned}
$$
lo que nos deja que para cada $g \in G$ la accion sobre $a$ es la permutación $\sigma_{g}(a) = b$. Luego podemos definir el siguiente morfismo.
$$
\begin{aligned}
\Psi : G &\to S_{n} \\
g &\to \sigma_{g}
\end{aligned}
$$
Entonces verificamos que sea un homomorfismo.

1. **La identidad mapea a la identidad:** Primero verificamos que $\Psi(e_{G}) = e_{S_{n}}$, entonces sea la permutación $\sigma_{e}$ la cual es la accion inducida por la identidad de $G$. Como $\sigma_e$ es también una accion cumple el primer axioma de [[Acción De Grupos]].

2. **Mantenimiento De La Estructura:** Entonces sean dos elementos $g,h \in G$ entonces evaluamos.
   $$ \Psi(gh)(a) = \sigma_{gh}(a) = (gh) \cdot a = g \cdot (h \cdot a) = \sigma_g(\sigma_h(a)) = \sigma_{g} \circ \sigma_{h} = \Psi(g)\Psi(h) $$
Entonces $\Psi$ es un homomorfismo. Por ultimo nos interesa el $\text{ker}(\Psi)$ para usar el [[Primer Teorema Del Isomorfismo]].
$$
\begin{aligned}
\text{ker}(\Psi) &= \{ g \in G \mid \sigma_{g} = e_{S_{n}} \} \\
&= \{ g \in G \mid \sigma_{g}(a) = a, \;\forall a \in G \} \\ 
&= \{ g \in G \mid ga = a, \;\forall a \in G \} \\ 
&= \{ g \in G \mid g = e_{G}, \;\forall a \in G \} \\
&= \{ e \}.
\end{aligned}
$$
Por lo tanto concluimos.
$$
G \cong \text{Im}(\Psi) \leq S_{n}.
$$
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)