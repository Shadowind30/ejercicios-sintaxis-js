# Capítulo 10: Ambito de las variables


**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Declarar 5 variables 
**Ejemplos:**
```javascript
const one = 1;
const f = 'efe';
const yes = true;
const tresStr = '3'
```

## 2. Hacer 5 funciones que muestren el valor de cada variable
**Ejemplos:**nciona para 
```javascript
function showValue() {
    console.log(one) // 1
}
```

## 3. Hacer 5 funciones que declaren una variable que no sea ninguna de las antes declaradas y mostrar el valor
**Ejemplos:**
```javascript
function showValue() {
    const two = 2;
    console.log(two) // 2
}
```

## 4. Hacer 5 funciones que declaren una variable con el mismo nombre que cada una de las globales y que muestren su valor
**Ejemplos:**
```javascript
function showValue() {
    const f = 'no es efe';
    console.log(f); // 'no es efe' -> javascript primero busca las variables del ambito actual antes de buscar afuera
}
```

## 5. Mostrar por consola el valor de las 5 variables del ejercicio 3, pero fuera de la funciones donde se declararon
**Ejemplos:**
```javascript
console.log(two) // Error ya que la variable solo existe dentro de la funcion donde se declaro
```