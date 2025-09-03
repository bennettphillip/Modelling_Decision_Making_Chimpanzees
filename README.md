# Modelling_Decision_Making_Chimpanzees
My dissertation project modelling how fission-fusion dynamics affect decision making in Chimpanzees, specifically decisions to play aggressively or cooperatively.
This is based on the Hawk-Dove model from game theory, where agents can either play aggressively (Hawk) or cooperatively (Dove). Payoffs are dependent on competition choices.
I model chimpanzees as individual agents, with groups being agents dependent on the model. The decision to fission or fuse is treated on both an individual or group level depending on the model.
A parameter sweep is performed for both the shared decision parameter, omega, and for the resource factor, V/C, to see how sharing decisions and the level or resources in the envrironment affects system equilibria.
Parameters are:
epsilon - Leader proportion
Omega - Shared decision parameter
P - Probability of playing aggressively (Hawk)
N - Total number of chimpanzees
C - Total cost of losing a conflict
dv - distribution of value across subgroups
dc - distributioon of cost across subgroups
