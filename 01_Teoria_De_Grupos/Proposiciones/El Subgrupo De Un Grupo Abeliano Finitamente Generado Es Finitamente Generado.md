---
tags:
  - proposicion
  - algebra
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Proposición
Un subgrupo de un grupo abeliano finitamente generado y libre es abeliano finitamente generado y libre.
## Demostración
Esta demostración requiere uso de inducción por lo que es útil separar la demostración por pasos.

1. Sea $A$ un subgrupo finitamente generado y libre entonces existe un $n$ positivo y un isomorfismo $\varphi : \mathbb{Z}^{n} \to A$.

   Luego sea $H \leq A$ un subgrupo cualquiera de $A$ entonces por propiedades del isomorfismo sabemos que.
   $$
K = \varphi^{-1}(H) \leq \mathbb{Z}^{n}.
   $$
2. Ahora consideremos que $(n = 1)$. Si $K \leq \mathbb{Z}$, sabemos que la los únicos grupos de $\mathbb{Z}$ tienen la forma $d\mathbb{Z}$ para algún $d \geq 0$. Entonces existe un isomorfismo $f : \mathbb{Z} \to d\mathbb{Z}, \; n \mapsto dn$ de modo que $K$ es abeliano finitamente generado y libre.

3. Paso inductivo $(n > 1)$. Asumimos que es verdad para grupos del tipo $\mathbb{Z}^{n-1}$. Luego $K \leq \mathbb{Z}^{n}$ y sea$$\pi : K \to \mathbb{Z}, \; (x_{1},...,x_{n}) \mapsto x_{n}$$Donde el $\text{ker}(\pi) \cong K \cap Z^{n-1} \leq \mathbb{Z}^{n-1}$ un grupo abeliano finito generado libre. Además $\pi(K) \cong r\mathbb{Z} \leq \mathbb{Z}$ entonces también es un grupo abeliano finito generado libre. Fijamos un elemento $a \in H$ tal que $\pi(a) = r$ (generador de $H$ )

4. Por ultimo construirnos la siguiente función $$\phi : K \to (K \cap \text{ker}(\pi)) \times \pi(K), \; h \mapsto \left(h - \frac{\pi(h)}{\pi(a)}a, \pi(h)\right)$$es un isomorfismos de grupos entonces.$$ K \cong (\text{ker}(\pi) \cap \mathbb{Z}^{n-1}) \times \pi(K)$$
Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)