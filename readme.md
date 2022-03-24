# 背景说明
> **写在前面**：github的markdown解析不支持文本颜色和公式，建议「**下载后**」进行浏览

这是一个针对常见的机器学习算法的数学推导过程梳理的仓库，并不是一个介绍算法的仓库，而是对算法进行一个推导梳理，以及对常用的名词进行较为深入的数学理解

**约定**
1. 推导过程中尽量使用矩阵形式表达
2. 每一个markdown开篇会解释以下所列所有名词，尽量通俗易懂
3. 表达的过程中有很多自己的理解，争取使用偏感性的方式解释，加强理解。有不到位的地方，欢迎来提issue。

# 算法列表
算法     | 算法原理代码实现   |  名词解释
----     | ----     | ----
[线性回归](线性回归.md)  | 梯度下降   |`MSE`、`似然函数`、`极大似然估计`、`对数似然函数`、`正规解`
[逻辑回归](逻辑回归.md)  | 梯度下降   |`sigmoid`、`softmax`、`交叉熵`、`KL散度`、`判别模型\生成模型`、`L1正则化/L2正则化`、`LASSO、岭回归`
[朴素贝叶斯](朴素贝叶斯.md)  | 手写   |`贝叶斯公式`、`先验概率`、`后验概率`、`似然概率函数`、`条件独立`、`拉普拉斯平滑`
[K近邻](K近邻.md)  | 手写   |`kd树`、`R树`
[决策树](决策树.md)  | [手写（ID3、CART）](./番外-一次决策过程（ID3和CART）.md)   |`树`、`ID3/C4.5/CART`、`熵`、`条件熵`、`信息增益`、`信息增益率`、`GINI系数`、`剪枝`
[随机森林](随机森林.md)  |    |`集成学习`、`Bagging/Stacking/Boosting`、`OOB`
[AdaBoost](AdaBoost.md)  | 手写   |
[梯度提升树](梯度提升树.md)  |    |
[XGBoost](XGBoost.md)  |          |
# TODO
线性回归：补充实现链接：线性回归.md中，readme.md中