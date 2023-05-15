PING PONG
Process Communication between sockets with GUI

OS PROJECT
BCS-4A

Huzaifa Rashid    21K-3299
Aarib Azfar       21K-3342
Abdullah Ashar    21K-3189

Overview:
A simple pong game between two computers. On each computer only their area of the screen and overall score is displayed

Details:
	A ping pong game with displayed GUI. A player(Client) connects to a server in its LAN. 
Then player plays the game, client and server communicate in between sending data packets consisting information about player and ball position. 
Server does 2 things. It simulates the game which is ball movement, paddle movement, collision detection and 
maintaining the score and receives input from the two clients  about which arrow key is pressed then moves the paddle in that direction.
The two clients which are two players on different computers have only two jobs. 
To draw the paddle a the ball at the coordinates received by the server and to send input data to server about which arrow key is pressed.

Objectives:

    • Make a simple pong game
    • Make a server to share the coordinates of the ball and the score
    • Make 2 clients where the game runs and share data with the server

Application Information:

    • Language used: Python
    • Modules: Pygame
    • Os concepts: Threading, Sockets

Future Todo:

    • Main Menu
    • Different levels
    • Customizability
    •  Port the game over to WAN/Internet
