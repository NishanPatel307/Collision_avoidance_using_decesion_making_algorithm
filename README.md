# Probability-of-Collision-with-cars-and-pop-up-message

INTRODUCTION :


Vehicle collisions are a major threat to human lives and a
lot of people die in road accidents every year. According to
the data worlds’ 1% of the vehicle are owned by Indians, but
road accidents record 11% of the worlds’ total. With the
advancement of technology and the development in the field
of machine learning, we can implement it to avoid the daily
deaths that are occurring due to road accidents. Reinforcement
Learning, a sub-branch of machine learning deals with the
training of agents in a particular environment by conducting
the actions and analysing the result for the same. It is a
feedback-based technique and consists of rewarding the agent
for correct action, whereas a negative reward for the wrong
action. The decision making of the agent for a particular state
space is definite. A higher reward would be granted if the
machine follows correct instructions in a tedious environment.

Whenever vehicles are moving on road there is always probability of collision or
accident but drivers are driving vehicles to minimize the probability of accident.
Let’s consider N nodes are moving with capability to create their own map of
surroundings which includes neighboring nodes. Each node is moving with its
own velocity and acceleration. If we consider N = 2 then node n1 is having
velocity v1 and acceleration a1, node n2 is having velocity v2 and acceleration
a2. Now here velocity and acceleration of all nodes are changing as well as
number of surrounding nodes are changing as nodes are moving. If we assume
full degree of freedom for all moving nodes then what is the probability of
collision or accident. In Indian perspective, this full degree of freedom makes
this problem very hard to solve. The probability of collision or accident of each
node depends on the velocity and acceleration of all surrounding or neighboring
nodes. Let’s assume first topology with single lane and limit degree of freedom
for each node to particular lane only.


simple traffic topology with two nodes and single lane. Node n2 is leading vehicle moving with velocity
v2 and acceleration a2, Node n1 is behind it with velocity v1 and acceleration
a1. Let’s introduce variable time t with which all parameters are changing. At
time t’, velocity of node n1 is v′1 and acceleration is a′1, velocity of node n2 is v′2 and acceleration is a′2.
Node n2 is moving faster than node n1, node n1 is
moving faster than node n2, and both nodes are moving at same speed. Node
n2 is moving with a constant speed and node N1 is moving very fast is also one
possibility. There are chances of accident when node n1 is moving faster than
node n2 or node n2 is moving at a constant speed and node n1 is moving very
faster than node n2.
![image](https://github.com/PriteshPatel4739/Probability-of-Collision-with-cars-and-pop-up-message/assets/69390119/c4360e76-6142-41f9-a2e7-a8c04e28e814)




