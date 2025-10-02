>[!Info]
>Clase: The Odin Project
>Fecha: 02/Oct/2025
# [Fuente]()
---

	Every single thing on a webpage is a rectangular box. These boxes can have other boxes in them and can sit alongside one another.

# Padding, border n margin

	The only real complication here is that there are many ways to manipulate the size of these boxes, and the space between them, using `padding`, `border`, and `margin`

- **Padding:**
	- Incrementa el espacio entre *el borde de la caja* y *el contenido de esta*.
- **Border:**
	- Añade espacio entre *el margen* y *el padding*.
- **Margin:**
	- Incrementa el espacio entre *los bordes de la caja* y los *bordes de cajas adyacentes*.

# Content n Border --box
## content-box
Se comporta como una *adición* a la caja original

```css
* {
	box-sizing: content-box;
	width: 700px;
	height: 300px;
	
	padding: 50px;
	border: 30px solid black;
}
```
![[content-box.png]]
## border-box
Se comporta como una *sustracción* a la caja original
```css
* {
	box-sizing: border-box;
	width: 700px;
	height: 300px;
	
	padding: 50px;
	border: 30px solid black;
}
```
![[border-box.png]]
