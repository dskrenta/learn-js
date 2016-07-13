# Variables

Variables are containers that store values. The syntax for declaring a variable is the keyword var followed by the variable name:

```
var myVariable
```

Note that the variable name cannot contain any spaces which is why my variable is camel cased. Camel casing is the first word lowercase followed by the next word with the first letter capitalized. Camel casing is considered standard in Javascript because it is used by the standard API's.

After declaring a variable you can give it a value:

```
myVariable = 'Bill'
```

All of this can also be done on one line:

```
var myVariable = 'Bill'
```

You can retrieve the value of myVariable by just calling the variable name:

```
myVariable
```

If you would like to retrieve the variable and print it to the console, just use the same code from the hello world example but modify the input like so:

```
console.log(myVariable)
```

After giving a variable a value, you can also always choose to change it:

```
var myVariable = 'Bill'
myVariable = 'Bob'
```

We have experimented with the string data type but variables have these other data types:

Data Type | Explanation | Example
---|---|---
String | A string of text. To signify the variable is a string, enclose it with quote marks | ```var myVariable = 'Bob'```
Number | A number | ```var myNumber = 42```
Boolean | A True/False value. The words true and false are special keywords in JS, and don't need quotes | ```var myBool = true```
Array | A structure that allows you to store multiple values in one single variable | ```var myArray = [1, 'Bill', 'Bob', 10, false]```
Object | Anything. Everything in JS is an object, and can be stored in a variable. Keep objects in mind when you learn JS in future sections. | ```var myValue = document.querySelector('h1')```

You might be wondering at this point why we need variables. Well, variables allow you to do interesting things in programming like making a thank you message with a dynamic name. Substitute Bill for Bob or any other value. Variables allow you to write dynamic content, things that changes based on the value of their variables. If objects seem confusing to you now, they will be reviewed again in further detail later.

[continue to the next section](https://github.com/dskrenta/learn-js/blob/master/core/comments.md) 
