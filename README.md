# Bootcamp Day #1 | From Zero to Hero Journey
We're going to start by installing some tools required for our journey.



# Getting started



1. [Install Visual Studio Code](https://code.visualstudio.com/download)


2. [Install Nodes.JS](https://nodejs.org/en/download/)


## What's VS Code?

Visual Studio Code, also commonly referred to as VS Code, is a source-code editor made by Microsoft for Windows, Linux and macOS. Features include support for debugging, syntax highlighting, intelligent code completion, snippets, code refactoring, and embedded Git. Users can change the theme, keyboard shortcuts, preferences, and install extensions that add additional functionality.



## What's Node.JS

Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm, unifying web-application development around a single programming language, rather than different languages for server-side and client-side scripts.



# Writing Hello World app

After installing the tools required for our journey, let's start by writing our first application in Javascript. Follow the next recipe:



1. Create a folder in your machine in the `C:\dev` path.
> **Important**: this will be our root folder for all the apps that we're going to create in our journey
2. Create one folder for our hello world app `C:\dev\hello-world`.
3. Open VS Code.
    1. Click on `File -> Open`.
    2. Search the `hello-world` folder and select it.
4. With your folder opened, create a file named `app.js`.
5. Add the following contents to the `app.js` file.
```js
function helloWorld() {
    console.log('Hello World!');
}

helloWorld();
```
6. In your VS Code open a terminal 
7. Run this command `node app.js`
8. Voilá! You just created your first program!
    1.The output should be `Hello World!`


## Program explanation ⚠️



> 👍 Tip: you can add comments to your code by typing `//`


```js
function helloWorld() { // Declare a function with name helloWorld
    console.log('Hello World!'); // console.log is a global function used to print messages, printing the Hello World! message 
}

helloWorld(); // Your function won't be called unless you explicitly call/invoke it
```


## Command explanation ⚠️

To run a Javascript program in your computer we should use Node like this:



```sh
node [your file name]
```


In our case the filename is `app.js`, so our command becomes:



```sh
node app.js
```


# Task #1 👩‍💻



Modify your hello world program to read your a given firstname and last name like this:



```sh
node app.js John Smith
> Hello John Smith!
```


```sh
node app.js Homer Simpson
> Hello Homer Simpson!
```


## Hints 💭



1. [Reading command line arguments](https://nodejs.dev/learn/nodejs-accept-arguments-from-the-command-line)
2. [Concatenating strings](https://www.samanthaming.com/tidbits/15-4-ways-to-combine-strings/)


# What's next 🚀



1. [Data types in Javascript](https://www.programiz.com/javascript/data-types)
2. [Operators in Javascript](https://www.tutorialspoint.com/javascript/javascript_operators.htm#)
3. [JavaScript Conditionals](https://www.javascript.com/learn/conditionals#:~:text=Conditional%20statements%20control%20behavior%20in,for%20a%20block%20of%20code.)

