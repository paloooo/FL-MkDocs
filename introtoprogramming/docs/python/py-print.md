---
hide:
  - navigation
---
# La función `print()`
***
## **Descripción**


## **La sintaxis**

Después del comando print hay un par de paréntesis `( )`. Dentro de estos paréntesis está lo que se va a imprimir (presentar) en la pantalla o en la consola. 

> :pushpin: **¡RECUERDA!**
>
>Usar paréntesis para pasar información a una función es una práctica muy común en las matemáticas y en la mayoría de los lenguajes de programación.

***
## **`Strings`**

Para imprimir **`strings`** ***(cadenas de texto)*** hay que añadir comillas (`" "`) antes y después del **`string`** a imprimir. 

*Observa el código a continuación :point_down::*

```python title="Ejemplo de la función de print" linenums="1" hl_lines="1"
print("Hola Mundo")
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169389558-49e8c7e7-f12a-4fc4-952c-eaae1aa79879.png "Captura de pantalla de replit.com. Se muestra el código y el resultado.")

Pero, si no se escriben las comillas (`" "`), ***Python :snake:*** va a interpretar que estás tratando de escribir una ***expresión***. 
*Observa el código a continuación :point_down::* 
```python title="Un error al tratar de imprimir un texto (string)" linenums="1" hl_lines="1"
print(Hola Mundo)#Esto va a devolver un error.  
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169391175-ef79fd27-3be1-4541-b175-c901b1ca68a4.png "Captura de pantalla de replit.com. Se muestra el editor de código y el error producido en la consola.") 

***
## **Números**

Para imprimir números, no se necesitan las comillas (`" "`). 

*Observa el código a continuación :point_down::*

```python title="La función de print con números" linenums="1" hl_lines="1"
print(3 + 2)# En este caso va a imprimir 5
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169395262-62a6cdec-1c7e-4523-99b9-b759ab6dbc56.png "Captura de pantalla de replit.com. Se muestra la función de print aplicada a una suma.")

Pero, si añadimos las comillas (`" "`), entonces ***Python :snake:*** va a interpretar que estás tratando de imprimir un `string`. 

*Observa el código a continuación :point_down::*

```python title="La función de print con números interpretados como texto (strings)" linenums="1" hl_lines="1"
print("3 + 2")# En este caso va a imprimir 3 + 2
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169401172-25c60ad8-dbbb-478c-b8c9-318472771d95.png "Captura de pantalla de replit.com. Se muestra la función de print presentando una suma cómo un string.")

***
### **Expresiones Matemáticas** 

***
## **Variables**

Para poder imprimir el contenido o valor de una variable primero tenemos que tener una variable con un valor asignado. Para asignar valores a una variable usamos el [operador de asignación](https://introtoprogramminglab-025.palo-ooo.repl.co/#operador-de-asignacion). Una vez tenemos un valor asignado, podemos hacer referencia al nombre de la variable. En el ejemplo a continuación se le asigna un valor de 3 a la variable **`x`** 

*Observa los códigos a continuación :point_down::*

```python title="La función de print ( ) haciendo referencia a una variable" linenums="1" hl_lines="1"
x = 3
print(x)
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169404043-151aea9d-10c3-4e56-8f0c-22f44a45b449.png "Captura de pantalla de replit.com. Se muestra cómo imprimir el valor de una variable.")

La variable puede contener un `string`; 
```python title="La función de print ( ) haciendo referencia a una variable" linenums="1" hl_lines="1"
x = "Puerto Rico"
print(x)
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169405044-f3ec23a7-9aec-41cf-8b29-97bc1b1e5b24.png "Captura de pantalla de replit.com. Se muestra cómo imprimir el valor de una variable. En este caso un string.")

### **Expresiones de comparación** 

ó, Puede contener una expresión. En este caso **Python :snake:** va a imprimir el resultado de la expresión luego de ser evaluada. 
```python title="La función de print ( ) haciendo referencia a una variable" linenums="1" hl_lines="1"
x = (3 < 2)
print(x)
```
![Captura de Replit.com - Python](https://user-images.githubusercontent.com/67485637/169405531-7eb56f97-dd2f-46d4-8802-dd47a47b08ac.png "Captura de pantalla de replit.com. Se muestra cómo imprimir el valor de una variable. En este caso el resultado o la evaluación de la expresión." )

<iframe frameborder="0.25" width="775px" height="300px" src="https://replit.com/@Forwardlearning/La-funcion-de-print?embed=true"></iframe>

***