>[!Info]
>Clase: Fundamentos matemáticos
>Fecha: 04/Oct/2024

---
# Matriz
Arreglo rectangular de expresiones, cuyas dimensiones se expresan en filas y columnas (f\*c)
# Suma y resta
Después de verificar que las matrices tienen dimensiones iguales se suman/restan los números que comparten posición.
$$
\begin{bmatrix}
a & b\\
c & d\\
\end{bmatrix}
\pm
\begin{bmatrix}
e & f\\
g & h\\
\end{bmatrix}
=
\begin{bmatrix}
a \pm e & b \pm f\\
c \pm g & d \pm h\\
\end{bmatrix}
$$
# Escalar
Para multiplicar la matriz por una expresión solo se realiza una multiplicación entre la expresión y cada elemento de la matriz.
$$
2*
\begin{bmatrix}
	a \\
	b \\
\end{bmatrix}
\Longrightarrow
\begin{bmatrix}
	2a \\
	2b \\
\end{bmatrix}
$$
# Multiplicación
Todo tipo debe tener dimensiones compatibles
### (FC) Fila por columnas
$F*C=\sum F_n+C_n$
$$
\begin{bmatrix}
	a & b & c \\
\end{bmatrix}
*
\begin{bmatrix}
	d \\
	e \\
	f \\
\end{bmatrix}
= \sum
$$
### (CF) Columnas por filas
Combinación de filas con cada columna
$$
\begin{bmatrix}
	a \\
	b \\
	c \\
\end{bmatrix}
*
\begin{bmatrix}
	d & e \\
\end{bmatrix}
=
\begin{bmatrix}
	a*d & a*e \\
	b*d & b*e \\
	c*d & c*e \\
\end{bmatrix}
$$
