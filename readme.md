# 豆瓣爬虫(deprecated)

运行环境：windows10 python2.7.11  
第三方库：beautifulSoup

# 简介

## 2016.2.25

目前可以妥妥的爬下豆瓣全部标签的全部页面的全部书籍链接，有56087本  
下一步会根据这些索引去爬取书籍详细内容  

## 2016.2.24  

求代理列表。爬了一次全部标签第一页的全部书籍链接，成功率不到5%。是代理问题还是代码问题？  
已经随机代理，随机延时，随机UA了  
把proxy.py也改进成比较通用的了

## 2016.2.22  

刚学python爬虫，想把豆瓣全部标签页的全部图书都爬下来  
还在完善中...  
工程量不小，一步一步来  
目前可以爬下豆瓣全部标签的第一页的全部书籍链接，不过有点小问题，慢慢来吧= =  
中间的GetTags().run()有问题，无法运行
