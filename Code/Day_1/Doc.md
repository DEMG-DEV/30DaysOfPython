# Day 1

I found this great video where the founder himself shares a brief story about the language.

[![IMAGE ALT TEXT HERE](https://res.cloudinary.com/practicaldev/image/fetch/s--1uZXWigR--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://img.youtube.com/vi/J0Aq44Pze-w/0.jpg)](https://www.youtube.com/watch?v=J0Aq44Pze-w)

## Understanding about how Python works in simple words

Python is a high-level interpreted programming language.
What it means is that the python code needs to be translated (interpreted) by another software program which is called the interpreter that executes the code line by line and converts it into bytecode (very close to machine-readable code).

This bytecode is run by the Python virtual machine (gets installed when we install python) and then converted into machine-readable binary code which computers can process and perform the necessary action.

While installing Python, what we install is the python interpreter along with the virtual machine.

There are different variations of python interpreters:

- CPython - comes with the official installation and is written - in C language
- Jython
- PyPy
- IronPython

Each of the implementations of their own features and trade-offs.

## Versions

There are two major versions v2 and v3. In 2008, several major improvements were introduced in the language that introduced some breaking changes without considering backwards compatibility. The official docs now recommend using v3 and support for v2 would be ceased after 2020.

## First beginner's program 😄

To keep things extremely simple at first, I wanted to play around with some basic hello world type code, to begin with.

I used the amazing online playground REPL to kickstart writing some python code and do a syntax comparison with JavaScript as well.

```Python
name = input('What is your name?') #promts user input in console and store in a variable
print('Welcome to the world of Python ' + name) # prints to console 
```

comparing it with JavaScript

```Javascript
const name = prompt('What is your name?');
console.log('Welcome to the world of JavaScript ' + name);
```

Well, that's pretty much for Day-1! I know I have barely written any code. I just wanted to spend my first day in building the roadmap. Now that I have the language split into chunks, the goal would be to focus on the weekly goals and share daily progress about the same.

Have a great one!