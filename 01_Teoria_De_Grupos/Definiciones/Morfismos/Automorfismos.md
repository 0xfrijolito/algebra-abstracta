---
tags:
  - definicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Definición
Sea un grupo $(G, *)$, un **automorfismo** de $G$ es un *isomorfismo* desde $G$ hacia sí mismo ($\varphi : G \to G$).

El conjunto de todos los automorfismos de $G$ se denota por $\text{Aut}(G)$. Si asociamos este conjunto con la operación de composición de funciones $(\circ)$, se demuestra que $(\text{Aut}(G), \circ)$ cumple con todos los axiomas de grupo. A esta estructura se le conoce como el **Grupo de Automorfismos** de $G$.

Intuitivamente, un automorfismo es una simetría de la estructura del propio grupo: una forma de permutar sus elementos de modo que la "tabla de multiplicar" del grupo permanezca idéntica.
## Observaciones
1. Para cada elemento $x \in G$, el automorfismo interno $\phi_x(g) = xgx^{-1}$ es un elemento de $\text{Aut}(G)$. Al conjunto de todos estos automorfismos internos se le denota por $\text{Inn}(G)$.
2. El mapeo identidad $\text{id} : G \to G$ siempre es el elemento identidad del grupo $(\text{Aut}(G), \circ)$.
3. Obviamente todo grupo es isomorfo a un subconjunto de $S_{n}$ pero en este caso es mas fácil de ver para grupos finitos ya que nos funcionan las permutaciones que mueven elementos de orden $n$ a otro de orden $n$.
## Teoremas
1. [[Teorema del Isomorfismo para Inn(G)]]: Se cumple que $G / Z(G) \cong \text{Inn}(G)$, donde $Z(G)$ es el centro de $G$.
## Proposiciones
1. [[El Conjunto De Automorfismos de G Es Un Grupo Bajo La Composición]] 
2. [[Inn(G) Es Un Subgrupo Normal De Aut(G)]]
3. [[Automorfismos de Grupos Cíclicos]]
## Ejemplos
1. **Automorfismos de $\mathbb{Z}_3$:**
   Consideremos el grupo cíclico $\mathbb{Z}_3 = \{0, 1, 2\}$ bajo la adición módulo 3. Cualquier automorfismo $\varphi$ debe enviar el elemento identidad a la identidad, por lo que $\varphi(0) = 0$.
   Para los elementos restantes, un automorfismo está completamente determinado por a dónde envía al generador $1$.
   - Si $\varphi(1) = 1$, entonces $\varphi(2) = 2$ (la identidad $\text{id}$).
   - Si $\varphi(1) = 2$, entonces $\varphi(2) = \varphi(1+1) = 2+2 \equiv 1$. Este mapeo es biyectivo y preserva la estructura.
   Por lo tanto, $\text{Aut}(\mathbb{Z}_3)$ tiene solo 2 elementos, lo que implica que $\text{Aut}(\mathbb{Z}_3) \cong \mathbb{Z}_2$.
1. **Automorfismos del Grupo de Klein $V_4$:**
   El grupo de Klein $V_4 = \{e, a, b, c\}$ tiene tres elementos de orden 2 ($a, b, c$) que se comportan de manera completamente simétrica (el producto de cualesquiera dos de ellos da el tercero, por ejemplo, $a*b=c$).
   Como cualquier automorfismo debe preservar el orden de los elementos y fijar la identidad $e$, podemos permutar los elementos $\{a, b, c\}$ de cualquier manera imaginable.
   Dado que hay $3! = 6$ formas de permutar estos tres elementos, y cada una de estas permutaciones preserva la estructura algebraicas del grupo, concluimos que:
   $$\text{Aut}(V_4) \cong S_3$$
   Donde $S_3$ es el grupo simétrico de 3 elementos. Este es un ejemplo fascinante donde el grupo de simetrías de un grupo abeliano resulta ser un grupo no abeliano.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)