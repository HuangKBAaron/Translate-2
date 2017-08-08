# 有道词典的api使用
想法：往往在使用翻译软件时，繁琐，以及app占的内存比较大，导致如此有耐心的我，很是不爽，于是我想能不能创建一个属于自己的翻译功能，接在我的微信平台上

就像宋丹丹说的：“于是乎，我就冒出个想法”，写出来

我看了文档说api,api是啥啊，不了解，开始看，然后知道了使用api的用处，以及后来的微信上接图灵机器人我都用的api,方便啊，百度开放平台一大堆api,不用白不用。

我后面代码实现的是爬虫系列，你说打脸不打脸

***
我把代码封装了起来。给他设置一个函数，以后传参直接调用就ok了，你说简单不简单，哈哈哈哈哈，这就是我的api，hahahhahahha


工具：chrome
参数：

    url = 'http://fanyi.youdao.com/translate?smartresult=dict&smartresult=rule&smartresult=ugc&sessionFrom=http://www.youdao.com/'
    data = {}
    data['type'] = 'AUTO'
    data['i'] = content
    data['doctype'] = 'json'
    data['xmlVersion'] = '1.8'
    data['keyfrom'] = 'fanyi.web'
    data['ue'] = 'UTF-8'
    data['action'] = 'FY_BY_CLICKBUTTON'
    data['typoResult'] = 'true'
***


