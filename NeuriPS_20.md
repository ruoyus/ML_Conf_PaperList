### NeurIPS'20 Tutorials
Tutorial: (Track1) There and Back Again: A Tale of Slopes and Expectations
  We discuss backpropagation in three settings: in probabilistic graphical models, through an equality constraint, and with an inequality constraint. To complete the round-trip, we explore algorithms for calculating gradients of expectations, the basis of methods for variational inference, reinforcement learning, and experimental design.
  https://neurips.cc/virtual/2020/public/tutorial_880c6de112a048b0fc4ddb0a8b513e17.html  

Tutorial: (Track2) Equivariant Networks
It has become clear that in all of these cases and more, equivariance to symmetry transformations is the key principle that points us to an effective generalization. New architectures inspired by this principle have already proved their effectiveness in multiple domains.
https://neurips.cc/virtual/2020/public/tutorial_3e267ff3c8b6621e5ad4d0f26142892b.html


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

Wed
22:15 – 22:30 CST
2 - Oral: Entropic Optimal Transport between Unbalanced Gaussian Measures has a Closed Form
Hicham Janati, Boris Muzellec, Gabriel Peyré, Marco Cuturi

22:30 – 22:45 CST
3 - Oral: Acceleration with a Ball Optimization Oracle
Yair Carmon, Arun Jambulapati, Qijia Jiang, Yujia Jin, Yin Tat Lee, Aaron Sidford, Kevin Tian
Consider an oracle which takes a point x and returns the minimizer of a convex function f in an l_2 ball of radius r around x.


22:30 – 22:45 CST
3 - Oral: Training Generative Adversarial Networks with Limited Data
Tero Karras, Miika Aittala, Janne Hellsten, Samuli Laine, Jaakko Lehtinen, Timo Aila

10:00 – 10:15 CST
1 - Oral: Implicit Neural Representations with Periodic Activation Functions
We analyze SIREN activation statistics to propose a principled initialization scheme and demonstrate the representation of images, wavefields, video, sound, and their derivatives.


23:10 – 23:20 CST
6 - Spotlight: GAIT-prop: A biologically plausible learning rule derived from backpropagation of error
Nasir Ahmad, Marcel A. J. van Gerven, Luca Ambrogioni
Traditional backpropagation of error, though a highly successful algorithm for learning in artificial neural network models, includes features which are biologically implausible for learning in real neural circuits. An alternative called target propagation proposes to solve this implausibility by using a top-down model of neural activity to convert an error at the output of a neural network into layer-wise and plausible ‘targets’ for every unit. These targets can then be used to produce weight updates for network training. However, thus far, target propagation has been heuristically proposed without demonstrable equivalence to backpropagation. Here, we derive an exact correspondence between backpropagation and a modified form of target propagation (GAIT-prop) where the target is a small perturbation of the forward pass. Specifically, backpropagation and GAIT-prop give identical updates when synaptic weight matrices are orthogonal. In a series of simple computer vision experiments, we show near-identical performance between backpropagation and GAIT-prop with a soft orthogonality-inducing regularizer.
想法: 对target prop (ADMM)做 spectrum control; maybe worth a paper. 

10:15 – 10:30 CST
2 - Oral: Pixel-Level Cycle Association: A New Perspective for Domain Adaptive Semantic Segmentation
Guoliang Kang, Yunchao Wei, Yi Yang, Yueting Zhuang, Alexander Hauptmann
Domain adaptive semantic segmentation aims to train a model performing satisfactory pixel-level predictions on the target with only out-of-domain (source) annotations. 
想法：能否分析landcape或优化性质？(Yi Yang是以前百度的研究员)

10:30 – 10:45 CST
3 - Oral: Coupling-based Invertible Neural Networks Are Universal Diffeomorphism Approximators
Takeshi Teshima, Isao Ishikawa, Koichi Tojo, Kenta Oono, Masahiro Ikeda, Masashi Sugiyama
Invertible neural networks based on coupling flows (CF-INNs) have various machine learning applications such as image synthesis and representation learning. However, their desirable characteristics such as analytic invertibility come at the cost of restricting the functional forms. This poses a question on their representation power: are CF-INNs universal approximators for invertible functions? Without a universality, there could be a well-behaved invertible transformation that the CF-INN can never approximate, hence it would render the model class unreliable. We answer this question by showing a convenient criterion: a CF-INN is universal if its layers contain affine coupling and invertible linear functions as special cases. As its corollary, we can affirmatively resolve a previously unsolved problem: whether normalizing flow models based on affine coupling can be universal distributional approximators. In the course of proving the universality, we prove a general theorem to show the equivalence of the universality for certain diffeomorphism classes, a theoretical insight that is of interest by itself.
  **这个文章讨论了流行的normalizing flow和invertible network; 值得一读。或许和landcape以及preconditioning layer有着深刻的联系。**


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

Wed, Dec 9th @ 23:50 CST – Thu, Dec 10th @ 00:00 CST
10 - Spotlight: Implicit Bias in Deep Linear Classification: Initialization Scale vs Training Accuracy
Edward Moroshko, Blake Woodworth, Suriya Gunasekar, Jason Lee, Nati Srebro, Daniel Soudry
We provide a detailed asymptotic study of gradient flow trajectories and their implicit optimization bias when minimizing the exponential loss over "diagonal linear networks". This is the simplest model displaying a transition between "kernel" and non-kernel ("rich" or "active") regimes. We show how the transition is controlled by the relationship between the initialization scale and how accurately we minimize the training loss. Our results indicate that some limit behavior of gradient descent only kick in at ridiculous training accuracies (well beyond 10^-100). Moreover, the implicit bias at reasonable initialization scales and training accuracies is more complex and not captured by these limits.

23:20 – 23:30 CST
7 - Spotlight: IDEAL: Inexact DEcentralized Accelerated Augmented Lagrangian Method
Yossi Arjevani, Joan Bruna, Bugra Can, Mert Gurbuzbalaban, Stefanie Jegelka, Hongzhou Lin
We introduce a framework for designing primal methods under the decentralized optimization setting where local functions are smooth and strongly convex. Our approach consists of approximately solving a sequence of sub-problems induced by the accelerated augmented Lagrangian method, thereby providing a systematic way for deriving several well-known decentralized algorithms including EXTRA and SSDA. When coupled with accelerated gradient descent, our framework yields a novel primal algorithm whose convergence rate is optimal and matched by recently derived lower bounds. We provide experimental results that demonstrate the effectiveness of the proposed algorithm on highly ill-conditioned problems.

00:20 – 00:30 CST
13 - Spotlight: Linearly Converging Error Compensated SGD
Eduard Gorbunov, Dmitry Kovalev, Dmitry Makarenko, Peter Richtarik
In this paper, we propose a unified analysis of variants of distributed SGD with arbitrary compressions and delayed updates. Our framework is general enough to cover different variants of quantized SGD, Error-Compensated SGD (EC-SGD), and SGD with delayed updates (D-SGD). Via single theorem, we derive the complexity results for all the methods that fit our framework. For the existing methods, this theorem gives the best-known complexity results. Moreover, using our general scheme, we develop new variants of SGD that combine variance reduction or arbitrary sampling with error feedback and quantization and derive the convergence rates for these methods beating the state-of-the-art results. In order to illustrate the strength of our framework, we develop 16 new methods that fit this. In particular, we propose the first method called EC-SGD-DIANA that is based on error-feedback for biased compression operator and quantization of gradient differences and prove the convergence guarantees showing that EC-SGD-DIANA converges to the exact optimum asymptotically in expectation with constant learning rate for both convex and strongly convex objectives when workers compute full gradients of their loss functions. Moreover, for the case when the loss function of the worker has the form of finite sum, we modified the method and got a new one called EC-LSVRG-DIANA which is the first distributed stochastic method with error feedback and variance reduction that converges to the exact optimum asymptotically in expectation with constant learning rate.


23:20 – 23:30 CST
7 - Spotlight: Adversarial Training is a Form of Data-dependent Operator Norm Regularization
Kevin Roth, Yannic Kilcher, Thomas Hofmann
We establish a theoretical link between adversarial training and operator norm regularization for deep neural networks. Specifically, we prove that $l_p$-norm constrained projected gradient ascent based adversarial training with an $l_q$-norm loss on the logits of clean and perturbed inputs is equivalent to data-dependent (p, q) operator norm regularization. This fundamental connection confirms the long-standing argument that a network’s sensitivity to adversarial examples is tied to its spectral properties and hints at novel ways to robustify and defend against adversarial attacks. We provide extensive empirical evidence on state-of-the-art network architectures to support our theoretical results.

00:30 – 00:40 CST
14 - Spotlight: Understanding Gradient Clipping in Private SGD: A Geometric Perspective
Xiangyi Chen, Steven Wu, Mingyi Hong

00:00 – 00:10 CST
11 - Spotlight: ExpandNets: Linear Over-parameterization to Train Compact Convolutional Networks
Shuxuan Guo, Jose M. Alvarez, Mathieu Salzmann
We introduce an approach to training a given compact network. To this end, we leverage over-parameterization, which typically improves both neural network optimization and generalization. Specifically, we propose to expand each linear layer of the compact network into multiple consecutive linear layers, without adding any nonlinearity. As such, the resulting expanded network, or ExpandNet, can be contracted back to the compact one algebraically at inference. In particular, we introduce two convolutional expansion strategies and demonstrate their benefits on several tasks, including image classification, object detection, and semantic segmentation. As evidenced by our experiments, our approach outperforms both training the compact network from scratch and performing knowledge distillation from a teacher. Furthermore, our linear over-parameterization empirically reduces gradient confusion during training and improves the network generalization.

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
