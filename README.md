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
comantdo: print('Programming', 'Essentials', 'in', 'Python', sep='***', end='...')

La función print() muestra texto en pantalla, pero en este caso utiliza dos parámetros especiales:

- sep="***"
Cambia el separador entre cada palabra.
Normalmente Python separa con un espacio, pero aquí coloca tres asteriscos *** entre cada elemento.

- end="..."
Cambia lo que aparece al final de la impresión.
Normalmente print() termina con un salto de línea, pero aquí termina con tres puntos ..., haciendo que la siguiente impresión continúe en la misma línea.


# Lab3: formatos de salida

comando: print("    *\n   * *\n  *   *\n *     *\n***   ***\n  *   *\n  *   *\n  *****")
Permite reducir varias funciones print() en una sola, mostrando cada parte en una línea diferente.

comando: 
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

comando:
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

comando:
print('    *')
print('   * *')
print('  *   *')
print(' *     *')
print('***   ***')
print('  *   *')
print('  *   *')
print('  *****')
Funciona igual que con comillas dobles.

# session 2

