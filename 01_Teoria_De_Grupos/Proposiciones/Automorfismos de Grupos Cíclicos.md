---
tags:
  - proposicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Proposición
El grupo $\text{Aut}(G)$ de un grupo cíclico de orden $n$ es isomorfo al [[Grupos De Unidades De Enteros Modulo n]] $(\mathbb{Z}/n\mathbb{Z})^{\times}$, un grupo abeliano de orden $\varphi(n)$. 
## Demostración
Sea $x$ el generador del grupo cíclico $\mathbb{Z}/n\mathbb{Z}$. Si $\psi \in \text{Aut}(\mathbb{Z}/n\mathbb{Z})$ entonces $\psi(x) = x^{a}$ para algún $a \in \mathbb{Z}$ que determina únicamente a $\psi$. Denotamos este automorfismo como $\psi_{a}$. 

Como es usual, tenemos que $|x| = n$, entonces el entero $a$ esta definido bajo el mod $n$. Como $\psi_{a}$ es un automorfismo, $x$ y $x^{a}$ tiene el mismo orden, es decir $\text{gcd}(n, a) = 1$. (De acá ya se puede ver la conexión con el grupo unidad).

Entonces podemos crear el siguiente morfismo.
$$
\begin{aligned}
\Psi : \text{Aut}(\mathbb{Z}/n\mathbb{Z}) &\to (\mathbb{Z}/n\mathbb{Z})^{\times} \\
\psi_{a} &\mapsto a \; (\text{mod}\;n)
\end{aligned}
$$
Se ve rápidamente que es un homomorfismo ya que.
$$
(\psi_{a} \circ \psi_{b})(x) = \psi_{a}(x^{b}) = x^{a+b} = \psi_{ab}
$$
Entonces
$$
\Psi(\psi_{a} \circ \psi_{b}) = \Psi(\psi_{ab}) = ab\;(\text{mod}\; n) = \Psi(\psi_{a})\Psi(\psi_{b}).
$$
Como $\text{gcd}(a, n) = 1$ entonces claramente la función es sobreyectiva, por lo que concluimos.
$$
\text{Aut}(\mathbb{Z}/n\mathbb{Z}) \cong (\mathbb{Z}/n\mathbb{Z})^{\times}
$$
Q.E.D

## Notas extra
Al final $\text{Aut}(G)$ nos habla de los *ejes de simetría* de nuestro grupo, es decir cuantas veces puedo reagrupar mis términos sin romper el grupo de forma que su estructura actúe igual. Entonces para los grupos abelianos cíclicos este es el grupo de unidades, algo similar a las raíces de nuestro grupo.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)