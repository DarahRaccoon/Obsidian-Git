>[!Info]
>Clase: Bioquímica
>Fecha: --/--/----

---
# pK
Primero, debemos recordar las reacciones reversibles, las cuales son aquellas que pueden proceder tanto hacia adelante como hacia atrás, y cuando se llega al punto en el cual tanto el proceso hacia adelante como el proceso inverso suceden a la misma velocidad, se dice que se llegó a un estado de equilibrio químico. Es importante recordar que aunque las concentraciones son constantes en el equilibrio la reacción no se ha detenido, y es por eso que a este estado también se le llama equilibrio dinámico.
De acuerdo con las concentraciones de todas las especies de la reacción en equilibrio, podemos definir una cantidad llamada la constante de equilibrio ($K$), la cual describe las concentraciones molares en el equilibrio para una temperatura específica.
[Khan Academy](https://es.khanacademy.org/science/ap-chemistry/chemical-equilibrium-ap/equilibrium-constant-ap/a/the-equilibrium-constant-k)

La magnitud de la constante de equilibrio refleja explícitamente la composición de una mezcla de reacción en el equilibrio y puede interpretarse con respecto a la extensión de la reacción directa. Una reacción que presenta una constante K grande alcanzará el equilibrio cuando la mayor parte del reactivo se haya convertido en producto, mientras que una constante K pequeña indica que la reacción alcanza el equilibrio después de que se haya convertido muy poco reactivo. Es importante tener en cuenta que la magnitud de K no indica la rapidez o lentitud con que se alcanzará el equilibrio.
[Química 2ed - Flowers & Langley - 2022](https://openstax.org/books/qu%C3%ADmica-2ed/pages/13-2-constantes-de-equilibrio)

Se define pA de un número A como el logaritmo negativo de A. De tal manera que pK es el logaritmo negativo de la constante de equilibrio:
$$
pK = -log(K)
$$
[UAG](https://libroelectronico.uaa.mx/capitulo-3-ph-y-soluciones/concepto-de-pk.html)
# Efecto del pH en los aminoácidos
Todo aminoácido tiene un grupo amino y un grupo carboxilo, y cada grupo puede existir en forma ácida o en forma básica dependiendo del pH de la solución en la que se encuentre en ese momento.
Las estructuras de las formas ácida y básica de cada grupo es:
## Grupo carboxilo
### Forma ácida
```smiles
CC(=O)O
```
### Forma básica
```smiles
CC(=O)[O-]
```
## Grupo amino
### Forma ácida
```smiles
CC[NH3+]
```
### Forma básica
```smiles
CC[NH2]
```
---
Como regla general, se espera que en solución una especie esté en su forma ácida si el pH del medio es menor al valor de su pKa, y que esté en su forma básica si el pH del medio es mayor al valor de su pKa.
Los valores de pKa para los grupos ionizables de cada aminoácido están resumidos en la siguiente tabla:
![[Valores de pKa.png]]
[Tabla](https://uruguayeduca.anep.edu.uy/sites/default/files/inline-files/1%20Propiedades%20%C3%A1cido-base%20de%20los%20amino%C3%A1cidos.pdf)
# Anfoterismo de los aminoácidos
Los *aminoácidos disueltos en agua* presentan un *comportamiento anfótero*, es decir:
- Pueden ionizarse, comportándose como ácido o como base, dependiendo del pH.
Esta característica se debe a la existencia del grupo carboxilo y del grupo amino:
- Cuando el pH es *alcalino*, se comporta como *ácido*.
	- Los grupos COOH liberan protones, quedando como COO-.
	- ```smiles
	  C(=O)O>>[H+].C(=O)[O-]
	  ```
- Cuando el pH es *ácido*, se comporta como *base*.
	- Los grupos NH2 captan protones, quedando como NH3+.
	- ```smiles
	  [NH2].[H+]>>[NH3]
	  ```

Debido a su comportamiento anfótero, los aminoácidos tienden a neutralizar las variaciones de pH del medio, ya que pueden comportarse como un ácido o una base, liberando o retirando protones del medio. Esta propiedad es importante en la homeostasis porque atenúan las variaciones de pH del medio, funcionando como un sistema tampón o amortiguador del pH.  
Cada aminoácido tiene un pH en el que tiende a adoptar una forma dipolar neutra (o zwitterión), con tantas cargas positivas como negativas, que se denomina punto isoeléctrico.
[Biología-Geología.com](https://biologia-geologia.com/biologia2/422_propiedades_de_los_aminoacidos.html)
