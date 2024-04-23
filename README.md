# arrays
- Un Array es una zona de almacenamiento continuo, donde se puedenintroduzir varios valores, cada uno de ellos ubicados por la posicición ue ocupa en el array.
- También son denominados arreglos o vectores, y cuando son de dos dimensiones son llamados matrices.
- Los arrays nos brindran la capacidad de almacenar una colección de elementos y acceder a ellos de manera individual
- Cada elemento se identifica mediante su posición en el array, denominada indice **indice** y estos indices so siempre secuenciales.
- En Javascript son altamente flexibles en términos de los diferentes tipos de datos que podemos almacenar en cada posición del array

## crear array 

1. Decarando un array con elelmentos en linea 

```javascript
let miArray= [1,2,3]
console.log(miArray)
```

2. declarando un array con la sintaxis **newArray()**
```javascript
let miArray= new Array(1,2,3)
console.log(miArray)
```
3. declarando un array con un tamaño especifico utilizando la sintaxis **new array** y asignando valores despues:
```javascript
let miArray= new Array(3)
miArray[0] = 1;
miArray[0] = 2;
miArray[0] = 3;
console.log(miArray)
```
4. 
```javascript
let miArray4= [1. "dos", true, {nombre: "juan" edad: 30 }] 
miArray4[0] = 1;
miArray4[0] = 2;
miArray4[0] = 3;
console.log(miArray4);
```