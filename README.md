2 Applied Projects

For the practical track you are required to re-implement two famous RL algorithms among the ones listed be-
low. You should also test them on some of the following OpenAI-Gym environments: Cartpole, MountainCar,
MountainCarContinuous, Acrobot and Pendulum.

In your report of 6–8 pages you are required to compare the two algorithms of your choice based on of
your empirical observation. This means providing appropriate plots and score statistics of your algorithms
based on fair comparison between them.

Possible algorithms:

• DQN by Mnih et al. [21]

• PPO by Schulman et al. [27]

• SAC by Haarnoja et al. [10]

• TD3 by Fujimoto et al. [8]


You can also add a qualitative discussion about the two algorithms building around the following questions:

• Which algorithm is more computationally expensive per iteration ?

• Which algorithm store the policy more compactly ?

• Which one scales better for continuous actions ?

• Which algorithm makes efficient use of off-policy data ?


Finally, view the report as diary in which you can keep track of the observations made during the implementa-
tion process. We are interested in knowing which small details in the implementation you found are crucial to
make the algorithm work in practice! For example, if you had a bug that took you you a long time fix, write
it down. If you found that the algorithm’s performance is very sensitive to certain hyperparameter tuning,
write it down. Take also note if you find out that an hyperparameter affects the performance only minimally,
and think about possible reasons. Corroborate your claims by showing plots that compare the algorithms
when run for the different hyperparameters (i.e., do not only report the final, good hyperparameter choices
that made it work eventually).

Important: Each plot you present should report an algorithm’s performance averaged across at least 3 seeds.
