# Pricing Formula Evaluation of Spread Option

*Zheng Hao, Luo Jiarong, He Junjie*

A spread call option with expiry T and strike K has the payoff

<img src="http://latex.codecogs.com/gif.latex?\max\{S_1(T)-S_2(T)-K,0\}"/>

where 
<img src="http://latex.codecogs.com/gif.latex?S_1(t),S_2(t)"/> 
are the price of two stocks and follow

<img src="http://latex.codecogs.com/gif.latex?\frac{dS_i(t)}{S_i(t)}=rdt+\sigma_idW_i(t)\quad i=1,2"/>

and

<img src="http://latex.codecogs.com/gif.latex?dW_1dW_2=\rho dt"/>

Kirk's(1995) developed an approximation formula of the spread option. This report and code is used to evaluate the performance of this approximatation.

Report:
[Report pdf](Report.pdf)