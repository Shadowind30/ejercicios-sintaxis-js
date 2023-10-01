# Capítulo 6: Bucles

**Notas del autor**
+ Empece a hacer este como el capitulo 5, pero luego vi que aun faltaba practicar las condicionales
+ No queria ireme tanto a la parte logica, pero no habia otra manera.

**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Hacer un bucle while que muestre por consola los numeros del 1 al 10 y otro que muestre del 100 al 1
**Ejemplos:**
```javascript
// Ejemplo de un hipotetico juego donde un personaje se mueve a la derecha mientras este vivo
const posX = 0; /// Posicion de un jugador
const isAlive = true; // Si esta vivo o no
const speed = 5; // Velocidad
while(isAlive) {
    posX += speed;
}
```

## 2. Hacer varios bucles for que muestren por consola los numeros siguentes
+ Del 1 al 20;
+ Del 15 al 81;
+ Del 156 al 58;
+ Del 30 a 90 (solo los numeros pares se mostraran por consola);
+ Un fizzBuzz [Explicacion](http://exponentis.es/el-test-de-fizz-buzz-para-contratar-programadores)
+ Del 1 al 100 pero que se detenga en el numero que estara declarado en una variable llamada limite al inicio de la app. Pista [Tomate un break](https://desarrolloweb.com/articulos/568.php)


**Ejemplos:**
```javascript
// Bucle for con numeros del 1 al 10, excepto el 7 y mostrando par en los numeros pares
for(let i = 1; i<= 10; i++) {
    if(i % 2 ===0 ) {
        console.log(i, 'Par');
    }
   else if(i === 7) {
        continue;
    }

    else {
        console.log(i);
    }
    
}

```

## 3. Crear 10 variables tipo array (minimo 3 elementos en cada array) y mostrar cada elemento por consola usando for...in
**Ejemplos:**
```javascript
cont arr = [1, 2, 3, 4, 5];
for(numero in arr) {
    console.log(numero); // numero representa a cada elemento del array (1, 2, 3, 4 y 5 en este caso. Pero puede ser cualquier nombre)
}
cont arr2 = ['a', 'b', 'c', 'd'];
for(letra in arr2) {
    console.log(letra); // letra representa a cada elemento del array ('a', 'b', 'c' y 'd' en este caso. Pero puede ser cualquier nombre)
}
```

## 4. Crear 10 variables de tipo objeto (minimo 2 keys en cada objeto) y mostrar  cada elemento por consola usando for...of
**Ejemplos:**
```javascript
cont obj1 = {
    uno: 1,
    dos: 2,
    tres: 3
}
for(key in obj1) {
    console.log(key, obj1[key]); // Key representa cada clave del objeto (uno, dos y tres en este caso. Pero puede ser cualquier nombre)
}
cont obj2 = {
    be: 'b',
    ce: 'c',
    efe: 'f'
}
for(key in obj2) {
    console.log(key, obj2[key]); // Key representa cada clave del objeto (be, ce y efe en este caso. Pero puede ser cualquier nombre)
}
```