# IB-Coin-Tossing
Implementation of the agent described in the following article : https://charlesr-w.github.io/crw-blog/Infra-Bayesianism-Distillation/, in which an agent plays a coin toss game (see Example 0, p.3). The agent doesn't know which environment it is in, which its rewards depends on, and has to choose a policy.
It computes infra-values by taking the worst-case expected reward across environments, then uses gluing to compute infra-probability and the paper’s update rule after observing Heads or Tails.
