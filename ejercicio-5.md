# Capítulo 5: Estructuras condicionales

**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Comprobar usando if, si una variable numero es igual a los numeros del 1 al 25
**Ejemplos:**
```javascript
const numero = 0;
if(numero === 1) {
    console.log(numero);
}
if(numero === 2) {
    console.log(numero);
}
```

## 2. Comprobar usando if else, si una variable numero es igual a los numeros del 25 al 50, y si no mostrar por consola que no lo es
**Ejemplos:**
```javascript
const numero = 0;
if(numero === 25) {
    console.log(numero);
} else {
    console.log('No es igual a 25');
}
if(numero === 26) {
    console.log(numero);
} else {
    console.log('No es igual a 26');
}
```

## 3. Comprobar usando if else y else if, si una variable numero es igual a los numeros del 51 al 60, y si es otro numero por consola que no lo es y mostrar el valor en cuestion, si no es un numero mostrar que no es un numero. Una vez terminado repetir para los numeros del 61 al 70

**Ejemplos:**
```javascript
const numero = 'hola madre';
if(numero === 51) {
    console.log(numero);
} else if (typeof numero === 'number') {
    console.log(`No es igual a 51, pero es ${numero}`);
} else {
    console.log('no es un numero')
}
```

## 4. Comprobar usando if else de una linea, si los numeros del 71 al 80 son pares o impares

**Ejemplos:**
```javascript
if(70 % 2 === 0) console.log('70 es par');
else console.log('70 es impar');
```

## 5. Usar un Switch Case para mostrar el equivalente en letras a los numeros del 81 al 100;
**Ejemplos:**
```javascript
const numero = 81;
switch(numero) {
    case 81: {
        console.log('Ochenta y uno');
        break;
    }
    case 82: {
        console.log('Ochenta y dos');
        break;
    }
    case 83: {
        console.log('Ochenta y tres');
        break;
    }
}
```
