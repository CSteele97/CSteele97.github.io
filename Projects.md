[Return to Homepage](https://csteele97.github.io)

# Programming for Social Science Portfolio

This portfolio contains the work conducted in order to complete the first assignment for the Programming for Social Scientists module conducted at the University of Leeds. The aim of the assignment is to build an Agent Based Model and display the output on a website, as well as linking the code to the model. 

## Agent Based Modelling 

Agent Based Models attempt to capture the behaviour of individuals within an environment, where individual objects have their own behaviours and the ability to interact with each other and their environment. They are iterative models, wherenby the model runs until a defined stopping condition has been met, or a number of iterations reached. The key elements of an ABM are as follows:
* Model code - this runs the model iterations and checks stopping conditions, as well as plots the end output
* Agent code - this builds the agents behaviour
* Environment code - represents the 'world' the agents interact with 

## ABM Project

Click [here](https://github.com/CSteele97/GEOG5995M_Assignment_1) for the repository for Assignment 1

Within the repository there are two .py files. One is the Agent code (**agentframework.py**) which sets out the agent behaviours, and the other is the Model code (**new_model.py**) which contains the code required to run the model and holds many of the variables.

In order to complete this assignment, I have created an ABM to model sheep grazing in a field. Each of the 10 agents is an independent sheep, who exhibit behaviours such as moving, eating the environment around them, and communicating with their neighbours by sharing their food stores if they are in a close proximity. The sheep stop grazing once a certain stopping condition has been met; in this case, when one of the sheep has a food store of 5000 units, all of the sheep stop moving. 

The final output of the model can be seen below:

<p align="center">
  <img width="600" height="600" src="leeds_final.gif">
</p>

