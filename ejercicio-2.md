# Capítulo 2: Cadenas de textos

**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Declarar 10 variables con nombres (5 con let y 5 con const)

**Ejemplos:**
```javascript
let name1 = 'Juan';
const name2 = 'Jose';
```

## 2. Declarar 10 variables con apellidos (5 con let y 5 con const)

**Ejemplos:**
```javascript
let surname1 = 'Perez';
const surname2 = 'Ramirez';
```

## 3. concatenar los 10 nombres con los 10 apellidos y mostrarlos por consola

**Ejemplos:**
```javascript
console.log(name1 + ' ' + surname1); // Juan Perez
console.log(name2 + ' ' + surname2); // Jose Ramirez
```

## 4. usar template literals para mostrar los nombres y apellidos de forma ordenada

**Ejemplos:**
```javascript
console.log(`[1] ${name1} ${surname1}`); // [1] Juan Perez
console.log(`[2] ${name2} ${surname2}`); // [2] Jose Ramirez
```

## 5. Mostrar los nombres y la longitud de los mismos usando String.length (5 concatenaciones y 5 template literals) 

**Ejemplos:**
```javascript
console.log(name1 + ' tiene ' + name1.length + ' caracteres'); // Juan tiene 4 caracteres
console.log(`${name2} tiene ${name2.length} caracteres`); // Jose tiene 4 caracteres
```