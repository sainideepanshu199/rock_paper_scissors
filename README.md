# rock_paper_scissors
rock_paper_scissors app in dart using command line
## Project: Rock, Paper & Scissors

Build a command line tool that can play rock, paper and scissors.

When started, the program should show this prompt:

```
Rock, paper or scissors? (r/p/s)

```

It should then read the user input and use it as follows:

- If the user enters "r", "p", or "s", treat this as a valid move.
- If the user enters "q", quit the program.
- If the user enters anything else, show "Invalid input", and prompt again.

After the user has entered a valid move, generate another move at random, then compare the two moves according to the rules of the game.

For example, if you played "rock", and the program played "paper", the output should be:

```
You played: rock
AI played: paper
You lose

```

The game should repeat until the player quits by pressing


#pseudocode for game logic
 1. while true
 2. show prompt
 3. read user input from console
 4. if input is valid move("r", "p","s")
 5. choose the AI move at random
 6. compare the player move with AI move
 7. show the result
 8.  else if input is "q"
 9. Quit the progress
 10. else
 11. invalid input
  
![image](https://github.com/sainideepanshu199/rock_paper_scissors/assets/114583893/cc2adeeb-238b-48f3-8575-cae51016e920) ![image](https://github.com/sainideepanshu199/rock_paper_scissors/assets/114583893/7eca11d7-59f5-4ff1-977c-926dad6a4013)

