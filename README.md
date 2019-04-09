# 数据科学竞赛入门



在文件 `Titanic Data Science Solutions.ipynb` 翻译了一篇国外大神的***[数据科学竞赛（Kaggle）](https://kaggle.com/startupsci/titanic-data-science-solutions/notebook)***入门的文章。



**现在开始总结这篇文章到底讲了什么**



## 总结



### 一切都要从数据已给的特征开始

```python
train_df.columns.values
```



通过观察要回答下述多个问题



+ **数据集中有哪些特征是可以有类别的？** 
+ **数据集中有哪些特征是数字？**
+ **有哪些特征值包含空数据？**
+ **所有特征的数据类型是什么？**
+ **每一个特征的数值有哪些特点？**
+ **有类别的特征的分布是什么**

 回答完上述问题之后，我们需要做出基于数据分析的假设。其中最重要的一步是**判断相关性！**

+ 在我们建立模型的早期就要判断，特征与目标之间的相关性。
+ 补全某些特征值
+ 纠正某些特征，比如删掉某些特征，或者对某些特征做处理
+ 创建新的特征
+ 根据类别添加我们的假设



### 相关性



为了回答第一个问题，采用**可视化的手段分析数据**



+ **数值特征**与目标的相关性（可利用直方图）
+ **有序特征（有数字编号）**与目标的相关性（可利用直方图）
+ **分类特征（字符串编号）**与目标的相关性（pointplot、直方图）



### 整理数据

+ **通过丢弃数据来整理**
+ **补充连续特征值**
  + 一种简单的方法是在均值和标准差之间生成随机数。
  + 猜测缺失值的更准确方法是使用其他相关特征。
  + 猜测缺失值的更准确方法是使用其他相关特征。
+ **创建新的特征**
+ **将所有数据变成数字**



### 使用常见分类模型分类

- Logistic Regression
- KNN or k-Nearest Neighbors
- Support Vector Machines
- Naive Bayes classifier
- Decision Tree
- Random Forrest
- Perceptron
- Artificial neural network
- RVM or Relevance Vector Machine

最后选一个分类效果最好的



## 最后

待我看完《机器学习实战》再更新一些 Scikit-Learn 和 TensorFLow 的实战用法。









