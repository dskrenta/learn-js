# Functions

Functions are reusable packages of code. You can declare you functions anywhere in your code and use them anywhere you want. Functions are useful because the programmer no longer has to type out everything over and over again. The best programmers are lazy programmers meaning that they use functions for everything instead of rewriting the same code resulting in wasted time. You have seen some built in functions before:

```
console.log('Hello')
alert('Hello')
```

These functions are built into your browser for use whenever you like.

If you have been paying attention you probably have noticed that these functions take input inside parentheses. These values passed to functions are called parameters. The basic model of a function is it takes in data, performs some time of operation, and returns something.

For example the alert function creates a pop-up box in the browser but you have to pass it a value for what to put in that box. After the function runs it returns so you can continue through the rest of your code.

The good news is you can define your own functions:

```
function sum (num1, num2) {
  var result = num1 + num2
  return result
}
```

After declaring this function, you can use it anywhere:

```
sum(1, 3) // 4
sum(100, 4) // 104
sum(41, 1) // 42
```

[continue to the next section](https://github.com/dskrenta/learn-js/blob/master/core/events.md) 
