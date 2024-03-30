# Aim and prerequisites
Voter Coevolution Model is created by setting a N-node graph with $\langle k \rangle$ average links per node. Nodes represent agents with states/opinions $s_i=\{-1,1\}$. Every time step 2 linked agents are randomly selected: $n_1$, $n_2$. If their opinions differ, with probability $p$ $n_1$ changes opinion. With $1-p$ it breaks link with $n_2$ and creates a new one with agent of same oppinion as theirs. Magnetization:
$$M=\frac{1}{N} \sum_{i=0}^{N-1} s_i$$
**The aim of the project** was to find numerically critical parameter $p_c$ that divides 2 basins of attraction:
1. The graph is unified and all agents have the same opinion. $M = \{-1, 1\}$
2. The graph breaks in two. $M\approx 0$

# Results
A plot of magnetization M with respect to parameter $p$ is created and critical $p_c$ is found 
