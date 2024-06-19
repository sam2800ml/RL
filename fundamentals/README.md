## Fundamentals

### Policy
>
This defines the way the agent will behave at a given time. This depends on the moment and the action it must take. It could be stochastic, meaning having a probability distribution for each action in every state. With this, we can say that the policy can establish, depending on the moment, which action can be performed, given the different probabilities.
>
### Reward Function
>
When the agent is at the moment of making a decision, this will imply a reward or a loss of points, so it can learn from the action it is doing to do it better or stop at that moment. This can make the model learn from good and bad events, but when we think of a biological system, at that moment we cannot be too strict. In those cases, we can make the reward a bias that can change depending on the actions the agent is taking, and we can have low rewards to identify those moments.
>
### Value Function
>
The value function helps us specify what is good in the long run, determining the long-term desirability of states. We can say that at a given moment, our model made a decision that received a low reward, but this can sometimes happen if the next actions are compensated with a high reward. This can help us understand that some actions will not necessarily always receive high rewards from the start, but some of them may have a low reward, but the path will lead us to the highest rewards in the end.
>
### Model
>
It is something that mimics the behavior of the environment. If we pass an action and a state to this model, it can predict the result of the next state and reward. It can help us with planning; with this, we can use it to know, at a given time, what the output, reward, state, and action will be.on
>
### Agent
>
The agent is the one we are going to train. It is the entity that will take the action, trying to learn given those reward functions, and trying to maximize the value function, which is that long-term reward.
>
### environment 
>
The environment is a space where the agent will interact. It can provide some insights and rewards to the agent, and it can depend on the agent's action.
>
In conclusion, we can say that the agent will interact with the environment, taking some decisions given its policy at the moment. The environment will respond with observations and rewards. The objective of the agent will be to learn about its policy, trying to maximize its value function.
>