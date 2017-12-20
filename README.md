Bayesian Linear regression using MCMC and Variational Inference <br />

Performed bayesian linear regression using the following 2 approaches: <br />
Markov chain monte carlo based inference <br />
Variational Inference <br />


The error distribution is assumed to be guassian. <br />

To demonstrate these methods, we use data containing 21 daily responses of stack loss, the amount of ammonia escaping, as a function of air flow, temperature, and acid concentration. <br />



Files and their functions <br />
stacks-robust-regression.pdf - Contains detailed explanation of the mathematics behind the inference methods and discusses the results.<br />
LinearRegVI.py - Implementation of MCMC based Bayesian Linear Regression<br />
linearReg_Normal.py - Implementation of Variational Inference based Bayesian Linear Regression<br />
