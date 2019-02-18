# 数据采集从入门到放弃

## 内容介绍

本书会介绍我目前所知的所有关于爬虫的东西，更像是我的技能清单，仔细把其中所有的内容过一遍，目标是传播知识。

大概会分为这么几个大方向：

1. 爬虫介绍、就业情况
2. HTTP协议介绍
3. Requests使用
4. 解析器Xpath介绍
5. MongoDB与MySQL
6. 多线程爬虫
7. Scrapy介绍
8. Scrapy-redis介绍

可能还会增加一些别的，主要是看心情。如：

1. 简单验证码处理（这个我也在学）
2. IOS逆向
3. Chrome断点调试和加密分析
4. Docker使用
5. Selenium与Appnium、pyppeteer
6. 布隆过滤器
7. Charles、mitmproxy抓包
8. 全站爬取思路
9. Flask开发
10. Spark相关
11. 其他语言如Go、JAVA爬虫



这其中的每一点都需要花很多时间去研究，希望我们一起进步。

![](https://ws3.sinaimg.cn/large/006tKfTcly1g077kx4c26j308c04oaa8.jpg)



我不会讲Python基础语法那些，建议去[BeginnersGuide](https://wiki.python.org/moin/BeginnersGuide/Programmers) 和 [documentation](https://docs.python.org/3/) 看。



## 开发环境

- Python3系列
- 建议macOS或Linux系统
- PyCharm开发



## 说说标题

先解释下标题，为什么是入门到放弃。

首先这并不是一句调侃的话，而是我现在的内心感受。我做爬虫快两年了，是从运营转过来的。我觉得我对爬虫有这三个阶段：

1. **喜欢** 。刚开始还没有真正接触到真实企业需求时，由于知乎的渲染（你懂得），我对爬虫真的超级感兴趣，打开的每个新网站都想去试试如何爬取，有什么反爬没。这个阶段持续到开始做实际项目，就慢慢地转变为下个阶段。这里我想说下，肯定有别人和我一样对爬虫保持有很高的热情，喜欢去爬取一些网站的数据，有一个关键点就是数据的问题。很多时候数据不完整，或者数据不持久，没有持续的数据分析，你爬取的数据就是没有价值的，这是我做了几个长期项目的感受。
2. **无感** 。爱好变为职业是一个很痛苦的事情，之前做运营时超级羡慕爬虫工程师们，感觉他们好幸福。当自己真正开始做了，刚开始还是挺好的，过一年心态就会发生变化，原因很多，这个有时间再慢慢说吧。这首歌就是红玫瑰：*得不到的永远在骚动，被偏爱的都有恃无恐*，自行体会吧。
3. **放弃** 。阶段二与阶段三是同时会有的感受，因为对爬虫没有之前那么多兴趣，就会慢慢的想开始去做别的事情。我的博客中的描述是“数据采集、数据处理、机器学习”，数据采集知识第一步，数据处理、机器学习才是重点（高薪职业），是未来有前景的方向。所以我才会去学Spark，去学Scala，也是希望在未来的某个时候可以转行去真正接触“数据”，研究数据。

## 个人介绍

我叫小歪，公众号：**Python爬虫与算法进阶** ，知乎上也叫小歪。