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
