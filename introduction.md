# Introduction to Javascript

## What is Javascript?

JavaScript (JS) is a high-level, dynamic, untyped, interpreted programming language. Ok, great... Meaning? The easiest way in my opinion to think of a high-level language is it is easier for humans to understand but harder for the computer. Lower level languages have stricter syntax and less built in functionality making it easier for the computer to understand the instructions. Dynamic meaning at runtime JS extends itself to allow the computer to understand the language without compiling before execution. Untyped meaning the variables don't have types, the JS compiler with automatically assign types to the variables you define based on what you decide to store in them. Interpreted languages execute instructions directly instead of being first compiled into machine-language instructions. Most JS engines (the things that run JS in the browser) are written in C/C++ which is a good thing to keep in mind. JS is not a good language to pick for low level performance intensive tasks. When and where to use JS will be covered later in this book.

JS has been standardized by the ECMAScript language specification meaning it has versions and widespread browser support. JS is one of the core technologies of the web alongside HTML and CSS. If you have not heard of HTML and CSS now would be a good time to go and learn them before learning JS.  

One of the best features of JS and why I recommend people learn JS as their first programming language is its versatility. You can use JS to do almost anything which is not common in more specific targeted language. JS also has a C like syntax which is shared with most modern programming languages today meaning it will be easy to learn the syntax of other languages after leaning JS.

The JS language can be broken into two components: the core language and API's built for interfacing with the core language. API stands for application programming interface which is just a set of tools you can include and use with your core JS. Javascript's API's can widely be attributed as the reason for its mass popularity on the web and as a back-end language. JS's extensibility will be addressed later in the book.

## Alright enough talk, let's write some code!

JS is one of the best programming languages to learn due to it's low barrier to entry and it's widespread use and functionality. It is a 100% guarantee that a tech company is using JS is some way shape or form. Luckily for you since you are about to learn JS you will always be employable.

### How to run these examples

[Getting setup with a Javascript environment](https://github.com/dskrenta/learn-js)

### The "hello world" example

```
console.log('Hello, world!')
```

Well that was pretty easy right? Let's break it down: Starting from the left side of the screen we see the word console which is a reference to the console object, a built in object of JS. .log is a member function or method called on the console object allowing us to "log something to the javascript console". Since log is a function we surround our input to the function in parentheses. Since our input is a string (a list of characters) we must surround encapsulate it with either 'stuff' or "stuff" (single quotes or double quotes). My explanation of this example is probably quite confusing to you since you have never been exposed to any of these concepts before. Not to worry, values, objects, functions, and methods will all be explained in future chapters to come.     

##### Congratulations, you have started on your JS journey!

[continue to the next section](https://github.com/dskrenta/learn-js/blob/master/core/variables.md) 
