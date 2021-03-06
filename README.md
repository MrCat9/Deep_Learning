# Deep_Learning

```
一文看懂四种基本的神经网络架构  https://www.jianshu.com/p/546dc40b52c8
```

## 目录

#### 1_M-P模型与BP神经网络
```
M-P模型  https://blog.csdn.net/u013007900/article/details/50066315
BP神经网络  https://blog.csdn.net/u013007900/article/details/50118945

Neural Networks  https://www.2cto.com/kf/201610/553336.html
前向通路的计算过程总结为：样本经过权值的计算后（乘以权值，累加），再经过激活函数得到输出，最终得到误差。（摘自  https://www.2cto.com/kf/201610/553336.html）

反向传播  https://www.jianshu.com/p/964345dddb70
前向传递输入信号直至输出产生误差，反向传播误差信息更新权重矩阵。（摘自 https://www.jianshu.com/p/964345dddb70）
反向传播算法可以说是梯度下降在链式法则中的应用。 （摘自 https://www.jianshu.com/p/964345dddb70）
```

#### 2_深度学习  花书 http://www.deeplearningbook.org/

#### 3_深度学习  花书  中文版 https://github.com/exacity/deeplearningbook-chinese

#### 4_张量

张量的通俗理解 https://www.cnblogs.com/abella/p/10142935.html

#### 5_Embedding

Embedding的理解 https://zhuanlan.zhihu.com/p/46016518

深度学习中的embedding https://blog.csdn.net/qq_35799003/article/details/84780289

什么是 word embedding https://www.zhihu.com/question/32275069

怎么形象理解embedding这个概念 https://www.zhihu.com/question/38002635

#### [6_MedicalNet](https://github.com/Tencent/MedicalNet)

```
3D医疗影像  3D-ResNet
```

#### 7_softmax

https://segmentfault.com/a/1190000017320763

#### 8_Non-local Network

#### 9_视频分类

https://www.jianshu.com/p/e416b837351d

#### 10_GCN

Graph Convolutional Network（GCN） https://www.zhihu.com/question/54504471?sort=created

#### 11_对loss和acc的分析和处理

train loss 和 test loss的关系与作用 https://blog.csdn.net/u012986684/article/details/79179640

对loss和acc的分析、处理 https://blog.csdn.net/wydbyxr/article/details/84852672

#### 12_小型数据集卷积神经网络CNN训练策略

小型数据集卷积神经网络CNN训练策略 https://blog.csdn.net/ccchen706/article/details/89714487

#### 13_常用的公共数据集

https://blog.csdn.net/m0_37570854/article/details/88736189

#### [14_Batch-normalized 应该放在非线性激活层的前面还是后面](https://www.zhihu.com/question/283715823/answer/438882036)

> 目前在实践上，倾向于把BN放在ReLU后面。