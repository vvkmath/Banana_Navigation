# Project Description
The purpose of this project is to create an agent using Deep Q Learning that collects Bananas in a large square world. To maximize its rewards, the agent needs to learn how to collect as many yellow bananas as possible while avoiding blue bananas. 

# Agent Environment
To train the RL agent, Unity Machine Learning Agents (ML-Agents), an open-source Unity plugin is used. The environment’s state space has 37 dimensions and contains information pertaining to the agent's velocity and information related to the perception of objects around the agent's forward direction.  The agent needs to learn how to select the best action to maximize its cumulative rewards. The four possible actions are as below:
•	0 - move forward.
•	1 - move backward.
•	2 - turn left.
•	3 - turn right.
The learning happens over many episodes where each episode represents a complete sequence of actions the agent would take to finish playing successfully in the environment. To solve the environment, the agent needs to get an average score of +13 over 100 consecutive episodes.

# Installation Requirements
To run the DQN model, we need to install Python version 3.6 and activate the virtual environment. Also, to install the Unity environment, reference is made to the file as shown in the code. Specific details about the environment (e.g., observation space size, action space size, etc.) are also shown in the code. 
Other dependencies that are relevant to training the agent are installed in Python (using Jupyter notebook ). Unzip the Python.zip folder to install files related to the Python, Unity environment and requirements.

# Model Execution and Evaluation
The code to run the model is included in the Jupyter notebook file titled Banana_Navigation_Solution.Ipynb.  The code shows the details of how the DQN is constructed and the various functions that are used to obtain an optimal policy. The performance of the model is depicted as a chart as the agent learns over the course of many episodes. 
