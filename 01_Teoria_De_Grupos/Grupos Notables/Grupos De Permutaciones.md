---
tags:
  - álgebra
  - definicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Definición
Sea $X$ un conjunto no vacío. El conjunto $S(X)$ de las permutaciones de $X$ es un grupo con la composición:
$$
S(X) = \{ f : X \to X \mid f\ \text{biyectiva}\}
$$
Si $X = \{ 1, ..., n\}$ el grupo de las permutaciones se denota como $S_{n}$ y se llama grupo simétrico sobre $n$ elementos. Los elementos de $S_{n}$ se llaman permutaciones.

### Estructura
1. **Permutaciones:** Una permutación $\sigma \in S_{n}$ es un ***$k$-ciclo*** si es de la forma $(i_{1}, ... , i_{k})$ con $i_k \in \{1, ..., n\}$ En este caso el conjunto $\{i_{1}, ... , i_{k} \}$ es el soporte del ciclo y $k$ es el largo del ciclo. Ver [[#^ejemplo-1|ejemplo 1]].

2. **Soporte:** Decimos que un elemento $\alpha \in S_{n}$ mueve a $i$ si $\alpha(i) \neq i$ y que $\alpha$ **fija a $i$** si $\alpha(i) = i$. El soporte de $\alpha$ es$$\text{supp}\ \alpha = \{ i \in {1,..., n} \mid \alpha(i) \neq i \}$$
3. **Ciclos:** Sean $\alpha \in S_{n}$ y $r \in \mathbb{Z}$ con $r > 1$. Decimos que $\alpha$ es un **ciclo de longitud r** o un **$r$-ciclo** si existen $i_{1}, ..., i_{r} \in \{ 1, ..., n\}$ distintos tales que $\text{supp}\ \alpha = \{i_{1}, ..., i_{r}\}$ y $$\begin{align*}
\alpha(i_t) = \begin{cases}
i_{t+1} & \text{si } t \in \{1, \dots, r-1\} \\
i_1 & \text{si } t = r.
\end{cases}
\end{align*}$$Donde la permutación ${id} \in S_{n}$ es un **ciclo de longitud** 1. Los ciclos de longitud 2 se llaman **transposiciones**. Ver [[#^ejemplo-2|ejemplo 2]].
### Permutaciones Disjuntas
Sean $\alpha, \beta \in S_{n}$. Decimos que $\alpha$ y $\beta$ son **disjuntas** o **ajenas** si el $\text{supp}\ \alpha \cap \text{supp}\ \beta = \emptyset$ es decir que dado $i \in \{1,...,n\}$ se tiene que
$$
\alpha(i) \neq i \Rightarrow \beta(i) = i
$$
Además es útil notar que toda permutación tiene expresión disjunta gracias a la siguiente [[Las Permutaciones Tienen Expresión De Soportes Disjuntos|proposicion]].

### Factorización Completa
Sea $\alpha \in S_{n}$. Una factorización completa de $\alpha$ es una descomposición de $\alpha$ en ciclos disjuntos con un 1-ciclo por cada elemento fijado por $\alpha$.
$$
\begin{align*}
\alpha = \begin{pmatrix}
1 & 2 & 3 & 4 & 5 & 6 & 7 & 8\\
3 & 2 & 1 & 5 & 7 & 6 & 4 & 8
\end{pmatrix}.
\end{align*}
$$
Entonces $\alpha = (1\ 3)(4\ 5\ 7)$ es una factorización de $\alpha$ en ciclos disjuntos pero no es una factorización completa de $\alpha$. Por otro lado $\alpha = (1\ 3)(4\ 5\ 7)(2)(6)(8)$ también es una factorización completa de $\alpha$.

Una factorización completa es **única** salvo por el orden de los factores.
### Estructura Cíclica y Polinomio Vandermonde
Sea $f \in \mathbb{R}[x_{i}, ..., x_{n}]$. Dado $\sigma \in S_{n}$ se define $\sigma \cdot f$ como el polinomio que se obtiene aplicando $\sigma$ a los índices de las variables. Ver [[#^ejemplo-4|Ejemplo 4]].

Sea un entero positivo $n$ definimos el polinomio de Vandermonde como
$$
\triangle_{n}(x_{1}, ..., x_{n}) := \prod_{1 \leq i \leq j \leq n}(x_{i} - x_{j})
$$
Donde si $\sigma \in S_n$ entonces $\sigma \cdot \triangle_{n} = \pm\triangle_{n}$ porque los factores son los mismo salvo un posible cambio de signo.

De este modo podemos definir el signo de $\sigma \in S_{n}$ como $\text{sign}(\sigma) \in \{1, -1\}$ tal que
$$
\sigma \cdot \triangle_{n} = \text{sign}(\sigma)\triangle_{n}.
$$
Si $\text{sign}(\sigma) = 1$ se dice que $\sigma$ es *par*, en caso contrario se dice que es impar.
## Observaciones
1. $|S_{n}| = n!$ 

## Teoremas
1. [[Teorema De Cayley]]
## Proposiciones
1. [[Las Permutaciones Tienen Expresión De Soportes Disjuntos]]
2. [[Las Permutaciones Disjuntas Conmutan]]
3. [[Cada permutación Tiene Expresión De Transposiciones]]
4. [[El Conjunto De Transposiciones Es Un Generador Para S]]
## Ejemplos
1. **Permutación en $S_{10}$**: 
   Sea $\alpha \in S_{10}$, esta definida como $$\begin{align*}
\alpha = \begin{pmatrix}1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 10\\
8 & 3 & 1 & 7 & 2 & 6 & 4 & 5 & 9 & 10 \end{pmatrix}.
\end{align*}$$
   La matriz es una manera de representar una permutación, la fila de arriba son todos los elementos de $X = \{1,2,3,3,4,5,6,7,8,9,10\}$ y la fila de abajo son las imagen de los elementos justo arriba de ellos. 

   En el contexto de un grupo no tiene sentido *aplicar* $\alpha$ a un solo elemento si no a todos los elementos de $X$ al mismo tiempo.
   ^ejemplo-1
2. **Ciclos de $S_{8}$:**  
   Sea $\alpha \in S_8$ definida por $$\alpha = \begin{pmatrix} 1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 \\ 1 & 4 & 3 & 5 & 8 & 2 & 7 & 6 \end{pmatrix}$$
   Podemos expresar $\alpha$ con su notaciones de ciclos como $$\begin{align*}
\alpha &= (2 \; 4 \; 5 \; 8 \; 6) = (4 \; 5 \; 8 \; 6 \; 2) \\
& = (5 \; 8 \; 6 \; 2 \; 4) = (8 \; 6 \; 2 \; 4 \; 5) \\
& = (6 \; 2 \; 4 \; 5 \; 8).
\end{align*}$$
   En este caso $\alpha$ es un $5$-ciclo por lo tanto tiene orden 5.
   ^ejemplo-2
3. **Ciclos Disjuntos:**
   Sean las permutaciones $\alpha, \beta \in S_{5}$ donde $\alpha = (1\ 2\ 3)$ y $\beta = (4\ 5)$. Donde el $\text{supp}$ de cada permutación nos queda como $$\begin{aligned} \text{supp}\ \alpha &= \{1, 2, 3\} \\ \text{supp}\ \beta &= \{4, 5\} \end{aligned}$$Donde claramente se ve que  $\text{supp}\ \alpha \cap \text{supp}\ \beta = \emptyset$.
   ^ejemplo-3
4. **Estructura Simétrica:**
   Sean $f(x_{i}, x_{2}, x_{3}) = x_{1}^{3} + 2x_{2}x_{3} + x_{3}^{2}$ y $\sigma = (1\ 2)$ una permutación entonces $$\sigma \cdot f(x_{1}, x_{2}, x_{3}) = x_{2}^{3} + 2x_{1}x_{3} + x_{3}^{2}$$
   ^ejemplo-4
5. 
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)