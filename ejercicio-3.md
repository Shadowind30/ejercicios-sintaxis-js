# Capítulo 3: Arreglos (o arrays)

**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Declarar 10 variables tipo array usando let, cada arreglo debe de tenr por lomenos 3 elementos

**Ejemplos:**
```javascript
let array1 = [1, 'a', false];
let array2 = ['Jose', 250, 'javascript'];
```

## 2. Declarar 10 variables tipo array usando const, cada arreglo debe de tenr por lomenos 3 elementos

**Ejemplos:**
```javascript
const array3 = [true, 1, 50, 25];
const array4 = [5.5, 'concatenar', false, '4'];
```

## 3. Mostrar el primer y ultimo elemento de cada array usando console.log (no importa como, siempre y cuando el console.log muestre ambos elementos)

**Ejemplos:**
```javascript
console.log(`1: Primer elemento ${array1[0]}; Ultimo elemento ${array1[array1.length - 1]}`); // 1: Primer elemento 1; Ultimo elemento false
console.log(array2[0] + ', ' + array2[array2.length - 1]); // 'jose', 'javascript'
```

## 4. Usar Array.push para agregar un elemento a los primeros 5 arrays

**Ejemplos:**
```javascript
array1.push('este es el ultimo elemento') // array1 quedara como [1, 'a', false, 'este es el ultimo elemento'];
```

## 5. Usar Array.pop para eliminar el ultimo elemento a los arrays del 6 al 10

**Ejemplos:**
```javascript
array2.pop() // array2 quedara como ['Jose', 250];
```

## 6. Usar Array.unshift para agregar un elemento al principio de los arrays 11 al 15
**Ejemplos:**
```javascript
array3.unshift('este es el primer elemento') // array3 quedara como ['este es el primer elemento', true, 1, 50, 25];
```

## 7. Usar Array.shift para eliminar el primer elemento a los arrays del 16 al 20

**Ejemplos:**
```javascript
array4.shift() // array4 quedara como ['concatenar', false, '4'];
```