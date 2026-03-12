---
tutorial: "https://www.youtube.com/watch?v=8PlacEppf2Y"
---

# `10` Creating a New Function

Como ya sabes, las funciones son un bloque útil de código que puedes reutilizar las veces que desees. En el último ejercicio, tuviste una función que recibía dos argumentos (dos entradas o inputs) y devolvía la suma de ellos. 

De esta forma:

```js
function addNumbers(a, b){
  return a + b;
}
```

¡Así que vamos a seguir aprendiendo más cosas! Analiza la siguiente función:

```js
function hello(myName) {
    console.log("Hello! my name is " + myName)
}

hello("Jose") // Esto imprimirá "Hello! my name is Jose" en la consola
```

En este bloque de código estamos declarando una función que recibe un argumento, `myName` que será un string que elijamos (idealmente un nombre) cuando llamemos la función, esto después imprimirá en consola el string que declaramos en el cuerpo de la función siendo `"Hello! my name is {myName}"` con el nombre que hayamos usado.

## 📝 Instrucciones:

1. Completa la función llamada `shortIntroduction()` la cual retorna una breve presentación sobre ti.

2. La función deberá tener 3 argumentos: `name`, `profession` y `age`.

3. Estos parámetros se concatenarán de la siguiente manera: `Hello! my name is {name}, my profession is {profession}. I am {age} years old.`

4. Finalmente, dentro de un `console.log()`, llama a la función con los datos en el orden correcto para terminar el ejercicio.

## 💡 Pista:

+ Recuerda usar el símbolo más (+) para concatenar diferentes strings y variables en el `console.log()`. Además, hay otras formas de concatenar strings y variables, si quieres saber más, [haz clic aquí](https://stackoverflow.com/questions/16600925/how-can-i-add-a-variable-to-console-log).
