# Objetos en Javascript

Hemos visto los objetos primitivos de javascript como:

- Numbers
- Booleans
- Strings
- Symbols
- Null
- Undefined

Otros elementos de javascript muy utilizados, pero que no son primitivos, ya que tienen "superpoders" (métodos) son:

- Arreglos
- Objetos

Ejemplos

```javascript
var arr = []
var obj = {}
```

Los arreglos se declaran utilizando `[]` y los objetos se declaran con llaves `{}`.

Los arreglos tienen sus elementos ordenados por índices, en cambio los objetos no tienen indices. Sus elementos se rescatan u obtienen mediante **llaves**. Ejemplo

```javascript
var hero = {
  name: "Thor",
  weapon: "Martillo",
  hair: "Rubio"
}

console.log(hero["name"])
console.log(hero["weapon"])
console.log(hero["hair"])
```

