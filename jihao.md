# 秋招



JD	job description	指职位描述

PR	public relations	公关



#  一名算法工程师的技术素质基本可以拆解成下面四个方面：知识、工具、逻辑、业务。

1 算法和理论基础

书籍：《统计学习方法》 统计学习的核心步骤：模型-策略-算法

 

算法：LR、SVM、KNN、决策树、各种聚类方法。

 

优化方法：梯度下降法、牛顿法、各种随机搜索法（基因、蚁群等）。

 

2 工程实现能力和编码水平

 

操作系统、计算机网络、数据库：

《程序员面试笔试宝典》

《Unix环境的高级编程》、《TCP-IP详解》

 

算法和数据结构：

《剑指offer》 、 《编程之美》 、 《编程珠玑》 、 

 

C++:

《effective C++》 、《primer C++》

 

行业了解：

《浪潮之巅》

# 面经

## 百度 机器学习

- 决策树：

  分类树与回归树的区别，分类树的输出是什么，回归树的输出是什么，决策树是按什么准则来构建树的？损失函数是什么？信息熵的含义？决策树创建过程。

- 集成算法：

  GBDT的原理，梯度提升原理，以及boosting算法原理，GBDT算法可以用于回归吗？

- 常用的损失函数有哪些？

- 分类和回归算法性能评估标准。

- 逻辑回归：

  损失函数是什么？交叉熵方程怎么写，以及曲线变换形式。

- SVM：

  损失函数，叫什么名？SVM算法可以用于回归吗？SVM可以用来处理多分类问题吗？

- CNN：

  CNN算法原理，以及卷积层，池化层，全连接层的含义，以及各自的作用？

- PCA：

  PCA的原理，以及怎么实现的？PCA的降维减少数据特征吗？和卷积层中的降维是否一样理解。

- 算法题：

  1. 多少中排序算法，特别是堆排序！快排的时间复杂度？排序的时间复杂度可以是O(N)吗？（连续的数字可以实现），通过代码实现排序，复杂度是O(N)，数组里包含的数是连续的未排序的数字。

## 宽拓科技 统计分析 

- 朴素贝叶斯算法：

  介绍算法原理，写贝叶斯定理（解释各个概率表达的意思），以及先验概率与后验概率的概念，算法是如何训练的，怎么调参的。

- 决策树算法：

  介绍决策树算法原理，信息熵以及信息增益公式，各表达的什么意思。

- CNN算法：

  介绍CNN的结构，以及卷积层、池化层、全连接层的概念以及如何实现的，通过实例写出卷积池化全连接得出的层数。

- SQL：

  写了一个小的查询代码，两个表连接，用到了左连接（比较简单）。

- Python：

  没有写代码，只是问了下会不会panda之类的。

## 百度 数据挖掘

一面：

- Kmeans算法：

  算法原理介绍，如何优化算法，欧式距离是否可以用其他方式替代，如何判断算法训练达到最优结果，理想情况下是K个值不变，但是如何判断达到最优结果（收敛概念）。正则化为什么要用二范数。

- 逻辑回归：

  如何判断算法得出的结果等级：精确度和召回率区别和联系，以及计算公                                           式。

- 算法题：
  1. 输出直角三角形图案
  2. 判断一个数是否为素数

二面：

- 随机森林：

  算法原理，如何调参

- CNN：

  为什么用CNN来处理图片数据，有什么优点吗

- 算法题：

  1. leetcode原题：28. Implement strStr()

     <https://blog.csdn.net/ddydavie/article/details/77340221>

     <https://blog.csdn.net/xx_123_1_rj/article/details/80901073>

## 微博 数据研发

- 逻辑回归：

  算法原理，损失函数，正则化，正则化的方法以及如何选择使用一范数还是二范数（对于应用，什么情况下使用二范数），

- 决策树：

  决策树划分依据，信息增益的概念

- 随机森林：

  随机森林的原理，GBDT

- CNN：

  算法结构，卷积核，如何卷积，如何池化的，最大法和平均法的区别（在什么情况下选择最大法或者平均法）

- 数据分析：

  对于连续值是如何处理的，如何归一化，归一化的原理，如何评价一个算法好坏，评判标准是什么，算法对比。

- 大数据：

  SPARK和Hadoop

- 算法题：
  1. 从一个字符串中删除指定的字符，以最小的时间复杂度。例如：abcdefab              删除’ab’ 和 ‘c’ 
  2.  一个循环有序的数组，查找其中某个数字，要求：算法的时间复杂度为O(lgn),例如：6782345，查找数字7。
  3. 一个字符串中含有N个字符，其中有M个不同的字符，N>>M，用最少的时间和空间找到包含所有的包含这M个字符的最短字符串，不考虑特殊字符，只考虑字母和数字即可。例如：abccbaddac, 返回：cbad     

## 滴滴 机器学习

- 逻辑回归：

  逻辑回归算法原理，损失函数，损失函数优化过程（写公式）

- SVM：

  算法原理，损失函数，损失函数怎么来的，算法如何训练的，算法是如何训练的，如何优化的，优化原理。拉格朗日乘子法怎么计算的，优化的条件是什么，如何考虑这些优化条件的。

- 神经网络算法：

  神经网络算法结构

- CNN：

  CNN算法结构，如何卷积，卷积核选多大的，如何池化，举例说明，以及卷积池化的作用，在什么情况下使用CNN算法。

- 大数据：

  SQL取数据，spark-sql取数据，SQL编程。

- NLP：

  实习介绍，以及word2vec算法原理

- 概率题：

  一幅52张的扑克，随机抽取五张，是３带２的概率。

- 正则表达式：

  表述时间的正则表达式，比如20181126的正则表达式如何表达。

- 算法题：

  1. 给出一个文本数据，每一行代表一个样本，随机抽取５％的样本数。思路：随机数函数？交叉验证抽取数据？交叉验证原理，在什么情况下用交叉验证？

  2. 给出一个无序的数组，写一个函数，返回第k个大的数，复杂度最小。

     方法一：先排序，在遍历排序后的数组，这样复杂度会比较大。

     方法二：边排序边查找，使用堆排序，这样复杂度也会比较大。

     方法三：边排序边查找，使用快排，这样**复杂度为n**，复杂度最小。

## 百度    机器学习

- python

  线程进程，垃圾机制，

- linux

  查询某路径下字符串个数，txt文件个数

- 数据库

  查询数据优化，数据库索引，两个表直接关联

- kmeam算法

  算法原理，如何取k，算法缺点

- 线性回归逻辑回归区别

- 数据结构

  二叉树中序遍历，平衡二叉树，中序遍历思路，快排和堆排序的原理，平衡树

- 垃圾邮件分类思路，能不能用到work2vec

- 算法题

  1. leetcode原题：20. Valid Parentheses

     <https://blog.csdn.net/qq_36963372/article/details/83896903>

  2. 二叉树中序遍历，

  3. 快排



## 美团 机器学习

- 逻辑回归

  算法输出，损失函数，梯度下降（公式推导）

- kmean与其他聚类不同

- 集成算法

  xgb原理：算法输出，损失函数，泰勒展开，论文

  xgb与gbdt的区别

  bagging boosting  stacking区别

- pandas  

   join与groupby应用

  join与merge区别

- 算法题

  1. leetcode原题：103. Binary Tree Zigzag Level Order Traversal

     二叉树层序遍历，奇数层从左往右遍历打印，偶数层从右往左打印

  2. 根据两个树的左子树来判断两个树是否相同

## 百度 机器学习

- 算法题

  1. 快排或者归并排序。

     快排时间复杂度，最好时间复杂度和最坏时间复杂度，在什么情况下会出现最好最坏复杂度，怎么避免最坏复杂度。

  2. leetcode原题：139. Word Break

     <https://blog.csdn.net/asd136912/article/details/79674146>

  3. leetcode原题：205. Isomorphic Strings

     <https://www.jianshu.com/p/7f3b57c99c99>

## 快手 算法工程师

- 实习

  介绍业务：ECR、K指标的介绍，xgb参数，K计算逻辑，召回率公式，xgb算法流程，集成算法思想。

- 算法题

  一个有序的数组，0-n个数，其中缺失一个元素，查找缺失元素是什么？

  方法：二分查找，注意边界条件。 

## 百度 算法工程师

- python

  数据类型有哪些？元组与字典区别？

- 数据结构

  有几种排序方法，以及各自的性能，快排最坏情况，在什么情况下冒泡比快排更优，快排稳定性问题。

- Linux

  Linux命令三剑客，常用命令

- git

  常用git命令，已经删除命令如何使用，分支建立

- Hadoop／spark

  Hadoop与spark区别与联系，mapreduce的原理

- numpy

  常用的计算函数

- word2vec

  原理！

- xgboost

  GBDT与xgboost的区别，xgboost常用的参数，调参范围，如何界定参数的上限以及下限。模型的训练时间以及模型的好坏评定。

- 评估指标

  精确率与召回率定义，AUC概念，ROC曲线

- 过拟合

  过拟合概念，以及解决过拟合的方法，如何判断过拟合问题出现。

- 模型评估

  方差与偏差的概念，如果样本集的正负样本不成比例如何解决？

- 算法题

  一个有序的数组，返回首次出现key的位置，数组元素非常多，如何解决？

## 作业帮 算法

- 算法题
  1. 已知一个字符串，表达树的前序遍历，建立一个树，返回树的根节点，并按后序遍历打印节点。
  2. 已知一个无序数组，返回连续最长自然素的个数，比如：[100，1，400，50，5，8，4，3，2]，连续自然数为[1,2,3,4,5],长度为5。

# work2vec	

它的特点是将所有的词向量化，这样词与词之间就可以定量的去度量他们之间的关系。word2vec词向量可以较好地表达不同词之间的相似和类比关系。

word2vec主要包含两个模型：跳字模型（skip-gram）和连续词袋模型（continuous bag of words，简称CBOW）

两种高效训练的方法：负采样（negative sampling）和层序softmax（hierarchical softmax）



词的表示方法类型：

1、词的独热表示one-hot

2、词的分布式表示 distributed representation

Dristributed representation的思路是通过训练，将每个词都映射到一个较短的词向量上来。所有的这些词向量就构成了向量空间，进而可以用普通的统计学的方法来研究词与词之间的关系。

**要想得到一个词的向量表达方法，并且这个向量的维度很小，而且任意两个词之间是有联系的，可以表示出在语义层面上词语词之间的相关信息。我们就需要训练神经网络语言模型，即CBOW和Skip-gram模型。这个模型的输出我们不关心，我们关心的是模型中第一个隐含层中的参数权重，这个参数矩阵就是我们需要的词向量。**

## CBOW

CBOW（Continuous Bag-of-Word Model）又称连续词袋模型，是一个三层神经网络。

特点：输入已知上下文，输出对当前单词的预测。 

## Skip-gram

Skip-gram只是逆转了CBOW的因果关系而已，即已知当前词语，预测上下文。 

## 优化训练方法

1.负采样（negative sampling） 
负采样（negative sampling）是用来提高训练速度并且改善所得到词向量的质量的一种方法。不同于原本每个训练样本更新所有的权重，负采样每次让一个训练样本仅仅更新一小部分的权重，这样就会降低梯度下降过程中的计算量。

2.层序softmax

## gensim中的work2vec

# python

1. 垃圾回收机制

<https://testerhome.com/topics/16556>

2. 请写出一段Python代码实现删除一个list里面的重复元素

方法一：使用set()函数，set(list)

方法二：使用字典函数

```python
a=[1,2,4,2,4,5,6,5,7,8,9,0]
b={}
b=b.fromkeys(a)
c=list(b.keys())
print c
```

3. python如何生成随机数

随机实数：

random.random( ):返回0到1之间的浮点数

random.uniform(a,b):返回指定范围内的浮点数。

random.randint(a, b)：返回生成一个指定范围内的整数。

随机数列表：

np.random.rand(10)：生成[0.0, 1.0)之间的随机浮点数组成的列表。

np.random.randint(10,size=10)：生成[1, 10)之间的随机浮点数组成的列表。

# 机器学习

## 数据结构

1. 红黑树



## 完整机器学习项目的流程

1. 抽象成数学问题 

明确问题是进行机器学习的第一步。这里的抽象成数学问题，指的我们明确我们可以获得什么样的数据，目标是一个分类还是回归或者是聚类的问题，如果都不是的话，如果划归为其中的某类问题。

2. 获取数据 

数据决定了机器学习结果的上限，而算法只是尽可能逼近这个上限。数据要有代表性，否则必然会过拟合。

而且对于分类问题，数据偏斜不能过于严重，不同类别的数据数量不要有数个数量级的差距。而且还要对数据的量级有一个评估，多少个样本，多少个特征，可以估算出其对内存的消耗程度，判断训练过程中内存是否能够放得下。如果放不下就得考虑改进算法或者使用一些降维的技巧了。如果数据量实在太大，那就要考虑分布式了。

3. 特征预处理与特征选择 

良好的数据要能够提取出良好的特征才能真正发挥效力。

特征预处理、数据清洗是很关键的步骤，往往能够使得算法的效果和性能得到显著提高。归一化、离散化、因子化、缺失值处理、去除共线性等，数据挖掘过程中很多时间就花在它们上面。这些工作简单可复制，收益稳定可预期，是机器学习的基础必备步骤。

筛选出显著特征、摒弃非显著特征，需要机器学习工程师反复理解业务。这对很多结果有决定性的影响。特征选择好了，非常简单的算法也能得出良好、稳定的结果。这需要运用特征有效性分析的相关技术，如相关系数、卡方检验、平均互信息、条件熵、后验概率、逻辑回归权重等方法。

4. 训练模型与调优 

直到这一步才用到我们上面说的算法进行训练。现在很多算法都能够封装成黑盒供人使用。但是真正考验水平的是调整这些算法的（超）参数，使得结果变得更加优良。这需要我们对算法的原理有深入的理解。理解越深入，就越能发现问题的症结，提出良好的调优方案。

5. 模型诊断 (评估)

如何确定模型调优的方向与思路呢？这就需要对模型进行诊断的技术。

过拟合、欠拟合 判断是模型诊断中至关重要的一步。常见的方法如交叉验证，绘制学习曲线等。过拟合的基本调优思路是增加数据量，降低模型复杂度。欠拟合的基本调优思路是提高特征数量和质量，增加模型复杂度。

误差分析 也是机器学习至关重要的步骤。通过观察误差样本，全面分析误差产生误差的原因:是参数的问题还是算法选择的问题，是特征的问题还是数据本身的问题……

诊断后的模型需要进行调优，调优后的新模型需要重新进行诊断，这是一个反复迭代不断逼近的过程，需要不断地尝试， 进而达到最优状态。

6. 模型融合 

一般来说，模型融合后都能使得效果有一定提升。而且效果很好。

工程上，主要提升算法准确度的方法是分别在模型的前端（特征清洗和预处理，不同的采样模式）与后端（模型融合）上下功夫。因为他们比较标准可复制，效果比较稳定。而直接调参的工作不会很多，毕竟大量数据训练起来太慢了，而且效果难以保证。

7. 上线运行 

这一部分内容主要跟工程实现的相关性比较大。工程上是结果导向，模型在线上运行的效果直接决定模型的成败。不单纯包括其准确程度、误差等情况，还包括其运行的速度(时间复杂度)、资源消耗程度（空间复杂度）、稳定性是否可接受。

## 特征工程

### 数据归一化

1. 为什么需要对数据归一化

http://www.cnblogs.com/LBSer/p/4440590.html

2. 标准化与归一化的区别

标准化是依照特征矩阵的列处理数据，其通过求z-score的方法，将样本的特征值转换到同一量纲下。

归一化是依照特征矩阵的行处理数据，其目的在于样本向量在点乘运算或其他核函数计算相似性时，拥有统一的标准，也就是说都转化为“单位向量”。

### 缺失值

1. 特征向量的缺失值处理：

1.缺失值较多.直接将该特征舍弃掉，否则可能反倒会带入较大的noise，对结果造成不良影响。

2.缺失值较少,其余的特征缺失值都在10%以内，我们可以采取很多的方式来处理:

1) 把NaN直接作为一个特征，假设用0表示；

2) 用均值填充；

3) 用随机森林等算法预测填充



### 过拟合

1. 如何解决过拟合（overfitting

链接：<https://blog.csdn.net/weixin_37933986/article/details/69681671>

- dropout

  <https://blog.csdn.net/program_developer/article/details/80737724>

- regularization

- batch normalizatin

2. L1和L2的区别

L1范数（L1 norm）是指向量中各个元素绝对值之和，也有个美称叫“稀疏规则算子”（Lasso regularization）。

比如 向量A=[1，-1，3]， 那么A的L1范数为 |1|+|-1|+|3|. 

简单总结一下就是：

L1范数: 为x向量各个元素绝对值之和。

L2范数: 为x向量各个元素平方和的1/2次方，L2范数又称Euclidean范数或Frobenius范数

Lp范数: 为x向量各个元素绝对值p次方和的1/p次方. 

L1范数可以使权值稀疏，方便特征提取。

L2范数可以防止过拟合，提升模型的泛化能力。

3. L1和L2正则先验分别服从什么分布 

L1是拉普拉斯分布，L2是高斯分布。

### 梯度消失和梯度爆炸

1. 问题本身

   <https://blog.csdn.net/weixin_37933986/article/details/69255863>

   1）梯度消失：

   根据链式法则，如果每一层神经元对上一层的输出的偏导乘上权重结果都小于1的话，那么即使这个结果是0.99，在经过足够多层传播之后，误差对输入层的偏导会趋于0。

   可以采用ReLU激活函数有效的解决梯度消失的情况。

   （2）梯度膨胀：

   根据链式法则，如果每一层神经元对上一层的输出的偏导乘上权重结果都大于1的话，在经过足够多层传播之后，误差对输入层的偏导会趋于无穷大。

2. 解决方案

   <https://blog.csdn.net/qq_25737169/article/details/78847691>

## 算法优化

梯度下降法、牛顿法、最小二乘法

1. 梯度下降

<https://www.cnblogs.com/LeftNotEasy/archive/2010/12/05/mathmatic_in_machine_learning_1_regression_and_gradient_descent.html>

注意：容易陷入局部最优

2. 梯度下降找到的一定是下降最快的方向吗？

梯度下降法并不是下降最快的方向，它只是目标函数在当前的点的切平面（当然高维问题不能叫平面）上下降最快的方向。在Practical Implementation中，牛顿方向（考虑海森矩阵）才一般被认为是下降最快的方向，可以达到Superlinear的收敛速度。梯度下降类的算法的收敛速度一般是Linear甚至Sublinear的（在某些带复杂约束的问题）。

3. 牛顿法

<https://blog.csdn.net/google19890102/article/details/41087931>

4. 牛顿法和梯度下降法有什么不同？

<https://blog.csdn.net/wtq1993/article/details/51607040>

5. 最小二乘法





## 常用的损失函数

链接：<https://blog.csdn.net/weixin_37933986/article/details/68488339>

机器学习算法都有一个目标函数，算法的求解过程就是对目标函数的优化过程。在分类或者回归问题中，通常使用损失函数作为目标函数。

损失函数分为经验风险损失函数和结构风险损失函数，经验风险损失函数指预测结果和实际结果的差别，结构风险损失函数是指经验风险损失函数加上正则项。

通常表示为：公式见原文

1. **0-1损失函数和绝对值损失函数** 

2. **log对数损失函数 （交叉熵损失函数）**
3. **指数损失函数**
4. **Hinge损失函数** 

## 谈谈判别式模型和生成式模型

判别方法：由数据直接学习决策函数 Y = f（X），或者由条件分布概率 P（Y|X）作为预测模型，即判别模型。

生成方法：由数据学习联合概率密度分布函数 P（X,Y）,然后求出条件概率分布P(Y|X)作为预测的模型，即生成模型。

由生成模型可以得到判别模型，但由判别模型得不到生成模型。

常见的判别模型有：K近邻、SVM、决策树、感知机、线性判别分析（LDA）、线性回归、传统的神经网络、逻辑斯蒂回归、boosting、条件随机场

常见的生成模型有：朴素贝叶斯、隐马尔可夫模型、高斯混合模型、文档主题生成模型（LDA）、限制玻尔兹曼机

## 逻辑回归算法

1. 把LR从头到脚都给讲一遍。建模，公式推导，每种解法的原理，正则化，LR和MaxEnt模型（最大熵模型）啥关系，LR为啥比线性回归好。有不少会背答案的人，问逻辑细节就糊涂了。原理都会? 那就问工程，并行化怎么做，有几种并行化方式，读过哪些开源的实现。还会，那就准备收了吧，顺便逼问LR模型发展历史。
2. 逻辑回归与线性回归的区别和联系





## SVM算法

1. 简单的介绍下SVM

SVM是一种有监督学习算法，主要用于分类，对于SVM主要是基于训练集在样本空间中找到一个超平面，将不同类别的样本进行分开，达到分类的效果。也就是说SVM学习算法主要就是求解能够正确的划分数据集并且几何间隔最大的超平面的过程。所以SVM算法就是寻找最大间隔。

一是针对线性可分的情况进行分析，而 针对线性不可分时，使用核函数将低维线性不可分的情况转化为高维线性可分的情况进行分析。

## tensorflow

1. 简单介绍tensorflow的计算图

Tensorflow是一个通过计算图的形式来表述计算的编程系统，计算图也叫数据流图，可以把计算图看做是一种有向图，Tensorflow中的每一个计算都是计算图上的一个节点，而节点之间的边描述了计算之间的依赖关系。

## 集成学习

1. **GBDT和XGBoost**有什么区别

- **基分类器的选择：**

  传统GBDT以CART作为基分类器，xgboost还支持线性分类器，这个时候xgboost相当于带L1和L2正则化项的逻辑斯蒂回归（分类问题）或者线性回归（回归问题）。

- **二阶泰勒展开：**

  传统GBDT在优化时只用到一阶导数信息，xgboost则对代价函数进行了二阶泰勒展开，同时用到了一阶和二阶导数。顺便提一下，xgboost工具支持自定义代价函数，只要函数可一阶和二阶求导。 GBDT和GBDT拟合的是都是残差。

- **方差-方差权衡：**

  xgboost在代价函数里加入了正则项，用于控制模型的复杂度。正则项里包含了树的叶子节点个数、每个叶子节点上输出的score的L2模的平方和。从Bias-variance tradeoff角度来讲，正则项降低了模型的variance，使学习出来的模型更加简单，防止过拟合，这也是xgboost优于传统GBDT的一个特性。 

- **Shrinkage（缩减）：**

  相当于学习速率（xgboost中的eta）。xgboost在进行完一次迭代后，会将叶子节点的权重乘上该系数，主要是为了削弱每棵树的影响，让后面有更大的学习空间。实际应用中，一般把eta设置得小一点，然后迭代次数设置得大一点。（补充：传统GBDT的实现也有学习速率） 

- **列抽样（column subsampling）：**

  xgboost借鉴了随机森林的做法，支持列抽样，我们会在同一层的结点分割前先随机选一部分特征，遍历的时候只用遍历这部分特征就行了，不需要便利全部特征，不仅能降低过拟合，还能减少计算，这也是xgboost异于传统gbdt的一个特性。

- **缺失值处理：**

  XGBoost考虑了训练数据为稀疏值的情况，可以为缺失值或者指定的值指定分支的默认方向，这能大大提升算法的效率，论文中“枚举”指的**不是枚举每个缺失样本在左边还是在右边**，而是枚举**缺失样本整体**在左边，还是在右边两种情况。分裂点还是只评估特征不缺失的样本，paper提到50倍。对于特征的值有缺失的样本，xgboost可以自动学习出它的分裂方向。 

- **XGBoost工具支持并行：**

  boosting不是一种串行的结构吗?怎么并行的？注意xgboost的并行不是tree粒度的并行，xgboost也是一次迭代完才能进行下一次迭代的（第t次迭代的代价函数里包含了前面t-1次迭代的预测值）。xgboost的并行是在特征粒度上的。我们知道，决策树的学习最耗时的一个步骤就是对特征的值进行排序（因为要确定最佳分割点），xgboost在训练之前，预先对数据进行了排序，然后保存为block结构，后面的迭代中重复地使用这个结构，大大减小计算量。这个block结构也使得并行成为了可能，在进行节点的分裂时，需要计算每个特征的增益，最终选增益最大的那个特征去做分裂，那么各个特征的增益计算就可以开多线程进行。

- **线程缓冲区存储：**

  按照特征列方式存储能优化寻找最佳的分割点，但是当以行计算梯度数据时会导致内存的不连续访问，严重时会导致cache miss，降低算法效率。paper中提到，可先将数据收集到线程内部的buffer（缓冲区），主要是结合多线程、数据压缩、分片的方法，然后再计算，提高算法的效率。

- **可并行的近似直方图算法：**

  树节点在进行分裂时，我们需要计算每个特征的每个分割点对应的增益，即用贪心法枚举所有可能的分割点。当数据无法一次载入内存或者在分布式情况下，贪心算法效率就会变得很低，所以xgboost还提出了一种可并行的近似直方图算法，用于高效地生成候选的分割点。大致的思想是根据百分位法列举几个可能成为分割点的候选者，然后从候选者中根据上面求分割点的公式计算找出最佳的分割点。

2. **为什么XGBoost要用泰勒展开，优势在哪里？**

<https://www.zhihu.com/question/61374305>

XGBoost使用了一阶和二阶偏导, 二阶导数有利于梯度下降的更快更准. 使用泰勒展开取得二阶倒数形式, 可以在不选定损失函数具体形式的情况下用于算法优化分析.本质上也就把损失函数的选取和模型算法优化/参数选择分开了. 这种去耦合增加了XGBoost的适用性。

3. **XGBoost如何寻找最优特征？是又放回还是无放回的呢？**

XGBoost在训练的过程中给出各个特征的评分，从而表明每个特征对模型训练的重要性.。XGBoost利用梯度优化模型算法, 样本是不放回的(想象一个样本连续重复抽出,梯度来回踏步会不会高兴)。但XGBoost支持子采样, 也就是每轮计算可以不使用全部样本。



## kmeans聚类算法

1. **在k-means或kNN，我们是用欧氏距离来计算最近的邻居之间的距离。为什么不用曼哈顿距离？**

曼哈顿距离只计算水平或垂直距离，有维度的限制。另一方面，欧氏距离可用于任何空间的距离计算问题。

因为，数据点可以存在于任何空间，欧氏距离是更可行的选择。例如：想象一下国际象棋棋盘，象或车所做的移动是由曼哈顿距离计算的，因为它们是在各自的水平和垂直方向做的运动

欧氏距离与曼哈顿距离的定义：<https://blog.csdn.net/weixin_42056745/article/details/80583016>

欧式距离是通过计算两个点或者多个点之间的距离表示法，比如x=(x1,…,xn)和y=(y1,…,yn)之间的距离，但是有个缺点，它会把样本点中的不同的属性之间的差别同等看待，这一点是不能满足实际需求的

曼哈顿距离，比如说是坐标系中的两个点分别向横坐标和纵坐标投影的和。|x1-x2|+|y1-y2|

## 朴素贝叶斯算法

1. 为什么朴素贝叶斯如此“朴素

因为它假定所有的特征在数据集中的作用是同样重要和独立的。正如我们所知，这个假设在现实世界中是很不真实的，因此，说朴素贝叶斯真的很“朴素”。

2. 简单的说下贝叶斯定理

条件概率（后验概率）：就是事件A在另外一个事件B已经发生条件下的发生概率。条件概率表示为P(A|B)，读作“在B条件下A的概率”。

联合概率：表示两个事件共同发生的概率。A与B的联合概率表示为P(A∩B)或者P(A，B)。

边缘概率（先验概率）：是某个事件发生的概率。边缘概率是这样得到的：在联合概率中，把最终结果中那些不需要的事件通过合并成它们的全概率，而消去它们（对离散随机变量用求和得全概率，对连续随机变量用积分得全概率），这称为边缘化（marginalization），比如A的边缘概率表示为P(A)，B的边缘概率表示为P(B)。

接着，考虑一个问题：P(A|B)是在B发生的情况下A发生的可能性。

1）首先，事件B发生之前，我们对事件A的发生有一个基本的概率判断，称为A的先验概率，用P(A)表示；

2）其次，事件B发生之后，我们对事件A的发生概率重新评估，称为A的后验概率，用P(A|B)表示；

3）类似的，事件A发生之前，我们对事件B的发生有一个基本的概率判断，称为B的先验概率，用P(B)表示；

4）同样，事件A发生之后，我们对事件B的发生概率重新评估，称为B的后验概率，用P(B|A)表示。

贝叶斯定理的公式表达式：

## CNN

1. 激活函数

常用的非线性激活函数有sigmoid、tanh、relu等等，前两者sigmoid/tanh比较常见于全连接层，后者relu常见于卷积层。

- sigmoid函数

Sigmoid的函数表达式如下：

也就是说，Sigmoid函数的功能是相当于把一个实数压缩至0到1之间。当z是非常大的正数时，g(z)会趋近于1，而z是非常小的负数时，则g(z)会趋近于0。

压缩至0到1有何用处呢？用处是这样一来便可以把激活函数看作一种“分类的概率”，比如激活函数的输出为0.9的话便可以解释为90%的概率为正样本。

2. 什么是卷积



3. 什么是池化pool层



1. 有一定的代码能力，熟悉python、Scala、sql等编程语言。
2. 对机器学习算法有一定的了解。
3. 对一定的实习经历，有一定的抗压能力。
4. 