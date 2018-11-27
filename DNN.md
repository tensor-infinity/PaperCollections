- [深度神经网络](#深度神经网络)
  * [人工神经网络](#人工神经网络)
  * [卷积神经网络](卷积神经网络)
  * [循环神经网络](#循环神经网络)
  * [自动编码器](#自动编码器)
  * [受限玻尔兹曼机](#受限玻尔兹曼机)
  * [生成对抗网络](#生成对抗网络)
  * [变分自动编码器](#变分自动编码器)
  * [深度模型压缩与优化](#深度模型压缩与优化)

## 深度神经网络

### 人工神经网络

[1] Anil K. Jain, Jianchang Mao, and K. Moidin Mohiuddin. Artificial neural networks: A tutorial. Computer, 29(3):31-44, 1996.

[2] Richard Lippmann. An introduction to computing with neural nets. IEEE ASSP Magazine, page 4-22, April 1987.

[3] David E. Rumelhart, Geoffrey E. Hinton, and Ronald J. Williams. Learning internal representations by back-propagating errors. Nature, 323(99): 533-536, 1986.

[4] Robert Hecht-Nielsen. Theory of the backpropagation neural network. In Proceeding of the International Joint Conference on Neural Networks(IJCNN), volume 1, 593-605. IEEE, New York, 1989.

[5] Kurt Hornik. Approximation capabilities of multilayer feedforward networks. Neural Networks.1991.

[6] Hava T Siegelmann, Eduardo D Sontag. On the computational power of neural nets. conference on learning theory. 1992.

[7] Hornik, K., Stinchcombe, M., and White, H. Multilayer feedforward networks are universal approximators. Neural Networks, 2, 359-366, 1989.

[8] Cybenko, G. Approximation by superpositions of a sigmoid function. Mathematics of Control, Signals, and Systems, 2, 303-314, 1989.

[9] Hornik, K., Stinchcombe, M., and White, H. Universal approximation of an unknown mapping and its derivatives using multilayer feedforward networks. Neural networks, 3(5), 551-560, 1990.

[10] Leshno, M., Lin, V. Y., Pinkus, A., and Schocken, S. Multilayer feedforward networks with a nonpolynomial activation function can approximate any function. Neural Networks, 6, 861-867, 1993.

[11] Barron, A. E. Universal approximation bounds for superpositions of a sigmoid function. IEEE Transactions on Information Theory, 39, 930-945, 1993.

[12] Raman Arora, Amitabh Basu, Poorya Mianjy, Anirbit Mukherjee. Understanding Deep Neural Networks with Rectified Linear Units. Electronic Colloquium on Computational Complexity. 2016.

[13] Xavier Glorot, Yoshua Bengio. Understanding the difficulty of training deep feedforward neural networks. Journal of Machine Learning Research. 2010.

[14] M. Riedmiller and H. Braun, A Direct Adaptive Method for Faster Backpropagation Learning: The RPROP Algorithm, Proc. ICNN, San Francisco (1993).

[15] Choromanska A, Henaff M, Mathieu M, Ben ArousG, Le Cun Y. The loss surfaces of multilayer networks. arXiv:1412.0233. 2014.

[16] Gori, M, Tesi, A. On the problem of local minima in backpropagation. IEEE Transcations on Pattern Analysis and Machine Intelligence, 14(1), 76-86. 1992.

[17] Saxe, A. M., McClelland, J. L., Ganguli, S. Exact solutions to the nonlinear dynamics of learning in deep linear neural networks. ICLR. 2013.

[18] Dauphin, Y., Pascanu, R., Gulcehre, C., Cho, K., Ganguli, S., Bengio, Y. 2014. Identifying and attacking the saddle point problem in high-dimensional non-convex optimization. NIPS 2014. 

[19] Goodfellow, I. J., Vinyals, O., Saxe, A. M. Qualitatively characterizing neural network optimization problems. International Conference on Learning Representations. 2015.

 

### 卷积神经网络

[1] LeCun, B.Boser, J.S.Denker, D.Henderson, R.E.Howard, W.Hubbard, and L.D.Jackel. Backpropagation applied to handwritten zip code recognition. Neural Computation, 1989.

[2] Y. LeCun, B. Boser, J. S. Denker, D. Henderson, R. E. Howard, W. Hubbard, and L. D. Jackel. Handwritten digit recognition with a back-propagation network. In David Touretzky, editor, Advances in Neural Information Processing Systems 2 (NIPS*89), Denver, CO, Morgan Kaufman, 1990.

[3] Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner. Gradient-based learning applied to document recognition. Proceedings of the IEEE, november 1998.

[4] Alex Krizhevsky, Ilya Sutskever, Geoffrey E.Hinton. ImageNet Classification with Deep Convolutional Neural Networks. 2012.

[5] Zeiler M D, Fergus R. Visualizing and Understanding Convolutional Networks. European Conference on Computer Vision, 2013.

[6] Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, Andrew Rabinovich, Going Deeper with Convolutions, Arxiv Link: http://arxiv.org/abs/1409.4842.

[7] K. Simonyan and A. Zisserman. Very Deep Convolutional Networks for Large-Scale Image Recognition. international conference on learning representations. 2015.

[8] Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun. Deep Residual Learning for Image Recognition. computer vision and pattern recognition, 2015.

[9] Andreas Veit,Michael J Wilber, Serge J Belongie. Residual Networks Behave Like Ensembles of Relatively Shallow Networks. neural information processing systems, 2016.

[10] Long J, Shelhamer E, Darrell T, et al. Fully convolutional networks for semantic segmentation. Computer Vision and Pattern Recognition, 2015.

### 循环神经网络

[1] Ronald J Williams, David Zipser. A learning algorithm for continually running fully recurrent neural networks.  Neural Computation. 1989.

[2] Mikael Boden. A guide to recurrent neural networks and backpropagation. 2001.

[3] Razvan Pascanu, Caglar Gulcehre, Kyunghyun Cho, Yoshua Bengio. How to Construct Deep Recurrent Neural Networks. international conference on learning representations. 2014.

[4] Fernando J Pineda. Generalization of back-propagation to recurrent neural networks. Physical Review Letters. 1987.

[5] Paul J Werbos. Backpropagation through time: what it does and how to do it. Proceedings of the IEEE.1990.

[6] Xavier Glorot, Yoshua Bengio. On the difficulty of training recurrent neural networks. international conference on machine learning. 2013.

[7] Y. Bengio, P. Simard, P. Frasconi. Learning long-term dependencies with gradient descent is difficult. IEEE Transactions on Neural Networks, 5(2):157-166, 1994.

[8] S. Hochreiter, J. Schmidhuber. Long short-term memory. Neural  computation, 9(8): 1735-1780, 1997.

[9] M. Schuster and K. K. Paliwal. Bidirectional recurrent neural networks. IEEE Transactions on Signal Processing, 45(11):2673-2681, 1997.

[10] Alex Graves. Supervised Sequence Labelling with Recurrent Neural Networks. 2012.

[11] Junyoung Chung, Caglar Gulcehre, Kyunghyun Cho, Yoshua Bengio. Gated Feedback Recurrent Neural Networks. international conference on machine learning. 2015.

[12] Alex Graves, Santiago Fernandez, Faustino J Gomez, Jurgen Schmidhuber. Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks.international conference on machine learning. 2006.

[13] A. Graves, A.Mohamed, G. Hinton, Speech Recognition with Deep Recurrent Neural Networks, ICASSP 2013.

[14] Ilya Sutskever, Oriol Vinyals, Quoc V Le. Sequence to Sequence Learning with Neural Networks. neural information processing systems. 2014.

[15] Tomas Mikolov, Martin Karafiat, Lukas Burget, Jan Cernocký, Sanjeev Khudanpur. Recurrent neural network based language model. 2010, conference of the international speech communication association.

[16] Graves, Alex. Generating sequences with recurrent neural networks. arXiv preprint arXiv:1308.0850 (2013).

 

### 自动编码器

[1] J. Deng, Z. X. Zhang, M. Erik. Sparse auto-encoder based feature transfer learning for speech emotion recognition[J]. Proc. of Humaine Association Conference on Affective Computing and Intelligent Interaction, 511-516, 2013.

[2] J. Gehring, Y. J. Miao, F. Metze. Extracting deep bottleneck features using stacked auto-encoders[J]. Proc. of the 26th IEEE International Conference on Acoustics, Speech and Signal Processing, 2013: 3377-3381.

[3] Salah Rifai, Pascal Vincent, Xavier Muller, Xavier Glorot, Yoshua Bengio. Contractive Auto-Encoders: Explicit Invariance During Feature Extraction. international conference on machine learning, 2011.

[4] Pascal Vincent, Hugo Larochelle, Yoshua Bengio, Pierreantoine Manzagol. Extracting and composing robust features with denoising auto encoders. international conference on machine learning, 2008.

[5] Junbo Jake Zhao,Michael Mathieu , Ross Goroshin , Yann Lecun. Stacked What-Where Auto-encoders. arXiv: Machine Learning, 2015.

[6] Pascal Vincent, Hugo Larochelle, Isabelle Lajoie, Yoshua Bengio, Pierreantoine Manzagol. Stacked Denoising Autoencoders: Learning Useful Representations in a Deep Network with a Local Denoising Criterion. Journal of Machine Learning Research, 2010.

[7] G.E.Hinton, A.Krizhevsky, S.D.Wang. Transforming Auto-encoders. international conference on artificial neural networks, 2011.

[8] G.E.Hinton, et al. Reducing the Dimensionality of Data with Neural Networks, Science 313, 504,2006.

 

### 受限玻尔兹曼机

[1] Nicolas Le Roux, Yoshua Bengio. Representational power of Restricted Boltzmann Machines and deep belief networks. Neural Computation., 2008.

[2] Geoffrey E Hinton.A Practical Guide to Training Restricted Boltzmann Machines. 2012.

[3] Ruslan Salakhutdinov, Geoffrey E Hinton. Deep Boltzmann Machines. international conference on artificial intelligence and statistics, 2009.

[4] Ruslan Salakhutdinov, Andriy Mnih, Geoffrey E Hinton. Restricted Boltzmann machines for collaborative filtering. international conference on machine learning, 2007.

 

### 生成对抗网络

[1] Goodfellow Ian, Pouget-Abadie J, Mirza M, et al. Generative adversarial nets. Advances in Neural Information Processing Systems, 2672-2680, 2014.

[2] Mirza M, Osindero S. Conditional Generative Adversarial Nets. Computer Science, 2672-2680, 2014.

[3] Radford A, Metz L, Chintala S. Unsupervised representation learning with deep convolutional generative adversarial networks. arXiv preprint arXiv:1511.06434, 2015.

[4] Denton E L, Chintala S, Fergus R. Deep Generative Image Models using a Laplacian Pyramid of Adversarial Networks. Advances in neural information processing systems. 1486-1494, 2015.

[5] S Reed, Zeynep Akata, Xinchen Yan, Lajanugen Logeswaran, Bernt Schiele,Honglak Lee. Generative Adversarial Text to Image Synthesis.  international conference on machine learning, 2016.

[6] Christian Ledig, Lucas Theis, Ferenc Huszar, Jose Caballero, Andrew Aitken, Alykhan Tejani, Johannes Totz, Zehan Wang, Wenzhe Shi. Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network. Computer Vision and Pattern Recognition, 2016.

[7] Chen X, Duan Y, Houthooft R, et al. InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets[J]. arXiv preprint arXiv:1606.03657, 2016.

[8] Martin Arjovsky, Leon Bottou. Towards Principled Methods for Training Generative Adversarial Networks. ICLR 2017.

 

### 变分自动编码器

[1] Diederik P Kingma, Max Welling. Auto-Encoding Variational Bayes. international conference on learning representations, 2014.

 

 

### 深度模型压缩与优化

[1] Song Han, Huizi Mao, William J Dally. Deep Compression: Compressing Deep Neural Networks with Pruning, Trained Quantization and Huffman Coding. international conference on learning representations, 2016.

[2] Mohammad Rastegari, Vicente Ordonez, Joseph Redmon, Ali Farhadi. XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks. european conference on computer vision, 2016.

[3] Matthieu Courbariaux, Itay Hubara, Daniel Soudry, Ran Elyaniv, Yoshua Bengio. Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1. arXiv: Learning, 2016.

[4] Han, Song, Pool, Jeff, Tran, John, and Dally, William J. Learning both weights and connections for efficient neural networks. In Advances in Neural Information Processing Systems, 2015.

[5] Denton, E.L, Zaremba, W, Bruna, J, LeCun, Y, Fergus, R. Exploiting linear structure within convolutional networks for efficient evaluation. In Advances in Neural Information Processing Systems. 1269-1277, 2014.

[6] Jaderberg. M, Vedaldi, A. Zisserman, A. Speeding up convolutional neural networks with low rank expansions. arXiv: 1405.3866, 2014.

[7] Shuchang Zhou, Yuxin Wu, Zekun Ni, Xinyu Zhou, He Wen, Yuheng Zou. DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients.

[8] Andrew G, Howard, Menglong Zhu, Bo Chen, Dmitry Kalenichenko, Weijun Wang, Tobias Weyand, Marco Andreetto, Hartwig Adam. MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications. 2017.
