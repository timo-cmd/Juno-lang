

<div align="center">
  <p>The Juno language</p>
  
![Code Climate](https://codeclimate.com/github/surovv/kleisli/badges/gpa.svg)
![](https://img.shields.io/badge/build-passing-brightgreen)

[![ForTheBadge uses-js](http://ForTheBadge.com/images/badges/uses-js.svg)](http://ForTheBadge.com)
![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)
[![forthebadge](https://forthebadge.com/images/badges/makes-people-smile.svg)](http://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/does-not-contain-treenuts.svg)](http://forthebadge.com)

  </div>
  
A little dynamic, class-based programming language. Built on top of JS. Very smooth.

Written for educational experiences. I’ve used less than 650 lines of artesian,
Handcrafted, JavaScript code. I’ve implemented it during a boring, rainy week. :). Juno is a dynamic, declerative and functional programming language. I've designed it to provide the best simplicity, but also the most efficiency for dynamic programming. 

### Syntax

Juno's syntax is inspired by python, scala and by Objective-C. Think a python-syntax, that is class-based(like scala) and that is finally wrapped up by an objective-c syntax. Really accurate! I've chosen those syntaxes because they match the requirements for dynamic languages. Juno is implemented in less than 660 Lines of JavaScript. This mustn't mean, it isn't powerful... Juno coveres a huge environment and concepts such: control flow, generic variable assigns, recursive functions, first-order functions, classes, superclasses, a multi-threading system and much more... I'll take you on a little trip for exploring it's syntax.

#### Basics:

Let's start by declaring the traditional hello, world in Juno:

```js
print("Hello, World!")
```

Really simple.

And now let's wrap a program in some awesome loops:

```js
from 1 to 3 with a:
from 1 to 3 with b:
from 1 to 3 with c:
  print(a, b, c)
:::
```
Classes:
```js
@implementation : CPObject:
    from 1 to 3 with a:
    from 1 to 3 with b:
    from 1 to 3 with c:
        print(a, b, c)
::::
```

Classes don’t work currently. I’ll fix it as fast as possible.

Functions: (contain pipeline return assigns.

```js
func greet(str a) :
   str a = null
   |> "Hello"
   |> a
:

greet("Hy")
```

Comments

```js
// this is a line comment
//...some code here...
/* this
is
a 
multiline comment */
```

In development

- superclasses
- Nil keyword
- First order funcs 
- Imports
- Multithreading
- NSLog
- Printf function
- Object initializations
- Inheritance and Metaprogtamming

Future:

- IDE
- Better vm//probably bytecode interpreted
- Atom support 
- REPL




Work in progress...

Built by Timo Sarkar, during a rainy, boring week.
