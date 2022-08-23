---
title: First steps in Node JS
sidebar: auto
---

Ok. Now you decided to start your Node JS journey. What are the first steps then?

As you read in the previous sections that Node uses javascript as it's scripting language. If you know the basic javascript, you are good to go.

## Your first node js program

Create a javascript file named `index.js`, and add the following code

```javascript
console.log("Hello World!");
```

Next, open your command prompt or terminal. Navigate to the folder where you have created the above file.

Then, type the following command in the terminal.

```sh
node index.js
```

The following output will be displayed in the terminal.

```
Hello World!
```

Congrats :tada: you have ran your first node js program.

## REPL

REPL stands for Read Evaluate Print Loop.

It is an environment used to execute single expression as user input and returns the result.

Basically it is used to quickly test simple javascript code.

## Using REPL

Go to command prompt or terminal and type node.

```sh
> node
  Welcome to Node.js v16.15.1.
  Type ".help" for more information.
>
```

::: tip Note
Make sure you have node installed in your computer
:::

The node command will stays in idle mode and waits for the user to type something.

Type the below sample code.

```js
console.log("Hello...");
```

You will see the below output

```sh
> console.log("Hello...");
Hello...
undefined
>
```

**Code explanation:**

- The first line `Hello...` is the output for `console.log("Hello...");` statement
- The second line undefined is the return value of `console.log()`

After executing the code we enter, the node command still stays idle and waiting for the user to enter the next lines of code until we exit.

::: tip Note
To exit from the REPL, use ctrl + c
:::
