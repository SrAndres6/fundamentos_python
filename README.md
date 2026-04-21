# fundamentos_python

# session-1

# Lab1: Hola Mundo
- comantdo: print('¡Hola, Mundo!')
La función print() muestra en pantalla el texto que está dentro de las comillas.
Las comillas dobles indican que lo escrito es una cadena de texto.

- print("Andres")
Se usa nuevamente print(), pero esta vez para mostrar tu nombre.
Python interpreta el contenido entre comillas como texto normal.

- print(Andres)
Al quitar las comillas, Python cree que Andres es una variable.
Como esa variable no existe, genera un error.

- print('Hola')
Python acepta tanto comillas dobles como simples para texto.

- print("Hola")
- print("Andres")
- print("Bienvenido")
Cada print() crea una nueva línea automáticamente.

- print("Hola"); print("Andres"); print("Bienvenido")
Al usar punto y coma (;), puedes escribir varios comandos en una sola línea.

# Lab2: funcion print y sus argumentos
- comantdo: print('Programming', 'Essentials', 'in', 'Python', sep='***', end='...')

La función print() muestra texto en pantalla, pero en este caso utiliza dos parámetros especiales:

- sep="***"
Cambia el separador entre cada palabra.
Normalmente Python separa con un espacio, pero aquí coloca tres asteriscos *** entre cada elemento.

- end="..."
Cambia lo que aparece al final de la impresión.
Normalmente print() termina con un salto de línea, pero aquí termina con tres puntos ..., haciendo que la siguiente impresión continúe en la misma línea.


# Lab3: formatos de salida

- comando: print("    *\n   * *\n  *   *\n *     *\n***   ***\n  *   *\n  *   *\n  *****")
Permite reducir varias funciones print() en una sola, mostrando cada parte en una línea diferente.

- comando: 
print("        *")
print("       * *")
print("      *   *")
print("     *     *")
print("    *       *")
print("   *         *")
print("  *           *")
print(" *             *")
print("*****       *****")
print("    *       *")
print("    *       *")
print("    *       *")
print("    *       *")
print("    *********")
Se agregan más espacios y más asteriscos para ampliar la figura sin deformarla.

- comando:
print("\nUsando multiplicacion de strings:")
espacio = " " * 2
print(("    *" + espacio) * 2)
print(("   * *" + espacio) * 2)
print(("  *   *" + espacio) * 2)
print((" *     *" + espacio) * 2)
print(("***   ***" + espacio) * 2)
print(("  *   *" + espacio) * 2)
print(("  *   *" + espacio) * 2)
print(("  *****" + espacio) * 2)
La cadena se imprime dos veces en la misma línea.

- comando:
print('    *')
print('   * *')
print('  *   *')
print(' *     *')
print('***   ***')
print('  *   *')
print('  *   *')
print('  *****')
Funciona igual que con comillas dobles.

# session-2

# Lab1: literales basicos
- comando: para enteros
- print(2)
- print(11_111_111)
- print(0o123)
- print(0x123)
2 → número entero normal.
11_111_111 → entero con guiones bajos para facilitar lectura.
0o123 → número en sistema octal.
0x123 → número en sistema hexadecimal.

- comando: para flootantes
- print(2.5)
- print(2.5e10)
- print(-0.4)
- print(6.62607E-34)
2.5 → número decimal.
2.5e10 → notación científica.
-0.4 → número decimal negativo.
6.62607E-34 → número muy pequeño en notación científica.
La letra e o E significa potencia de 10.

- comando: para cadena
- print("Me gusta \"Monty Python\"")
El texto va entre comillas.
\" permite mostrar comillas dentro del texto.
Python interpreta esto como una cadena.

- comando: paar booleand
-print(True)
- print(False)
True significa verdadero.
False significa falso.

# reto en boolean
- codigo:
- print(True > False)
- print(True < False)

- Explicación:
Python interpreta
True = 1
False = 0

- Entonces
True > False → 1 > 0 → True
True < False → 1 < 0 → False


# Lab2: cadenas literales
- comando: print("\"Estoy\"\"\"aprendiendo\"\"\"\"\"Python\"\"\"")
En esta línea se usa la función print() junto con caracteres de escape:

print() → muestra el texto en pantalla.
\ → es el carácter de escape.
\" → permite imprimir una comilla doble dentro del texto.
Al repetir varias comillas escapadas se obtiene exactamente el formato solicitado.

# session-3

- suma
print(7 + 5)

La función `print()` puede mostrar directamente el resultado de una operación matemática.
En este caso Python suma ambos valores y muestra el resultado en pantalla.

- exponenciacion
print(3 ** 2)
print(3 ** 2.)
print(3. ** 2)
print(3. ** 2.)


El operador `**` eleva un número a una potencia.

Ejemplo:

* `3 ** 2` significa 3 elevado a 2.
* Si uno de los valores es decimal, el resultado será flotante.


- multiplicacion
print(4 * 5)
print(4 * 5.)
print(4. * 5)
print(4. * 5.)

El operador `*` multiplica dos valores.

Python conserva:

* resultado entero si ambos son enteros
* resultado decimal si uno es flotante


- division
print(12 / 4)
print(12 / 4.)
print(12. / 4)
print(12. / 4.)


El operador `/` divide dos números.

Importante:
Python siempre devuelve un número decimal aunque la división sea exacta.


- division entera
print(12 // 4)
print(15 // 4)
print(-15 // 4)


El operador `//` elimina la parte decimal del resultado.

Python redondea siempre hacia abajo.


- residuo
print(17 % 5)
print(18 % 5.5)

El operador `%` devuelve el residuo de una división.

Ejemplo:
17 dividido entre 5 deja residuo 2.


- suma
print(-6 + 6)
print(-3. + 9)

El operador `+` realiza la suma entre dos valores.


- resta
print(-7 - 3)
print(9. - 4)

El operador `-` resta un valor de otro.

También puede usarse como operador unario:

print(-2.5)
print(+8)

* `-` cambia el signo
* `+` mantiene el signo


- prioridad de operadores
print(4 + 2 * 6)

Python respeta la prioridad matemática:

1. Potencias
2. Multiplicación y división
3. Suma y resta

Por eso primero multiplica y luego suma.


- enlazado de izquierda
print(11 % 7 % 3)

Los operadores del mismo nivel normalmente se evalúan de izquierda a derecha.


- exponenciacion de derecha
print(3 ** 2 ** 2)

La potencia se evalúa de derecha a izquierda.

Primero:
2 ** 2 = 4

Luego:
3 ** 4 = 81

- uso de parentesis
- codigo: print((6 * ((18 % 7) + 50) / (3 * 5)) // 2)

Los paréntesis permiten controlar el orden de ejecución de las operaciones y mejorar la legibilidad del código.

# session-4

# Lab1: variables
- codigo: 
john = 3
mary = 5
adam = 6

print(john, mary, adam)

total_apples = john + mary + adam

print(total_apples)
print("Numero total de manzanas:", total_apples)

- Explicacion:
Se crean tres variables: john, mary y adam.
Cada una almacena un número entero.
Luego se suman las tres variables y se guarda el resultado en total_apples.
Finalmente se imprime el resultado de varias formas.

# Lab2: variables: un convertidor simple
- codigo:
kilometers = 12.25
miles = 7.38

miles_to_kilometers = miles * 1.61
kilometers_to_miles = kilometers / 1.61

print(miles, "millas son", round(miles_to_kilometers, 2), "kilómetros")
print(kilometers, "kilómetros son", round(kilometers_to_miles, 2), "millas")

- Explicacion:
Se definen dos variables: kilometers y miles.
Luego se convierten una a otra usando multiplicación y división.
Finalmente se imprime el resultado redondeado a dos decimales.

# Lab3: operadores y expresiones
- codigo:
x = 1
x = float(x)

y = 3 * x**3 - 2 * x**2 + 3 * x - 5

print("y =", y)

- Explicacion:
Se define la variable x como 1 y luego se convierte a flotante.
Luego se calcula el valor de y usando la fórmula matemática.
Finalmente se imprime el resultado.