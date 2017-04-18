# Train a Smartcab How to Drive 

## Overview 
In this project, I applied reinforcement learning techniques for a self-driving agent in a simplified world to aid it in effectively reaching its destinations in the allotted time.  

The environment the agent operates in was investigated by constructing a very basic driving implementation. Each possible state the agent can be in was identified by considering such things as traffic lights and oncoming traffic at each intersection. With states identified, a Q-Learning algorithm was implemented for the self-driving agent to guide the agent towards its destination within the allotted time. The Q-Learning algorithm was also optimized to find the best configuration of learning and exploration factors to ensure the self-driving agent is reaching its destinations with consistently positive results. 

**Keywords**: Reinforcement Learning, Q-Learning 

## Libraries 
This project was done using **Python 3.5** and the following Python libraries: 

- Numpy 
- Pandas 
- Matplotlib 
- PyGame (install on Mac by running `pip install pygame==1.9.2`) 


## Run  

In a terminal or command window, navigate to the top-level project directory `smartcab/` (that contains this README) and run one of the following commands: 

```python smartcab/agent.py```  
```python -m smartcab.agent``` 

