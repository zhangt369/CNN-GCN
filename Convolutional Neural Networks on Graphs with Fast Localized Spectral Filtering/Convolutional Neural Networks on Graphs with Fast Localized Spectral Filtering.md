## Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering

##### **研究主题：解决什么问题，以前的研究通常是怎样解决的**

本文在谱图理论的基础上提出了一种基于局域网的快速卷积滤波器的构造方法，为图的局域化卷积滤波器的设计提供了必要的数学背景和有效的数值计算方法。

本文的主要目标之一，就是定义局部图过滤器，以便有效地进行评估和学习。



##### **解决问题/创新点：与其他研究有什么不同，最大的不同点是什么**

1.谱图理论陈述：在已有的图信号处理工具(GSP)的基础上，建立了基于图的CNN的谱图理论公式。

2.增强局部过滤器：证明了所提出的光谱滤波器的增强是严格局限在半径为*K*的球面上的

3.低计算复杂度：滤波器复杂度线性

4.有效的池化：我们提出了一种在将顶点重新排列为二叉树结构之后的类似于一维信号池化的有效的图的池化方法。

5.实验结果：我们进行了多个实验，最终表明我们的公式是**(i)**一个有用的模型，**(ii)**计算高效，**(iii)**在准确性和复杂性上都优于[文献[4]](https://arxiv.org/abs/1312.6203)中引入的先驱谱图 CNN。我们的图形公式执行类似于一个经典的 CNN对 MNIST，并研究了各种图结构对性能的影响。用于重现我们的结果并将模型应用于其他数据的 [TensorFlow[1]](https://arxiv.org/abs/1603.04467v1)代码作为开源软件数据库提供。



#####  **研究方法：提出框架、算法等**

将CNN推广到图需要三个基本步骤:**(i)**局部卷积滤波器的设计，**(ii)**将相似顶点组合在一起的图粗化过程，**(iii)**用图池化操作换取更高的滤波器分辨率。





##### **研究数据：实验中用到的数据，如何使用**

 

##### **结果分析：有哪些分析？递进实验还是并行实验？分析结果简单总结**



#####  **讨论点：从哪些方面进行讨论？**

 

##### **研究缺陷/展望：作者总结的缺陷有哪些？阅读文献后总结的缺点是否与作者相同？基于这个研究我们可以扩展哪些研究？**










