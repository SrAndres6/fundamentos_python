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