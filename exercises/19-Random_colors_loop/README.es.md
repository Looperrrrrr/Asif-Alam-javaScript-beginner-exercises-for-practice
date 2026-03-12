# `19` Random Colors Loop

Hasta ahora, hemos aprendido sobre condicionales, números aleatorios, funciones y bucles ¡Ahora vamos a unirlos todos en un programa! En vez de devolver simplemente números aleatorios, podemos devolver una selección aleatoria de lo que queramos ¡Cuántas veces queramos!

Hemos creado una función llamada `getColor` que regresa un color basado en un número entero entre `1` y `4`(incluido). Cualquier número diferente regresará el color `black`(negro).

Escenario: Digamos que eres profesor en un aula de 10 estudiantes y quieres asignar de forma aleatoria **UN** color (`red`, `yellow`, `blue` o `green`) a **CADA** estudiante. 

(Solo UN color POR estudiante)

## 📝 Instrucciones:

1. Completa la función `getAllStudentColors()` para que imprima 10 colores aleatorios, un color por cada estudiante.

## 💡 Pistas: 

+ Tienes 10 estudiantes, necesitas hacer un bucle 10 veces.

+ Cada vez que hagas un loop, genera un número aleatorio entre 1-4 usando la función `Math.floor()` y `Math.random()` que vimos en los últimos ejercicios.

+ Dentro del bucle, también debes llamar a la función `getColor()` para pasarle los números generados aleatoriamente (como argumento) para obtener y devolver un color.

+ Imprime el color en la consola.

## 🔎 Importante:

+ Si sientes que no estás entendiendo los bucles y estás atascado, haz primero estos [ejercicios](https://github.com/4GeeksAcademy/javascript-arrays-exercises-tutorial).
