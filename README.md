# Rock-Paper-and-Scissors-Multiplayer-Game
A simple Rock, Paper, and Scissors Multiplayer Game created with Python's PyGame Library <br>
## Installation
First, you need to install PyGame first since it didn't come with Python: <br>
`pip install pygame` <br>
Then, clone this repository using: <br>
`git clone https://github.com/giaphat-nham/Rock-Paper-and-Scissors-Multiplayer-Game.git` <br>
That will be it for the installation.
## Configuration
Now, you need to config the Server IP to whatever your server's host is. Open the file `server.py`, change the line `server = ...` to the IP of your Host. <br>
Then, do the same thing in the file `network.py` at line `self.server = ...` which located in the constructor of the `Network` class. <br>
And now you're good to run the game.
## Run the game
To run the game, in your command line, type `python server.py` on your host machine to start the server <br>
After that, for each client that want to join the game, in the command line, type `python client.py`
The game's window should show up for each client and they can start the game.
