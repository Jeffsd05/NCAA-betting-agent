# NCAA-Betting-Agent

Final project file is divide into two parts. 

1- Mixed action space:
      -run main.py
      -core2.py contains module, i.e. neural networks, replaybuffer and some other utility functions and DDPG class
      -gym-bet is the environment
      -config folder contains config.py file
      -config.py contains the parameters used in main.py
      -out_of_memory_cuda.png is a screenshot of output terminal showing the out of memory error raised by cuda

2- Discrete action:
      Go into DDQN-Master
      - run main.py 
      - bet_env is the environment
      - data contains data_norm.csv
      - Agent.py contains the agent decision tools
      - qNets contains the two neural networks
      - Graph for each set of actions are indicated in the folder DDQN graph 
     
      Bad Model - DQN is the model which results in NAN (There's no results there)
      
     
