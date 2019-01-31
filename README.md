凤凰金融 (Phoenix Finance) 量化投资大赛 参赛笔记
================
李家翔,武睿琦,靳晓松
2019-01-31

<!-- README.md is generated from README.Rmd. Please edit that file -->

1.  比赛: 凤凰金融 (Phoenix Finance) 量化投资大赛
2.  需求:
    预测各股票未来半年收益率
3.  比赛中，做了多个模型进行尝试，但是sense不够强，最后只止步于入围，b榜第28名，[链接这里](http://www.dcjingsai.com/static_page/m/cp_rank.html?cmptId=204)。
4.  比赛排名如下

![](https://raw.githubusercontent.com/JiaxiangBU/picbackup/master/DataCastleRanking.png)

![](https://raw.githubusercontent.com/JiaxiangBU/picbackup/master/DataCastleAward.png)

### 实现方式

我们主要的实现方式是

1.  主模型为 Xgboost
2.  进行了手动融合 (stacking)
3.  做了历史上传记录的融合 (stacking) ，效果不好，大概原因是过拟合。

具体见[Blog](https://jiaxiangli.netlify.com/2018/06/03/phoenix-finance/)

### 特征工程

见[Blog](https://jiaxiangli.netlify.com/2018/06/03/phoenix-finance/) 2
数据处理

### 不足

相比于 [phv](https://github.com/JiaxiangBU/phv)， 这算是早期项目，因此我们没有尝试深度学习
(RNN相关) 模型。

### 其他

readme 格式参考[github](https://github.com/JiaxiangBU/phv)

-----

<h4 align="center">

**Code of Conduct**

</h4>

<h6 align="center">

Please note that the ‘add2md’ project is released with a [Contributor
Code of Conduct](.github/CODE_OF_CONDUCT.md).<br>By contributing to this
project, you agree to abide by its terms.

</h6>

<h4 align="center">

**License**

</h4>

<h6 align="center">

GPL-3 © [Jiaxiang Li;Ruiqi Wu;Xiaosong Jin](LICENSE)

</h6>
