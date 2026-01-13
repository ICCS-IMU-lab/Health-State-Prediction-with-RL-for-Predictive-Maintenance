# Health-State-Prediction-with-RL-for-Predictive-Maintenance
DOI of Publication is : Not available yet

The focus of this study is the CNC Machine Wear Prediction Problem. A CNC (Computer Numerical Control) machine is an automated manufacturing tool that uses pre-programmed computer software to control the movement and operation of machinery, allowing for precise and efficient production of complex parts. The data is provided by the PHM (Prognostics and Health Management) Society and was part of the 2010 PHM Data Challenge. The goal is to predict the wear of the flutes in cutters of a high-speed CNC milling machine using measurements from dynamometer, accelerometer, and acoustic emission sensors. For the predictive maintenance (PdM) task in this context, a specialized methodology has been employed, as illustrated in the diagram below:

<img width="698" height="698" alt="image" src="https://github.com/user-attachments/assets/980a93b0-7ff2-476e-9fd3-b045cd688a03" />


The primary objective is Wear Prediction, which is based on data from sensor equipment condition monitoring. This data is integrated into the Markov Decision Process (MDP) framework, which is crucial for formulating the problem in a manner that is suitable for RL algorithms. The reinforcement learning algorithms applied are specifically model-free algorithms. These algorithms are categorized into off-policy and on-policy methods. Off-policy methods include Deep Deterministic Policy Gradient (DDPG) and Soft Actor-Critic (SAC), while on-policy methods encompass Proximal Policy Optimization (PPO) and Advantage Actor-Critic (A2C). The end goal is to develop an RL-based PdM agent capable of making autonomous decisions to predict wear and avoid potential and functional failures in CNC machines effectively.
