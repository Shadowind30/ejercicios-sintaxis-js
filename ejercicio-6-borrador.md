# Capítulo 6: Bucles (Todavia no esta completado)

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

## 3. Acceder a cada propiedad de cada objeto usando bracket notation

**Ejemplos:**
```javascript
console.log(`Nombre: ${obj1['nombre']}, Edad: ${obj1['edad']}, Ocupacion: ${obj1['ocupacion']}`); // Nombre: el man, Edad 25, Ocupacion: pega blo
console.log(`${obj2['nombre']} tiene ${obj2['edad']} años y trabaja como ${obj2['ocupacion']}`); // random tiene 20 años y trabaja como Frontend Developer;
```

## 4. Crear una propiedad salario en cada objeto

**Ejemplos:**
```javascript
obj1.salario = 1500; // obj1 quedara como {name: 'el man', edad: 25, ocupacion: 'pega blo', salario: 1500}
obj2.salario = 2000; // obj2 quedara como {name: 'random', edad: 20, ocupacion: 'Frontend Developer', salario: 2000};
```

## 5. borrar la propiedad edad en cada objeto usando dot notation

**Ejemplos:**
```javascript
delete obj1.edad; // obj1 quedara como {name: 'el man', ocupacion: 'pega blo'}
delete obj2.edad; // obj2 quedara como {name: 'random', ocupacion: 'Frontend Developer'};
```

## 6. borrar la propiedad ocupacion en cada objeto usando bracket notation

**Ejemplos:**
```javascript
delete obj1['ocupacion']; // obj1 quedara como {name: 'el man', edad: 25};
delete obj2['ocupacion']; // obj2 quedara como {name: 'random', edad: 20};
```
