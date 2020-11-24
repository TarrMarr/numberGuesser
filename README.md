# Project Name
> A number guessing game vs. the computer!

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Code Examples](#code-examples)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
A simple game of guess the number played against the computer using HTML, CSS and JavaScript  

## Screenshots
![Example screenshot](https://github.com/TarrMarr/numberGuesser/blob/main/screenshot.JPG)

## Technologies
* HTML5
* CSS
* JavaScript  

## Code Examples
Show examples of usage:
`nextRoundButton.addEventListener('click', () => {
    advanceRound();
    roundNumberDisplay.innerText = currentRoundNumber;
    nextRoundButton.setAttribute('disabled', true);
    guessButton.removeAttribute('disabled');
    targetNumberDisplay.innerText = '?';
    guessButton.innerText = 'Make a Guess';
    humanGuessInput.value = '';
    computerGuessDisplay.innerText = '?';
    computerWinsDisplay.innerText = '';
    guessButton.classList.remove('winning-text');
});`

## Status
Project is: _finished_

## Inspiration
Created for Codecademy's Full Stack Engineer program  

## Contact
Created by TarrMarr(https://www.tarrynmarr.me) - feel free to contact me!
