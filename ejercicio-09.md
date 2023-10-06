# Capítulo 9: Conversion de datos


**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Declarar 5 variables numericas, 5 tipo string y 5 tipo boolean
**Ejemplos:**
```javascript
const one = 1;
const f = 'efe';
const yes = true;
const tresStr = '3'
```

## 2. Hacer una conversion a numero de todas las variables string usando parseInt
**Ejemplos:**
```javascript
console.log(parseInt(f))
```

## 3. Hacer una conversion a string de todas las variables numerica usando toString
**Ejemplos:**
```javascript
console.log(one.toString())
```

## 4. Hacer una conversion a boolean de todas las variables numericas y string
**Ejemplos:**
```javascript
console.log(!!f);
```

## 5. Hacer una conversion a numero de todas las variables string y boolean usando +
**Ejemplos:**
```javascript
// el operador + tiene 2 usos: sumar y concatenar, el operador toma el valor de la izquierda para decidir que operacion procede
// al poner +tresStr es lo mismo que poner undefined + tresStr, por lo que javascript convertira el undefined a un numero (0) y retornara el resultado de la suma
// Como la suma de un numero + 0 es el mismo numero, el valor no cambiara, de todas como el valor era un string se termina convirtiendo en numero para hacer la suma. Si el string no tiene una representacion numerica, javascript retornara un numero especial llamado NaN, cualquier operacion aritmetica que
// se haga sobre NaN retornara NaN
console.log(+tresStr) // '3' -> 3
console.log(+f) // 'efe' -> NaN
console.log(+yes) // true -> 1 ya que cualquier numero diferente de 0 equivale a true
```

## 6. Hacer una conversion a string de todas las variables numericas y boolean usando '' + 
**Ejemplos:**
```javascript
// Como explique arriba el operador + decide la operacion en base al valor de la izquierda, si pones '' + one Javascript convertira el valor de one a
// string y hara la concatenacion, como la concatenacion es con un string vacio pues el contenido no cambiara
console.log('' + one) // 1 -> '1'
console.log('' + yes) // true -> 'true'
```