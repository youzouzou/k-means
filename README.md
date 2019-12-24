# k-means
环境：macOS 10.14.5
语言：JavaScript
作者：尤桂芳
日期：2019.12.24
项目：[项目源码](https://github.com/youzouzou/k-means)
报告：[运行结果](https://youzouzou.github.io/k-means/index)

---
#### 算法实现步骤：

1.为每个聚类选择一个初始聚类中心

2.将样本集按照最小距离原则分配到最邻近聚类

3.使用每个聚类的样本均值更新聚类中心

4.重复2、3，直到聚类数据不再更新或达到最大迭代次数

5.输出最终的聚类中心和k个簇划分
