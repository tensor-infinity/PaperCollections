- [机器学习理论](#机器学习理论)
  * [PCA(probably approximately correct)学习理论](#pca)
  * [VC(Vapnik–Chervonenkis dimension)维](#vc)
  * [泛化理论](#泛化理论)
  * [最优化理论和方法](#最优化理论和方法)
  * [决策树](#决策树)
  * [贝叶斯分类器](#贝叶斯分类器)
  * [数据降维](#数据降维)
    + [主成分分析（PCA）](#pca1)
    + [流形学习](#manifold)
    + [线性判别分析（LDA）](#lda)
  * [logistic回归](#logistic回归)
  * [支持向量机（SVM）](#svm)
  * [距离度量学习](#距离度量学习)
  * [集成学习](#集成学习)
    + [Bagging与随机森林](#Bagging与随机森林)
    + [Boosting算法](#Boosting算法)
  * [概率图模型](#概率图模型)
    + [贝叶斯网络](#贝叶斯网络)
    + [隐马尔可夫模型](#隐马尔可夫模型)
    + [条件随机场](#条件随机场)
  * [聚类算法](#聚类算法)
  * [半监督学习](#半监督学习)
  * [强化学习](#强化学习)

## 机器学习理论

### PCA(probably approximately correct)学习理论

[1] L. Valiant. A theory of the learnable. Communications of the ACM, 27, 1984.

 

### VC(Vapnik–Chervonenkis dimension)维

[1] Blumer, A., Ehrenfeucht, A., Haussler, D., Warmuth, M. K. Learnability and the Vapnik–Chervonenkis dimension. Journal of the ACM. 36 (4): 929–865, 1989.

[2] Natarajan, B.K. On Learning sets and functions. Machine Learning. 4: 67–97, 1989.

[3] Karpinski, Marek; Macintyre, Angus. Polynomial Bounds for VC Dimension of Sigmoidal and General Pfaffian Neural Networks. Journal of Computer and System Sciences. 54 (1): 169–176, 1997.

 

### 泛化理论

[1] Wolpert, D.H., Macready, W.G. No Free Lunch Theorems for Optimization. IEEE Transactions on Evolutionary Computation 1, 67, 1997.

[2] Wolpert, David. The Lack of A Priori Distinctions between Learning Algorithms. Neural Computation, pp. 1341-1390, 1996.

[3] Wolpert, D.H., and Macready, W.G. Coevolutionary free lunches. IEEE Transactions on Evolutionary Computation, 9(6): 721-735, 2005.

[4] Whitley, Darrell, and Jean Paul Watson. Complexity theory and the no free lunch theorem. In Search Methodologies, pp. 317-339. Springer, Boston, MA, 2005.

[5] Kawaguchi, K., Kaelbling, L.P, and Bengio. Generalization in deep learning. 2017.

[6] Chiyuan Zhang, Samy Bengio, Moritz Hardt, Benjamin Recht, Oriol Vinyals. Understanding deep learning requires rethinking generalization. international conference on learning representations, 2017.

 

### 最优化理论和方法

[1] L. Bottou. Stochastic Gradient Descent Tricks. Neural Networks: Tricks of the Trade. Springer, 2012.

[2] I. Sutskever, J. Martens, G. Dahl, and G. Hinton. On the Importance of Initialization and Momentum in Deep Learning. Proceedings of the 30th International Conference on Machine Learning, 2013.

[3] Duchi, E. Hazan, and Y. Singer. Adaptive Subgradient Methods for Online Learning and Stochastic Optimization. The Journal of Machine Learning Research, 2011.

[4] M. Zeiler. ADADELTA: An Adaptive Learning Rate Method. arXiv preprint, 2012.

[5] T. Tieleman, and G. Hinton. RMSProp: Divide the gradient by a running average of its recent magnitude. COURSERA: Neural Networks for Machine Learning.Technical report, 2012.

[6] D. Kingma, J. Ba. Adam: A Method for Stochastic Optimization. International Conference for Learning Representations, 2015.

[7] Hardt, Moritz, Ben Recht, and Yoram Singer. Train faster, generalize better: Stability of stochastic gradient descent. Proceedings of The 33rd International Conference on Machine Learning. 2016.

 

### 决策树

[1] Breiman, L., Friedman, J. Olshen, R. and Stone C. Classification and Regression Trees, Wadsworth, 1984.

[2] J. Ross Quinlan. Induction of decision trees. Machine Learnin, 1(1): 81-106, 1986.

[3] J. Ross Quinlan. Learning efficient classification procedures and their application to chess end games. 1993.

[4] J. Ross Quinlan. C4.5: Programs for Machine Learning. Morgan Kaufmann, San Francisco, CA, 1993.

 

### 贝叶斯分类器

[1] Rish, Irina. An empirical study of the naive Bayes classifier. IJCAI Workshop on Empirical Methods in Artificial Intelligence, 2001.

 

### 数据降维

#### 主成分分析(PCA)
[1] Pearson, K. On Lines and Planes of Closest Fit to Systems of Points in Space. Philosophical Magazine. 2 (11): 559–572. 1901.

[2] Ian T. Jolliffe. Principal Component Analysis. Springer Verlag, New York, 1986.

[3] Scholkopf, B.,Smola,A.,Mulller,K.-P. Nonlinear component analysis as a kernel eigenvalue problem. Neural Computation, 10(5), 1299-1319, 1998.

[4] Sebastian Mika,Bernhard Scholkopf,Alexander J Smola,Klausrobert Muller,Matthias Scholz Gun. Kernel PCA and de-noising in feature spaces. neural information processing systems, 1999.

 

#### 流形学习

[1] Roweis, Sam T and Saul, Lawrence K. Nonlinear dimensionality reduction by locally linear embedding. Science, 290(5500). 2000: 2323-2326.

[2] Belkin, Mikhail and Niyogi, Partha. Laplacian eigenmaps for dimensionality reduction and data representation. Neural computation. 15(6). 2003:1373-1396.

[3] He Xiaofei and Niyogi, Partha. Locality preserving projections. NIPS. 2003:234-241.

[4] Tenenbaum, Joshua B and De Silva, Vin and Langford, John C. A global geometric framework for nonlinear dimensionality reduction. Science, 290(5500). 2000: 2319-2323.

[5] Laurens Van Der Maaten, Geoffrey E Hinton. Visualizing Data using t-SNE. 2008, Journal of Machine Learning Research.

 

#### 线性判别分析(LDA)

[1] Ronald A. Fisher. The use of multiple measurements in taxonomic problems. Annals of Eugenics, 7 Part 2: 179-188, 1936.

[2] Geoffrey J. McLachlan. Discriminant Analysis and Statistical Pattern Recognition. Wiley, New York, 1992.

 

### logistic回归

[1] Cox, DR. The regression analysis of binary sequences (with discussion). J Roy Stat Soc B. 20 (2): 215–242, 1958.

[2] David W Hosmer, Stanley Lemeshow. Applied logistic regression. Technometrics. 2000.

[3] Thomas P. Minka. A comparison of numerical optimizers for logistic regression, 2003.

[4] Kwangmoo Koh, Seung-Jean Kim, and Stephen Boyd. An interior-point method for large scale l1-regularized logistic regression. Journal of Machine Learning Research, 8:1519-1555, 2007.

[5] Chih-Jen Lin, Ruby C.Weng, S.Sathiya Keerthi. Trust Region Newton Method for Large-Scale Logistic Regrression. Journal of Machine Learning Research,9, 627-650, 2008.

[6] Rong-En Fan, Kai-Wei Chang, Cho-Jui Hsieh, Xiang-Rui Wang, Chih-Jen Lin. LIBLINEAR: A Library for Large Linear Classification. Journal of Machine Learning Research, 9, 1871-1874, 2008.

 

### 支持向量机(SVM)

[1] B.E.Boser, I.Guyon, and V. Vapni. A training algorithm for optimal margin classifiers. In Proceedings of the Fifth Annual Workshop on Computational Learning Theory, pages 144-152. ACM Press, 1992.

[2] Cortes, C. and Vapnik, V. Support vector networks. Machine Learning, 20, 273-297, 1995.

[3] Bernhard Scholkopf, Christopher J. C. Burges, and Valdimir Vapnik. Extracting support data for a given task. 1995.

[4] Burges JC. A tutorial on support vector machines for pattern recognition. Bell Laboratories, Lucent Technologies, 1997.

[5] Scholkopf, Christopher J. C. Burges, and Alexander J. Smola, editor. Advances in Kernel Methods - Support Vector Learning, Cambridge, MA, MIT Press. 1998.

[6] John C. Platt. Fast training of support vector machines using sequential minimal optimization. 1998.

[7] C.-C. Chang and C.-J. Lin. LIBSVM: a Library for Support Vector Machines. ACM TIST, 2:27:1-27:27, 2011.

 

### 距离度量学习

[1] S. Chopra, R. Hadsell, Y. LeCun. Learning a similarity metric discriminatively, with application to face verification. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2005), pages 349-356, San Diego, CA, 2005.

[2] Kilian Q Weinberger, Lawrence K Saul. Distance Metric Learning for Large Margin Nearest Neighbor Classification. Journal of Machine Learning Research, 2009.

 

### 集成学习

#### Bagging与随机森林

[1] Breiman, Leo. Random Forests. Machine Learning 45 (1), 5-32, 2001.

 

#### Boosting算法

[1] Freund, Y. Boosting a weak learning algorithm by majority. Information and Computation, 1995.

[2] Yoav Freund, Robert E Schapire. A decision-theoretic generalization of on-line learning and an application to boosting. computational learning theory. 1995.

[3] Freund, Y. An adaptive version of the boost by majority algorithm. In Proceedings of the Twelfth Annual Conference on Computational Learning Theory, 1999.

[4] R.Schapire. The boosting approach to machine learning: An overview. In MSRI Workshop on Nonlinear Estimation and Classification, Berkeley, CA, 2001.

[5] Freund Y, Schapire RE. A short introduction to boosting. Journal of Japanese Society for Artificial Intelligence, 14(5):771-780. 1999.

[7] Jerome Friedman, Trevor Hastie and Robert Tibshirani. Additive logistic regression: a statistical view of boosting. Annals of Statistics 28(2), 337–407. 2000.

[8] Jerome H Friedman. Greedy function approximation: A gradient boosting machine. Annals of Statistics, 2001.

[9] Tianqi Chen, Carlos Guestrin. XGBoost: A Scalable Tree Boosting System.  knowledge discovery and data mining, 2016.

[10] Guolin Ke, Qi Meng, Thomas Finley, Taifeng Wang, Wei Chen, Weidong Ma,  Qiwei Ye, Tieyan Liu. LightGBM: A Highly Efficient Gradient Boosting Decision Tree. neural information processing systems, 2017.

 

### 概率图模型

#### 贝叶斯网络

[1] Nir Friedman, Dan Geiger, Moises Goldszmidt. Bayesian Network Classifiers. Machine Learning.1997.

 

#### 隐马尔可夫模型

[1] Baum, L. E., Petrie, T. Statistical Inference for Probabilistic Functions of Finite State Markov Chains. The Annals of Mathematical Statistics. 37 (6): 1554–1563. 1966.

[2] Baum, L. E., Eagon, J. A. An inequality with applications to statistical estimation for probabilistic functions of Markov processes and to a model for ecology. Bulletin of the American Mathematical Society. 73 (3): 360. 1967.

[3] Baum, L. E., Petrie, T., Soules, G., Weiss, N. A Maximization Technique Occurring in the Statistical Analysis of Probabilistic Functions of Markov Chains. The Annals of Mathematical Statistics. 41: 164. 1970

[4] Baum, L.E. An Inequality and Associated Maximization Technique in Statistical Estimation of Probabilistic Functions of a Markov Process. Inequalities. 3: 1–8. 1972.

[5] Lawrence R. Rabiner. A tutorial on Hidden Markov Models and selected applications in speech recognition. Proceedings of the IEEE. 77 (2): 257–286. 1989.

 

#### 条件随机场

[1] Lafferty, J., McCallum, A., Pereira, F. Conditional random fields: Probabilistic models for segmenting and labeling sequence data. Proc. 18th International Conf. on Machine Learning. Morgan Kaufmann. pp. 282–289. 2001.

 
### 聚类算法

[1] MacQueen, J. B. Some Methods for classification and Analysis of Multivariate Observations. Proceedings of 5th Berkeley Symposium on Mathematical Statistics and Probability. 1. University of California Press. pp. 281–297, 1967

[2] Martin Ester, Hanspeter Kriegel, Jorg Sander, Xu Xiaowei. A density-based algorithm for discovering clusters in large spatial databases with noise. Proceedings of the Second International Conference on Knowledge Discovery and Data Mining, pp. 226–231, 1996.

[3] Mihael Ankerst, Markus M Breunig, Hanspeter Kriegel, Jorg Sander. OPTICS: Ordering Points To Identify the Clustering Structure. ACM SIGMOD international conference on Management of data. ACM Press. pp. 49–60, 1999.

[4] Yizong Cheng. Mean Shift, Mode Seeking, and Clustering. IEEE Transactions on Pattern Analysis and Machine Intelligence, 1995.

[5] J C Dunn. A Fuzzy Relative of the ISODATA Process and Its Use in Detecting Compact Well-Separated Clusters. Cybernetics and Systems, 1973.

[6] Charles Elkan. Using the triangle inequality to accelerate k-means. international conference on machine learning, 2003.

[7] Arthur P Dempster, Nan M Laird, Donald B Rubin. Maximum Likelihood from Incomplete Data via the EM Algorithm. Journal of the royal statistical society series b-methodological, 1976.

[8] Dan Pelleg, Andrew W Moore. X-means: Extending K-means with Efficient Estimation of the Number of Clusters. In ICML (Vol. 1), 2000.

[9] Greg Hamerly, Charles Elkan. Learning the k in k-means. Advances in neural information processing systems, 2004.

[10] M Emre Celebi, Hassan A Kingravi, Patricio A Vela. A comparative study of efficient initialization methods for the k-means clustering algorithm. Expert Systems With Applications, 2013.

[11] Andrew Y Ng, Michael I Jordan, Yair Weiss. On Spectral Clustering: Analysis and an algorithm. neural information processing systems, 2002.

[12] Ulrike Von Luxburg. A tutorial on spectral clustering. Statistics and Computing, 2007.

[13] Dorin Comaniciu, Peter Meer. Mean shift: a robust approach toward feature space analysis. IEEE Transactions on Pattern Analysis and Machine Intelligence, 2002.

 

### 半监督学习

[1] Olivier Chapelle, Bernhard Schlkopf, Alexander Zien. Semi-supervised learning. Cambridge. Mass: MIT Press. ISBN 978-0-262-03358-9.

[2] Isaac Triguero, Salvador Garcia, Francisco Herrera. Self-labeled techniques for semi-supervised learning: taxonomy, software and empirical study. Knowledge and Information Systems, 2015.

[3] Zhu, Xiaojin. Semi-supervised learning literature survey. Computer Sciences, University of Wisconsin-Madison, 2008.

[6] Antti Rasmus, Harri Valpola, Mikko Honkala, Mathias Berglund, Tapani Raiko. Semi-supervised learning with Ladder networks. neural information processing systems, 2015.

[7] M. Belkin, P. Niyogi. Semi-supervised Learning on Riemannian Manifolds. Machine Learning. 56 (Special Issue on Clustering): 209–239, 2004.

[8] Diederik P Kingma, Shakir Mohamed, Danilo Jimenez Rezende, Max Welling. Semi-supervised Learning with Deep Generative Models. neural information processing systems, 2014.

[9] Thorsten Joachims. Transductive inference for text classification using support vector machines.  international conference on machine learning, 1999.

 

### 强化学习

[1] Kaelbling, Leslie P., Littman, Michael L., Moore, Andrew W. Reinforcement Learning: A Survey. Journal of Artificial Intelligence Research. 4: 237-285, 1996.

[2] Richard Sutton. Learning to predict by the methods of temporal differences. Machine Learning. 3 (1): 9-44.1988.

[3] Volodymyr Mnih, Koray Kavukcuoglu, David Silver, Alex Graves, Ioannis Antonoglou. Playing Atari with Deep Reinforcement Learning. NIPS 2013.

[4] Mnih, Volodymyr, et al. Human-level control through deep reinforcement learning. Nature. 518 (7540): 529-533, 2015.

[5] John N Tsitsiklis, B Van Roy. An analysis of temporal-difference learning with function approximation. IEEE Transactions on Automatic Control, 1997.

[6] Richard S Sutton, David A Mcallester, Satinder P Singh, Yishay Mansour. Policy Gradient methods for reinforcement learning with function approximation. neural information processing systems, 2000.

[7] Timothy P Lillicrap, Jonathan J Hunt, Alexander Pritzel, Nicolas Heess, Tom Erez, Yuval Tassa. Continuous Control With Deep Reinforcement Learning. international conference on learning representations, 2016.

[8] Volodymyr Mnih, Adria Puigdomenech Badia, Mehdi Mirza, Alex Graves, Tim Harley, Timothy P Lill. Asynchronous methods for deep reinforcement learning. international conference on machine learning, 2016.

[9] Yuxi Li. Deep Reinforcement Learning: An Overview. 2017.

[10] David Silver, et al. Mastering the Game of Go with Deep Neural Networks and Tree Search. Nature, 2016.

[11] David Silver, Thomas Hubert, Julian Schrittwieser, Ioannis Antonoglou, Matthew Lai, Arthur Guez. AlphaZero: Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm. arXiv: Artificial Intelligence, 2017.

[12] Christopher JCH Watkins and Peter Dayan. Q-learning. Machine learning, 8(3-4):279–292, 1992.

[13] Gerald Tesauro. Temporal difference learning and TD-gammon. Communications of the ACM, 38(3):58–68, 1995.