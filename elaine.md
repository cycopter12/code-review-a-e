# Code Review for Elaine

## Project Repo

[Catch The Mouse](https://lainelim.github.io/wdi-project-1-lainelim/)

## Review

#### Project Purpose

* This game was created to meet Project 1 of GA's Web Development Immersive (SG) requirement.

#### Project Organization
* readme.md
* index.html: Main page for Catch the Mouse
* script.js: logics of game javascript
* style.css: main css script

#### Features

* getRandomInt function:
  * This function is to generate a random time for the mouse to appear.

* start function:
  * Points and mouse count start at 0. Score board will also display 0 on 'Mice Caught'. Once the game has started, the mouse class of visible will be remove. At every 2 seconds, the mouse will reappear.

*  getRandomMouse:
    * This function will generate a random mouse to pop up by its number. There are 11 mouse all together.

* mouseAppears function:    
  *  This function would make use of the getRandomMouse function and it will pull a random mouse. Once the mouse appears the mouse counter will increase by 1. The mouse is under a timer of .5,2000 seconds.

* catchMouse function:
  * If a mouse pops up and is clicked a 'pow' css will be activated. The 'pow' class 'hidden' will be remove and it will add to the 'visibility' class. Points will be added by increments of 1 after clicking a mouse. After the points have been updated, the 'pow' will have to be reset at .5 secs.

* mouseDisappears function
    * This function will check if the last mouse has appeared in the isGameOver function. After 3 seconds, the pop up for the game is over will appeared. If the game is over, before 3 seconds is done, the mouse will disappear before the alert comes up.

* isGameOver function
      * Once the mouse count has reached 20 count, the game will finish. If the points is more than or equal to 15, an alert will appear saying "You're a pro!"
      * If your points is below 15, an alert will pop up saying "Would you like to try again?"

#### Areas of Success (Code, Organization)

* Nice work on practicing binding!
  * Good work on using binding in your functions and using "this" keyword.
* Nice flow of code
  * Very easy to read the code. Nice flow in each function. Able to trace each function and purpose of the function in code.

#### Areas for Improvement (Code, Organization)

* Create two functions for mouse and pow
  * There were a few repetition of code. Two functions could be created to perform the remove('visible') and add('hidden') without repeating itself in other functions.
* Create a start and reset button
  * There could be a start and reset button for when the game begins and when it ends. Currently, the player does not know that the game has start until he/she sees the mouse.

## Additional Notes

_Place any additional notes here_
