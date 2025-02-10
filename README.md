# AWS-DeepRacer-Competition

Action Space & Hyperparameter Optimization in Amazon DeepRacer
Action Space
In Amazon DeepRacer, the action space defines the set of possible actions the autonomous car can take at each time step. It consists of:

Steering Angles: Typically ranging from -30 to +30 degrees.
Throttle (Speed) Values: A range of speeds the car can select from.

A discrete action space is commonly used, where predefined combinations of steering and throttle values allow the model to learn optimal driving strategies efficiently.

Hyperparameter Optimization
To improve the DeepRacer model’s performance, key hyperparameters are optimized:

Learning Rate: Determines how much the model updates in each training step.
Batch Size: Defines the number of samples used per training update.
Discount Factor (Gamma, γ): Controls the importance of future rewards in reinforcement learning.
Exploration vs. Exploitation: Adjusted using epsilon-greedy strategies or entropy regularization.
Neural Network Architecture: Optimized for feature extraction from sensor inputs (camera images).
Fine-tuning these parameters ensures the DeepRacer efficiently learns optimal racing strategies, balancing speed and control while staying on track.
