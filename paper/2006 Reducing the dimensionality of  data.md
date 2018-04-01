#降维

	训练
		多层神经网络   -> 重建高维输入
		中央层

but this works well only if	the initial weights are close to a good solution

An effective way of initializing the weights

降维促进分类，视觉化，通信，大数据储存
A simple and widely used method is
principal components analysis (PCA)

We describe a nonlinear generalization of PCA that
uses an adaptive, multilayer “encoder” network to transform the high-dimensional data into a low-dimensional code 
and a similar “decoder” network to recover the data from the code.

Starting with random weights in the two networks, 
they can be trained together by minimizing the discrepancy between the original data and its reconstruction. 

It is difficult to optimize the weights in nonlinear autoencoders that have multiple hidden layers (2–4).

With large initial weights,autoencoders typically find poor local minima;
with small initial weights, the gradients in the early layers are tiny, making it infeasible to train autoencoders with many hidden layers.

二进制向量 
RBM

The network assigns a probability to every possible image via this energy function
The
probability of a training image can be raised by adjusting the weights and biases to lower the energy of that image and to raise the energy of
similar, “confabulated” images that the network would prefer to the real data.