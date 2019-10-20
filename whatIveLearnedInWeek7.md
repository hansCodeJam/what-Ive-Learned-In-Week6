# What I've Learned in week 7


### While Loops

```Javascript
function theNumberIs(){
    let text = "";
    let i = 0;
    while (i < 10) {
      text += "The number is " + i + "\n" ;
      i++;
    }
    return text;
}

theNumberIs();
// The number is 0
// The number is 1
// The number is 2
// The number is 3
// The number is 4
// The number is 5
// The number is 6
// The number is 7
// The number is 8
// The number is 9
```

### String Interpolation

Cleaner way of writing concatenation

```Javascript
let x = 1;
let y = 2;
let total = x + y;
console.log(`The addition of ${x, y} is ${total}`)


let custume = ['spidey suit', 'banana custom', 'power ranger',  'ups driver'];
let random = custume[Math.floor(Math.random()*custume.length)];

console.log(`I will wear ${random} for Helloween`);
// I will wear ups driver for Helloween
```

### Increment and Decrement

```javascript
// Increment
num = num + 1
num += 1
num++

num = num + 2
num += 2

//Decrement
num = num - 1
num -= 1
num--

num = num - 2
num -= 2
```

### Array

We use array to keep things in order

```javascript
let cars = ['BMW', 'Volvo', 'Acura'] //Arrays
function randomCar(){
    return cars[Math.floor(Math.random() * cars.length)];
}
randomCar();
//BMW

console.log(cars[0])
//BMW
console.log(cars[1])
//Volvo

