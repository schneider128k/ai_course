# Taxonomy of Reinforcement Learning Methods #

RL methods can be classified according to:

* Model-free or model-based
* Value-based or policy-based
* On-policy or off-policy

Model-free means methods do not build a model of the environment. They directly connect states to actions (or to values of actions). 
Model-based methods try to build a model of the environment.

Policy-based methods directly approximate the policy, that is, what actions the agent should carry out at each step. 
Policies are usually represented by probability distributions over the available actions.
Value-based methods first approximate the values of actions and then choose actions with the maximum value in each state.

Off-policy methods have the ability to learn on old historical data, whereas on-policy methods need fresh data.
