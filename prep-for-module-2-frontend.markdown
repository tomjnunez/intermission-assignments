# Module 2 Prep Work


## JavaScript

We'll be introducing some new JavaScript syntax this module which we'd like you to familiarize yourself with. Read the following chapters of [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read):

- [Functions](https://leanpub.com/understandinges6/read#leanpub-auto-functions)
- [Expanded Object Functionality](https://leanpub.com/understandinges6/read#leanpub-auto-expanded-object-functionality)
- [Destructuring for Easier Data Access](https://leanpub.com/understandinges6/read#leanpub-auto-destructuring-for-easier-data-access)
- [Improved Array Capabilities](https://leanpub.com/understandinges6/read#leanpub-auto-improved-array-capabilities) (You're only expected to read the sections on "Creating Arrays" and "New Methods on All Arrays")

Then go through this [ES6 Tutorial](http://ccoenraets.github.io/es6-tutorial/):
  - `Setting Up Babel`
  - `Using let Variables`
  - `Using Destructuring`
  - `Using Arrow Functions`

Set up a repl.it account by folowing the directions [here](https://gist.github.com/thatPamIAm/ec20e805e385cc2b423185ef26bed046) 

And do the codecademy [ES6 Class Tutorial](https://www.codecademy.com/courses/learn-javascript-classes/lessons/classes/exercises/introduction)


## Linting

In Mod 1, you were given general [style guides](https://github.com/turingschool-examples/javascript/tree/master/es5) for how you should be writing your code. In Mod 2, we're going to enforce a linter. A linter helps make sure that the way you write your JavaScript conforms to certain stylistic patterns and best practices.

We'll be working with a tool called [eslint](https://eslint.org/), and your projects will be required to abide by the following [rules](https://github.com/turingschool-examples/javascript/blob/master/linters/module-2/non-react/.eslintrc). Read through the "rules" object in the `.eslintrc` file and look through the eslint documentation to [find each rule](https://eslint.org/docs/rules/), and familiarize yourself with what it does.

Set yourself up with eslint by installing it with npm. In your terminal (from any directory), run the following command:

`npm install -g eslint`


## Debugging

While you may have seen and used the browser's Developer Tools in module 1, we'd like you to step through this Udemy course on [Dev Tools](https://www.udemy.com/devtools-2017-the-basics-of-chrome-developer-tools/). Some of it may be review, but you may pick up some new tricks along the way!


## Coding: Refactor Mod 1 Projects
  - *rewrite long, nested if/else statements into [switch statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)*
    - familiarize yourself with the syntax of switch statements
  - *DRY up your code*
    - find areas where code is duplicated and break it out into a function
  - *change for loops into `forEach`*
    - you'll be working with a lot of Array iterator methods in Mod 2 like [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach), start practicing them now!
  - *try out converting some ES5 syntax to ES6*
    - you do not need to set up babel to do this, you can simply refactor and your projects should still work in Google Chrome
  - *install the linter configuration and lint your JavaScript style*
    - add the `.eslintrc` file linked above to your project directory (it must be named `.eslintrc`)
    - from your terminal, within your project directory, run: `eslint ./index.js` (or whatever JavaScript file you want to lint)
    - read through the output and fix the errors - you are given line numbers and an explanation of what's wrong for each error!