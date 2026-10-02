---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: true
---
## Proposición
Sea $H$ y $K$ subgrupos de $G$. El numero de formas diferentes de escribir cada elemento del conjunto $HK$ de la forma $hk$, para algún $h \in H$ y $k \in K$ es $| H \cap K|$. En particular si $H \cap K =\{e\}$. Cada  elemento de $HK$ tiene un único $hk$.
## Demostración
Sea el conjunto que contiene todas las formas de expresar un termino $y \in HK$$
$$
S_y = \{(h, k) \in H \times K \mid hk = y\}
$$
Nuestro objetivo es demostrar que $\vert{}S_y\vert{} = \vert{}H \cap K\vert{}$ construyendo una función biyectiva $f: H \cap K \to S_y$ dada por:
$$
f(x) = (h_1 x,\ x^{-1} k_1)
$$
1. **Es bien definida:** Para cualquier $x \in H \cap K$, por clausura de subgrupos tenemos que $h_1 x \in H$ (pues $h_1, x \in H$) y $x^{-1} k_1 \in K$ (pues $x^{-1}, k_1 \in K$). Además, al multiplicarlos: $(h_1 x)(x^{-1} k_1) = h_1 (x x^{-1}) k_1 = h_1 e k_1 = y$. Por lo tanto, $f(x) \in S_y$.
2. **Es inyectiva:** Si $f(x) = f(z)$, entonces $(h_1 x,\ x^{-1} k_1) = (h_1 z,\ z^{-1} k_1)$. Igualando la primera coordenada tenemos $h_1 x = h_1 z$, y cancelando $h_1$ por la izquierda obtenemos $x = z$.
3. **Es sobreyectiva:** Sea $(h_2, k_2) \in S_y$ otra representación cualquiera de $y$. Entonces $h_1 k_1 = h_2 k_2$. Multiplicando por $h_1^{-1}$ por la izquierda y por $k_2^{-1}$ por la derecha obtenemos:
   $$h_1^{-1} h_2 = k_1 k_2^{-1}$$
   Llamemos $x = h_1^{-1} h_2$. Como $h_1, h_2 \in H$, claramente $x \in H$. Pero como también $x = k_1 k_2^{-1}$, tenemos que $x \in K$. Por lo tanto, $x \in H \cap K$. Despejando de nuestras igualdades, vemos que $h_2 = h_1 x$ y $k_2 = x^{-1} k_1$. Es decir, $(h_2, k_2) = f(x)$.

Al existir una biyección entre $H \cap K$ y $S_y$, concluimos que hay exactamente $\vert{}H \cap K\vert{}$ formas diferentes de escribir cada elemento de $HK$.

En particular, si $H \cap K = \{e\}$, entonces $\vert{}H \cap K\vert{} = 1$, lo que implica directamente que $\vert{}S_y\vert{} = 1$ para todo $y \in HK$, probando la unicidad de la representación.

Q.E.D
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)