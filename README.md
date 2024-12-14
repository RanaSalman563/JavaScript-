


_1. Calculate Age_


```
const birthYear = 1990; // replace with your birth year
const currentYear = 2024; // replace with current year

const age = currentYear - birthYear;
console.log(`Your age is: ${age}`);
```


_2. Rectangle Area_


```
const length = 5;
const width = 3;

const area = length * width;
console.log(`The area of the rectangle is: ${area}`);
```


_3. Circle Area_


```
const radius = 4;

const area = Math.PI * (radius ** 2);
console.log(`The area of the circle is: ${area}`);
```


_4. Cube Area_


```
const side = 5;

const area = 6 * (side ** 2);
console.log(`The surface area of the cube is: ${area}`);
```


_5. Temperature Conversion_


```
const temperature = 32; // Fahrenheit
const unit = "F"; // or "C" for Celsius

let convertedTemperature;

if (unit === "F") {
  convertedTemperature = (temperature - 32) * 5 / 9;
  console.log(`${temperature} Fahrenheit is equal to ${convertedTemperature} Celsius.`);
} else if (unit === "C") {
  convertedTemperature = (temperature * 9 / 5) + 32;
  console.log(`${temperature} Celsius is equal to ${convertedTemperature} Fahrenheit.`);
} else {
  console.log("Invalid unit. Please enter F for Fahrenheit or C for Celsius.");
}
```


_6. Time Conversion_


```
const seconds = 120;

const minutes = Math.floor(seconds / 60);
const remainingSeconds = seconds % 60;

console.log(`${minutes} minutes and ${remainingSeconds} seconds.`);
```


_7. Percentage Calculation_


```
const number = 100;
const percentage = 25;

const result = (number / 100) * percentage;
console.log(`The percentage of ${number} is ${result}.`);
```


_Increment and Decrement Operator Questions_


I'll answer these questions directly:


Q1: `let a = 2; let b = ++a * 2; // b?`
Answer: `b` will be 8.


Q2: `let x = 5; let y = x-- + 2; // y?`
Answer: `y` will be 7.


Q3: `let x = 3; let y = ++x + x++ + ++x; // y?`
Answer: `y` will be 12.


Q4: `let m = 2; let n = ++m * m++ * --m; // n?`
Answer: `n` will be 12.


Q5: `let a = 3; let b = 5; let result = ++a + b-- - a++ + --b; // result?`
Answer: `result` will be 7.


Q6: `let m = 2; let n = 4; let p = m++ + ++n - --m + n--; // m?,n?,p?`
Answer: `m` will be 2, `n` will be 4, and `p` will be 9.


Q7: `let a = 5; let b = 3; let c = 2; let d = 7; let result = ++a * (b-- + c) / --d; // a?, b?, c?, d? ,result?`
Answer: `a` will be 6, `b` will be 2, `c` will be 2, `d` will be 6, and `result` will be 2.


Q8: `let m = 2; let n = 3; let o = 4; let result = m++ * (--n + m) / (o-- - n); // m?, o?, n?, result?`
Answer: `m` will be 2, `o` will be 3, `n` will be 2, and `result` will be 1.# JavaScript-
