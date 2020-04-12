# matlab_neural_network_snake_withtail
This project creates a snake trained by a neural network reinforcement learning algorithm. In this game, the snake tries to eat as much food as possible without hitting the boundaries of the box. The neural network has sixteen input neurons, and four output neurons.There are 8 directions the snake looks at any given time: (North,Northeast,East,Southeast,South,Southwest,West,and Northwest). The inputs are the distances to food and distances to a wall if applicable for any given direction it looks in, else the value is a -1. While training the algorithm, a progress graph will display the effectiveness of the training. A simulation of the snake also diplays in a figure to help visualize what the neural network is "thinking" while training.
