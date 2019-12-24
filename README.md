# k-means

环境：macOS 10.14.5

语言：JavaScript

作者：尤桂芳

日期：2019.12.24

项目：[项目源码](https://github.com/youzouzou/k-means)

数据集来源：[UCI](http://archive.ics.uci.edu/ml/datasets/Iris)

报告：[运行结果演示](https://youzouzou.github.io/k-means/index)

---
#### 算法实现步骤：

1.为每个聚类选择一个初始聚类中心

2.将样本集按照最小距离原则分配到最邻近聚类

3.使用每个聚类的样本均值更新聚类中心

4.重复2、3，直到聚类数据不再更新或达到最大迭代次数

5.输出分类正确率和聚类划分结果

---

#### 初始参数说明
- 划分的簇的数目：k
- 最大迭代次数：n
- 中心点数据数组：centers
- 中心点数据数组对应在数据集中的下标，用于初始化中心点时进行排重：centerIndexs
- 当前迭代次数：m