https://openreview.net/pdf?id=H1eArT4tPH
finite width neural-nets; 有人做了

https://openreview.net/pdf?id=rkeO-lrYwr  把LTH和 mode connectivity结合起来，有人做了

https://openreview.net/pdf?id=B1g5sA4twr
Deep double descent
做了更多试验验证 deep nn 还有double descent现象  

https://openreview.net/pdf?id=SJlVY04FwH  
CONVERGENCE BEHAVIOUR OF SOME GRADIENTBASED METHODS ON BILINEAR ZERO-SUM GAMES
这篇文章比较有意思，用eigenvalues 来分析所有已知的算法对min-max linear game的收敛性, 可以给出精确的收敛性条件. 或许部分可以解释stepsize大小的问题

https://openreview.net/pdf?id=ryg7vA4tPB
RIGGING THE LOTTERY: MAKING ALL TICKETS WINNERS
似乎没说太清楚什么是tickets？

https://openreview.net/pdf?id=HkxedlrFwB
USING THE VARIATION OF THE GRADIENT TO ACCELERATE FIRST-ORDER OPTIMIZATION ALGORITHMS
简单却有效的universal加速优化算法的方法. 

https://openreview.net/pdf?id=rkgOlCVYvB
Linear network geometry, using determinental variety

https://openreview.net/pdf?id=Byg9A24tvB
一个新的loss, 说比cross-entropy好 for robustness

https://openreview.net/pdf?id=SygD31HFvB
lower bound, 可能是北大张志华的工作

https://openreview.net/pdf?id=BkgXHTNtvS  另外一个相关的工作，也是证明ReLU network 有strict local min

**GANS**
https://openreview.net/pdf?id=HylsTT4FvB
steeribility of GANs.
 讨论为什么GAN不能表示out-of-sample data; 同时解释为什么可能可以generate new data, 如果使用某些技巧的话

https://openreview.net/pdf?id=ryxMW6EtPB
training GAN with duality gap
看上去有意思

https://openreview.net/pdf?id=B1x3EgHtwB
EXPANDNETS: LINEAR OVER-PARAMETERIZATION TO TRAIN COMPACT CONVOLUTIONAL NETWORKS
有趣的想法：直接用多层线性代替一层线性，可以提高表现

https://openreview.net/pdf?id=B1lPaCNtPB
1m*1m generation
realness GAN

https://openreview.net/pdf?id=r1eCy0NtDH
NTK and mean-field analysis, 似乎比较强

https://openreview.net/pdf?id=SJlbGJrtDB
Dynamic Sparse Training: Find Efficient Sparse Network From Scratch With Trainable Masked Layers

https://openreview.net/pdf?id=SyeHPgHFDr
除了vision dataset之外，存在bad local minima

https://openreview.net/pdf?id=rJePwgSYwB
SGD learns 2-layer-net in WGAN

https://openreview.net/pdf?id=Skeh-xBYDH
ON SYMMETRY AND INITIALIZATION FOR NEURAL NETWORKS
show that when learning symmetric functions, one can choose initial conditions so that standard SGD training efficiently produces generalization guarantees.

https://openreview.net/pdf?id=SJeLIgBKPS
implicit regularization of neural-nets


https://openreview.net/pdf?id=SJgwzCEKwH
mode connectivity and robustness, 我本来想做的

https://openreview.net/pdf?id=HyxyIgHFvr
TRUTH OR BACKPROPAGANDA? AN EMPIRICAL INVESTIGATION OF DEEP LEARNING THEORY
一些landscape猜想的实验讨论; 说明bad local-min存在

https://openreview.net/pdf?id=BJgnXpVYwS
new smoothness condition and GD convergence proof; nice paper
WHY GRADIENT CLIPPING ACCELERATES TRAINING: A THEORETICAL JUSTIFICATION FOR ADAPTIVITY

https://openreview.net/forum?id=ryl5CJSFPS
GENERALIZATION GUARANTEES FOR NEURAL NETS VIA HARNESSING THE LOW-RANKNESS OF JACOBIAN
 
https://openreview.net/pdf?id=B1gX8kBtPr
universal approximation and robust
 
https://openreview.net/pdf?id=rkl8sJBYvH
NTK works on small data sets, and sometimes better than ResNet;
a bit surprising
 
https://openreview.net/pdf?id=SkgBfaNKPr
Topology of neural-nets
改变betti number 到最小 

https://openreview.net/pdf?id=rylmoxrFDH
binary network,  signal propagation and order-to-chaos theory;  derive an initialization that is different from common belief

https://openreview.net/pdf?id=BJgctpEKwr
interpretable GAN;  RP-GAN.  实验文章，但有意思, 值得再读

https://openreview.net/pdf?id=B1xGGTEtDH
universal approximation of deep narrow networks,
 only d_x + d_y width enough

https://openreview.net/pdf?id=H1gBsgBYwH
double descent study for 2-layer neural-nets; 

https://openreview.net/pdf?id=Bylp62EKDH
loss function design for triplet loss; finding strange behavior of triplet loss
问题: 能否从Landscape角度讨论？

https://openreview.net/pdf?id=B1xw9n4Kwr
MODEL ARCHITECTURE CONTROLS GRADIENT DESCENT DYNAMICS: A COMBINATORIAL PATH-BASED FORMULA
直接计算paths, 来分析GD的收敛速度；比较神奇的角度

https://openreview.net/pdf?id=SkgsACVKPH
Gradient signal preservation
似乎是训练小网络的一种方式，值得一读. --之后: GraSP 比较有趣

https://openreview.net/pdf?id=ByeSYa4KPS
和上面似乎类似

https://openreview.net/pdf?id=rJe4_xSFDB
LIPSCHITZ CONSTANT ESTIMATION FOR NEURAL NETWORKS VIA SPARSE POLYNOMIAL OPTIMIZATION
估计lipschitz constant的方法

https://openreview.net/pdf?id=HyxLRTVKPH
BUDGETED TRAINING: RETHINKING DEEP NEURAL NETWORK TRAINING UNDER RESOURCE CONSTRAINTS
learning rate schedule, 给定epochs数目，如何选择learning rate decay?
有意思。可以作为收敛理论分析的Motivation, 说明应该采用Linear decay, 只是斜率不同. 

https://openreview.net/pdf?id=Sygg3JHtwB
stepsize optimization
又一个优化stepsize. 把stepsize作为一部分优化，用ADMM来解这个问题。表现相当不错。值得一读。

https://openreview.net/pdf?id=BJevJCVYvB
又一个优化learning rate schedule的文章 

https://openreview.net/pdf?id=Ske6qJSKPH
再来一个learning rate schedule

https://openreview.net/pdf?id=S1eik6EtPB
一般的min-max框架, beyond adversarial training

https://openreview.net/pdf?id=BkgNqkHFPr
CNTK,进化版, 表现刷到了89% on CIFAR-10.

https://openreview.net/pdf?id=HJx0U64FwS
A MECHANISM OF IMPLICIT REGULARIZATION IN DEEP LEARNING
一个random walk analysis, 
给出了generalization bounds.

https://openreview.net/pdf?id=SklfY6EFDH
REPRESENTATION QUALITY EXPLAIN ADVERSARIAL ATTACKS

https://openreview.net/pdf?id=HJlU-AVtvS
NTK的spectra的分析 

https://openreview.net/pdf?id=BJgRsyBtPB
max-sliced GAN; sorting is worse than greedy assignment

https://openreview.net/pdf?id=rkg1ngrFPr
INFORMATION GEOMETRY OF ORTHOGONAL INITIALIZATIONS AND TRAINING
把正交初始化, dynamical isometry和NTK联系起来

https://openreview.net/pdf?id=BylKwnEYvS
star convexity for NMF. A bit surprising this can be proved.

https://openreview.net/pdf?id=H1gEP6NFwr
略神奇. 如何比较”easy to tune”? 本文提出了一个quantify的方法，从而进一步说明了adam确实比SGD更容易tune. I’ve thought about this idea before. 
https://openreview.net/pdf?id=HygrAR4tPS
非常相关的工作，也是说明如何比较”tuning effort”,也说明Adam比SGD更好

https://openreview.net/pdf?id=B1l0wp4tvr
information bottleneck的升级版；更好的估计mutual info的方法.  

https://openreview.net/pdf?id=H1lMogrKDH
LEARNING DIFFICULT PERCEPTUAL TASKS WITH HODGKIN-HUXLEY NETWORKS
用更接近神经科学的模型来解决图像分类;在CIFAR-10上表现尚可

https://openreview.net/pdf?id=Byxl-04KvH
NESTED LEARNING FOR MULTI-GRANULAR TASKS

https://openreview.net/pdf?id=BJlrF24twB
BACKPACK: 用backprop来处理beyond gradient的信息，比如Hessian-vector product. 这条线由来已久，这个工作可能是一个加强，并有PyTorch包. 如果做二阶方法，这个工作会有用

https://openreview.net/pdf?id=rkxsgkHKvH
polynomial activations.
一篇神奇的工作，测试了很多很多polynomial neurons, 并提出了优化方法使得它们能够很好的训练。我们应该cite, 并指出：只有我们的工作才给了它们以理论支持

https://openreview.net/pdf?id=Byg9bxrtwS
KERNEL AND RICH REGIMES IN OVERPARAMETRIZED MODELS
又一篇NTK的follow-up，展示了从kernal到rich的转折--和初始点选取有关

https://openreview.net/pdf?id=rygT_JHtDr
SCALABLE DEEP NEURAL NETWORKS VIA LOWRANK MATRIX FACTORIZATION
可瘦身的网络; 和slimmable network相关,压缩by low-rank

https://openreview.net/pdf?id=rkgfdeBYvH
HOW THE CHOICE OF ACTIVATION AFFECTS TRAINING OF OVERPARAMETRIZED NEURAL NETS
两层的网络分析，神经元对网络的影响

https://openreview.net/pdf?id=S1gFvANKDS
wide-network analysis by Feymann diagrams
计算高斯积分的方式,宽网络分析

https://openreview.net/pdf?id=SJxSDxrKDr
robustness. 结合AT和certified training. 

https://openreview.net/pdf?id=HyxJhCEFDS
Adversarial training的两个发现: 1)把clean images从训练中拿掉之后表现好了18%; 2)深度对robustness有效，即使push到638层ResNet也有提升


https://openreview.net/pdf?id=B1l6y0VFPr
IDENTITY CRISIS: MEMORIZATION AND GENERALIZATION UNDER EXTREME OVERPARAMETERIZATION
有意思，检查了最简单的task, 看到底是memorize还是generalize, 发现CNN比fully connected好

https://openreview.net/pdf?id=ByxGkySKwH
ODD: know what you don’t know, provably

https://openreview.net/pdf?id=rJxvD3VKvr
WIDE NEURAL NETWORKS ARE INTERPOLATING KERNEL METHODS: IMPACT OF INITIALIZATION ON GENERALIZATION

https://openreview.net/pdf?id=BylldnNFwS
fancy math系列, tropical topology for LTH

https://openreview.net/pdf?id=SkliR1SKDS   
RETHINKING DATA AUGMENTATION: SELF-SUPERVISION AND SELF-DISTILLATION
