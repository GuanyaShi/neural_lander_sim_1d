# neural_lander_sim_1d
A simple 1d simulator for the "[Neural-Lander](https://arxiv.org/abs/1811.08027)" paper, ICRA 2019

This simulator is simple but realistic: it considers aerodynamics, motor delay, noise, etc. The aerodynamics model `Fa_net_12_3_full_Lip16.pth` is represented by a DNN trained from real data.

Two controllers are provided: a baseline nonlinear controller and an "oracle" controller which perfectly knows the DNN aerodynamics.
