# Capítulo 4: Objetos

**Reglas:**
- Usar block de notas para los ejercicios.
- No usar copy-paste.

## 1. Declarar 10 objetos usando const, con nombre, edad y ocupacion
**Ejemplos:**
```javascript
const obj1 = {name: 'el man', edad: 25, ocupacion: 'pega blo'};
const obj2 = {name: 'random', edad: 20, ocupacion: 'Frontend Developer'};
```

## 2. Acceder a cada propiedad de cada objeto usando dot notation

**Ejemplos:**
```javascript
console.log(`Nombre: ${obj1.nombre}, Edad: ${obj1.edad}, Ocupacion: ${obj1.ocupacion}`); // Nombre: el man, Edad 25, Ocupacion: pega blo
console.log(`${obj2.nombre} tiene ${obj2.edad} años y trabaja como ${obj2.ocupacion}`); // random tiene 20 años y trabaja como Frontend Developer;
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
