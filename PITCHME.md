## Data Structures

---

## Arrays

+++

```js
    const numArray: number[] = [1,2,3,4]
    const anyArray: any[] = [1,"2", [3], {a: 4}]
```

+++

### Accessing Arrays
```js
    const numArray: number[] = [1,2,3,4]
    const item1 = numArray[0]
    const item2 = numArray[1]
```

+++

### Iterating through Arrays
```js
    const charsArray: string[] = ["a","b","c","d"]
    for(i in charsArray){
        console.log(charsArray[i])
    }
```

---

## Objects

+++

```js
    const object = {a: 1, b:2}
```

+++

### Accessing Objects

```js
    const object = {a: 1, b:2}
    const item_a = object.a
    const item_b = object["b"]
```

+++

### Iterating through Objects
```js
    const object = {a: 1, b:2}
    for(i in object){
        console.log(i)
        console.log(object[i])
    }
```

---

## For Loops
```js
    const charsArray: string[] = ["a","b","c","d"]
    for(let i; i < charsArray.length; i ++){
        console.log(charsArray[i])
    }
```