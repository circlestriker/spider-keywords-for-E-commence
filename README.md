# spider-keywords-for-E-commence
电子商务网站：京东，淘宝，拼多多的爬虫集合

## 思路

+ 主要是从github盗取的源代码，然后做了进一步的改进
+ 拼多多反爬虫比较厉害，我用的是最笨的办法，手动复制搜索的json文件，然后处理的；当然还有其他的利用加密js的破解方法，哈哈哈，我不会啦
+ 京东的没有反爬虫机制，搜索关键字的时候不需要登陆
+ 淘宝的有反爬虫机制，在滑动验证操作的时候经常性翻车，后来我采用手工登陆的方式，然后就可以通过关键字得到我想要的内容了

## 环境

+ mac
+ selenium                           3.141.0
+ pandas                             0.24.2
+ pyquery                            1.4.1

## 说明

+ 感谢github上给我提供有价值代码的大佬们

