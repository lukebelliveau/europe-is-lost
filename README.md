# europe-is-lost
let's share

# 00. ENTER THE RABBIT HOLE
first thing to know, when you see text (prededed with slashes) that looks like this:

`// this is a comment`

that is a comment, it is meant for us to speak english to each other. anything in front of backslashes will not be executed as code.

that is a comment. that means it is not code that will be executed, it is our way of leaving notes for each other

# 01. INTRO 
We will first produce a phrase - you will code it, and the computer will print it back to you. Traditionally, the first phrase is "Hello World". Tradition is fucking stupid, so print whatever you want. You will do so like this. Type this into your 01.js file:

`console.log("hello, world")`

to execute the program, type the following into your terminal:

`node 01_intro/01.js`

you should see whatever dumb message you decided to write back on your terminal. if you got lost along the way, please ask and you will find a helping hand. let's go down the rabbit hole <33

# 02. WE'RE ALL VARIABLE
Variables are used to store information. They are useful because they allow you to store, label, and manipulate data. The keyword `let` is used to assign a value to a variable - for example, `let five = 5`.

Here, we will use two variables to store two numbers and add them. Consider the following code:

```js
let two = 2
let five = 5

let sum = two + five

console.log(sum)
```

Before executing this code, ask yourself - what do you expect to be printed?

Once you've made your guess, type the above code into 02.js. Execute it by typing the following into your terminal:

`node 02_variables/02.js`

# 03. A STRANGE LOOP
Together, we are going to learn to count to 5. The following paragraph will explain how, but if you just want to code it without thinking, skip this next one.

An important part of programming is the "for, each" loop. For example, "we start at 0, and for each time we enter the loop, we increment by 1. If we are at 5, stop the loop". This is how we teach a computer to count to 5. I wish I knew how to count to 5. The code is below:

```js
for (let i = 0; i < 5; i++) {
  console.log("The value of i is " + i)
}
```

Let's break down the top line:
- `let i = 0`: define a variable, `i`, and assign it the value of 0.
- `i < 5`: each time we restart the loop, evaluate if the statement `i < 5` is true. If it **is** true, execute the loop again. Otherwise, end the loop.
- `i++`: Each time we execute the loop, increment the value of `i` by 1.

Executing this code should result in the following output:
```
The value of i is 1
The value of i is 2
The value of i is 3
The value of i is 4
The value of i is 5
``` 
