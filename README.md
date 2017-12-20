Bayesian Linear regression using MCMC and Variational Inference\n


Performed bayesian linear regression using the following 2 approaches:\n
Markov chain monte carlo based inference\n
Variational Inference\n


The error distribution is assumed to be guassian.\n

To demonstrate these methods, we use data containing 21 daily responses of stack loss, the amount of ammonia escaping, as a function of air flow, temperature, and acid concentration.\n



Files and their functions\n
stacks-robust-regression.pdf - Contains detailed explanation of the mathematics behind the inference methods and discusses the results.\n
LinearRegVI.py - Implementation of MCMC based Bayesian Linear Regression\n
linearReg_Normal.py - Implementation of Variational Inference based Bayesian Linear Regression\n
