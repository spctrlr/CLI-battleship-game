# Battleship game
Battleship (also known as Battleships or Sea Battle[1]) is a strategy type guessing game for two players. It is played on ruled grids (paper or board) on which each player's fleet of warships are marked. The locations of the fleets are concealed from the other player. Players alternate turns calling "shots" at the other player's ships, and the objective of the game is to destroy the opposing player's fleet. Visit [wikipedia](https://en.wikipedia.org/wiki/Battleship_(game)) for more information.

# Requirements
Any vesion of linux and ruby 2.2 or above, bundle.

# Installation and play
`$ git clone https://github.com/spctrlr/CLI-battleship-game.git`<br>
`$ cd battleship_game`<br>
`$ bundle install`<br>

# Usage
## Run the game
`$ cd battleship_game`<br>
`$ ruby lib/play_battleship.rb`<br>

## Controls
When start the game a prompt will appear so player is able to choose size in numbers. e.g. submitting 5 means 5 field to the left(columns) and 5 fields down(rows)<br>
To choose which spot to mark the player have to input numbers and separate them with **space** in the form '0 0', '1 0' and submit them with **enter**.
