---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
Sea $R$ un [[Anillo]]. Entonces
1. $0a = a0 = 0$ para todo $a \in R$.
2. $(-a)b = a(-b) = -(ab)$ para todo $a, b \in R$, donde $-a$ denota el inverso aditivo de $a$.
3. $(-a)(-b) = ab$ para todo $a, b \in R$.
4. Si $R$ tiene identidad $1$, entonces la identidad es única y $-a = (-1)a$.

## Demostración
**(1)** Sea $a \in R$. Como $0 = 0 + 0$, por la distributividad $$ 0a = (0 + 0)a = 0a + 0a. $$ Como $(R, +)$ es un grupo abeliano, podemos sumar $-(0a)$ a ambos lados y obtenemos $0a = 0$. De forma análoga, $a0 = a(0 + 0) = a0 + a0$, luego $a0 = 0$.

**(2)** Sean $a, b \in R$. Por la distributividad y por (1), $$ \begin{aligned} ab + (-a)b &= (a + (-a))b \ &= 0b = 0. \end{aligned} $$ Entonces $(-a)b$ es un inverso aditivo de $ab$, y por la [[Unicidad del Inverso en Grupos|unicidad del inverso]] en $(R,+)$ se tiene $(-a)b = -(ab)$. De forma análoga, $ab + a(-b) = a(b + (-b)) = a0 = 0$, luego $a(-b) = -(ab)$.

**(3)** Sean $a, b \in R$. Aplicando (2) dos veces, $$ \begin{aligned} (-a)(-b) &= -\big(a(-b)\big) \ &= -\big(-(ab)\big) = ab, \end{aligned} $$ donde la última igualdad se debe a que en un grupo el inverso del inverso es el propio elemento.

**(4)** Supongamos que $1$ y $1'$ son identidades de $R$. Como $1$ es identidad, $1 \cdot 1' = 1'$, y como $1'$ es identidad, $1 \cdot 1' = 1$. Luego $$ 1 = 1 \cdot 1' = 1', $$ así la identidad es única. Finalmente, por (2), $$ (-1)a = -(1a) = -a. $$ Q.E.D

---

**Metadatos de estudio:**

- **Última vez editado:** 2026-09-30
- **Estudiado:** No