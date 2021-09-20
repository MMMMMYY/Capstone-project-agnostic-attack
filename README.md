# Capstone-project-agnostic-attack
Dataset: CIFAR  
Dataset load and processing code are shown as code block 10 and code block 11.
## About  
Federated learning model poisioning attack  
Type: Agnostic-attack
## Getting start  
#### 1. Use Agnostic-attack for your work
In this example code, the federated learning framework is based on Alexnet. 
The attacks are defined as two functions. The inputs of each function are :
    attack_tp: the type of attacks (min-sum,min-max) min_max as default
    all_updates: grediants of users
    model_re: the global updates after aggregation
    n_attackers: the number of attackers
    dev_type: the type of disturbance variable (std as defualt)
The output is malious updates produced(should be combined with others benign updates by aggregation you choosed).
The process is shown as last code block.   
#### 2.Run the example code
Make sure place the the cifar folder and AGR_agnostic.ipynb in the same directory.
And run the AGR_agnostic.ipynb.

## Reference
Shejwalkar, V., & Houmansadr, A. (2021). Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses for Federated Learning. Internet Society, 18.
https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning
