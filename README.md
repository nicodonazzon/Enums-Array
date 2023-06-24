# Enums-Array
Los Enums y los Arrays son estructuras de conjuntos de datos que se podrán implementar según las necesidades de los desarrolladores.

Por empezar tenemos:

**Los Enums en TypeScript:**

Un enum, o enumeración, en TypeScript es una forma de definir un conjunto de valores constantes con nombres descriptivos. Proporciona una forma más legible y mantenible de trabajar con conjuntos de valores predefinidos.

Ejemplo de un enum en TypeScript:

```typescript
enum Color {
  Red,
  Green,
  Blue,
}
```

En este ejemplo, se define un enum llamado `Color` que tiene tres valores: `Red`, `Green` y `Blue`. Por defecto, los valores numéricos asignados a cada elemento son incrementales comenzando desde cero (`Red` es 0, `Green` es 1, `Blue` es 2`). Sin embargo, puedes asignar explícitamente valores personalizados si lo deseas.

Uso de un enum en TypeScript:

```typescript
let color: Color = Color.Red;
console.log(color);  // Output: 0

if (color === Color.Blue) {
  console.log("The color is blue");
}
```

En este ejemplo, se declara una variable `color` de tipo `Color` y se le asigna el valor `Color.Red`. Luego, se compara el valor de `color` con `Color.Blue` para mostrar un mensaje en la consola si coinciden.

Los enums en TypeScript proporcionan una forma clara y segura de trabajar con conjuntos de valores constantes, evitando el uso de números mágicos o cadenas literales en el código.

**Arrays en TypeScript:**

En TypeScript, los arrays son estructuras de datos que almacenan una colección de elementos del mismo tipo. Puedes declarar arrays y trabajar con ellos de manera similar a JavaScript, pero con la ventaja adicional de tener información de tipo estática.

Declaración de un array en TypeScript:

```typescript
let numbers: number[] = [1, 2, 3, 4, 5];
let names: string[] = ["John", "Jane", "Bob"];
```

En este ejemplo, se declaran dos arrays. `numbers` es un array de números, mientras que `names` es un array de cadenas. Al especificar el tipo de elementos entre corchetes (`number[]` y `string[]`), TypeScript realiza verificaciones estáticas de tipo para asegurarse de que solo se agreguen elementos del tipo especificado.

Acceso y manipulación de elementos en un array:

```typescript
let numbers: number[] = [1, 2, 3, 4, 5];

console.log(numbers[0]);  // Output: 1

numbers.push(6);
console.log(numbers);  // Output: [1, 2, 3, 4, 5, 6]

numbers.pop();
console.log(numbers);  // Output: [1, 2, 3, 4, 5]
```

En este ejemplo, se accede al primer elemento del array `numbers` utilizando la sintaxis de corchetes (`numbers[0]`). También se muestra cómo agregar elementos al final del array utilizando `push()` y cómo eliminar el último elemento utilizando `pop()`.

Además de los métodos básicos de acceso y manipulación, TypeScript proporciona varias funciones de array incorporadas y métodos de iteración que puedes utilizar para trabajar con arrays de manera eficiente.

Estos ejemplos te brindan una visión general de cómo trabajar con enums y arrays en TypeScript. Puedes ampliar tus conocimientos explorando más características y funcionalidades avanzadas de TypeScript relacionadas con enums y arrays en el desarrollo de tu curso.
