PicCrawler
===

Version 1.0.0
---
2018-02-13
 *  优化代码，底层依赖的包全部升级到最新版本
 *  原先的CrawlerClient改成PicCrawlerClient

Version 0.5.0
---
2017-11-28
 *  记录代理失败的次数。
 *  增加代理的丢弃机制，如果代理不可用那么从代理池中丢弃

Version 0.4.0
---
2017-11-14
 *  增加autoReferer功能
 *  增加Parser层，方便以后扩展成自定义图片Parser
 *  调整结构将strategy包放到download包下

Version 0.3.0
---
2017-11-12
 *  支持传递多个代理，内部的HttpManager在使用网络框架时会采用轮询算法选取代理。

Version 0.2.0
---
2017-10-27
 *  支持下载单个图片
 *  支持下载多个图片
 *  支持下载某个网页的图片
 *  支持下载多个网页的图片