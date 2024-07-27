# Snake_RL

Reinforcement Learning (RL) is a subset of ML concerned w how software agents take actions in an environment to maximize the notion of cumulative reward.

One approach, using deep learning, is Deep Q Learning.

The approach used deep neural networks to predict actions! We will implement RL for a Snake game.

Our model will be a feed forward neural network using PyTorch. Very simple model that I will work to improve and fine tune. Training will be done with Deep Q Learning using Q Value, Quality of Action. Our loss function (to minimze our loss) we will use Bellman Equation (updating our next Q Value).

After almost 200 games, our model is learning very well. It achieved high scores near 60 while fluctuates around the 30 range near the final runs. The average score was 16.4, but of course, after the first 80 games, it drastically improved shown by the drastic increase in mean scores!

To improve upon our model, we will modify the game to track distance from walls as well as add complexity to the neural network!

Theory and inspiration from Patrick Loeber YouTube