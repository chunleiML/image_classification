## Udacity机器学习纳米学位作业5

* 使用CIFAR-10数据集，利用tensorflow构建了两个卷积层，两个全连接层，前面使用RELU做为激活函数，对各层使用了0.5的dropout来避免过拟合，最后输出层使用Softmax做为分类函数，最后实现测试集分类预测准确率为72%.

* 项目设计思路：
   * 数据集下载，了解数据格式
   * 数据预处理，数据归一化，one-hot 编码
   * 构造神经网络模型
      * Convolution Lalyer
      * Max Pooling Layer
      * Flatten Layer
      * Fully-Connected Layer
      * Output Layer
      * 构造Cost  function, 梯度下降使用Adam optimization method
   * 训练过程中使用一个Batch数据集做为验证集来调参
   * 使用测试集验证最终模型效果

