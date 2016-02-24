# battleship

this is a command line based adaption of the popular battleship board game.

if you 'Download ZIP' and decompress it

pc - open cmd prompt and run:  Downloads\battleship-master\battleship_server.py</br>
pc - open a new prompt window and run:  Downloads\battleship-master\battleship_client.py ServerIpAddress PORT</br>
linux - open terminal and run:  python Downloads/battleship-master/battleship_server.py</br>
linux - open a new terminal window and run:  python Downloads/battleship-master/battleship_client.py ServerIpAddress PORT

'battleship_server.py' will display the ServerIpAddress and PORT at runtime.

you can run as many instances of 'battleship_client.py' as you like.

as clients connect to 'battleship_server.py' it will behave as a lobby and 2 x 2 serve them a new game and control it.</br>
when a game ends by annihilation of a players force or the opponent disconnects from the server.</br>
the client will delay 5 seconds before rejoining the servers games queue.

sockets allow the programs to communicate on your local computer or accross your LAN.</br>
it is quite interesting to load the task manager, hone in on python network traffic and watch the data transfer.

those new to python will need to download and install at least python 2.7 available at <a href="https://python.org/downloads">https://python.org/downloads</a>
