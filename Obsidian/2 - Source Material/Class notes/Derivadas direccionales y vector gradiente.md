>[!Info]
>Clase: Cálculo de varias variables
>Fecha: 25/Sept./2025
# [Manual](https://drive.google.com/file/d/1HART8nKv4Us81cWT7bBQ-lRG8ye4VKd3/view?usp=drive_open)
---
# Elementos a tener en cuenta
Si $f$ es una función diferenciable de $x$ y de $y$, entonces $f$ tiene una derivada *direccional* en la dirección de cualquier vector unitario $u = [a, b]$
$$
D_uf(x, y) = f_x(x,y)a + f_y(x,y)b
$$
Si $f$ es una función de dos variables $(x,y)$, entonces el *gradiente* de $f$ es la función
vectorial definida por:
$$
\nabla{}f(x, y)
=
\frac{\partial f}{\partial x}i
+
\frac{\partial f}{\partial y}j
$$
Donde la derivada direccional se puede calcular como el producto del gradiente de la función con el vector de dirección.
$$
\begin{split}
\vec{u} &= (x,y)
\\
D_\vec{u} f(x, y) &= \nabla{} f(x,y) * u
\end{split}
$$
Esta ecuación expresa la *derivada direccional* en la dirección de $u$ como la *proyección escalar* del vector gradiente en $u$.
En caso de que la función tenga *tres variables*, es decir, $f(x, y, z)$ se tienen las siguientes definiciones:
$$
\begin{split}
\nabla f(x,y,z)
&=
\frac{\partial f}{\partial x} i
+
\frac{\partial f}{\partial y} j
+
\frac{\partial f}{\partial z} k
\\
\\
\vec{u} &= (x,y,z)
\\
\\
D_u f(x,y,z) &= \nabla f(x,y,z) * \vec{u}
\end{split}
$$
Básicamente, la *derivada direccional* es la *tasa de cambio* de la función a medida que la entrada se mueve con el vector de dirección. Es como obtener la derivada de una función al cambiar simultáneamente las variables independientes.