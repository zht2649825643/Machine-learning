﻿# 机器学习实战
## 总结一 （逻辑回归和线性回归的区别）<br>
1）线性回归要求变量服从正态分布，logistic回归对变量分布没有要求。<br>
2）线性回归要求因变量是连续性数值变量，而logistic回归要求因变量是分类型变量。<br>
3）线性回归要求自变量和因变量呈线性关系，而logistic回归不要求自变量和因变量呈线性关系。<br>
4）logistic回归是分析因变量取某个值的概率与自变量的关系，而线性回归是直接分析因变量与自变量的关系。<br>

总之, logistic回归与线性回归实际上有很多相同之处，最大的区别就在于他们的因变量不同，其他的基本都差不多。<br>
正是因为如此，这两种回归可以归于同一个家族，即广义线性模（generalized linear model）。<br>
如果是连续的，就是多重线性回归，如果是二项分布，就是logistic回归。logistic回归的因变量可以是二分类的，也可以是多分类的，但是二分类的更为常用，也更加容易解释。所以实际中最为常用的就是二分类的logistic回归。<br>

