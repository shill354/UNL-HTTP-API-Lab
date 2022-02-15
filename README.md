# HTTP & API Basics Lab

## Introduction

The purpose of this lab is to expose you to when HTTP requests are used, and how to use them to interact with Application Programming Interfaces (APIs). It does so via using Javascript's Fetch API, which is a well-used, well-documented API for HTTP Requests in the JavaScript language.

Here are some resources you will probably want a reference to when you complete the lab. Part of the purpose of this lab is to teach you how to research and look into documentation of existing APIs to use them in your future projects and work.

[Javascript's Fetch API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/fetch)

[JavaScript's Await Keyword Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)

[PokeApi's Documentation](https://pokeapi.co/docs/v2)

And again, like all programming tasks, the internet is your friend, and searching for resources that will *help* is encouraged! However, strictly copy and pasting code is *not*, and is not the intention for this lab!

## Getting Started

To begin the lab, first clone the source code by running:

```
git clone https://github.com/lseper/UNL-HTTP-and-API-Lab.git
```

Then, create a new branch to push to. Do this by running the following command:

```
git checkout -b Partner1Name-Partner2Name
```

Where `Partner1Name-Partner2Name` are you and your partner's names. For example, an example branch would look like this:

```
git checkout -b LiamSeper-GraceClausen
```

Then, once your branch has been created, run the following command:

```
git --set-upstream origin Partner1Name-Partner2Name
```
The branch name should be the same as the one you created.

Finally, to run the code, simply right click the file `index.html` in your file explorer, and open it in your web browser.

## Your Job

Open the file `index.js`. At the top of the file, there is a function for you to complete, the `getPokemon` function.

The first line of the function fetches the pokemon entered in from the website, and stores it in an array of strings corresponding to each pokemon's name. DO NOT CHANGE THIS LINE. You will be using the variable `pokemon` to complete the rest of the function body.

The function should not return anything. Rather, your task will be to use the PokeApi to retrieve information on each of the pokemon in the `pokemon` array, extract the relevant information, and use the `buildCard` method to display the pokemon on the website.

Note: You do not need to understand how the `buildCard` function works, only what it takes in as arguments, which are defined on the comment above the function.

When you make changes to `index.js`, simply reload the website in your browser for them to take affect on the website.

## Acceptance Criteria

If you successfully complete the function's body, your website should function like so:

1. When valid pokemon are entered into 1, 2, 3, 4, or 5 of the slots, they should appear on the website with the following stats displayed:
   1. Types
   2. Abilities
   3. Base Attack
   4. Base Defense
   5. Base Special Attack
   6. Base Special Defense
   7. Base HP
   8. Base Speed



## Submitting Your Code

Simply push your code to the branch you created when you set up the project. Then you're done!
