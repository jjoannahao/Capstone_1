# REINFORCEMENT LEARNING PROJECT: CLIFFWALKING

### Environment: CliffWalking-v0 (from OpenAI's gymnasium library)
In this environment, an agent (character sprite) tries to reach its goal (a cookie) without falling off the cliff,
which is indicated by the burgundy squares found in the bottom row of the rendered image of the environment

### Solution
Using Q-learning, the agent learns how to most efficiently and effectively reach its goal. When a human analyzes the environment,
we can determine that the minimum number of steps required for the agent to reach its goal is 13, which means that the ideal reward
the agent can achieve in this environment is -13 (-1 reward per step taken). 
