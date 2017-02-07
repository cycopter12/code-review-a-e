# Code Review for Andre

## Project Repo

[Andre's Game](https://cycopter12.github.io/wdi-project-1-cycopter12/)

## Review

#### Project Purpose

The purpose of the game is to complete typing as many complicated words as possible with the least number of mistakes within the 30 second time.

#### Project Organization
readme.md
javascript.js
style.css
index.html
#### Features

* Function newWord()
  * Selects a random word from a pre-defined list and iterates each letter of the word to an inline element (span) to display on the screen.
* Function keyCheck(e)
  * returns the character input from the key press event, checks the input against the letter of the word. If the input is the same as the letter, player gains a point; Else, a point accumulates for the error score. Both points and scores are updated.
* Function UpdateTimer()
  * Starts a countdown timer of 30 seconds, disables start button. Once time is up, the results of the game are declared. The game is reset.

#### Areas of Success (Code, Organization)

* Functions
  * All functions were clearly named and written succinctly.
* Code
  * Pseudocode was used and helped with the organization of the code.

#### Areas for Improvement (Code, Organization)

* Closures
  * Encourage better use of overAll's returned functions after DOM content is loaded.

* Variables
  * Encourage semantic naming of variables to strengthen ease of understanding.
