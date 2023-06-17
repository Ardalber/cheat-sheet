# on top

[map](#map) | [filter](#filter) | [isArray](#isArray) | 
--------------------------------------------------------------------------------------------------
[math.min](#math.min) | [array.from](#array.from) | [array.join](#array.join)
--------------------------------------------------------------------------------------------------
[array.slice](#array.slice) | [array.reverse](#array.reverse) | [array.includes](#array.includes)
--------------------------------------------------------------------------------------------------
[array.concat](#array.concat) |
--------------------------------------------------------------------------------------------------
[array.reduce](#array.reduce) |
--------------------------------------------------------------------------------------------------



# map 
[on top](#on-top)

```const array1 = [1, 4, 9, 16];

// Pass a function to map
const map1 = array1.map(x => x * 2);

console.log(map1);
// Expected output: Array [2, 8, 18, 32]
```

# filter
[on top](#on-top)

```function isBigEnough(value) {
  return value >= 10;
}

const filtered = [12, 5, 8, 130, 44].filter(isBigEnough);
// filtered is [12, 130, 44]
```

# isArray      
[on top](#on-top)
```
const array1 = [1, 2, 3];
console.log(Array.isArray(array1));  // Output: true

const array2 = "Hello";
console.log(Array.isArray(array2));  // Output: false

const array3 = { name: "John", age: 30 };
console.log(Array.isArray(array3));  // Output: false

const array4 = [];
console.log(Array.isArray(array4));  // Output: true
```
# math.min

[on top](#on-top)

TRES IMPORTANT DE METTRE ... QUAND C'EST UN TABLEAU
```
console.log(Math.min(2, 3, 1));
// Expected output: 1

console.log(Math.min(-2, -3, -1));
// Expected output: -3

const array1 = [2, 3, 1];

console.log(Math.min(...array1));
// Expected output: 1
```

# array.from
[on top](#on-top)
```
console.log(Array.from('foo'));
// Expected output: Array ["f", "o", "o"]

console.log(Array.from([1, 2, 3], x => x + x));
// Expected output: Array [2, 4, 6]
```


# array.join
[on top](#on-top)

```
var a = new Array("Vent","Pluie","Feu");
a.join();      // "Vent,Pluie,Feu"
a.join(", ");  // "Vent, Pluie, Feu"
a.join(" + "); // "Vent + Pluie + Feu"
a.join("");    // "VentPluieFeu"
```

# array.slice
[on top](#on-top)

```
var chaine = "Exemple";
var nouvelleChaine = chaine.slice(1, -1);

console.log(nouvelleChaine); // Affiche "xempl"
```

# array.reverse
[on top](#on-top)

```
const array1 = ['one', 'two', 'three'];
console.log('array1:', array1);
// Expected output: "array1:" Array ["one", "two", "three"]

const reversed = array1.reverse();
console.log('reversed:', reversed);
// Expected output: "reversed:" Array ["three", "two", "one"]

// Careful: reverse is destructive -- it changes the original array.
console.log('array1:', array1);
// Expected output: "array1:" Array ["three", "two", "one"]
```


# array.includes 
[on top](#on-top)

sert à verifier si une valeur es présente dans le tableau

```
[1, 2, 3].includes(2);     // true
[1, 2, 3].includes(4);     // false
[1, 2, 3].includes(3, 3);  // false
[1, 2, 3].includes(3, -1); // true
[1, 2, NaN].includes(NaN); // true

['a', 'b', 'c'].includes('c', 5);    // false
['a', 'b', 'c'].includes('c', -100); // true
```
# Array.concat
[on top](#on-top)

```
const array1 = ['a', 'b', 'c'];
const array2 = ['d', 'e', 'f'];
const array3 = array1.concat(array2);

console.log(array3);
// Expected output: Array ["a", "b", "c", "d", "e", "f"]

```


# array.reduce
[on top](#on-top)
```
[0, 1, 2, 3, 4].reduce(function(accumulateur, valeurCourante, index, array){
  return accumulateur + valeurCourante;
});

```