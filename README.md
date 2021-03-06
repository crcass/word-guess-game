# Hail to the Chief!

## Game Start
User can click or touch anywhere to begin. 
Answer key will automatically populate from the array, with _ replacing letters.
Each letter pressed by the user will be checked against the answer and either replace _ in the answer key or push input to an array of unused letters.
As the user guesses incorrect letters, the number of remaining guesses will reduce.

## Game End
If the user correctly guesses all the correct letters before the remaining guesses = 0, a win screen will display and audio will play.
If the user reduces the remaining letters to 0 before correctly guessing the answer, a defeat screen will display.

In either case, clicking (or touching on mobile) anywhere will reset the game and increment the score depending on the win or loss condition.

## Known Issues
### iOS
* occasionally the first letter guessed will be correct but end up in the "Unused Letters" array
* pull-to-refresh does not always work in Chrome for iOS
* during the game, touching the screen outside of the keyboard area hides the "Unused Letters" array until another unused letter is guessed

### Android
* testers needed!

### All Platforms
* some letters that are guessed correctly will not appear in the solution array or the "Unused Letters" array
* a few non-alpha characters are accepted as input. Currently those key are counted so guess carefully!
* currently, there is no way to see the correct answer if the user does not win the game

♥︎ cc