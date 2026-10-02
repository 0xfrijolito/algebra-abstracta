---
tags:
  - definicion
fecha_creacion: 2026-07-10
ultima_edicion: YYYY-MM-DD
estudiado: false
---
## Definición
Es el grupo formado por las clases de equivalencia de los enteros coprimos con $n$, bajo la operación de multiplicación modulo $n$.
$$
U(n) = \{ x \in \mathbb{Z}/n\mathbb{Z} \mid \text{gcd}(x, n) = 1 \}
$$
Donde la multiplicación modular es su operación, el elemento neutro es el $1 \;(\text{mod} (n))$ y su ***orden esta dado por la función Totiente de Euler***.
## Observaciones
- **No es un grupo bajo la suma:** La suma de dos unidades no necesariamente es invertible (ej. en $U(5)$, tenemos que $2 + 3 = 5 \equiv 0$, y el $0$ no tiene inverso multiplicativo).
- **Generadores (Raíces Primitivas):** Cuando el grupo $U(n)$ es cíclico, a sus elementos generadores se les denomina históricamente *raíces primitivas módulo $n$*. Existen exactamente $\varphi(\varphi(n))$ generadores distintos cuando el grupo es cíclico.
- **La anomalía de las potencias de 2:** Es el error más común asumir que todas las potencias de primos forman grupos cíclicos. Para $2^k$ con $k \ge 3$, el grupo **nunca** es cíclico.

## Teoremas
1. [[Condicion De Ciclicidad]]. El grupo $U(n)$ es cíclico si y solo si $n \in \{1, 2, 4, p^k, 2p^k\}$, donde $p$ es un número primo impar y $k \ge 1$. En estos casos, se cumple que $U(n) \cong \mathbb{Z}/\varphi(n)\mathbb{Z}$.
2. [[Descomposicion Por Teorema Del Resto Chino]]. Si $n$ se factoriza en enteros coprimos tal que $n = m \cdot k$ con $\gcd(m, k) = 1$, el grupo se descompone en un producto directo: $$U(mk) \cong U(m) \times U(k)$$
3. [[Teorema de Euler-Fermat]] Como corolario directo del Teorema de Lagrange aplicado a este grupo, para todo elemento $x \in U(n)$ se cumple que $x^{\varphi(n)} \equiv 1 \pmod n$.
## Proposiciones
1. **[[Automorfismos de Grupos Cíclicos]]**
2. **[[Generalización de Wilson-Gauss]]:** 
3. **[[Subgrupo de Residuos Cuadráticos]]:** Para $p$ primo impar, el homomorfismo $f(x) = x^2 \pmod p$ tiene un núcleo de orden 2 ($\{1, -1\}$). Su imagen forma un subgrupo normal de orden $\frac{p-1}{2}$, demostrando que exactamente la mitad de las unidades son cuadrados perfectos.
## Ejemplos
1. **Caso Primo (Estructura Cíclica):** Para $n = 5$, los coprimos son $U(5) = \{1, 2, 3, 4\}$. - Orden: $\varphi(5) = 4$. - Es un grupo cíclico generado por el elemento $2$ (ya que $2^1=2, 2^2=4, 2^3=3, 2^4=1$). - Isomorfismo: $U(5) \cong \mathbb{Z}/4\mathbb{Z}$.

2. **Caso Potencia de 2 (Excepción No Cíclica - Grupo de Klein):** Para $n = 8$, los coprimos son $U(8) = \{1, 3, 5, 7\}$. - Orden: $\varphi(8) = 4$. - Si elevamos cualquier elemento al cuadrado: $3^2=9\equiv 1$, $5^2=25\equiv 1$, $7^2=49\equiv 1$. - Como todos los elementos distintos de la identidad tienen orden 2, no existe ningún generador de orden 4. Por tanto, **no es cíclico**. - Isomorfismo: $U(8) \cong \mathbb{Z}_2 \oplus \mathbb{Z}_2$ (Grupo de Klein $V_4$).

3. **Caso Primos Distintos (Aplicación del Teorema Chino):** Para $n = 15 = 3 \times 5$, sus $8$ elementos son $U(15) = \{1, 2, 4, 7, 8, 11, 13, 14\}$. - Orden: $\varphi(15) = \varphi(3) \cdot \varphi(5) = 2 \times 4 = 8$. - Descomposición: $U(15) \cong U(3) \times U(5) \cong \mathbb{Z}/2\mathbb{Z} \oplus \mathbb{Z}/4\mathbb{Z}$.
***
**Metadatos de estudio:**
- **Última vez editado:** YYYY-MM-DD
- **Estudiado:** No (o Sí)