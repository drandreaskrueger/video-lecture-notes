
# Deep Learning with Differential Privacy
Ilya Mironov, at CCS 2016 in Vienna 2016-10-25  

TOC of the video https://www.youtube.com/watch?v=ZxDBEyjiPxI  
of this event https://www.sigsac.org/ccs/CCS2016/agenda/  
about this paper https://arxiv.org/abs/1607.00133  
with sourcecode at https://github.com/tensorflow/models/tree/master/differential_privacy  

### TOC

00:45 start  
01:06 training data <-> utility  
02:05 no protection of parameters & outputs of models  
02:50 ensure model itself is privacy preserving  
03:15 fallacy: ML models always preserve training data  
04:00 examples for methods  
04:35 models can be very large  
04:57 attacks! model inversion attack; membership inference attack  
05:50 deep learning recipe  
06:50 layered neural network  
07:05 gradient descent --> stochastic G.D.  
08:25 differential privacy, D & D' differing in single record; epsilon leakage, delta probability of failure  
09:09 training data D & D'  
09:45 Gaussian mechanism  
10:28 simple recipe, sensitivity --> Gaussian noise  
11:00 composition theorem  
11:19 composite functions  
11:50 deep learning with differential privacy  
12:10 "fruit flies of ML": 2 classification databases  
12:42 PCA layer  
13:15 stochastic gradient descent with D.P.  
14:15 hyperparameters  
14:35 naive privacy analysis --> disappointed  
15:35 advanced composition theorems  
17:10 strong composition theorem --> big progress but still unacceptable  
18:00 amplification by sampling  
18:31 privacy loss random variable; 20% sampling  
19:22 higher moments, privacy loss accountant --> acceptable  
21:00 results, summary & comparison  
22:47 their results  
23:00 contributions: Tensorflow repo, innovations, lessons  
24:15 Q: why Gaussian not Laplacian?  
24:50 Q: exponential mechanism  
25:20 Q: PCA - how practical?  
26:38 Q: dimension reductions of colors = ?  
27:15 Q: other deep n.n. architectures? RNN?  
28:10 Q: tried model inversion attacks?  



### contributors
Please fork, edit/correct/extend, and pull request. Thanks.    

* https://github.com/drandreaskrueger


