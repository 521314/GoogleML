# Hello world
> Google Machine Learning Recipes 1

> 官方中文博客 http://chinagdg.org/2016/03/machine-learning-recipes-for-new-developers/

> 视频地址 http://v.youku.com/v_show/id_XMTUxODA1NTY3Mg==.html

> Github工程地址 https://github.com/ahangchen/GoogleML

> 欢迎Star，也欢迎到[Issue区讨论](https://github.com/ahangchen/GoogleML/issues)

## Supervised learning

原本我们是教会机器我们的规则，由机器执行规则进行分类，识别。

但规则总有漏洞，我们总能举出规则的反例。

我们不能为每种反例都对规则做修正，那是个无底洞。

所以我们让**机器自己学习规则**。

## 分类器
Input: Data (features)

Output: class (label)

## 机器学习的过程

- 收集训练数据： examples
> 我们需要从data中，提取出可以作为分类依据的特征作为feature
- 训练分类器： 分类器有很多种，我们这个部分使用了决策树
- 进行预测


## 环境搭建
使用[scikit-learn](http://scikit-learn.org/stable/index.html)做Python上的机器学习；

官网推荐使用[Anaconda](https://www.continuum.io/downloads)进行安装，轻松解决依赖，有两个版本可以用，我使用[Python2版本](http://repo.continuum.io/archive/Anaconda2-4.0.0-Linux-x86_64.sh), 因为许多库只支持python2, 而且教程使用的也是python2

安装后，关联Pycharm，新建一个工程，选择interpreter为anaconda里的python，这样才能顺利引用机器学习的库；
> 如果已经选了其他编译器，需要在File - Settings - 搜索interpreter，修改 

## 代码
[Hello world](../../src/hello_world.py)：一个简单的分类器训练与预测

> 如果觉得我的文章对您有帮助，请随意打赏～

<img src="../../res/wxmoney.jpg" width = "400" height = "400" alt="图片名称" align=center />