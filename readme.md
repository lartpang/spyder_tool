# python爬虫工具集合

> 主要针对python3

[TOC]

## 常用库

### 获取目标

* chrome/firefox
    - [chrome开发者工具小技巧](https://coolshell.cn/articles/17634.html)
    - [史上最全的Chrome使用技巧集锦](http://www.codeceo.com/article/chrome-usage-most-useful.html)
* fiddler
    - [project]()
    - [download-unofficial](https://pc.qq.com/detail/10/detail_3330.html)
    - [download-official](https://telerik-fiddler.s3.amazonaws.com/fiddler/FiddlerSetup.exe)
    - [articles](https://www.cnblogs.com/miantest/p/7289694.html)
    - Fiddler是最强大最好用的Web调试工具之一，它能记录所有客户端和服务器的http和https请求，允许你监视，设置断点，甚至修改输入输出数据，使用Fiddler无论对开发还是测试来说，都有很大的帮助。Fiddler4基于4.0的.NET。
* wireshark
    - [download](https://www.wireshark.org/download.html)
    - [articles](https://www.cnblogs.com/dragonir/p/6219541.html)
    - Wireshark（前称Ethereal）是一个网络封包分析软件。网络封包分析软件的功能是撷取网络封包，并尽可能显示出最为详细的网络封包资料。Wireshark使用WinPCAP作为接口，直接与网卡进行数据报文交换。

### 开始下载

* urllib
    - Urllib是python提供的一个用于操作url的模块。
    - 在python2中，有urllib库和urllib2库。在python3中，urllib2合并到urllib库中,我们爬取网页的时候，经常用到这个库。
    - [urllib库在python2与python3中的区别](https://blog.csdn.net/moll_77/article/details/78581817)
* urllib3
    - [github](https://github.com/urllib3/urllib3)
    - urllib 3是一个强大的、健全友好的Python HTTP客户端。大多数Python系统已经使用了urllib 3，您也应该使用urllib 3，urllib 3带来了Python标准库所缺少的许多关键特性。
* requests
    - [github](https://github.com/requests/requests/)
    - [doc](http://cn.python-requests.org/zh_CN/latest/)
    - Requests 允许你发送纯天然，植物饲养的 HTTP/1.1 请求，无需手工劳动。你不需要手动为 URL 添加查询字串，也不需要对 POST 数据进行表单编码。Keep-alive 和 HTTP 连接池的功能是 100% 自动化的，一切动力都来自于根植在 Requests 内部的 urllib3。
* requests-html
    - [github](https://github.com/kennethreitz/requests-html)
    - requests-html 是基于现有的框架 PyQuery、Requests、lxml、beautifulsoup4等库进行了二次封装，作者将Requests设计的简单强大的优点带到了该项目中。([By 虫师](https://www.cnblogs.com/fnng/p/8948015.html))

### 验证码识别

* PIL
* opencv
* pybrain
* 打码平台

### 文本解析

* beautiful soup
    - [doc](https://www.crummy.com/software/BeautifulSoup/bs4/doc/##)
    - Beautiful Soup 提供一些简单的、python 式的函数用来处理导航、搜索、修改分析树等功能。它是一个工具箱，通过解析文档为用户提供需要抓取的数据，因为简单，所以不需要多少代码就可以写出一个完整的应用程序。Beautiful Soup 自动将输入文档转换为 Unicode 编码，输出文档转换为 utf-8 编码。你不需要考虑编码方式，除非文档没有指定一个编码方式，这时，Beautiful Soup 就不能自动识别编码方式了。然后，你仅仅需要说明一下原始编码方式就可以了。Beautiful Soup 已成为和 lxml、html6lib 一样出色的 python 解释器，为用户灵活地提供不同的解析策略或强劲的速度。
* lxml
    - [doc](https://lxml.de/)
    - lxml库结合libxml2快速强大的特性,使用xpath语法来进行文件格式解析,与Beautiful相比,效率更高。
* pyquery
    - [github](https://github.com/gawel/pyquery/)
    - [doc](https://pyquery.readthedocs.io/en/latest/)
    - PyQuery库也是一个非常强大又灵活的网页解析库，如果你有前端开发经验的，都应该接触过jQuery,那么PyQuery就是你非常绝佳的选择，PyQuery 是 Python 仿照 jQuery 的严格实现。语法与 jQuery 几乎完全相同.
* re
    - python内置
    - [指南](https://www.cnblogs.com/huxi/archive/2010/07/04/1771073.html)
    - 正则表达式本身是一种小型的、高度专业化的编程语言，而在python中，通过内嵌集成re模块，程序员们可以直接调用来实现正则匹配。正则表达式模式被编译成一系列的字节码，然后由用C编写的匹配引擎执行。

### 提速处理

* 并发编程
    + [多进程多线程介绍](https://www.cnblogs.com/wdliu/p/6828070.html)
    + [进程线程异步](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)
    + 同步
        * threading
        * multiprocessing
    + 异步
        * aiohttp
        * gevent
* Queue
    - python内置 
    - Queue是python标准库中的线程安全的队列（FIFO）实现,提供了一个适用于多线程编程的先进先出的数据结构，即队列，用来在生产者和消费者线程之间的信息传递

### 数据存储

* 数据库
    - pymysql
    - redis
    - sqlalchemy(ORM)

### 数据处理

* numpy
* pandas
* matplotlib
* wordcloud

### 自动化测试

* selenium
    - [doc](https://selenium-python.readthedocs.io/index.html)
    - [webdriver](https://www.seleniumhq.org/projects/webdriver/)
    - Selenium 是自动化测试工具。它支持各种浏览器，包括 Chrome，Safari，Firefox 等主流界面式浏览器，如果你在这些浏览器里面安装一个 Selenium 的插件，那么便可以方便地实现Web界面的测试。换句话说叫 Selenium 支持这些浏览器驱动。Selenium支持多种语言开发。
* htmlunit
    + [sourceforge](http://htmlunit.sourceforge.net/)
    + HtmlUnit是一个无界面浏览器Java程序。它为HTML文档建模，提供了调用页面、填写表单、单击链接等操作的API。就跟你在浏览器里做的操作一样。HtmlUnit不错的JavaScript支持(不断改进)，甚至可以使用相当复杂的AJAX库，根据配置的不同模拟Chrome、Firefox或Internet Explorer等浏览器。HtmlUnit通常用于测试或从web站点检索信息。
    + httpClient的局限性：对于使用java实现的网页爬虫程序，我们一般可以使用apache的HttpClient组件进行HTML页面信息的获取，HttpClient实现的http请求返回的响应一般是纯文本的document页面，即最原始的html页面。对于一个静态的html页面来说，使用httpClient足够将我们所需要的信息爬取出来了。但是对于现在越来越多的动态网页来说，更多的数据是通过异步JS代码获取并渲染到的，最开始的html页面是不包含这部分数据的。([By johnson_moon](https://blog.csdn.net/johnson_moon/article/details/78457543))
* headless：Headless 提供一种无 GUI 的纯浏览器环境，对于 Web 应用和网页的自动化测试非常有用。
    * Chrome-headless 模式
        - [chromedriver download1](http://npm.taobao.org/mirrors/chromedriver/)
        - [chromedriver download2](https://chromedriver.storage.googleapis.com/index.html)
        - [chromedriver 与Chrome版本的对应关系](https://blog.csdn.net/huilan_same/article/details/51896672)
        - [官方介绍](https://developers.google.cn/web/updates/2017/04/headless-chrome)
        - Google 针对 Chrome 浏览器 59版 新增加的一种模式，可以让你不打开UI界面的情况下使用 Chrome 浏览器，所以运行效果与 Chrome 保持完美一致。([By 虫师](https://www.cnblogs.com/fnng/p/7797839.html))
    * Firefox-headless 模式
        - [geckodriver](https://github.com/mozilla/geckodriver/releases)
        - [官方介绍1](https://hacks.mozilla.org/2017/12/using-headless-mode-in-firefox/)
        - [官方介绍2](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Headless_mode)
* phantomjs
    - 【NOTE】该项目目前处于停滞状态，已经不被新版 selenium 支持了
    - [github](https://github.com/ariya/phantomjs)
    - PhantomJS是一个基于webkit的JavaScript API。它使用QtWebKit作为它核心浏览器的功能，使用webkit来编译解释执行JavaScript代码。任何你可以在基于webkit浏览器 做的事情，它都能做到。它不仅是个隐形的浏览器，提供了诸如CSS选择器、支持Web标准、DOM操作、JSON、HTML5、Canvas、SVG等， 同时也提供了处理文件I/O的操作，从而使你可以向操作系统读写文件等。PhantomJS的用处可谓非常广泛，诸如前端无界面自动化测试（需要结合 Jasmin）、网络监测、网页截屏等。

### 高级框架

* pyspider
    - [github](https://github.com/binux/pyspider)
    - [doc](http://docs.pyspider.org/en/latest/)
    - [pyspider中文网](http://www.pyspider.cn/)
    - 一个国人编写的强大的网络爬虫系统并带有强大的WebUI。采用Python语言编写，分布式架构，支持多种数据库后端，强大的WebUI支持脚本编辑器，任务监视器，项目管理器以及结果查看器。
* scrapy
    - [github](https://github.com/scrapy/scrapy)
    - [doc](https://scrapy-chs.readthedocs.io/zh_CN/latest/index.html)
    - Scrapy是一个为了爬取网站数据，提取结构性数据而编写的应用框架。 可以应用在包括数据挖掘，信息处理或存储历史数据等一系列的程序中。

## 开发环境

* spyder
    - [github](https://github.com/spyder-ide/spyder)
    - [doc](https://docs.spyder-ide.org/)
    - [汉化](https://github.com/kingmo888/Spyder_Simplified_Chinese)
    - Python数据科学集成开发环境。
* ipython
    - [github](https://github.com/ipython/ipython)
    - ipython是一个python的交互式shell，比默认的python shell好用得多，支持变量自动补全，自动缩进，支持bash shell命令，内置了许多很有用的功能和函数。它提供了一个强大的python交互式shell和供Jupyter notebooks使用的一个Jupyter内核（IPython notebook）
* jupter notebook
    - [github](https://github.com/jupyter)
    - [doc](https://jupyter.readthedocs.io/en/latest/index.html)
    - [jupyter-themes](https://github.com/dunovank/jupyter-themes)
    - Jupyter Notebook 的本质是一个 Web 应用程序，便于创建和共享文学化程序文档，支持实时代码，数学方程，可视化和 markdown。 用途包括：数据清理和转换，数值模拟，统计建模，机器学习等等。

## 关于爬虫

* [本系列教程介绍使用Python及相关为实现网络爬虫。](http://www.testclass.net/crawler/)
* [如何成为一名爬虫工程师](https://www.kawabangga.com/posts/2277)
* [爬虫常用工具](https://www.kawabangga.com/posts/2365)
    - curl
    - postman、paw
    - curl to requests
    - python -m “json.tool”
    - Proxifier

## 一些建议

* 延时
* 异常处理