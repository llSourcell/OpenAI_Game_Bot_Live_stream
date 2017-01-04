# OpenAI_Game_Bot_Live_stream

##Overview

This is the code for the "How to Install OpenAI's Universe and Make a Game Bot" live session by Siraj Raval on [Youtube](https://www.youtube.com/watch?v=XI-I9i_GzIw). The bot is for the Coaster Racer flash game and determines the answer to 2 questions -- should I turn, and which way should I turn? It answers the first by checking if it's been receiving a reward for a certain interval (no crashes), and if it has it will turn. It answers the second by randomly picking a turn between left and right. This bot is able to complete the race. So it's a bot that uses reinforcement learning to determine when to turn and each turn is a random direction.

##Dependencies

* Universe- install instructions [here](https://github.com/openai/universe) 
* random (pip install random) 

##Usage

Run `python demo.py` in terminal to run this code

##Credits

Credits go to [Mick](https://github.com/mickvanhulst/). I've merely created a wrapper to get people started. 

