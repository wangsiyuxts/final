# 项目简介
本文探究近年来世界孕产妇死亡原因，找出影响孕产妇死亡率的因素。首先对数据预处理，进行探索性分析，用可视化方式展示数据基本情况。使用多元线性回归和岭回归，探究数据之间的联系。最后找到造成孕产妇死亡的重要因素，并给出一些建议。
# 说明
## 数据
### 数据来源
本文的数据来自网站：'https://ourworldindata.org/maternal-mortality'。
### 数据介绍
在上传的数据文件中，'国内生产总值与人口数.csv'，'每十万婴儿孕妇死亡人数.csv'，'熟练保健人员接生比率.csv'，'新生儿死亡率.csv'，'子女数.csv'，'2000-2017孕产妇死亡原因.csv'，'2000-2017孕妇死亡比率二维表.csv'这几个数据为未经处理的原始数据，'2017data.csv'为处理过的数据。
## 代码
### 版本
#### python版本
3.8.3 (default, Jul  2 2020, 17:30:36) [MSC v.1916 64 bit (AMD64)]
#### 所使用的包及其版本
pandas,version 1.5.2

plotnine,version 0.10.1

numpy,version 1.23.4

scikit-learn,version 0.23.1

pyecharts,version 2.0.1

matplotlib,version 3.6.1

statsmodels,version 0.13.2

处理器	Intel(R) Core(TM) i5-8250U CPU @ 1.60GHz   1.80 GHz
