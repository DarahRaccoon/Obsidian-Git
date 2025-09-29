>[!Info]
>Clase: Balance de materia y energía
>Fecha: 08/Sept/2025

---
# Balances diferenciales
Indican lo que ocurren un instante determinado. Cada término de la ecuación de balance es una velocidad (entrada, degeneración, etc.) y se da en las unidades de la cantidad balanceada dividida entre la unidad de tiempo $(\frac{kg}{t})$
Este tipo de balance se aplica a un proceso continuo.
# Balances integrales
Describe lo que ocurre entre 2 instantes determinados
Cada término de la ecuación es una porción de una cantidad que se balancea  y tiene la unidad correspondiente.
Este tipo de balance suele aplicarse a procesos intermitentes o por lotes (batch), y los 2 instantes determinados son:
1) El momento después de que se realiza la alimentación.
2) El momento anterior a que se retira el producto.
# Reglas
Las reglas siguientes pueden aplicarse para simplificar la ecuación de balance de materia:
1) Si la cantidad balanceada es la masa total, establecer que:
	1) Generación es igual a 0 $(G=0)$;
	2) Consumo es igual a 0 $(C=0)$
		1) **Excepción**: Las reacciones nucleares, pues no se puede crear o destruir la masa
2) Si la sustancia balanceada es una especia no reactiva (ni reactivo ni producto), establecer que:
	1) Generación es igual a 0 $(G=0)$;
	2) Consumo es igual a 0 $(C=0)$
3) Si un sistema se encuentra en estado estacionario, establecer que:
	1) Acumulación es igual a 0 $A=0$; sin importar lo que se esté balanceando. Por definición, en un sistema en estado estacionario nada cambia con el tiempo, incluyendo la cantidad de la variable que se balancea.
# Balances de procesos continuos
En estado estacionario no hay acumulación $(A=0)$, por tanto, la ecuación de balance queda:
$$
E+G=C+S
$$
y cuando es una especie no reactiva la ecuación es:
$$
E=S
$$
## Ejemplo 1
Cada hora se separa por destilación en 2 fracciones 1000 kg de una mezcla de benceno$(CH_6)$ y tolueno, que contiene 50% de benceno por masa. La velocidad del flujo másico del benceno en la corriente superior es de 450 $\frac{kh(B)}{h}$, y la del tolueno en la corriente inferior es de 475 $\frac{kh(T)}{h}$. La operación se encuentra en estado estacionario.
Escriba los balances del benceno y del tolueno para calcular las velocidades del flujo de los componentes en las corrientes de salida.
# Balances integrales en un proceso intermitente
## Ejemplo 1

Un reactor intermitente produce amoniaco a partir de $N$ y $H$, donde $t=0 \rightarrow (t_p)$ no hay $NH_4 \rightarrow (N_0)$ y al finalizar $(t_f)$ la reacción se retira el $NH_4$ el cual incluye moles finales de $NH_4$ $(N_f)$.
Entre $t_0$ y $t_f$ no entra ni sale $NH_4$ a través de la frontera del reactor, de modo que la ecuación de balance es la siguiente:
- $G=A$;
- $N_f-N_0$;
- $A=S-E$
- $A=G-C$
## Ejemplo 2
Se tienen 2 mezclas de metanol-agua en matraces distintos, la 1 contiene 40% en peso de metanol, y la 2 tiene 70%.
Si se combinan 220 gr de la 1 con 150 gr de la 2, ¿cuál será la masa y composición del producto?
# Balances integrales en procesos semi-continuos
se emplea un balance diferencial del sistema y después de integrarlo entre 2 instantes determinados puede ser complejo.
## Ejemplo 1
Se burbujea en un tambor de hexano a una velocidad de 0.1$\frac{kmol}{min}$. La corriente de gas que sale del tambor contiene 10% de vapor de hexano. El aire puede ser considerado insoluble en el hexano líquido.
Estime el tiempo requerido para vaporizar 10m³ de líquido
La gravedad especifica del hexano es de 0.654

## Ejemplo 2
Las fresas contienen alrededor de 15% de sólidos y 85% de agua. Para preparar mermelada de fresa se mezclan las fresas trituradas en una relación 45:55, y la mezcla se calienta para evaporar agua hasta que el residuo contenga una tercera parte de agua en masa.
Dibuje y etiquete el diagrama de flujo de este proceso y utilicelo para calcular cuantos kilogramos de fresa se necesitan para producir 1 kg de mermelada.
