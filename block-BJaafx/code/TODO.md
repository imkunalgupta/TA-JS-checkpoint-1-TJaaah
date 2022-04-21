1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
let sum = 0;

for(let i=1; i<=10; i++ ){
  let input1 = +prompt('Enter the input.');
   sum = sum + input1;
} 
alert(sum/10);
console.log(average);
```
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
It show an error, saying that println is not defined.

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js
let sum = null;

function getEvenSum( max = 10 ) {
  for ( let i = 0; i <= max; i++ ) {
      if ( i % 2 === 0 ) {
        sum = sum + i ;
      } 
    } console.log(sum);
}
getEvenSum(40);
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

```js
function getOddSum (max = 10){
  let sum = 0;
  for (let i = 10; i <= max; i++){
    if(i %2 !== 0){
      sum +=i;
    }
  }
  return sum;
}
etOddSum(20);
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // bigger than 5;
check(1); // smaller than 5;
check(5); // "5";
```
Here two condition are given condition for greater than 5 and condition for lesser than 5 and for remaining return should be num which is entered. so 5 is coming into remaining and output is coming string 5.

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // "You are arya"
getOutput('John'); // 'You are john'
getOutput(); // 'Who are you'
```
for first two condition return is given and for all other value condition is given "Who are you?"

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // It will display You are Arya and will return value will be 'Who are you' because return value for all is same.
getOutput('John'); // It will display You are john and will return value will be 'Who are you' because return value for all is same.
getOutput(); // 'when no arguement will be passed then we will get 'Who are you' as output
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Yes a function can have mulitple return statement  only when if....else or switch condition is used.
for example :- function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  else return 'Who are you';
}
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
The main difference between for and while loop is that we intialize the value inside the for loop and in while loop we initialize , outside the while loop, while loop needs a true condition to execute the body.
