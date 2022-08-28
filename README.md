# Battleship-Game

This is my first project which I used the support from the Python 2 Module provided from the Codecademy website.
My code begins by importing randint to generate random integers for the location of the battleship.
A 'board' is created by appending "O" to a 5 x 5 list.
Random integers are created within range for row and column location.
Variable ship_row and ship_column assigned for location of ship.

A turn variable is created to denote the turn number of the player.
Two variable guess_row and guess_col are created to store the input guess of player.
An if statement for is guess_row = ship_ row and guess_col and ship_col
then break
else statements: for if guess_row or guess_col not in range.
elif for if guess_row and guess_col for have been guessed prior.
A final else statement for if guess_row and guess_col are wrong.

Then a final if statement for when turn reaches 3 then game is terminated.
