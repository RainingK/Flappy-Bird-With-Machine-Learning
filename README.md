# Flappy-Bird-With-Machine-Learning
A flappy bird game where the app uses neural networks to learn and continuously move between pipes.

## Modules Needed
pygame  
neat-python  

Install using ```pip install -r requirements.txt```


## Overview
This is a flappy bird app where each bird (max 20) learns to fly between 2 pipes through various generation.  
Using neural networks with the help of the 'neat-python' module we were able to make the birds learn from whichever of the birds had moved the most frames forward. Using the one that was able to move the furthest we create an entire new generation with its 'fitness' to be used for future generations.