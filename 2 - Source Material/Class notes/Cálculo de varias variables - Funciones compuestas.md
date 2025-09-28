>[!Info]
>Clase: Cálculo de varias variables
>Fecha: 19/Sept./2025

---
# [Manual](https://drive.google.com/drive/u/0/folders/1i1PDhfiXo9lov6iWS07USewCkczIm2fW)
# Introducción
El concepto de funciones compuestas se refiere a una situación en que existe una función donde las variable que la componen son otras funciones con sus propias variables.
Un ejemplo sería tener $z=2y$, y que a su vez que $y$ sea una función que consista en $y=2x$. Así pues tendríamos que la función completa sería $z=2(2x)$.
Podríamos entonces llamar:
- $z$ la función;
- $y$ una variable de la función $z$;
- y a$x$ la podriamos llamar tanto una "subvariable" de la función $z$, como una variable de la función $y$
# Ordenamiento general
Para obtener una subvariable de interés, podemos aplicar la *regla de la cadena*, la cual es simplemente obtener las derivadas parciales de las diferentes variables que tengamos y luego ordenarlas de cierta manera.
$$
{\frac {\partial \text{ F}} {\partial \text{ Subvar}}
=
\sum_{\text{Var(a)}}^{\infty}
\frac {\partial \text{ F}} {\partial \text{ Var(a)}}
*
\frac {\partial \text{ Var(a)}} {\partial \text{ Subvar}}}
$$
Un ejemplo de este ordenamiento podría verse abajo para una función $T$ la cual dependa de las variables $x$ y $y$, y a su vez cada una de estas dependa de $r$ y $s$
1) $\frac{\partial T}{\partial r}=\frac{\partial T}{\partial x}*\frac{\partial x}{\partial r}+\frac{\partial T}{\partial y}*\frac{\partial y}{\partial r}$
2) $\frac{\partial T}{\partial s}=\frac{\partial T}{\partial x}*\frac{\partial x}{\partial s}+\frac{\partial T}{\partial y}*\frac{\partial y}{\partial s}$
# 2.1 - Ejercicio 10
Dado: $T(x,y)=x³ - xy + y³$
- Función de $x$: $x = r * cos(s)$
- Función de $y$: $y = r * Sen(s)$

Obtener: $\frac{\partial T}{\partial r}$ y $\frac {\partial T}{\partial s}$
1) Obtener parciales de $T$
	1) $\frac{\partial T}{\partial x}=3x²-y$
	2) $\frac{\partial T}{\partial y}=-x+3y²$
2) Obtener parciales de cada variable $(x,y)$ respecto a las "subvariables"$(r,s)$
	1) $\frac{\partial x}{\partial r}=cos(s)$
	2) $\frac{\partial x}{\partial s}=-r*sen(s)$
	3) $\frac{\partial y}{\partial r}=sen(s)$
	4) $\frac{\partial y}{\partial s}=r*cos(s)$
3) Ordenar parciales $\frac{\partial T}{\partial r}$ y $\frac{\partial T}{\partial s}$
	1) $\frac{\partial T}{\partial r}=(3x²-y)*(cos(s))+(-x+3y²)*(sen(s))$
	2) $\frac{\partial T}{\partial s}=(3x²-y)*(-r*sen(s))+(-x+3y²)*(r*cos(s))$
# 2.1 - Ejercicio 11
Dado $U(x,y,z)=z*sen(\frac{y}{x})$
- Función de $x$ : $x=3r²+2s$
- Función de $y$ : $y=4r-2s³$
- Función de $z$ : $z=2r²-3s²$

Obtener: $\frac{\partial U}{\partial r}$ y $\frac {\partial U}{\partial s}$
1) Obtener parciales de $T$
	1) $\frac{\partial x}{\partial r}=-\frac{yzcos(\frac{y}{x})}{x²}$
	2) $\frac{\partial y}{\partial s}=-\frac{yzcos(\frac{y}{x})}{x}$
	3) $\frac{\partial U}{\partial z}=sen(\frac{y}{x})$
2) Obtener parciales de cada variable $(x,y)$ respecto a las "subvariables"$(r,s)$
	1) $\frac{\partial x}{\partial r}=6r$
	2) $\frac{\partial x}{\partial s}=2$
	3) $\frac{\partial y}{\partial r}=4$
	4) $\frac{\partial y}{\partial s}=6s²$
	5) $\frac{\partial z}{\partial r}=4r$
	6) $\frac{\partial z}{\partial s}=-6s²$
3) Ordenar parciales $\frac{\partial T}{\partial r}$ y $\frac{\partial T}{\partial s}$
	1) $\frac{\partial T}{\partial r}=(-\frac{yzcos(\frac{y}{x})}{x²})*(6r)+(-\frac{yzcos(\frac{y}{x})}{x})*(4)+(sen(\frac{y}{x}))*(4r)$
	2) $\frac{\partial T}{\partial s}=(-\frac{yzcos(\frac{y}{x})}{x²})*(2)+(-\frac{yzcos(\frac{y}{x})}{x})*(6s²)+(sen(\frac{y}{x}))*(-6s²)$
	