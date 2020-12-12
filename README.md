# NLA-RL
Rep fro the NLA project, 2nd Term, Skoltech.



# Done so far

1. The env is chosen: Atari Breakthrough v.4

2. Found the working Q-learning based solution (NN is adequate, there is space for compressing, Dense layer of size 512)


# Link to the working prototype to be reimplemented

https://keras.io/examples/rl/deep_q_network_breakout/


# Split To-Do

1. Think over which hyperparameters we have to optimize (using the original, unchanged code, think of the intuition)

2. Re-implement the working code in PyTorch, same functionalities and buffers

3. Introduce the compression of the nn.Linear(512) Layer, think over possible activation and it's impact

4. Implement the diagnostic function, keeping (most important above all the info about the action std's, we need to see how they are impacted by the compression)

Actually, we may just use the buffers, which were collected during the training process.


