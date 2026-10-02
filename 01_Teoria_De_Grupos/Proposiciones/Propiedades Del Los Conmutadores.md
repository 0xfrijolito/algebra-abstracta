---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $G$ un grupo, sean $x, y \in G$ y sea $H \leq G$ un subgrupo. Entonces:
1. $xy = yx[x, y]$ (en particular, $xy = yx \iff [x, y] = 1$).
2. $H \trianglelefteq G \iff [H, G] \leq H$.
3. $\sigma([x, y]) = [\sigma(x), \sigma(y)]$ para cualquier automorfismo $\alpha$ de $G$. Además, $G'$ es  característico respecto a $G$ (el subgrupo derivado es característico) y $G/G'$ es abeliano.
4. $G/G'$ es el mayor cociente abeliano de $G$ en el sentido de que si $H \trianglelefteq G$ y $G/H$ es abeliano, entonces $G' \leq H$. Recíprocamente, si $G' \leq H$, entonces $H \trianglelefteq G$ y $G/H$ es abeliano.
5. Si $\varphi: G \to A$ es cualquier homomorfismo de $G$ en un grupo abeliano $A$, entonces $\varphi$ se factoriza a través de $G'$ (es decir, $G' \leq \ker \varphi$) y el siguiente diagrama conmuta:
## Demostración
1. Se ve inmediatamente de la definición
   $$ yx[x, y] = yx(x^{-1}y^{-1}xy) = y(y^{-1}xy) = xy $$
2. $\Rightarrow$ Entonces sea $H$ un subgrupo normal calculamos su grupo conmutador. 
   $$
\begin{aligned}
[][H, G] &= \left<[h,g] \mid h \in H, g \in G \right> \\
&=  \left< h^{-1}g^{-1}hg \mid h \in H, g \in G \right>
\end{aligned}
$$
   Como $g^{-1}hg \in H$ entones la operación completa son elementos de $H$, además nos queda $hh'$ la accion regular por la izquierda que forma una partición completa. Entonces $[H, G] = H$.

   $\Leftarrow$ Ahora sabemos que $[H, G] = H$ entonces $$H = \left< h^{-1}g^{-1}hg \mid h \in H, g \in G \right>$$Donde lo anterior solo es posible si los generadores pertenecen a $H$ por lo tanto $H$ es normal respecto a $G$.

3. Sea $\sigma \in \text{Aut}(G)$ un automorfismo de $G$ y sean $x, y \in G$. Entonces
   $$ \sigma([x, y]) = \sigma(x^{-1}y^{-1}xy) = \sigma(x)^{-1}\sigma(y)^{-1}\sigma(x)\sigma(y) = [\sigma(x), \sigma(y)]$$
   Luego para que $G'$ sea característico se tiene que cumplir que para cada automorfismo de interno mantiene $G'$ pero el conmutador de los elementos de $[x,y]$ bajo cualquier automorfismo se mantiene entonces es un subgrupo característico.
   
   Por ultimo para verificar que el grupo cociente es abeliano sean los clases laterales.
   $$ xG' \cdot yG' = xyG' = yx[x, y]G' = yxG' \cdot [x,y]G' = yxG' $$

4. Suponemos que $H$ es normal a $G$ y $G/H$ es abeliano. Entonces $x, y \in G$ tenemos que $(xH)(yH) = (yH)(xH)$ tal que.
   $$ 
\begin{aligned}
eH &= (xH)^{-1}(yH)^{-1}(xH)(yH) \\
   &= [x, y]H.
\end{aligned} $$
   Como $[x, y] \in H$ para todo $x, y \in G$ tenemos que $G' \leq H$.
5. 
   
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)