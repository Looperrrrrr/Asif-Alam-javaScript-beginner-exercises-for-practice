# `18` The "while" Loop

Como hemos mencionado en un ejercicio anterior, los bucles `while` son similares a los bucles `for`, solo que están estructurados de manera diferente.

Aquí está nuevamente:

```js
expresionInicial;
while (condicional) {
    ...declaraciones;
    expresionIncremental;
}
```
Digamos que tenemos el siguiente bucle `while`:

```js
// un bucle "while" 
let i = 0;
while (i < 10) {
    console.log("Goodbye!");
}
```

Puede que ya hayas experimentado con este bucle (loop) 

¿Notas que falta algo? 

No hay una *expresión de incremento* en nuestro bucle. Esto es un problema porque queremos incrementar la variable `i` hasta alcanzar el valor deseado para salirnos del bucle. Si no incrementamos `i`, queda permanentemente en `0`, lo que generará un bucle infinito y hará que nuestro programa deje de funcionar. 

## 📝 Instrucciones:

1. Arregla el bucle `while` para que funcione y no genere un bucle infinito.

2. Imprime del 100 al 0. 

3. Devuelve la variable `counter` cuando llegue a 0.

## 🔎 Importante: 

+ Hay ejercicios dedicados a Arrays, te recomendamos realizar esos [ejercicios](https://github.com/4GeeksAcademy/javascript-arrays-exercises-tutorial) después de que termines este ejercicio. *Cuando te sientas cómodo con este contenido, regresa y continua con estos ejercicios.*

