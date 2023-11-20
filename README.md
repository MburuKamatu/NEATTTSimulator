# NEAT time trial simulator
This is a 2D AI car simulator that attempts to see how fast a car can make it around a track.
The car is controlled by radar sensors that detect collisions i.e. when th car collides with the edge of the track.
The car is also part of a model that runs in the NEAT algorithm. The algorithm runs populations of cars through generations, with each subsequent generation of cars having attributes inherited from the previous generation.
# Features
* AI opponents controlled using the NEAT algorithm
* Options for the user to create their own tracks then import them into the game
* Options to set number of opponents and the difficulty level they compete at
# Installation
* Clone the github repo to your local machine. 
* Install pycharm: https://www.jetbrains.com/pycharm/download/ 
* Install the NEAT library : https://pypi.org/project/neat-python/ OR pip install neat-python 
* Install pygame: pip install pygame 
* Run cargenerator.py through the terminal
