# 🕐🐊 - Later Gator

## will synchronicity You know

We've begun the work of beginning event driven programming (a form of asynchronous programming) by adding event listeners such that certain code is invoked when other actions happened. Now we take it a step farther and start to build a bridge toward:

1. Making HTTP Requests (and receiving their responses)
1. Comparing and contrasting 3 different approaches to asynchronicity:
    1. Callbacks
    1. Promises
    1. async/await

### Part 1

Make a little web app that has 2 user interface elements (these are actually provided):

* a text input element
* an output element

#### Tasks
1. Add an event listener such that when the text input has focus and the user presses enter, 
    1. the text they've entered is used to search for a possible [valediction](https://en.wikipedia.org/wiki/Valediction), and 
    1. that found valediction is displayed in the output element.

See it in action 🎬:

[![later gator demo](https://img.youtube.com/vi/WH2TbnkirpQ/0.jpg)](https://www.youtube.com/watch?v=WH2TbnkirpQ)

### Part 2

1. Modify the code you have for Part 2 such that the user's input is instead used to find possible valediction targets.
1. These matching targets are displayed as buttons, and 
1. when one of the buttons is clicked, 
1. the valediction target displayed on the button is used to query for the corresponding valediction (similar to what you had in Part 1), which
1. finally is displayed in the output element.

## Process

1. You may work in pair or trios, if you wish.
1. Start with the provided code:
    1. `later.js` - in theory, you need not even open this file. The information you need about it is available in `main.js`'s comments
    1. `main.js` - this is where you will do your work
    1. `main.css` - puts on the fancypants
    1. `index.html` - the structure of the page, doesn't validate. you need not edit this file
1. read the comments in `main.js`, observing especially:
    1. the documentation of the 2 provided functions at the top of the file: 
        1. `later(targetQuery, callback)`
        1. `options(callback, query)`
    1. the `TODO` items guiding you to the areas to start editing for Part 1
1. you only need to edit `main.js`
1. submit your `main.js` code to this assignment