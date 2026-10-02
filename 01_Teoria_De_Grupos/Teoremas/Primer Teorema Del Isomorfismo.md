---
tags:
  - teorema
  - álgebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Teorema
Sea $f : G_{1} \to G_{2}$ un homomorfismo de grupos y sea $H := \text{ker}(f)$. Entonces $G_{1}/H$ es isomorfo a $Im(f)$.  Mas precisamente la función:
$$
\pi : G_{1}/H \to \text{im(f)}, \;\; aH \mapsto f(a)
$$
es un isomorfismo de grupos.
## Demostración
$\pi$ es una función bien definida: si $aH = a'H \Rightarrow a' = ah$, $h \in H$ entonces.
$$
\pi(a'H) = f(a') = f(ah) = f(a)f(h)= f(a) = \pi(aH).
$$
Luego $\pi$ es un homomorfismo
$$
\pi(aH \cdot bH) = \pi(abH) = f(ab) = f(a)f(b) = \pi(aH)\cdot\pi(bH).
$$
Ahora verificamos la inyectividad
$$
\pi(aH) = f(a) = e \Rightarrow a \in H \Rightarrow aH = eH = H.
$$
entonces $\text{ker}(\pi) = \{H\}$ 

Por ultimo la sobreyectividad, si $b \in Im(f)$, entonces 
$$
b = f(a) = \pi(aH), \; a \in G_{1}
$$
luego $b \in Im(\pi)$.

Q,E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)