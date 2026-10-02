---
tags:
  - definicion
  - morfismo
---
## Definición
Sea los Grupos $(G, *)$ y $(H, \star)$, un mapeo $\varphi : G \to H$ tal que cumple.
$$
\varphi(x * y) = \varphi(x) \star \varphi(y) \;\; \text{Para todo } x, y \in G.
$$
Se le llama **Homomorfismo de grupos**.
Intuitivamente el mapeo $\varphi$ es una función que respeta la estructura del dominio y condominio.
## Observaciones
Existe un automorfismo de un grupo $G$ denotado por $\phi_{x}$ llamado *automorfismo interno asociado a $x$ donde $\phi_x(g) = xgx^{-1}$. El cual es un homomorfismo.
## Proposiciones
1. [[Propiedades Fundamentales De Los Homomorfismos]];
2. [[El Conjunto De Automorfismos de G Es Un Grupo Bajo La Composición]];
3. [[El Conjunto De Autoformismos Internos De x Es Un Subgrupo al Grupo De Automorfismo ]]
## Ejemplos
1. Para cualquier grupo $G$, se cumple que $G \cong G$. El mapeo identidad $\text{id} : G \to G$ provee un isomorfismo obvio (aunque, en general, no es el único isomorfismo de $G$ en sí mismo).
   Más aún, si $\mathcal{Q}$ es una colección no vacía de grupos, es fácil verificar que la relación de isomorfismo $\cong$ es una relación de equivalencia sobre $\mathcal{Q}$. A las clases de equivalencia bajo esta relación se les llama **clases de isomorfismo**. Esto justifica el lenguaje simétrico que usamos al decir "los grupos son isomorfos".

2. Consideremos la función exponencial $\exp : \mathbb{R} \to \mathbb{R}^+$ definida por $\exp(x) = e^x$, donde $e$ es la base del logaritmo natural. Este mapeo es un isomorfismo desde el grupo aditivo $(\mathbb{R}, +)$ hacia el grupo multiplicativo $(\mathbb{R}^+, \cdot)$. * Es una biyección porque posee una función inversa bien definida (el logaritmo natural, $\ln x$). * Preserva la operación de grupo, ya que por las propiedades de los exponentes:
   $$ 
   \exp(x + y) = e^{x+y} = e^x e^y = \exp(x) \cdot \exp(y)
   $$
   En este ejemplo, tanto los elementos de los conjuntos como las operaciones binarias son distintos. Sin embargo, ambos grupos son isomorfos; es decir, como grupos, poseen estructuras idénticas.
   
3. El tipo de isomorfismo de un grupo simétrico depende exclusivamente de la cardinalidad del conjunto subyacente que está siendo permutado.
   Sean $A$ y $B$ conjuntos no vacíos. Los grupos simétricos $S_A$ y $S_B$ son isomorfos si y solo si $|A| = |B|$.
   Intuitivamente: dado que $|A| = |B|$, existe una biyección $\theta : A \to B$. Podemos pensar que los elementos de $A$ y $B$ están "pegados" a través de $\theta$; es decir, cada $x \in A$ se corresponde con $\theta(x) \in B$.
   Para construir explícitamente el isomorfismo $\varphi : S_A \to S_B$, tomamos una permutación $\sigma \in S_A$. Definimos $\varphi(\sigma)$ como la permutación en $S_B$ que mueve los elementos de $B$ de la misma manera que $\sigma$ mueve los elementos correspondientes en $A$. Formalmente, si $\sigma(x) = y$ para $x, y \in A$, entonces $\varphi(\sigma)(\theta(x)) = \theta(y)$ en $B$. Dado que $\theta$ es biyectiva, se puede verificar que $\varphi$ también posee una inversa y respeta la operación de composición.