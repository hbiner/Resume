黄 斌   
======

- 联系电话: [188-****-0703](tel://188-****-0703)
- 电子邮箱: <hbiner1114@gmail.com>
- Github : [hbiner](https://github.com/hbiner/)
- 毕业学校/年份：广东工业大学/2016
- GPA ：3.67/4
- 求职意向：推荐系统、数据挖掘或机器学习相关岗位


Summary
-------

广东工业大学的在读研究生，研究方向主要是推荐系统、数据挖掘和机器学习。关注一些开源项目，也会在 Github 上分享自己的代码。喜欢参加一些数据挖掘相关比赛，结交志同道合之士，共同提高。行走在追寻技术的道路上，拥有较强的实践能力，能够独立完成小型的产品和项目。

Honors and Awards
-----------------

- 2013 美国大学生数学建模竞赛（MCM）二等奖（国际赛）
- 2015 阿里移动推荐算法竞赛 最终排名/参数队数：37/7186
- 2014 “云上贵州”智能交通大数据竞赛，最终排名/参赛队数：55/3743
- 2014 阿里巴巴大数据竞赛 最终排名/参赛队数：73/7276 
- 2011 全国大学生数学建模竞赛广东赛区一等奖（国赛）
- 2011-2012 两次荣获国家励志奖学金


Papers & Research
------------------
- 《基于级联过滤的多模型融合的推荐方法》（第一作者,小型微型计算机系统）
- A Reinforcement Learning Approach based on Gradient Tree Boosting Model to Virtual Machines Auto-configuration （The computer journal审稿中）
- 云计算中虚拟机资源与应用系统参数的协同自适应配置研究，国家自然科学基金项目，NO.61272382


Skills
---------

- 熟悉Q-Learning、GBDT、RF等机器学习模型，了解CF、KNN、K-Means、LR等算法；
- 了解Boosting和Bagging等集成学习方法，以及简单的模型融合方法；
- 会用C/C++/Java/SQL/Python/Excel等进行数据分析，有过完整的建模实践经验；
- 能简单地运用MapReduce的程序架构；
- 通过CET6，具有良好的听说读写能力，阅读技术类文档资料能力较强。


Tools
------------------
这些是我平时用过/熟悉的编程语言、框架和工具。

#### Programming Languages

- [C/C++]()
- [Java](http://developer.mozilla.org/en/JavaScript)
- [SQL]()
- [HTML]()


#### Frameworks & APIs

- [MapReduce](http://zh.wikipedia.org/wiki/MapReduce)
- [mlpack](http://www.mlpack.org/)


#### Software & Tools

- [Git](http://git-scm.com)
- [Visual Studio]()
- [Eclipse](http://www.eclipse.org/)
- [Ubuntu Linux](http://ubuntu.com)
- [Sublime Text](http://www.sublimetext.com)
- [Excel](http://www.microsoftstore.com.cn/%E7%B1%BB%E5%88%AB/Office/c/office)
- [MySQL](http://mysql.com)
- [SQL Server](http://www.microsoft.com/en-us/server-cloud/products/sql-server/) 


Projects & Intern
-------------------------

#### 2015	**阿里巴巴大数据竞赛**	*Java,HiveSQL,PAI,C++*

此竞赛以阿里移动电商平台的58亿条真实用户-商品行为记录为基础，通过大数据和算法构建面向移动电子商务
的商品推荐模型。通过创建一个Maven项目远程操作阿里云御膳房平台上的数据，使用HiveSQL进行数据分析及
数据集的切分，采用MapReduce和HiveSQL程序来提取和处理特征，使用PAI脚本实现整个推荐模型的自动化过
程（构造训练集、验证集与测试集、特征提取、模型训练与验证、提交线上预测结果等）。解决问题的主要思
路：把推荐问题抽象成为二分类模型，采用GBDT（梯度提升回归树）、RF（随机森林）和LR（逻辑回归）来处
理，分别训练了若干子模型获取到各模型的评分值，然后用Rank指数排名进行融合，最后取评分值高的User-Item
对做top-N推荐。此竞赛获得了F1=8.21%的评分值。

#### 2014	**级联过滤数据集的多模型融合的推荐**	*C++,mlpack,SQL,Matlab*

此项目基于大量的用户-品牌记录，通过分析用户对品牌的行为规律，构建用户的品牌偏好模型，并预测用户在
未来一个月时间品牌下商品的购买情况。此项目使用多级的Logistic Regression过滤掉一些无法甄别的离群样
本和弱贡献率样本，然后采用基于Boosting的GBDT算法训练若干的评分预测模型算法，运用LR算法进行线性融
合，得到评分值较高的用户-品牌对。此项目很好地缓解了主流推荐算法无法甄别的离群样本、弱贡献率样本和
泛化能力较弱等问题。

#### 2013-2015	**基于强化学习的云资源自学习重配置系统**	*C++, mlpack, mysql*

此项目为国家自然科学基金项目《云计算中虚拟机资源与应用系统参数的协同自适应配置研究》的原型系统，主
要是建立在云计算资源自主管理平台上，实现Xen下云计算资源实时监控和虚拟机资源的自动重配置管理。面对
负载瞬息万变的云环境，此项目通过强化学习（Q-Learning）的方式，不断的去探索不同负载下，不同配置对云
计算平台性能的影响，同时收集大量的<configuration,performance>形式的样本进行离线学习，通过离线学习，
得到能够指导虚拟机簇进行资源重配置的策略库，为实际线上云环境所作初始调整或者直接的进行策略复用。

#### 2012.6-2012.9	广东群英网络有限公司	C++软件开发与维护
#### 2013.1-2013.4	中国平安银行深圳分行	主要负责小额贷款相关业务


Others
---------

- 崇尚极客文化与开源精神；
- 使用的工具有Shell,Git,Stackoverflow等；
- 喜欢尝试新鲜的事物，爱折腾，爱观察，业余时间喜欢收看体育赛事、动漫、旅游等。

