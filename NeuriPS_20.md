### NeurIPS'20 Oral

On the training dynamics of deep networks with L2 regularization  
Aitor Lewkowycz (Google) · Guy Gur-Ari (Google)  
Link: https://arxiv.org/abs/2006.08643

Ultra-Low Precision 4-bit Training of Deep Neural Networks  
Xiao Sun (IBM) · Naigang Wang (IBM) · Chia-Yu Chen (IBM) · Jia-min Ni (IBM) · Ankur Agrawal (IBM) · Xiaodong Cui (IBM) · Swagath Venkataramani (IBM) · Kaoutar El Maghraoui (IBM) · Vijayalakshmi Srinivasan (IBM) · Kailash Gopalakrishnan (IBM)  
Link: https://papers.nips.cc/paper/2020/hash/13b919438259814cd5be8cb45877d577-Abstract.html

Acceleration with a Ball Optimization Oracle  
Yair Carmon (Stanford) · Arun Jambulapati (Stanford) · Qijia Jiang (Stanford) · Yujia Jin (Stanford) · Yin Tat Lee (University of Washington) · Aaron Sidford (Stanford) · Kevin Tian (Stanford)  
Link: https://arxiv.org/abs/2003.08078

Convex optimization based on global lower second-order models  
Nikita Doikov (Catholic University of Louvain) · Yurii Nesterov (Catholic University of Louvain)  
Link: https://arxiv.org/abs/2006.08518



[A Group-Theoretic Framework for Data Augmentation](https://arxiv.org/pdf/1907.10905.pdf)
Shuxiao Chen, Edgar Dobriban, Jane H Lee



[Is normalization indispensable for training deep neural networks?](https://papers.nips.cc/paper/2020/file/9b8619251a19057cff70779273e95aa6-Paper.pdf)
Jie Shao · Kai Hu · Changhu Wang · Xiangyang Xue · Bhiksha Raj




### NeurIPS'20 Spotlight

23:00 – 23:10 CST
5 - Spotlight: What if Neural Networks had SVDs?
Alexander Mathiasen, Frederik Hvilshøj, Jakob Rødsgaard Jørgensen, Anshul Nasery, Davide Mottin
Various Neural Networks employ time-consuming matrix operations like matrix inversion. Many such matrix operations are faster to compute given the Singular Value Decomposition (SVD). Techniques from (Zhang et al., 2018; Mhammedi et al., 2017) allow using the SVD in Neural Networks without computing it. In theory, the techniques can speed up matrix operations, however, in practice, they are not fast enough. We present an algorithm that is fast enough to speed up several matrix operations. The algorithm increases the degree of parallelism of an underlying matrix multiplication H*X where H is an orthogonal matrix represented by a product of Householder matrices.

23:10 – 23:20 CST
6 - Spotlight: Practical Quasi-Newton Methods for Training Deep Neural Networks
Donald Goldfarb, Yi Ren, Achraf Bahamou
We consider the development of practical stochastic quasi-Newton, and in particular Kronecker-factored block diagonal BFGS and L-BFGS methods, for training deep neural networks (DNNs). In DNN training, the number of variables and components of the gradient n is often of the order of tens of millions and the Hessian has n^2 elements. Consequently, computing and storing a full n times n BFGS approximation or storing a modest number of (step, change in gradient) vector pairs for use in an L-BFGS implementation is out of the question. In our proposed methods, we approximate the Hessian by a block-diagonal matrix and use the structure of the gradient and Hessian to further approximate these blocks, each of which corresponds to a layer, as the Kronecker product of two much smaller matrices. This is analogous to the approach in KFAC , which computes a Kronecker-factored block diagonal approximation to the Fisher matrix in a stochastic natural gradient method. Because the indefinite and highly variable nature of the Hessian in a DNN, we also propose a new damping approach to keep the upper as well as the lower bounds of the BFGS and L-BFGS approximations bounded. In tests on autoencoder feed-forward network models with either nine or thirteen layers applied to three datasets, our methods outperformed or performed comparably to KFAC and state-of-the-art first-order stochastic methods.

23:30 – 23:40 CST
8 - Spotlight: On the linearity of large non-linear models: when and why the tangent kernel is constant
Chaoyue Liu, Libin Zhu, Misha Belkin
The goal of this work is to shed light on the remarkable phenomenon of "transition to linearity" of certain neural networks as their width approaches infinity. We show that the "transition to linearity'' of the model and, equivalently, constancy of the (neural) tangent kernel (NTK) result from the scaling properties of the norm of the Hessian matrix of the network as a function of the network width. We present a general framework for understanding the constancy of the tangent kernel via Hessian scaling applicable to the standard classes of neural networks. Our analysis provides a new perspective on the phenomenon of constant tangent kernel, which is different from the widely accepted "lazy training''. Furthermore, we show that the "transition to linearity" is not a general property of wide neural networks and does not hold when the last layer of the network is non-linear. It is also not necessary for successful optimization by gradient descent.


### Other papers (to be organized)
FedSplit: an algorithmic framework for fast federated optimization
Reese Pathak (University of California, Berkeley) · Martin Wainwright (UC Berkeley)
12:18

Network Pruning via Greedy Optimization: Fast Rate and Efficient Algorithms
Mao Ye (The University of Texas at Austin) · Lemeng Wu (UT Austin) · Qiang Liu (UT Austin)
12:20
https://neurips.cc/Conferences/2020/AcceptedPapersInitial searched “optimization” in Neurips 20 paper list; only find 2 interesting papers.

neurips.cc
Accepted Papers
NeurIPS Website


The Generalization-Stability Tradeoff In Neural Network Pruning
Brian Bartoldson (Lawrence Livermore National Laboratory) · Ari Morcos (Facebook AI Research) · Adrian Barbu (Florida State University, USA) · Gordon Erlebacher (Florida State University)

12:25
Logarithmic Pruning is All You Need
Laurent Orseau (DeepMind) · Marcus Hutter (DeepMind) · Omar Rivasplata (DeepMind & UCL)

12:25
Batch Normalization Biases Residual Blocks Towards the Identity Function in Deep Networks
Soham De (DeepMind) · Sam Smith (Google Brain)
12:26

Escaping the Gravitational Pull of Softmax
Jincheng Mei (University of Alberta / Google Brain) · Chenjun Xiao (University of Alberta) · Bo Dai (Google Brain) · Lihong Li (Google Research) · Csaba Szepesvari (DeepMind / University of Alberta) · Dale Schuurmans (Google Brain & University of Alberta)
12:26

Training Generative Adversarial Networks by Solving Ordinary Differential Equations
Chongli Qin (DeepMind) · Yan Wu (DeepMind) · Jost Tobias Springenberg (DeepMind) · Andy Brock (DeepMind) · Jeff Donahue (DeepMind) · Timothy Lillicrap (DeepMind & UCL) · Pushmeet Kohli (DeepMind)
12:27

Your GAN is Secretly an Energy-based Model and You Should Use Discriminator Driven Latent Sampling
Tong Che (MILA) · Ruixiang ZHANG (Mila/UdeM) · Jascha Sohl-Dickstein (Google Brain) · Hugo Larochelle (Google Brain) · Liam Paull (Université de Montréal) · Yuan Cao (Google Brain) · Yoshua Bengio (Mila / U. Montreal)
12:28

Why Do Deep Residual Networks Generalize Better than Deep Feedforward Networks? --- A Neural Tangent Kernel Perspective
Kaixuan Huang (Princeton University) · Yuqing Wang (Georgia Institute of Technology) · Molei Tao (Georgia Institute of Technology) · Tuo Zhao (Gatech)
12:29

What Neural Networks Memorize and Why: Discovering the Long Tail via Influence Estimation
Vitaly Feldman (Google Brain) · Chiyuan Zhang (Google Brain)
12:29

What Do Neural Networks Learn When Trained With Random Labels?
Hartmut Maennel (Google) · Ibrahim Alabdulmohsin (Google Research) · Ilya Tolstikhin (Google, Brain Team, Zurich) · Robert Baldock (Google) · Olivier Bousquet (Google Brain (Zurich)) · Sylvain Gelly (Google Brain (Zurich)) · Daniel Keysers (Google Research, Brain Team)
12:30

The Surprising Simplicity of the Early-Time Learning Dynamics of Neural Networks
Wei Hu (Princeton University) · Lechao Xiao (Google Brain) · Ben Adlam (Google) · Jeffrey Pennington (Google Brain)
12:30

Top-k Training of GANs: Improving GAN Performance by Throwing Away Bad Samples
Samarth Sinha (University of Toronto, Vector Institute) · Zhengli Zhao (UCI, Google Brain) · Anirudh Goyal ALIAS PARTH GOYAL (Université de Montréal) · Colin A Raffel (Google Brain) · Augustus Odena (Google Brain)
12:31

The Unreasonable Effectiveness of Big Models for Semi-Supervised Learning
Ting Chen (Google) · Simon Kornblith (Google Brain) · Kevin Swersky (Google) · Mohammad Norouzi (Google Brain) · Geoffrey E Hinton (Google & University of Toronto)
12:31

Reparameterizing Mirror Descent as Gradient Descent
Ehsan Amid (University of California, Santa Cruz) · Manfred K. Warmuth (Google Brain)
12:32

Sanity-Checking Pruning Methods: Random Tickets can Win the Jackpot
Jingtong Su (Peking University) · Yihang Chen (Peking University) · Tianle Cai (Peking University) · Tianhao Wu (Peking University) · Ruiqi Gao (Peking University) · Liwei Wang (Peking University) · Jason Lee (Princeton University


12:33
Directional Pruning of Deep Neural Networks
Shih-Kang Chao (University of Missouri) · Zhanyu Wang (Purdue University) · Yue Xing (Purdue University) · Guang Cheng (Purdue University)
12:33

Pruning neural networks without any data by conserving synaptic flow
Hidenori Tanaka (NTT Research, PHI Lab / Stanford University) · Daniel Kunin (Stanford University) · Daniel Yamins (Stanford University) · Surya Ganguli (Stanford)
12:34

Optimal Lottery Tickets via Subset Sum: Logarithmic Over-Parameterization is Sufficient
Ankit Pensia (University of Wisconsin-Madison) · Shashank Rajput (University of Wisconsin - Madison) · Alliot Nagle (UW-Madison) · Harit Vishwakarma (University of Wisconsin Madison) · Dimitris Papailiopoulos (University of Wisconsin-Madison)
12:34

Winning the Lottery with Continuous Sparsification
Pedro Savarese (TTIC) · Hugo Silva (Independent Researcher) · Michael Maire (University of Chicago)
