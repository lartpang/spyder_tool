# python爬虫工具集合 #

> 主要针对python3

## 常用库 ##

* urllib
    - Urllib是python提供的一个用于操作url的模块。
    - 在python2中，有urllib库和urllib2库。在python3中，urllib2合并到urllib库中,我们爬取网页的时候，经常用到这个库。
    - [urllib库在python2与python3中的区别](https://blog.csdn.net/moll_77/article/details/78581817)
* urllib3
    - [github](https://github.com/urllib3/urllib3)
    - urllib3 is a powerful, sanity-friendly HTTP client for Python. Much of the Python ecosystem already uses urllib3 and you should too. urllib3 brings many critical features that are missing from the Python standard libraries.
* requests
    - [github](https://github.com/requests/requests/)
    - Requests allows you to send organic, grass-fed HTTP/1.1 requests, without the need for manual labor. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.
* requests-html
    - [github](https://github.com/kennethreitz/requests-html)
    - This library intends to make parsing HTML (e.g. scraping the web) as simple and intuitive as possible.
* beautiful soup
    - [doc](https://www.crummy.com/software/BeautifulSoup/bs4/doc/##)
    - Beautiful Soup 提供一些简单的、python 式的函数用来处理导航、搜索、修改分析树等功能。它是一个工具箱，通过解析文档为用户提供需要抓取的数据，因为简单，所以不需要多少代码就可以写出一个完整的应用程序。Beautiful Soup 自动将输入文档转换为 Unicode 编码，输出文档转换为 utf-8 编码。你不需要考虑编码方式，除非文档没有指定一个编码方式，这时，Beautiful Soup 就不能自动识别编码方式了。然后，你仅仅需要说明一下原始编码方式就可以了。Beautiful Soup 已成为和 lxml、html6lib 一样出色的 python 解释器，为用户灵活地提供不同的解析策略或强劲的速度。
* lxml
    - [doc](https://lxml.de/)
    - lxml is the most feature-rich and easy-to-use library for processing XML and HTML in the Python language.
* phantomjs
    - [github](https://github.com/ariya/phantomjs)
    - PhantomJS是一个基于webkit的JavaScript API。它使用QtWebKit作为它核心浏览器的功能，使用webkit来编译解释执行JavaScript代码。任何你可以在基于webkit浏览器 做的事情，它都能做到。它不仅是个隐形的浏览器，提供了诸如CSS选择器、支持Web标准、DOM操作、JSON、HTML5、Canvas、SVG等， 同时也提供了处理文件I/O的操作，从而使你可以向操作系统读写文件等。PhantomJS的用处可谓非常广泛，诸如前端无界面自动化测试（需要结合 Jasmin）、网络监测、网页截屏等。
* selenium
    - [doc](https://selenium-python.readthedocs.io/index.html)
    - Selenium 是自动化测试工具。它支持各种浏览器，包括 Chrome，Safari，Firefox 等主流界面式浏览器，如果你在这些浏览器里面安装一个 Selenium 的插件，那么便可以方便地实现Web界面的测试。换句话说叫 Selenium 支持这些浏览器驱动。PhantomJS是一个浏览器,那么 Selenium 支持，二者便可以实现无缝对接了。Selenium支持多种语言开发，安装一下 Python 的 Selenium 库，再安装好 PhantomJS，就可以实现 Python＋Selenium＋PhantomJS 的无缝对接。PhantomJS 用来渲染解析JS，Selenium 用来驱动以及与 Python 的对接，Python 进行后期的处理。
* pyquery
    - [github](https://github.com/gawel/pyquery/)
    - [doc](https://pyquery.readthedocs.io/en/latest/)
    - PyQuery库也是一个非常强大又灵活的网页解析库，如果你有前端开发经验的，都应该接触过jQuery,那么PyQuery就是你非常绝佳的选择，PyQuery 是 Python 仿照 jQuery 的严格实现。语法与 jQuery 几乎完全相同.
* pyspider
    - [github](https://github.com/binux/pyspider)
    - [doc](http://docs.pyspider.org/en/latest/)
    - [pyspider中文网](http://www.pyspider.cn/)
    - 一个国人编写的强大的网络爬虫系统并带有强大的WebUI。采用Python语言编写，分布式架构，支持多种数据库后端，强大的WebUI支持脚本编辑器，任务监视器，项目管理器以及结果查看器。
* scrapy
    - [github](https://github.com/scrapy/scrapy)
    - [doc](https://scrapy-chs.readthedocs.io/zh_CN/latest/index.html)
    - Scrapy是一个为了爬取网站数据，提取结构性数据而编写的应用框架。 可以应用在包括数据挖掘，信息处理或存储历史数据等一系列的程序中。
* re
    - python内置
    - [指南](https://www.cnblogs.com/huxi/archive/2010/07/04/1771073.html)
    - 正则表达式本身是一种小型的、高度专业化的编程语言，而在python中，通过内嵌集成re模块，程序员们可以直接调用来实现正则匹配。正则表达式模式被编译成一系列的字节码，然后由用C编写的匹配引擎执行。
* spyder
    - [github](https://github.com/spyder-ide/spyder)
    - [doc](https://docs.spyder-ide.org/)
    - [汉化](https://github.com/kingmo888/Spyder_Simplified_Chinese)
    - Spyder, the Scientific Python Development Environment,
* ipython
    - [github](https://github.com/ipython/ipython)
    - ipython是一个python的交互式shell，比默认的python shell好用得多，支持变量自动补全，自动缩进，支持bash shell命令，内置了许多很有用的功能和函数。它提供了一个强大的python交互式shell和供Jupyter notebooks使用的一个Jupyter内核（IPython notebook）
* jupter notebook
    - [github](https://github.com/jupyter)
    - [doc](https://jupyter.readthedocs.io/en/latest/index.html)

## 外部工具 ##

* chrome
    - [chrome开发者工具小技巧](https://coolshell.cn/articles/17634.html)
    * [史上最全的Chrome使用技巧集锦](http://www.codeceo.com/article/chrome-usage-most-useful.html)
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

## 关于爬虫技术 ##

* [如何成为一名爬虫工程师](https://www.kawabangga.com/posts/2277)
* [爬虫常用工具](https://www.kawabangga.com/posts/2365)
    - curl
    - postman、paw
    - curl to requests
    - python -m “json.tool”
    - Proxifier

