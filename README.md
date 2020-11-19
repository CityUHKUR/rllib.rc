# rllib.rc
Reinforcement Learning Library for Robotics Control

# Approach
github action -> azure pipeline -> spawn gazebo server machine + compute cluster -> rl agent interact with the environment -> collect + combine + update policy -> when the score/ time reach threashold -> save model + save score -> github action -> update the score plot -> close machines

# Update
since the there were an great advancement on reinforcement learning, I decided to seperate the current approach into different module, with the help of different framework, to help distributed + scale reinforcement learning.


# To-Do
[] reinforcement learning library (build our own optimizted library using framework frame ray+rllib+pytorch)
[] model architechture for optimization

