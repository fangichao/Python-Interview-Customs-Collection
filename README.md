# python-面试通关宝典
秋招、春招的小伙伴，有面Python开发方向的，看这一个repo就够啦😘
（ps:也欢迎大家贡献面试中遇到的Python相关问题，不断丰富这个repo以帮助到更多的人✿✿ヽ(°▽°)ノ✿）


Table of Contents
=================

   * [python-面试通关宝典](#python-面试通关宝典)
      * [<strong>一.语言特性</strong>](#一语言特性)
         * [1.谈谈对 Python 和其他语言的区别？](#1谈谈对-python-和其他语言的区别)
         * [2.简述解释型和编译型编程语言？](#2简述解释型和编译型编程语言)
         * [3.Python 的解释器种类以及相关特点？](#3python-的解释器种类以及相关特点)
         * [4.说说你知道的 Python3 和 Python2 之间的区别？](#4说说你知道的-python3-和-python2-之间的区别)
         * [5.Python3 和 Python2 中 int 和 long 的区别？](#5python3-和-python2-中-int-和-long-的区别)
         * [6.xrange 和 range 的区别？](#6xrange-和-range-的区别)
      * [<strong>二.编码规范</strong>](#二编码规范)
         * [7.什么是 PEP8？](#7什么是-pep8)
         * [8.了解 Python 之禅吗？](#8了解-python-之禅吗)
         * [9.了解 docstring 吗？](#9了解-docstring-吗)
         * [10.了解类型注解吗？](#10了解类型注解吗)
         * [11.例举你知道 Python 对象的命名规范，例如方法或者类等。](#11例举你知道-python-对象的命名规范例如方法或者类等)
         * [12.Python 中的注释有几种？](#12python-中的注释有几种)
         * [13.如何优雅的给一个函数加注释？](#13如何优雅的给一个函数加注释)
         * [14.如何给变量加注释？](#14如何给变量加注释)
         * [15.Python 代码缩进中是否支持 Tab 键和 空格 混用？](#15python-代码缩进中是否支持-tab-键和-空格-混用)
         * [16.是否可以在一句 import 中导入多个库？](#16是否可以在一句-import-中导入多个库)
         * [17.在给 Python 文件命名的时候需要注意什么？](#17在给-python-文件命名的时候需要注意什么)
         * [18.例举几个规范 Python 代码风格的工具。](#18例举几个规范-python-代码风格的工具)
      * [<strong>三.数据类型</strong>](#三数据类型)
         * [<strong>字符串</strong>](#字符串)
            * [19.列举 Python 中的基本数据类型。](#19列举-python-中的基本数据类型)
            * [20.如何区别 可变数据类型 和 不可变数据类型？](#20如何区别-可变数据类型-和-不可变数据类型)
            * [21.将 "hello world" 转换为首字母大写 "Hello World"。](#21将-hello-world-转换为首字母大写-hello-world)
            * [22.如何检测字符串中只含有数字？](#22如何检测字符串中只含有数字)
            * [23.将字符串 "ilovechina" 进行反转。](#23将字符串-ilovechina-进行反转)
            * [24.Python 中的字符串格式化方式你知道哪些？](#24python-中的字符串格式化方式你知道哪些)
            * [25.有一个字符串开头和末尾都有空格，比如 " adabdw "。要求写一个函数把这个字符串的前后空格都去掉。](#25有一个字符串开头和末尾都有空格比如--adabdw-要求写一个函数把这个字符串的前后空格都去掉)
            * [26.获取字符串 "123456" 最后的两个字符。](#26获取字符串-123456-最后的两个字符)
            * [27.一个编码为 GBK 的字符串 S，要将其转成 UTF-8 编码的字符串，应如何操作？](#27一个编码为-gbk-的字符串-s要将其转成-utf-8-编码的字符串应如何操作)
            * [28.字符串 s = "info:xiaoZhang 33 shandong"，用正则切分字符串输出 ['info', 'xiaoZhang', '33', 'shandong']。](#28字符串-s--infoxiaozhang-33-shandong用正则切分字符串输出-info-xiaozhang-33-shandong)
            * [29.怎样将字符串转换为小写？](#29怎样将字符串转换为小写)
            * [30.单引号、双引号和三引号的区别？](#30单引号双引号和三引号的区别)
            * [31.字符串 a = "你好     中国  "，去除多余空格只留一个空格。](#31字符串-a--你好-----中国--去除多余空格只留一个空格)
         * [<strong>列表</strong>](#列表)
            * [32.已知 AList = [1,2,3,1,2]，对 AList 列表元素去重，写出具体过程。](#32已知-alist--12312对-alist-列表元素去重写出具体过程)
            * [33.如何将 "1,2,3" 变成 ["1","2","3"]？](#33如何将-123-变成-123)
            * [34.给定两个 list，A 和 B，找出相同元素和不同元素。](#34给定两个-lista-和-b找出相同元素和不同元素)
            * [35.用一行代码展开该列表 [[1,2],[3,4],[5,6]]，得出[1,2,3,4,5,6]。](#35用一行代码展开该列表-123456得出123456)
            * [36.合并列表 [1,5,7,9] 和 [2,2,6,8]。](#36合并列表-1579-和-2268)
            * [37.如何打乱一个列表的元素？](#37如何打乱一个列表的元素)
         * [<strong>字典</strong>](#字典)
            * [38.字典操作中 del 和 pop 有什么区别？](#38字典操作中-del-和-pop-有什么区别)
            * [39.将如下字典按照年龄排序。](#39将如下字典按照年龄排序)
            * [40.请合并下面两个字典 a = {"A":1,"B":2}，b = {"C":3,"D":4}。](#40请合并下面两个字典-a--a1b2b--c3d4)
            * [41.如何使用生成式的方式生成一个字典，写一段功能代码。](#41如何使用生成式的方式生成一个字典写一段功能代码)
            * [42.如何把 元组 ("a","b") 和 元组(1,2)，变为字典{"a":1,"b":2}？](#42如何把-元组-ab-和-元组12变为字典a1b2)
         * [<strong>综合数据类型</strong>](#综合数据类型)
            * [43.Python 常用的数据结构的类型及其特性？](#43python-常用的数据结构的类型及其特性)
            * [44.如何将 元组("A","B") 和 元组(1,2) 合并成 字典{"A":1,"B":2}？](#44如何将-元组ab-和-元组12-合并成-字典a1b2)
            * [45.Python 里面如何实现 tuple 和 list 的转换？](#45python-里面如何实现-tuple-和-list-的转换)
            * [46.我们知道对于列表可以使用切片操作进行部分元素的选择，那么如何对生成器类型的对象实现相同的功能呢？](#46我们知道对于列表可以使用切片操作进行部分元素的选择那么如何对生成器类型的对象实现相同的功能呢)
            * [47.请将 [i for i in range(3)] 改成 生成器。](#47请将-i-for-i-in-range3-改成-生成器)
            * [48.将 a="hello" 和 b="你好" 编码成 bytes 类型。](#48将-ahello-和-b你好-编码成-bytes-类型)
            * [49.下面的代码输出结果是什么？](#49下面的代码输出结果是什么)
            * [50.下面的代码输出的结果是什么？](#50下面的代码输出的结果是什么)
         * [<strong>操作类题目</strong>](#操作类题目)
            * [51.在 Python 中交换两个变量的值。](#51在-python-中交换两个变量的值)
            * [52.在读文件操作的时候会使用 read、readline 或者 readlines，简述它们各自的作用。](#52在读文件操作的时候会使用-readreadline-或者-readlines简述它们各自的作用)
            * [53.json 序列化时，可以处理的数据类型有哪些？如何定制支持 datetime 类型？](#53json-序列化时可以处理的数据类型有哪些如何定制支持-datetime-类型)
            * [54.json 序列化时，默认遇到中文会转换成 unicode，如果想要保留中文怎么办？](#54json-序列化时默认遇到中文会转换成-unicode如果想要保留中文怎么办)
            * [55.有两个磁盘文件 A 和 B，各存放一行字母，要求把这两个文件中的信息合并（按字母顺序排列），输出到一个新文件 C 中。](#55有两个磁盘文件-a-和-b各存放一行字母要求把这两个文件中的信息合并按字母顺序排列输出到一个新文件-c-中)
            * [56.如果当前的日期为 20190530，要求写一个函数输出 N 天后的日期（比如 N 为 2，则输出 20190601)。](#56如果当前的日期为-20190530要求写一个函数输出-n-天后的日期比如-n-为-2则输出-20190601)
            * [57.写一个函数，接收整数参数 n，返回一个函数。函数的功能是把函数的参数和 n 相乘并把结果返回。](#57写一个函数接收整数参数-n返回一个函数函数的功能是把函数的参数和-n-相乘并把结果返回)
            * [58.下面的代码会存在什么问题，如何改进？](#58下面的代码会存在什么问题如何改进)
            * [59.一行代码输出 1-100 之间的所有偶数。](#59一行代码输出-1-100-之间的所有偶数)
            * [60.with 语句的作用，并用它写一段代码。](#60with-语句的作用并用它写一段代码)
            * [61.Python 字典和 json 字符串相互转化方法。](#61python-字典和-json-字符串相互转化方法)
            * [62.请写一个 Python 逻辑，计算一个文件中的大写字母数量。](#62请写一个-python-逻辑计算一个文件中的大写字母数量)
         * [<strong>高级特性</strong>](#高级特性)
            * [63.函数装饰器有什么作用？请列举说明。](#63函数装饰器有什么作用请列举说明)
            * [64.简述 Python 垃圾回收机制。](#64简述-python-垃圾回收机制)
            * [65.魔法函数 __call__怎么使用？](#65魔法函数-__call__怎么使用)
            * [66.如何判断一个对象是函数还是方法？](#66如何判断一个对象是函数还是方法)
            * [67.简述 @classmethod 和 @staticmethod 用法和区别。](#67简述-classmethod-和-staticmethod-用法和区别)
            * [68.Python 中的接口如何实现？](#68python-中的接口如何实现)
            * [69.你了解 Python 中的反射吗？](#69你了解-python-中的反射吗)
            * [70.简述 metaclass 的作用和其应用场景。](#70简述-metaclass-的作用和其应用场景)
            * [71.对比 hasattr()，getattr() 和 setattr() 的用法。](#71对比-hasattrgetattr-和-setattr-的用法)
            * [72.请列举你知道的 Python 的魔法方法及用途。](#72请列举你知道的-python-的魔法方法及用途)
            * [73.如何知道一个 Python 对象的类型？](#73如何知道一个-python-对象的类型)
            * [74.Python 中的 元类(metaclass) 使用举例。](#74python-中的-元类metaclass-使用举例)
            * [75.简述 any() 和 all() 方法。](#75简述-any-和-all-方法)
            * [76.用 filter 方法求出列表 a =  [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 中的所有奇数，并构造新列表。](#76用-filter-方法求出列表-a---1-2-3-4-5-6-7-8-9-10-中的所有奇数并构造新列表)
            * [77.什么是猴子补丁？](#77什么是猴子补丁)
            * [78.在 Python 中是如何管理内存的？](#78在-python-中是如何管理内存的)
            * [79.当退出 Python 时是否释放所有内存分配？](#79当退出-python-时是否释放所有内存分配)
         * [<strong>正则表达式</strong>](#正则表达式)
            * [80.使用正则表达式匹配&lt;html&gt;&lt;h1&gt;www.baidu.com&lt;/html&gt;中的地址。](#80使用正则表达式匹配htmlh1wwwbaiducomhtml中的地址)
            * [81.正则表达式匹配中 (.*) 和 (.**?) 匹配区别？](#81正则表达式匹配中--和--匹配区别)
            * [82.写一段匹配邮箱的正则表达式。](#82写一段匹配邮箱的正则表达式)
         * [<strong>其他内容</strong>](#其他内容)
            * [83.解释一下 Python 中 pass 语句的作用。](#83解释一下-python-中-pass-语句的作用)
            * [84.简述你对 input() 函数的理解。](#84简述你对-input-函数的理解)
            * [85.Python 中的 is 和 == 有什么区别？](#85python-中的-is-和--有什么区别)
            * [86.Python 中的作用域有哪些？](#86python-中的作用域有哪些)
            * [87.三元运算写法和应用场景。](#87三元运算写法和应用场景)
            * [88.了解 enumerate 吗？](#88了解-enumerate-吗)
            * [89.列举 5 个 Python 中的标准模块。](#89列举-5-个-python-中的标准模块)
            * [90.如何在函数中设置一个全局变量？](#90如何在函数中设置一个全局变量)
            * [91.pathlib 的用法举例。](#91pathlib-的用法举例)
            * [92.请对 Python 中的异常处理写一个简单的应用场景。](#92请对-python-中的异常处理写一个简单的应用场景)
            * [93.Python 中递归的最大次数是多少？如何突破？](#93python-中递归的最大次数是多少如何突破)
            * [94.什么是面向对象的 MRO？](#94什么是面向对象的-mro)
            * [95.简述 isinstance 的作用以及应用场景。](#95简述-isinstance-的作用以及应用场景)
            * [96.什么是断言？并描述一个应用场景。](#96什么是断言并描述一个应用场景)
            * [97.lambda 表达式格式以及应用场景。](#97lambda-表达式格式以及应用场景)
            * [98.新式类和旧式类的区别有哪些？](#98新式类和旧式类的区别有哪些)
            * [99.dir() 是用来干什么的？](#99dir-是用来干什么的)
            * [100.一个包里有三个模块，demo1.py、demo2.py 和 demo3.py，但使用 from tools import * 导入模块时，如何保证只有 demo1、demo3 被导入？](#100一个包里有三个模块demo1pydemo2py-和-demo3py但使用-from-tools-import--导入模块时如何保证只有-demo1demo3-被导入)
            * [101.列举 5 个 Python 中的异常类型以及其含义。](#101列举-5-个-python-中的异常类型以及其含义)
            * [102.copy 和 deepcopy 的区别是什么？](#102copy-和-deepcopy-的区别是什么)
            * [103.请阐述代码中经常遇到的 *args, **kwargs 的含义及用法。](#103请阐述代码中经常遇到的-args-kwargs-的含义及用法)
            * [104.Python 中会有函数或成员变量包含单下划线前缀和结尾，或双下划线前缀结尾，它们的区别是什么？](#104python-中会有函数或成员变量包含单下划线前缀和结尾或双下划线前缀结尾它们的区别是什么)
            * [105.简述 w、a  和 wb 文件写入模式的区别。](#105简述-wa-和-wb-文件写入模式的区别)
            * [106.举例 sort 和 sorted 的区别。](#106举例-sort-和-sorted-的区别)
            * [107.什么是负索引？](#107什么是负索引)
            * [108.pprint 模块是干什么的？](#108pprint-模块是干什么的)
            * [109.解释一下 Python 中的赋值运算符。](#109解释一下-python-中的赋值运算符)
            * [110.解释一下 Python 中的逻辑运算符。](#110解释一下-python-中的逻辑运算符)
            * [111.讲讲 Python 中的位运算符。](#111讲讲-python-中的位运算符)
            * [112.<strong>在 Python 中如何使用多进制数字？</strong>](#112在-python-中如何使用多进制数字)
            * [113.怎样声明多个变量并赋值？](#113怎样声明多个变量并赋值)
         * [<strong>算法和数据结构</strong>](#算法和数据结构)
            * [114.已知：](#114已知)
               * [(1) 从 AList 和 BSet 中 查找 4，最坏时间复杂度那个大？](#1-从-alist-和-bset-中-查找-4最坏时间复杂度那个大)
               * [(2) 从 AList 和 BSet 中 插入 4，最坏时间复杂度那个大？](#2-从-alist-和-bset-中-插入-4最坏时间复杂度那个大)
            * [115.用 Python 实现一个二分查找的函数。](#115用-python-实现一个二分查找的函数)
            * [116.Python 单例模式的实现方法。](#116python-单例模式的实现方法)
            * [117.使用 Python 实现一个斐波那契数列。](#117使用-python-实现一个斐波那契数列)
            * [118.找出列表中的重复数字。](#118找出列表中的重复数字)
            * [119.找出列表中的单个数字。](#119找出列表中的单个数字)
            * [120.写一个冒泡排序。](#120写一个冒泡排序)
            * [121.写一个快速排序。](#121写一个快速排序)
            * [122.写一个拓扑排序。](#122写一个拓扑排序)
            * [123.用 Python 实现一个二进制计算。](#123用-python-实现一个二进制计算)
            * [124.有一组 " " 和 "-" 符号，要求将 " " 排到左边，"-" 排到右边，写出具体的实现方法。](#124有一组--和---符号要求将--排到左边--排到右边写出具体的实现方法)
            * [125.单链表反转。](#125单链表反转)
            * [126.交叉链表求交点。](#126交叉链表求交点)
            * [127.用队列实现栈。](#127用队列实现栈)
            * [128.找出数据流的中位数。](#128找出数据流的中位数)
            * [129.二叉搜索树中第 K 小的元素。](#129二叉搜索树中第-k-小的元素)
         * [<strong>爬虫相关</strong>](#爬虫相关)
            * [130.在 requests 模块中，requests.content 和 requests.text 什么区别？](#130在-requests-模块中requestscontent-和-requeststext-什么区别)
            * [131.简要写一下 lxml 模块的使用方法框架。](#131简要写一下-lxml-模块的使用方法框架)
            * [132.说一说 scrapy 的工作流程。](#132说一说-scrapy-的工作流程)
            * [133.简述 scrapy 的去重原理。](#133简述-scrapy-的去重原理)
            * [134.scrapy 中间件有几种类，你用过哪些中间件？](#134scrapy-中间件有几种类你用过哪些中间件)
            * [135.你写爬虫的时候都遇到过什么反爬虫措施，你是怎么解决的？](#135你写爬虫的时候都遇到过什么反爬虫措施你是怎么解决的)
            * [136.为什么会用到代理？](#136为什么会用到代理)
            * [137.代理失效了怎么处理？](#137代理失效了怎么处理)
            * [138.列出你知道 header 的内容以及信息。](#138列出你知道-header-的内容以及信息)
            * [139.说一说如何打开浏览器访问 <a href="http://www.baidu.com" rel="nofollow">www.baidu.com</a> 获取到结果，简述整个流程。](#139说一说如何打开浏览器访问-wwwbaiducom-获取到结果简述整个流程)
            * [140.爬取速度过快时，出现了验证码怎么处理？](#140爬取速度过快时出现了验证码怎么处理)
            * [141.scrapy 和 scrapy-redis 有什么区别？为什么选择 redis 数据库？](#141scrapy-和-scrapy-redis-有什么区别为什么选择-redis-数据库)
            * [142.分布式爬虫主要解决什么问题？](#142分布式爬虫主要解决什么问题)
            * [143.写爬虫是用多进程好还是多线程好？ 为什么？](#143写爬虫是用多进程好还是多线程好-为什么)
            * [144.解析网页的解析器使用最多的是哪几个？](#144解析网页的解析器使用最多的是哪几个)
            * [145.需要登录的网页，如何在不使用动态爬取的情况下解决 ip、cookie 和 session（其中有一些是动态生成的）的同时限制？](#145需要登录的网页如何在不使用动态爬取的情况下解决-ipcookie-和-session其中有一些是动态生成的的同时限制)
            * [146.验证码的解决。](#146验证码的解决)
            * [147.使用的最多的数据库（mysql，mongodb，redis 等）有哪些？并简述对它的理解？](#147使用的最多的数据库mysqlmongodbredis-等有哪些并简述对它的理解)
         * [<strong>网络编程</strong>](#网络编程)
            * [148.TCP 和 UDP 的区别有哪些？](#148tcp-和-udp-的区别有哪些)
            * [149.简要介绍三次握手和四次挥手。](#149简要介绍三次握手和四次挥手)
            * [150.什么是粘包？ socket 中造成粘包的原因是什么？ 哪些情况会发生粘包现象？](#150什么是粘包-socket-中造成粘包的原因是什么-哪些情况会发生粘包现象)
         * [<strong>并发</strong>](#并发)
            * [151.举例说明 conccurent.future 的中线程池的用法。](#151举例说明-conccurentfuture-的中线程池的用法)
            * [152.说一说多线程，多进程 和 协程 的区别。](#152说一说多线程多进程-和-协程-的区别)
            * [153.简述 GIL。](#153简述-gil)
            * [154.进程之间如何通信？](#154进程之间如何通信)
            * [155.IO 多路复用的作用？](#155io-多路复用的作用)
            * [156.select、poll 和 epoll 模型的区别。](#156selectpoll-和-epoll-模型的区别)
            * [157.什么是并发和并行？](#157什么是并发和并行)
            * [158.解释什么是异步非阻塞？](#158解释什么是异步非阻塞)
            * [159.简述 threading.local 的作用。](#159简述-threadinglocal-的作用)
         * [<strong>Git 面试题</strong>](#git-面试题)
            * [160.说说你知道的 git 命令。](#160说说你知道的-git-命令)
            * [161.git 如何查看某次提交修改的内容？](#161git-如何查看某次提交修改的内容)



## **一.语言特性**

#### 1.谈谈对 Python 和其他语言的区别？

```markdown
Python属于解释型语言，当程序运行时，是一行一行的解释，并运行，所以调式代码很方便，开发效率高，
还有龟叔给Python定位是任其自由发展、优雅、明确、简单，所以在每个领域都有建树，所有它有着非常强大的第三方库，
特点：
语法简洁优美，功能强大，标准库与第三方库都非常强大，而且应用领域也非常广
可移植性，可扩展性，可嵌入性
缺点：
　　运行速度慢，

- 解释型
    - python/php
- 编译型
    - c/java/c#        
```

#### 2.简述解释型和编译型编程语言？

```markdown
解释型：就是边解释边执行（Python，php），代码在执行过程中由解释器读取一行或者多行代码，并将其编译为字节码
    ，python虚拟机会解释这些字节码，并进行执行。

编译型：编译后再执行（c、java、c#），编译器会将所有的代码编译打包为可执行文件，如exe文件。然后再执行
```

#### 3.Python 的解释器种类以及相关特点？

```markdown
CPython

是官方版本的解释器：CPython。是使用C语言开发的，所以叫CPython。在命令行下运行python就是启动CPython解释器。
CPython是使用最广的Python解释器。教程的所有代码也都在CPython下执行。

IPython
IPython是基于CPython之上的一个交互式解释器，也就是说，IPython只是在交互方式上有所增强，但是执行Python代码的功能和CPython是完全一样的。
CPython用>>>作为提示符，而IPython用In [序号]:作为提示符。
比如使用jupyter notebook时，一般使用IPython解释器

PyPy

由Python写的解释器，它的执行速度是最快。PyPy采用JIT技术（即时编译），对Python代码进行动态编译（注意不是解释），
绝大部分Python代码都可以在PyPy下运行，但是PyPy和CPython有一些是不同的，这就导致相同的Python代码在两种解释器下执行可能会有不同的结果。

Jython
Jython是运行在Java平台上的Python解释器，可以直接把Python代码编译成Java字节码执行。

IronPython
IronPython和Jython类似，只不过IronPython是运行在.Net平台上的Python解释器，可以直接把Python代码编译成.Net的字节码。

小结：
　　Python的解释器很多，但使用最广泛的还是CPython。如果要和Java或.Net平台交互，最好的办法不是用Jython或IronPython，
    而是通过网络调用来交互，确保各程序之间的独立性。
```

#### 4.说说你知道的 Python3 和 Python2 之间的区别？

```markdown
1：打印时，py2需要可以不需要加括号，py3 需要
python 2 ：print ('lili')   ,   print 'lili'
python 3 : print ('lili')   
python3 必须加括号

exec语句被python3废弃，统一使用exec函数

2：内涵
Python2：1，臃肿，源码的重复量很多。
         2，语法不清晰，掺杂着C，php，Java，的一些陋习。
         3, 2020年1月1日开始停止维护    
Python3：几乎是重构后的源码，规范，清晰，优美。

3、输出中文的区别
python2：要输出中文 需加 # -*- encoding:utf-8 -*-
Python3 ： 直接搞

4：input不同
python2 ：raw_input
python3 ：input 统一使用input函数

5：指定字节
python2在编译安装时，可以通过参数-----enable-unicode=ucs2 或-----enable-unicode=ucs4分别用于指定使用2个字节、4个字节表示一个unicode；
python3无法进行选择，默认使用 ucs4
查看当前python中表示unicode字符串时占用的空间：

impor sys
print（sys.maxunicode）
#如果值是65535，则表示使用usc2标准，即：2个字节表示
#如果值是1114111，则表示使用usc4标准，即：4个字节表示

6：
py2：xrange
　　　　range
py3：range  统一使用range，Python3中range的机制也进行修改并提高了大数据集生成效率

7：在包的知识点里
包：一群模块文件的集合 + __init__
区别：py2 ： 必须有__init__
　　　py3：不是必须的了

8：不相等操作符"<>"被Python3废弃，统一使用"!="

9：long整数类型被Python3废弃，统一使用int

10：迭代器iterator的next()函数被Python3废弃，统一使用next(iterator)

11：异常StandardError 被Python3废弃，统一使用Exception

12：字典变量的has_key函数被Python废弃，统一使用in关键词

13：file函数被Python3废弃，统一使用open来处理文件，可以通过io.IOBase检查文件类型

14：Python 2: 当两个整数相除时，结果会被截断为整数（地板除）。例如：5 / 2 的结果是 2。
    Python 3: 整数相除会得到一个浮点数，结果是精确的除法结果。例如：5 / 2 的结果是 2.5。如果需要地板除，可以使用 // 运算符，例如 5 // 2 结果是 2。
```

#### 5.Python3 和 Python2 中 int 和 long 的区别？

```markdown
在python2里，整数分为int和long，对于int的长度通常与操作系统的位数有关，在32位操作系统int是32位，在64位操作系统，int就是64位。（跨平台或者跨操作系统不便）。
  long型是一种任意精度的类型，只有计算机内存允许，可以无限大。当给int变量赋值超过int范围时，会自动转为long型，后面会加上字母L

在python3里，只有一种整数类型int,大多数情况下，和python２中的长整型类似。
```

#### 6.xrange 和 range 的区别？

```markdown
xrange用法与range完全相同，所不同的是生成的不是一个数组，而是一个生成器。
要生成很大的数字序列的时候，用xrange会比range性能优很多，因为不需要一上来就开辟一块很大的内存空间，这两个基本上都是在循环的时候用。

在 Python 3 中，range() 是像 xrange() 那样实现，xrange()被抛弃。
```



## **二.编码规范**

#### 7.什么是 PEP8？

```markdown
PEP是 Python Enhancement Proposal 的缩写，翻译过来就是 Python增强建议书
简单说就是一种编码规范，是为了让代码“更好看”，更容易被阅读
具体可参考：
https://www.python.org/dev/peps/pep-0008/
```

#### 8.了解 Python 之禅吗？
```
总结来说，“Python之禅”强调了：

- 代码的可读性和简洁性： 鼓励编写清晰、易于理解的代码。
- 一致性和明确性： 避免模糊不清的表达，保持风格统一。
- 实用主义： 在理论 purity 和实际 applicability 之间找到平衡。
- 错误处理： 不要忽视错误，要妥善处理。
- 避免过度设计： 优先选择简单直接的方法。
```
```python
import this

The Zen of Python, by Tim Peters

Beautiful is better than ugly.
# 美观胜于丑陋。代码不仅要能工作，还要看起来优雅。

Explicit is better than implicit.
# 显式优于隐式。代码应该明确表达其意图，避免隐藏的规则或行为。

Simple is better than complex.
# 简单优于复杂。尽量用最简单直接的方式解决问题。

Complex is better than complicated.
# 复杂优于复杂难懂。如果问题本身复杂，那就坦然面对，但要避免不必要的复杂化。

Flat is better than nested.
# 扁平优于嵌套。尽量减少代码的嵌套层级，使结构更清晰。

Sparse is better than dense.
# 间隔优于拥挤。代码应该有适当的空格和换行，提高可读性。

Readability counts.
# 可读性很重要。代码是给人看的，其次才是给计算机执行的。

Special cases aren't special enough to break the rules.
# 特殊情况不足以违反规则。不要为了所谓的“特殊情况”而破坏整体设计原则，除非有非常充分的理由。

Although practicality beats purity.
# 尽管实用性胜过纯粹性。在纯粹的理论和实际应用之间找到平衡，有时为了解决实际问题可以适当妥协。

Errors should never pass silently.
# 错误不应该静默地通过。错误和异常应该被明确处理或报告。

Unless explicitly silenced.
# 除非被明确地静默。可以通过特定的机制（如 try-except）来捕获和处理异常，但这应该是故意的。

In the face of ambiguity, refuse the temptation to guess.
# 面对模棱两可的情况，拒绝猜测的诱惑。代码应该明确，避免歧义，不要依赖开发者的猜测。

There should be one-- and preferably only one --obvious way to do it.
# 事情应该有一种——最好只有一种——明显的做法。Python 致力于提供清晰、一致的语言特性，避免多种等价但风格迥异的方法。

Although that way may not be obvious at first unless you're Dutch.
# 虽然那种方法起初可能不明显（除非你是荷兰人 :-））。这是一个幽默的脚注，暗示 Guido van Rossum（荷兰人）有时能一眼看出最佳方案。

Now is better than never.
# 现在做事胜过永远不做。不要因为追求完美而迟迟不动手，先完成再迭代优化。

Although never is often better than *right* now.
# 尽管永远不做也比立刻做错要好。如果当前方案明显不合适或会导致大问题，不如暂缓。

If the implementation is hard to explain, it's a bad idea.
# 如果实现难以解释，那通常是个坏主意。好的代码应该是清晰易懂的。

If the implementation is easy to explain, it may be a good idea.
# 如果实现容易解释，那可能是个好主意。简洁明了往往意味着设计良好。

Namespaces are one honking great idea -- let's do more of those!
# 命名空间是个绝妙的想法——让我们多用用吧！命名空间有助于避免名字冲突，是组织代码的重要工具。

```

#### 9.了解 docstring 吗？

```markdown
Docstring 是 Python 中一种特殊的字符串，它出现在函数、方法、类或模块的开头，用于记录其用途、功能、参数、返回值、作者、示例等信息。它不是注释（虽然它的内容与注释类似），而是代码的一部分，并且可以通过 Python 的内置函数 help() 或对象的 .__doc__ 属性来访问。
优点：
- 增强代码的可读性和易理解，增加可维护性
- 使用IDE时，调用函数、类会自动提示函数的使用方式，包括参数返回值等信息，提升开发效率
- 使用pydoc等工具可以自动生成代码文档
```

#### 10.了解类型注解吗？

```markdown
def add(x:int, y:int) -> int:
    year:int = 2025
    return x + y
用 : 类型 的形式指定函数的参数类型，用 -> 类型 的形式指定函数的返回值类型。例如：
- List[T] / list[T]: 表示元素类型为 T 的列表。T 可以是任何类型，如 List[int] 或 list[str]。
- Dict[K, V] / dict[K, V]: 表示键类型为 K、值类型为 V 的字典。如 Dict[str, int] 或 dict[str, float]。
- Tuple[T1, T2, ...] / tuple[T1, T2, ...]: 表示具有特定类型元素的元组。如 Tuple[int, str] 或 tuple[str, ...]（表示第一个元素是 str，后面可以有任意数量的 str 元素）。
补充：类型注解本身不会改变 Python 的动态特性。你可以仍然给一个 age: int 变量赋一个字符串值，Python 运行时不会阻止你。
```

#### 11.例举你知道 Python 对象的命名规范，例如方法或者类等。

```
- 包名：同样使用短小、全小写的名称。避免使用下划线，因为一些包管理系统可能不支持带下划线的包名。
- 模块名：使用短小、全小写的名称。可以包含下划线 _ 来提高可读性，但通常建议保持简短。
- 类名都使用首字母大写开头(Pascal命名风格)的规范；
- 全局变量全用大写字母，单词之间用 _分割；
- 普通变量用小写字母，单词之间用 _分割；
- 普通函数和普通变量一样；
- 私有函数以 __ 开头（2个下划线），其他和普通函数一样；
- 实例变量/属性 (Instance Attributes):通常使用小写字母和下划线 _。如果希望表示一个受保护的（protected）属性（即不建议外部直接访问，但可以通过继承访问），
    可以在名称前加一个下划线 _。示例: self.name, self._age
```

#### 12.Python 中的注释有几种？

```markdown
单行注释，多行注释，docstring注释
```

#### 13.如何优雅的给一个函数加注释？

```markdown
在函数逻辑行的首行使用""" xxx """给函数添加注释，注释中可包含函数参数的说明，返回值说明等
def foo(bar):
    """
    This is an example.
    :param bar: explain param bar
    """
    return bar
```

#### 14.如何给变量加注释？

```python
参数注释：以冒号（:）标记
返回值注释：以 -> 标记
示例：
def add(x:int, y:int) -> int:
    return x + y
```

#### 15.Python 代码缩进中是否支持 Tab 键和 空格 混用？

```markdown
支持，Python 并没有强制要求你用Tab缩进或者用空格缩进，但在 PEP8中，建议使用4个空格来缩进
```

#### 16.是否可以在一句 import 中导入多个库？

```python
可以的
import json,random,requests
```

#### 17.在给 Python 文件命名的时候需要注意什么？

```markdown
全小写，单词之间使用下划线分隔
```

#### 18.例举几个规范 Python 代码风格的工具。

```markdown
pylint,black,pycharm也带有pep8的代码规范工具
```



## **三.数据类型**

### **字符串**
| 函数/操作                 | 描述                                                         | 示例                                                                 |
|---------------------------|--------------------------------------------------------------|----------------------------------------------------------------------|
| `str()`                   | 创建字符串，或将其他类型转换为字符串                         | `str(123)` -> `"123"`                                               |
| `len(s)`                  | 返回字符串的长度                                             | `len("hello")` -> `5`                                               |
| `s[index]`                | 通过索引访问单个字符（索引从0开始）                         | `"hello"[1]` -> `"e"`                                               |
| `s[start:end:step]`       | 切片操作，获取子字符串                                       | `"hello"[1:4]` -> `"ell"`, `"hello"[::-1]` -> `"olleh"`              |
| `s + t`                   | 字符串连接                                                   | `"hello" + " world"` -> `"hello world"`                             |
| `s * n`                   | 字符串重复n次                                               | `"ha" * 3` -> `"hahaha"`                                            |
| `in`, `not in`            | 成员运算符，检查子字符串是否存在                             | `"ell" in "hello"` -> `True`, `"x" not in "abc"` -> `True`          |
| `s.find(sub)`             | 查找子字符串 `sub` 第一次出现的位置，未找到返回 `-1`         | `"hello".find("ell")` -> `2`                                        |
| `s.index(sub)`            | 查找子字符串 `sub` 第一次出现的位置，未找到抛出异常          | `"hello".index("e")` -> `1`                                        |
| `s.count(sub)`            | 统计子字符串 `sub` 出现的次数                               | `"banana".count("a")` -> `3`                                       |
| `s.upper()`               | 转换为大写                                                   | `"hello".upper()` -> `"HELLO"`                                      |
| `s.lower()`               | 转换为小写                                                   | `"HELLO".lower()` -> `"hello"`                                      |
| `s.capitalize()`          | 将字符串的第一个字符转换为大写，其余为小写                   | `"hello world".capitalize()` -> `"Hello world"`                     |
| `s.title()`               | 将字符串中每个单词的首字母大写                               | `"hello world".title()` -> `"Hello World"`                          |
| `s.strip()`               | 去除字符串首尾的空白字符（空格、制表符、换行符等）           | `"  hello  ".strip()` -> `"hello"`                                  |
| `s.lstrip()`, `s.rstrip()`| 去除字符串左侧或右侧的空白字符                               | `"  hello".lstrip()` -> `"hello"`, `"hello  ".rstrip()` -> `"hello"` |
| `s.replace(old, new)`     | 将字符串中的 `old` 子字符串替换为 `new`                       | `"hello".replace("ll", "p")` -> `"hepo"`                            |
| `s.split(sep=None)`       | 按分隔符 `sep` 分割字符串，返回列表                          | `"a,b,c".split(",")` -> `["a", "b", "c"]`                           |
| `s.join(iterable)`        | 以字符串 `s` 作为分隔符，连接可迭代对象 `iterable` 中的元素   | `",".join(["a", "b", "c"])` -> `"a,b,c"`                            |
| `s.startswith(prefix)`    | 检查字符串是否以 `prefix` 开头                               | `"hello".startswith("he")` -> `True`                                |
| `s.endswith(suffix)`      | 检查字符串是否以 `suffix` 结尾                               | `"hello".endswith("lo")` -> `True`                                  |
| `s.isdigit()`             | 检查字符串是否只包含数字字符                                 | `"123".isdigit()` -> `True`                                         |
| `s.isalpha()`             | 检查字符串是否只包含字母字符                                 | `"abc".isalpha()` -> `True`                                         |
| `s.isalnum()`             | 检查字符串是否只包含字母和数字字符                           | `"a1b2".isalnum()` -> `True`                                        |
| `s.isspace()`             | 检查字符串是否只包含空白字符                                 | `"   ".isspace()` -> `True`                                         |
| `s.islower()`, `s.isupper()` | 检查字符串是否全是小写/大写字母                             | `"abc".islower()` -> `True`, `"ABC".isupper()` -> `True`            |
| `f"..."` 或 `f'...'`      | f-string（格式化字符串字面值），在字符串中嵌入表达式         | `name = "Alice"; f"Hello, {name}!"` -> `"Hello, Alice!"`            |
| `"{0} {1}".format(a, b)`  | 使用 `str.format()` 方法格式化字符串                         | `"{} {}".format("hello", "world")` -> `"hello world"`               |
| `s.encode(encoding)`      | 将字符串编码为字节串（bytes）                                | `"hello".encode('utf-8')` -> `b'hello'`                             |
| `s.decode(encoding)`      | （bytes对象的方法）将字节串解码为字符串                      | `b'hello'.decode('utf-8')` -> `"hello"`                             |


#### 19.列举 Python 中的基本数据类型。

```markdown
Python3 中有六个标准的数据类型：

Number（数字）
  - int
  - float
  - 复数complex
Boolean
String（字符串）
List（列表）
Tuple（元组）
Set（集合）
Dictionary（字典）
Python3 的六个标准数据类型中：

不可变数据（3 个）：Number（数字）、String（字符串）、Tuple（元组）；
可变数据（3 个）：List（列表）、Dictionary（字典）、Set（集合）。
```

#### 20.如何区别 可变数据类型 和 不可变数据类型？

```markdown
Python3 的六个标准数据类型中：

不可变数据（3 个）：Number（数字）、String（字符串）、Tuple（元组）；
可变数据（3 个）：List（列表）、Dictionary（字典）、Set（集合）。
```

#### 21.将 "hello world" 转换为首字母大写 "Hello World"。

```python
z = 'hello world'
z.title()
```

#### 22.如何检测字符串中只含有数字？

```python
# 分为两种情况
# 1.不包含正负号 +-
a = '32323'
a.isdigit()
# 2.含有正负号
import re
re.match(r'[+-]?\d+$',a)
```

#### 23.将字符串 "ilovechina" 进行反转。

```python
s = 'ilovechina'
s = s[::-1]
```

#### 24.Python 中的字符串格式化方式你知道哪些？

```python
# Python3.6之后的版本提供了三种字符串格式化的方式
# 1. %s占位符
def foo(name):
  return 'hello %s' % name

# 2. format() 
def foo(name):
  return 'hello {}'.format(name)

# f-string
def foo(name):
  return f'hello {name}'
```

#### 25.有一个字符串开头和末尾都有空格，比如 " adabdw "。要求写一个函数把这个字符串的前后空格都去掉。

```python
s = " adabdw "
s.strip()
```

#### 26.获取字符串 "123456" 最后的两个字符。

```python
s = '123456'

print(s[-2:])
```

#### 27.一个编码为 GBK 的字符串 S，要将其转成 UTF-8 编码的字符串，应如何操作？

```python
s.encode('utf-8')
```

#### 28.字符串 s = "info:xiaoZhang 33 shandong"，用正则切分字符串输出 ['info', 'xiaoZhang', '33', 'shandong']。

```python
import re
s="info:xiaoZhang 33 shandong"
re.split(r'[:\s]',s)
```

#### 29.怎样将字符串转换为小写？

```python
b = 'HHH'
b.lower()
```

#### 30.单引号、双引号和三引号的区别？

```python
s = 'hello'
s= "hello"
双引号可以包含单引号字符，单引号无法包含双引号字符
三引号可以用来加注释，所加注释可以使用__doc__查看
```

#### 31.字符串 a = "你好     中国  "，去除多余空格只留一个空格。

```markdown
注意下述str.split()会按照空白进行分割，包括空白、换行符、制表符等
str.split(' ')则会按照空格分割
```
```python
a = "你好     中国  "
s = ' '.join(a.strip().split())
```



### **列表**
| 函数/操作               | 描述                                       | 示例                                 |
|------------------------|------------------------------------------|------------------------------------|
| `list()`               | 创建一个空列表                               | `mylist = list()`                  |
| `list(iterable)`       | 使用可迭代对象创建列表                         | `mylist = list([1, 2, 3])`         |
| `len(list)`            | 返回列表的长度                               | `length = len(mylist)`             |
| `list[index]`          | 访问或设置列表中的元素                         | `value = mylist[0]`<br>`mylist[1] = 4` |
| `list.append(item)`    | 在列表末尾添加一个元素                         | `mylist.append(4)`                  |
| `list.insert(index, item)` | 在指定位置插入一个元素                     | `mylist.insert(1, 'a')`            |
| `list.extend(iterable)`| 将可迭代对象的元素扩展到列表末尾                 | `mylist.extend([4, 5, 6])`         |
| `list.remove(item)`    | 删除列表中的第一个匹配项                       | `mylist.remove(2)`                  |
| `list.pop([index])`   | 删除并返回指定位置的元素，默认为最后一个元素       | `last_item = mylist.pop()`<br>`item = mylist.pop(1)` |
| `list.clear()`         | 清空列表                                   | `mylist.clear()`                    |
| `list.index(item)`     | 返回列表中第一个匹配项的索引                     | `index = mylist.index('a')`        |
| `list.count(item)`     | 返回列表中元素出现的次数                       | `count = mylist.count(2)`          |
| `list.sort()`          | 对列表进行原地排序                             | `mylist.sort()`                     |
| `list.reverse()`       | 反转列表中的元素顺序                           | `mylist.reverse()`                  |
| `list.copy()`          | 返回列表的浅拷贝                             | `newlist = mylist.copy()`          |
| `list slicing`         | 获取列表的子集                               | `sublist = mylist[1:3]`            |
| `list comprehension`   | 创建列表的简洁方式                             | `squares = [x**2 for x in range(10)]` |
| `list.join()`          | 将列表中的元素连接成字符串（字符串方法，适用于字符串列表） | `''.join(['a', 'b', 'c'])` -> 'abc' |
| `list in`              | 检查元素是否在列表中                           | `if 2 in mylist:`                   |
| `list + list`          | 连接两个列表                                 | `newlist = mylist + [4, 5, 6]`     |
| `list * n`             | 重复列表n次                                 | `repeatedlist = mylist * 3`        |

#### 32.已知 AList = [1,2,3,1,2]，对 AList 列表元素去重，写出具体过程。

```python
a_list = [1,2,3,1,2]
ss = set(a_list)
```

#### 33.如何将 "1,2,3" 变成 ["1","2","3"]？

```python
s = "1,2,3"
s.split(',')
```

#### 34.给定两个 list，A 和 B，找出相同元素和不同元素。

```python
# 最直接的方法
list_a = [1,2,3,4,5,6]
list_b = [2,3,6]
same_l = []
not_same = []
for i in list_a:
    if i not in list_b:
        not_same.append(i)
for j in list_b:
    if j not in list_a:
        not_same.append(j)
for x in list_a:
  if x in list_b:
       same_l.append(x)
# 奇技淫巧
list_a = [1,2,3,4,5,6]
list_b = [2,3,6]
set1 = set(list_a)
set2 = set(list_b)
# 相同元素
print(set1&set2)
# 不同元素
print(set1^set2)
```

#### 35.用一行代码展开该列表 [[1,2],[3,4],[5,6]]，得出[1,2,3,4,5,6]。

```python
mm = [[1,2],[3,4],[5,6]]
[j for a in mm for j in a]
```

#### 36.合并列表 [1,5,7,9] 和 [2,2,6,8]。
```markdodn
注意append和extend的区别，两者都是list添加元素的函数，但是append是将待添加的对象作为整体添加，extend会将待添加对象的每个元素逐个添加
```

```python
a = [1,5,7,9]
b = [2,2,6,8]
# 方法1
a.extend(b)
# 方法2
a[0:0] = b
# 方法3
a += b
```

#### 37.如何打乱一个列表的元素？

```python
import random
a = [1,5,7,9]
random.shuffle(a)
```



### **字典**
| 函数/操作             | 描述                                       | 示例                                      |
|----------------------|------------------------------------------|-----------------------------------------|
| `dict()`             | 创建一个空字典                             | `my_dict = dict()`                      |
| `dict(key=value)`    | 使用键值对创建字典                         | `my_dict = dict(name='Alice', age=25)`  |
| `dict(iterable)`     | 使用可迭代对象创建字典                     | `my_dict = dict([('name', 'Alice'), ('age', 25)])` |
| `dict(**kwargs)`     | 使用关键字参数创建字典                     | `my_dict = dict(name='Alice', age=25)`  |
| `len(dict)`          | 返回字典中的项目数量                       | `length = len(my_dict)`                 |
| `dict[key]`          | 访问或设置字典中的项                       | `value = my_dict['name']`<br>`my_dict['age'] = 26` |
| `dict.get(key, default)` | 获取字典中的项，如果不存在则返回默认值     | `value = my_dict.get('name', 'Unknown')` |
| `dict.setdefault(key, default)` | 如果键不存在，则设置键值对               | `my_dict.setdefault('city', 'New York')` |
| `dict.update(other)` | 使用另一个字典或键值对更新字典             | `my_dict.update({'age': 26, 'city': 'Paris'})` |
| `key in dict`        | 检查字典中是否存在键                       | `if 'name' in my_dict:`                |
| `key not in dict`    | 检查字典中是否不存在键                     | `if 'city' not in my_dict:`            |
| `dict.keys()`        | 返回一个包含字典所有键的视图               | `keys = my_dict.keys()`                |
| `dict.values()`      | 返回一个包含字典所有值的视图               | `values = my_dict.values()`            |
| `dict.items()`       | 返回一个包含字典所有键值对的视图           | `items = my_dict.items()`              |
| `dict.pop(key, default)` | 删除指定的键并返回其值，如果不存在则返回默认值 | `value = my_dict.pop('name', 'Unknown')` |
| `dict.popitem()`     | 删除并返回字典中的最后一对键值对           | `key, value = my_dict.popitem()`       |
| `del dict[key]`      | 删除字典中的键值对                         | `del my_dict['name']`                  |
| `dict.clear()`       | 清空字典                                   | `my_dict.clear()`                      |
| `dict.copy()`        | 返回字典的浅拷贝                           | `new_dict = my_dict.copy()`            |
| `dict.fromkeys(iterable, value)` | 创建一个新字典，以可迭代对象为键，值为指定值 | `new_dict = dict.fromkeys(['a', 'b'], 1)` |



#### 38.字典操作中 del 和 pop 有什么区别？

```markdown
del 操作删除键值对，不返回值；
pop 操作删除键值对的同时，返回键所对应的值。
```

#### 39.将如下字典按照年龄排序。

```Python
d1 = [
    {'name':'alice', 'age':38},
    {'name':'bob', 'age':18},
    {'name':'Carl', 'age':28},
]
```

```python
sorted(d1,key=lambda x:x['age'])
```

#### 40.请合并下面两个字典 a = {"A":1,"B":2}，b = {"C":3,"D":4}。

```python
# python3合并字典有三种方式
# 1.
a = {'a':1,'b':2}
b = {'c':3,'d':4}
c = {}
c.update(a)
c.update(b)
# 2.
c = dict(a,**b)
# 3.
c = {**a,**b} # 官方推荐这种方式
```

#### 41.如何使用生成式的方式生成一个字典，写一段功能代码。

```python
{x:x*x for x in range(6)}
```

#### 42.如何把 元组 ("a","b") 和 元组(1,2)，变为字典{"a":1,"b":2}？

```python
a = ('a','b')
b = (1,2)
z=zip(a,b)
c = dict(z)
```



### **综合数据类型**

#### 43.Python 常用的数据结构的类型及其特性？

```markdown
List,tuple,dict,set是比较常用的数据结构，queue,heap,deque,ProrityQueue，multiprocessing.Queue等进阶的数据结构类型。
```
Python 提供了多种数据结构，用于存储和组织数据。这些结构各有特点，适用于不同的场景。

##### 43.1. 列表 (List)
- **介绍**：列表是有序的、可变的集合，可以包含重复元素。
- **特点**：
  - 有序：元素有固定顺序。
  - 可变：可以修改、添加和删除元素。
  - 动态：大小可变。
- **用途**：通用数据存储，适合需要频繁修改的数据集。

##### 43.2. 元组 (Tuple)
- **介绍**：元组是有序的、不可变的集合，可以包含重复元素。
- **特点**：
  - 有序：元素有固定顺序。
  - 不可变：一旦创建，不能修改。
  - 动态：大小固定。
- **用途**：存储不可变数据，如函数返回多个值。

##### 43.3. 字典 (Dict)
- **介绍**：字典是无序的、可变的键值对集合，键唯一。
- **特点**：
  - 无序：元素没有固定顺序。
  - 可变：可以修改、添加和删除键值对。
  - 键唯一：每个键只能对应一个值。
- **用途**：快速查找和存储键值对。

##### 43.4. 集合 (Set)
- **介绍**：集合是无序的、可变的唯一元素集合。
- **特点**：
  - 无序：元素没有固定顺序。
  - 可变：可以添加和删除元素。
  - 唯一：不包含重复元素。
- **用途**：成员资格测试、消除重复元素、集合运算。


##### 43.5. 队列 (Queue)
- **介绍**：队列是先进先出（FIFO）的数据结构。
- **特点**：
  - FIFO：第一个添加的元素第一个被移除。
  - 线程安全：适用于多线程环境。
- **用途**：任务排队、缓存。

##### 43.6. 堆 (Heap)
- **介绍**：堆是一种基于优先级的二叉树结构。
- **特点**：
  - 最小堆或最大堆：最小堆的父节点总是小于或等于其子节点，最大堆相反。
  - 动态：可以添加和删除元素。
- **用途**：实现优先队列、排序算法。

##### 43.7. 双端队列 (Deque)
- **介绍**：双端队列是两端都可以进行添加和删除操作的队列。
- **特点**：
  - 双向：可以在两端添加和删除元素。
  - 高效：两端操作时间复杂度为O(1)。
- **用途**：需要两端操作的场景，如滑动窗口。

##### 43.8. 优先队列 (PriorityQueue)
- **介绍**：优先队列是一种基于优先级的队列。
- **特点**：
  - 优先级：元素按照优先级排序。
  - 线程安全：适用于多线程环境。
- **用途**：任务调度、事件驱动编程。

##### 43.9. 多进程队列 (multiprocessing.Queue)
- **介绍**：多进程队列是用于进程间通信的队列。
- **特点**：
  - 进程安全：适用于多进程环境。
  - 通信机制：进程间可以通过队列传递数据。
- **用途**：多进程编程中的数据共享。

##### 43.10.数据结构对比

| 数据结构         | 有序 | 可变 | 唯一 | 键值对 | 线程安全 | 进程安全 | 主要用途                         |
|------------------|------|------|------|--------|----------|----------|----------------------------------|
| List             | 是   | 是   | 否   | 否     | 否       | 否       | 通用数据存储                     |
| Tuple            | 是   | 否   | 否   | 否     | 否       | 否       | 存储不可变数据                   |
| Dict             | 否   | 是   | 键唯一 | 是     | 否       | 否       | 快速查找和存储键值对             |
| Set              | 否   | 是   | 是   | 否     | 否       | 否       | 成员资格测试、消除重复元素       |
| Queue            | 是   | 是   | 否   | 否     | 是       | 否       | 任务排队、缓存                   |
| Heap             | 否   | 是   | 否   | 否     | 否       | 否       | 实现优先队列、排序算法           |
| Deque            | 是   | 是   | 否   | 否     | 否       | 否       | 需要两端操作的场景，如滑动窗口   |
| PriorityQueue    | 是   | 是   | 否   | 否     | 是       | 否       | 任务调度、事件驱动编程           |
| multiprocessing.Queue | 否 | 是   | 否   | 否     | 是       | 是       | 多进程编程中的数据共享           |

每种数据结构都有其独特的优势和适用场景，选择合适的数据结构可以大大提高程序的性能和可读性。


#### 44.如何将 元组("A","B") 和 元组(1,2) 合并成 字典{"A":1,"B":2}？

```Python
a = ('A','B')
b = (1,2)
z=zip(a,b)
c = dict(z)
```

#### 45.Python 里面如何实现 tuple 和 list 的转换？

```python
tuple(list) # tuple转list
list(tuple) # list 转tuple
```

#### 46.我们知道对于列表可以使用切片操作进行部分元素的选择，那么如何对生成器类型的对象实现相同的功能呢？

```python
使用自带的itertools库进行实现，具体实现方式 itertools.islice(生成器对象，起始位置，结束位置)，即可实现切片功能。
```

#### 47.请将 [i for i in range(3)] 改成 生成器。

```python
(i for i in range(3))
```

#### 48.将 a="hello" 和 b="你好" 编码成 bytes 类型。

```python
a.encode()
b.encode()
```

#### 49.下面的代码输出结果是什么？

```Python
a = (1,2,3,[4,5,6,7],8)
a[2] = 2
报错，元组是不可变对象，不支持修改
```

#### 50.下面的代码输出的结果是什么？

```Python
a = (1,2,3,[4,5,6,7],8)
a[5] = 2
报错，元组是不可变对象，下标越界

# 下述方式不会报错，输出(1, 2, 3, [4, 5, 6, 7, 77], 8)
a = (1,2,3,[4,5,6,7],8)
a[3].append(77)
print(a)
```

### **操作类题目**

#### 51.在 Python 中交换两个变量的值。

```python
a,b = b,a
```

#### 52.在读文件操作的时候会使用 read、readline 或者 readlines，简述它们各自的作用。

```python
read将整个文本都读取为一个字符串，占用内存大，readline读取为一个生成器，支持遍历和迭代，占用空间小。readlines将文本读取为列表，占用空间大
```

#### 53.json 序列化时，可以处理的数据类型有哪些？如何定制支持 datetime 类型？

```markdown
字符串、数字（整数和浮点数）、字典、列表、布尔值、None。使用strftime将datetime格式化为标准字符串类型即可。
```

#### 54.json 序列化时，默认遇到中文会转换成 unicode，如果想要保留中文怎么办？

```
使用json.dumps函数时，添加参数ensure_ascii=False，如果想显示的更美观，可以添加indent=2参数，会在每个key值前添加两个空格。
```

#### 55.有两个磁盘文件 A 和 B，各存放一行字母，要求把这两个文件中的信息合并（按字母顺序排列），输出到一个新文件 C 中。

```python
with open('A.txt','r') as f:
    a = f.readlines()[0]
with open('B.txt','r') as f:
    b = f.readlines()[0]
    a.extend(b).sort()
with open('C.txt','w') as f:
    for i in a:
        f.write(i)
```

#### 56.如果当前的日期为 20190530，要求写一个函数输出 N 天后的日期（比如 N 为 2，则输出 20190601)。

```python
from datetime import datetime, timedelta

def get_date_after_n_days(current_date_str, n):
    # 将输入的字符串转换为日期对象
    current_date = datetime.strptime(current_date_str, "%Y%m%d").date()
    
    # 计算N天后的日期
    future_date = current_date + timedelta(days=n)
    
    # 将日期对象格式化为字符串
    future_date_str = future_date.strftime("%Y%m%d")
    
    return future_date_str

# 示例使用
current_date = "20190530"
n = 2
result = get_date_after_n_days(current_date, n)
print(result)  # 输出: 20190601

```

#### 57.写一个函数，接收整数参数 n，返回一个函数。函数的功能是把函数的参数和 n 相乘并把结果返回。

```python
def mul(n):
  def wrapper(m):
    return n*m
  return wrapper
    
 # 闭包的基本操作
```

#### 58.下面的代码会存在什么问题，如何改进？
1、使用内置函数str作为变量名
```Python
def strappend(num):
    str='first'
    for i in range(num):
        str+=str(i)
    return str
```

#### 59.一行代码输出 1-100 之间的所有偶数。

```python
[x for x in range(101) if x %2 ==0]
[i for i in range(1, 100, 2)
```

#### 60.with 语句的作用，并用它写一段代码。
with 语句是 Python 提供的一种上下文管理协议 (Context Manager Protocol) 的语法糖，它的主要目的是简化资源管理，特别是在处理需要初始化和清理操作的对象时，比如文件、网络连接、锁等。
```python
# with语句用来管理资源，及时关闭文件等操作，避免资源的泄漏
with open('a.txt','r') as f:
    f.read()

class MyResource:
    def __init__(self, name):
        self.name = name

    def __enter__(self):
        print(f"Initializing {self.name} resource...")
        # 这里可以执行初始化操作，比如连接数据库
        return self # 通常返回 self 或其他需要管理的对象

    def __exit__(self, exc_type, exc_val, exc_tb):
        print(f"Cleaning up {self.name} resource...")
        # 这里执行清理操作，比如断开数据库连接
        # 如果需要抑制异常，可以返回 True
        return False # 默认不抑制异常

# 使用自定义的上下文管理器
with MyResource("Database") as resource:
    print(f"Doing work with {resource.name}...")
    # 模拟可能发生的异常
    # raise ValueError("Something went wrong!")
# 无论是否发生异常，"Cleaning up Database resource..." 都会打印

```

#### 61.Python 字典和 json 字符串相互转化方法。

```python
json.dumps()   将Python中的对象转换为JSON中的字符串对象
json.loads()   将JSON中的字符串对象转换为Python中的对象
```

#### 62.请写一个 Python 逻辑，计算一个文件中的大写字母数量。

```python
import re
with open('a.txt','r') as f:
    f_content = f.read()
    len_cap = len(re.compile(r'[A-Z]').findall(f_content))
```



### **高级特性**

#### 63.函数装饰器有什么作用？请列举说明。
函数装饰器可以在不修改原函数的条件下，为原函数添加额外的功能，例如记录日志，运行性能，缓存等以记录函数运行时间为例，实现一个装饰器
```python
import time

def time_it(func):
    def wrapper():
        start_time = time.time()
        res = func()
        end_time = time.time()
        print(f"Function {func.__name__} took {end_time - start_time} seconds to run.")
        return res
    return wrapper

@time_it
def hello():
    print("hello world")

hello()
    
```

#### 64.简述 Python 垃圾回收机制。

```python
引用计数机制：
python里每一个东西都是对象，它们的核心就是一个结构体：PyObject
 typedef struct_object {
 int ob_refcnt;
 struct_typeobject *ob_type;
} PyObject;

PyObject是每个对象必有的内容，其中ob_refcnt就是做为引用计数。当一个对象有新的引用时，它的ob_refcnt就会增加，当引用它的对象被删除，它的ob_refcnt就会减少
#define Py_INCREF(op)   ((op)->ob_refcnt++) //增加计数
#define Py_DECREF(op) \ //减少计数
    if (--(op)->ob_refcnt != 0) \
        ; \
    else \
        __Py_Dealloc((PyObject *)(op))

当引用计数为0时，该对象生命就结束了。
引用计数机制的优点：

简单
实时性：一旦没有引用，内存就直接释放了。不用像其他机制等到特定时机。实时性还带来一个好处：处理回收内存的时间分摊到了平时

```

#### 65.魔法函数 __call__怎么使用？
应用场景
函数工厂/策略模式：如上面的 PowerCalculator 示例，创建可配置的行为。
装饰器类：类可以像装饰器函数一样使用，通过 __call__ 来包装被装饰的函数。
模拟函数：创建具有状态的对象，这些对象在调用时可以访问和修改其内部状态。
回调对象：在需要回调的地方，可以传递一个实现了 __call__ 的对象，而不是一个简单的函数，这样回调对象可以拥有自己的状态和方法。
```python
class Bar:
    def __call__(self, *args, **kwargs):
        print('i am instance method')

b = Bar()  # 实例化
b()  # 实例对象b 可以作为函数调用 等同于b.__call__ 使用


# OUT: i am instance method

class PowerCalculator:
    def __init__(self, exponent):
        self.exponent = exponent
        print(f"PowerCalculator initialized with exponent {self.exponent}.")

    def __call__(self, base):
        print(f"Calculating {base} raised to the power of {self.exponent}.")
        return base ** self.exponent

# 创建一个计算平方的实例
square = PowerCalculator(2)
# 创建一个计算立方的实例
cube = PowerCalculator(3)

# 使用这些实例，就像使用函数一样
print(square(5))  # 输出: 25
print(cube(2))    # 输出: 8



# 带参数的类装饰器
class Bar:

    def __init__(self, p1):
        self.p1 = p1

    def __call__(self, func):
        def wrapper():
            print("Starting", func.__name__)
            print("p1=", self.p1)
            func()
            print("Ending", func.__name__)
        return wrapper


@Bar("foo bar")
def hello():
    print("Hello")
```

#### 66.如何判断一个对象是函数还是方法？

```Python
使用 type() 函数来检查对象的类型。函数通常是 function 类型，而方法通常是 method 或 classmethod、staticmethod 类型。
```

#### 67.简述 @classmethod 和 @staticmethod 用法和区别。

| 特性         | @classmethod                     | @staticmethod                     |
| :----------- | :------------------------------- | :-------------------------------- |
| 第一个参数   | 必须是类 (cls)                   | 没有自动参数 (self 或 cls)        |
| 访问类属性   | 可以 (cls.some_attr)              | 不行（除非通过类名 ClassName.some_attr） |
| 访问实例属性 | 不行（除非通过 cls 创建实例后访问） | 不行（除非通过参数传入）          |
| 调用方式     | ClassName.method() 或 instance.method() | ClassName.method() 或 instance.method() |
| 本质         | 特殊方法，与类紧密相关           | 普通函数，只是放在类里           |
| 主要用途     | 工厂方法、类级操作               | 工具函数、逻辑上相关但不依赖状态的操作 |

```python
一般来说，要使用某个类的方法，需要先实例化一个对象再调用方法。

而使用@staticmethod或@classmethod，就可以不需要实例化，直接类名.方法名()来调用。

这有利于组织代码，把某些应该属于某个类的函数给放到那个类里去，同时有利于命名空间的整洁。



既然@staticmethod和@classmethod都可以直接类名.方法名()来调用，那他们有什么区别呢

从它们的使用上来看,
@staticmethod不需要表示自身对象的self和自身类的cls参数，就跟使用函数一样。
@classmethod也不需要self参数，但第一个参数需要是表示自身类的cls参数。
如果在@staticmethod中要调用到这个类的一些属性方法，只能直接类名.属性名或类名.方法名。

而@classmethod因为持有cls参数，可以来调用类的属性，类的方法，实例化对象等，避免硬编码
class A(object):
    bar = 1
    def foo(self):
        print 'foo'
 
    @staticmethod
    def static_foo():
        print 'static_foo'
        print A.bar
 
    @classmethod
    def class_foo(cls):
        print 'class_foo'
        print cls.bar
        cls().foo()
 
A.static_foo()
A.class_foo()
```

#### 68.Python 中的接口如何实现？
在 Python 中，没有像 Java 或 C# 那样的显式“接口”关键字，但可以通过几种方式来实现接口的概念，主要是通过抽象基类（Abstract Base Classes, ABCs）和协议（Protocols）。
`抽象基类（ABCs）`：通过 abc 模块定义抽象基类，强制子类实现特定方法。
`协议（Protocols）`：通过 typing.Protocol 定义接口，更灵活，基于类型注解。
`模拟接口`：通过文档和约定来模拟接口，依赖文档和测试来确保实现。

```python
#抽象类加抽象方法就等于面向对象编程中的接口
from abc import ABC, abstractmethod

class MyInterface(ABC):
    @abstractmethod
    def method1(self):
        pass

    @abstractmethod
    def method2(self):
        pass

class MyClass(MyInterface):
    def method1(self):
        print("Method 1 implemented")

    def method2(self):
        print("Method 2 implemented")

# 创建实例
obj = MyClass()
obj.method1()
obj.method2()

```

#### 69.你了解 Python 中的反射吗？
在Python中，反射指的是程序在运行时检查、访问和修改自身结构或对象结构的能力。
它允许你动态地获取对象的信息（如类型、属性、方法等）并执行操作，而无需在编写代码时完全知道这些信息。
Python天生就具有很强的动态性和反射能力，这得益于其一切皆对象的设计哲学。
通过字符串映射object对象的方法或者属性
hasattr(obj,name_str): 判断objec是否有name_str这个方法或者属性
getattr(obj,name_str): 获取object对象中与name_str同名的方法或者函数
setattr(obj,name_str,value): 为object对象设置一个以name_str为名的value方法或者属性
delattr(obj,name_str): 删除object对象中的name_str方法或者属性

举个栗子
```python

import requests
class Http(object):
    def get(self,url):
        res = requests.get(url)
        response = res.text
        return response

    def post(self,url):
        res = requests.post(url)
        response = res.text
        return response

# 使用反射后
url = "https://www.jianshu.com/u/14140bf8f6c7"
method = input("请求方法>>>:")
h = Http()

if hasattr(h,method):
    func = getattr(h,method)
    res = func(url)
    print(res)
else:
    print("你的请求方式有误...")
```

#### 70.简述 metaclass 的作用和其应用场景。

```markdown
在Python中，元类是创建类的“工厂”。如果你把类看作是创建实例对象的模板，那么元类就是创建这些类（模板）的模板。
默认情况下，Python使用内置的 type 函数作为元类来创建所有的类。当你定义一个类时，Python会幕后调用 type.__new__ 和 type.__init__ 来生成这个类对象。
元类允许你在类创建时拦截、修改或观察类的定义过程。你可以通过自定义元类来控制类的创建行为，从而在类被定义时就对其结构或行为进行定制。
简单来说，元类的核心作用是：在类被创建时自动修改或增强类。
```

#### 71.对比 hasattr()，getattr() 和 setattr() 的用法。

```python
hasattr(obj,name_str): 判断objec是否有name_str这个方法或者属性
getattr(obj,name_str): 获取object对象中与name_str同名的方法或者函数
setattr(obj,name_str,value): 为object对象设置一个以name_str为名的value方法或者属性
delattr(obj,name_str): 删除object对象中的name_str方法或者属性
```

#### 72.请列举你知道的 Python 的魔法方法及用途。

```
1. __call__:允许一个类的实例像函数一样被调用。实质上说，这意味着 x() 与 x._call_() 是相同的
2.__init__:显示初始化属性
3.__str__,__repr__,定义类的时候，重写这两个方法可以让类更清晰
再就是__setattr__,__getattr__,__delattr__等等
```

#### 73.如何知道一个 Python 对象的类型？

```
type(obj)
```

81.**Python 的传参是传值还是传址？**

```
说传值或者传引用都不准确。非要安一个确切的叫法的话，叫传对象（call by object）
具体可以参考这篇文章：https://foofish.net/python-function-args.html
```

#### 74.Python 中的 元类(metaclass) 使用举例。

```markdown
元类的应用场景
由于元类提供了强大的类创建时干预能力，它通常用于一些比较高级或需要全局性影响的场景：

自动注册类：
当你定义一个类时，元类可以自动将这个类注册到一个全局的字典或列表中。这在实现插件系统、抽象基类（abc 模块内部就使用了元类）时非常有用。
例如，所有继承自某个基类的子类在定义时自动被收集起来。
实现接口检查（抽象基类 Abstract Base Classes, ABCs）：
Python的 abc.ABCMeta 就是一个元类。它可以在类创建时检查子类是否实现了所有必需的抽象方法。如果没有，它会阻止该类的实例化，确保接口契约被遵守。
创建描述符（Descriptors）和属性管理：
虽然可以直接在类中使用 __setattr__、__getattribute__ 等，但元类可以在类创建时统一处理所有属性的设置和获取逻辑，例如实现ORM（对象关系映射）框架中常见的字段验证、类型转换等。
代码生成或修改：
在类创建时，元类可以动态地添加新的方法或属性到类中，或者修改已有的方法（例如，统一添加日志记录、性能计时等功能，类似装饰器，但作用于整个类）。
实现单例模式（Singleton）：
可以通过元类控制类的 __call__ 方法，使得每次尝试创建实例时都返回同一个实例对象。
框架开发：
许多大型框架（如Django ORM、Flask的部分扩展）会使用元类来动态地处理用户定义的模型类或配置类，自动生成数据库表、路由处理逻辑等。
```

#### 75.简述 any() 和 all() 方法。

```python
#any(x)判断x对象是否为空对象，如果都为空、0、false，则返回false，如果不都为空、0、false，则返回true

#all(x)如果all(x)参数x对象的所有元素不为0、''、False或者x为空对象，则返回True，否则返回False
>>> any('123')
True
>>> any([0,1])
True
>>> any([0,'0',''])
True
>>> any([0,''])
False
>>> any([0,'','false'])
True
>>> any([0,'',bool('false')])
True
>>> any([0,'',False])
False
>>> any(('a','b','c'))
True
>>> any(('a','b',''))
True
>>> any((0,False,''))
False
>>> any([])
False
>>> any(())
False
>>> all(['a', 'b', 'c', 'd'])  #列表list，
True
>>> all(['a', 'b', 'c', 'd'])  #列表list，元素都不为空或0
True
>>> all(['a', 'b', '', 'd'])  #列表list，存在一个为空的元素
False
>>> all([0, 1,2, 3])  #列表list，存在一个为0的元素
False
>>> all(('a', 'b', 'c', 'd'))  #元组tuple，元素都不为空或0
True
>>> all(('a', 'b', '', 'd'))  #元组tuple，存在一个为空的元素
False
>>> all((0, 1,2, 3))  #元组tuple，存在一个为0的元素
False
>>> all([]) # 空列表
True
>>> all(()) # 空元组
True
>>> #注意：空元组、空列表返回值为True，这里要特别注意
```

#### 76.用 filter 方法求出列表 a =  [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 中的所有奇数，并构造新列表。

```python
list(filter(lambda x: x%2==1,a))
```

#### 77.什么是猴子补丁？

```markdown
猴子补丁是一个概念，不是python中发明的，其他动态语言也有这么个概念。 《松本行弘的程序世界》这本书，里面专门有一章讲了猴子补丁的设计，所谓的猴子补丁的含义是指在动态语言中，不去改变源码而对功能进行追加和变更
```

#### 78.在 Python 中是如何管理内存的？

```
主要可以归纳为以下几个核心机制：
`引用计数 (Reference Counting)`
原理：这是Python内存管理的基础机制。每个Python对象（如整数、列表、字典等）都有一个与之关联的引用计数器。这个计数器记录了当前有多少个变量名或其他对象指向这个对象。
工作方式：
当一个对象被创建并赋值给一个变量时，它的引用计数初始化为1。
当这个对象被赋值给另一个变量，或者作为参数传递给函数时，引用计数加1。
当一个变量超出作用域、被重新赋值或显式删除（del）时，引用计数减1。
内存回收：当一个对象的引用计数变为0时，意味着没有任何引用指向它了，这个对象就变成了“垃圾”。Python的内存管理器会立即回收该对象所占用的内存。
优点：回收机制简单直接，回收操作几乎是即时的，能快速释放不再使用的内存。
缺点：无法处理循环引用（后面会讲到）。每次增加或减少引用计数都有一定的开销。


`垃圾回收器 (Garbage Collector, GC)`
目的：为了解决引用计数无法处理的循环引用问题。循环引用指的是两个或多个对象相互引用，形成一个或多个循环，导致它们的引用计数永远不会降到0，即使它们实际上已经不再被程序的其他部分使用。
工作方式：
Python的垃圾回收器主要基于分代回收 (Generational Collection) 策略。
分代思想：对象被创建后，年轻的对象更容易较早地变成垃圾（因为它们的生命周期短），而存活时间较长的对象则可能继续存活。GC将对象分为三代（第0代、第1代、第2代）。
新创建的对象放入第0代。
在一次第0代回收中存活下来的对象，会被移到第1代。
在一次第1代回收中存活下来的对象，会被移到第2代。
第2代是“老年”对象，回收频率最低。
触发回收：当某一代的对象数量达到一定阈值时，就会触发该代的垃圾回收。通常，第1代和第2代的回收频率远低于第0代。
具体算法：在回收时，GC会识别出那些无法从根对象（如全局变量、栈帧等）到达的循环引用对象组，并将它们标记为垃圾进行回收。
如何触发：可以通过 gc 模块手动触发垃圾回收（如 gc.collect()），也可以查看当前的对象引用关系等。


`内存池 (Memory Pools / Pymalloc)`
目的：为了提高内存分配和释放的速度，减少频繁调用操作系统底层内存管理函数（如 malloc 和 free）带来的开销，并减少内存碎片。
工作方式：Python实现了一套自己的内存分配器，称为 pymalloc。它为不同大小的对象维护了多个内存池。
对于小的Python对象（如整数、短字符串等），pymalloc 会从其管理的内存池中分配和回收内存。这些内存通常在进程的生命周期内被重复使用，而不是每次都归还给操作系统。
对于较大的对象，可能会直接调用操作系统的内存管理函数。
优点：显著提高了小对象内存分配和释放的效率，尤其是在对象生命周期短、创建销毁频繁的情况下（如列表推导式、循环中创建临时对象）。
整数和短字符串的interning
Python为了节省内存和加速比较，会对一些常用的、不可变的小整数（通常是 -5 到 256）和短字符串进行“interning”（内部缓存）。这意味着相同的值只会在内存中存储一份，所有引用该值的变量都指向同一个内存地址。这减少了内存使用，并且 is 操作符（检查是否为同一个对象）对于这些值会更快。
```

#### 79.当退出 Python 时是否释放所有内存分配？

```
Python 的内部内存管理机制（引用计数、垃圾回收、内存池）在程序退出时会尽力释放它所直接管理的对象内存。
但是，操作系统级别的缓存（如文件缓存）不会因为 Python 退出而立即消失。
第三方 C 库或扩展可能存在内存泄漏，这部分内存不会在 Python 退出时被释放。
```


### **正则表达式**

#### 80.使用正则表达式匹配```<html><h1>www.baidu.com</html>```中的地址。

```python
import re
s = '<html><h1>www.baidu.com</html>'
p = re.compile(r'<html><h1>(.*?)</html>')
result = re.findall(p,s)[0]
```

a="张明 98 分"，用 re.sub，将 98 替换为 100

```python
import re
a="张明 98 分"
pa = re.compile(r'\d+')
re.sub(pa,'100',a)
```

#### 81.正则表达式匹配中 (.*) 和 (.**?) 匹配区别？

```
加？会将贪婪模式改成懒惰模式,如果有问号的话，则表示匹配0个或1个问号前面的表达式
```

#### 82.写一段匹配邮箱的正则表达式。

```python
r'[0-9a-zA-Z_]*@.+\.(com|cn|net)$'
```



### **其他内容**

#### 83.解释一下 Python 中 pass 语句的作用。

```markdown
Python pass 是空语句，是为了保持程序结构的完整性。

pass 不做任何事情，一般用做占位语句。
```

#### 84.简述你对 input() 函数的理解。

```
在python3中，input()获取用户输入，不论用户输入的是什么，获取到的都是字符串类型的。
```

#### 85.Python 中的 is 和 == 有什么区别？

```markdown
is比较的是两个对象的id值是否相等，也就是比较两个对象是否为同一个实例对象，是否指向同一个内存地址。

==比较的是两个对象的内容是否相等，默认会调用对象的__eq__()方法。
```

#### 86.Python 中的作用域有哪些？

```python
L （Local） 局部作用域
E （Enclosing） 闭包函数外的函数中
G （Global） 全局作用域
B （Built-in） 内建作用域
```

#### 87.三元运算写法和应用场景。

```python
条件语句比较简单时可以使用三元运算符，最常见的就是 
res = 'test True' if expression is True else 'test False'
```

#### 88.了解 enumerate 吗？

```python
# 遍历列表时候，携带索引index
a = ['a','b','c']
for index,item in enumerate(a):
    print(index,item)
```

#### 89.列举 5 个 Python 中的标准模块。

```python
json,re,random,datetime,codecs
```

#### 90.如何在函数中设置一个全局变量？

```Python
使用global关键字
```

#### 91.pathlib 的用法举例。

```python
from pathlib import Path

data_folder = Path("source_data/text_files/")

file_to_open = data_folder / "raw_data.txt"

f = open(file_to_open)

print(f.read())
```

#### 92.请对 Python 中的异常处理写一个简单的应用场景。

```Python
class NameTooShortError(ValueError): 
    pass
def validate(name):
    if len(name) < 10:
        raise NameTooShortError(name)
        
# 使用自定义异常类，使得发生异常时的错误更容易排查
```

#### 93.Python 中递归的最大次数是多少？如何突破？

```pyhton
python解释器限制最大的递归深度是999，可以通过
import sys
sys.setrecursionlimit(10000)  # set the maximum depth as 10000
重新设置最大递归深度
```

#### 94.什么是面向对象的 MRO？

```
对于支持继承的编程语言来说，其方法（属性）可能定义在当前类，也可能来自于基类，所以在方法调用时就需要对当前类和基类进行搜索以确定方法所在的位置。
而搜索的顺序就是所谓的「方法解析顺序」（Method Resolution Order，或MRO）。对于只支持单继承的语言来说，MRO 一般比较简单；
而对于 Python 这种支持多继承的语言来说，MRO 就复杂很多。
```

#### 95.简述 isinstance 的作用以及应用场景。

```python
来判断一个对象是否是一个已知的类型
举个栗子：
 p= 'sfa'
 isinstance(p,str)
 True
```

#### 96.什么是断言？并描述一个应用场景。

```python
Python 的断言语句是一种调试工具，用来测试某个断言条件。如果断言条件 为真，则程序将继续正常执行;但如果条件为假，则会引发 AssertionError 异常并显示相关 的错误消息。
```

#### 97.lambda 表达式格式以及应用场景。
lambda 参数1, 参数2, ... : 表达式
```python
d = {'a':2,'b':1,'c':3,'d':'4'}
sorted(d,key=lambda x :x[1]) 
# 将字典d按照值排序
```

#### 98.新式类和旧式类的区别有哪些？

```
Python 有两种类：经典类（classic class）和新式类（new-style class）。两者的不同之处在于新式类继承自 object。
在 Python 2.1 以前，经典类是唯一可用的形式；
在Python 2.2 引入了新式类，使得类和内置类型更加统一；
在 Python 3 中，新式类是唯一支持的类。
```

#### 99.dir() 是用来干什么的？

```
dir() 函数不带参数时，返回当前范围内的变量、方法和定义的类型列表；
带参数时，返回参数的属性、方法列表。如果参数包含方法__dir__()，该方法将被调用。如果参数不包含__dir__()，该方法将最大限度地收集参数信息。
```

#### 100.一个包里有三个模块，demo1.py、demo2.py 和 demo3.py，但使用 from tools import * 导入模块时，如何保证只有 demo1、demo3 被导入？

```python
但若想使用from pacakge_1 import *这种形式的写法，需在  init.py中加上：   all = [‘file_a’, ‘file_b’] #package_1下有file_a.py和file_b.py，在导入时init.py文件将被执行。 
但不建议在 init.py中写模块，以保证该文件简单。不过可在init.py导入我们需要的模块，以便避免一个个导入、方便使用。
```

#### 101.列举 5 个 Python 中的异常类型以及其含义。

```
1. ArithmeticError 此基类用于派生针对各种算术类错误而引发的内置异常: OverflowError, ZeroDivisionError, FloatingPointError
2. BufferError 当与 缓冲区 相关的操作无法执行时将被引发。
3. LookupError 此基类用于派生当映射或序列所使用的键或索引无效时引发的异常: IndexError, KeyError。 这可以通过 codecs.lookup() 来直接引发
4. ImportError 当 import 语句尝试加载模块遇到麻烦时将被引发。 并且当 from ... import 中的 "from list" 存在无法找到的名称时也会被引发
5. IndexError 当序列抽取超出范围时将被引发。 （切片索引会被静默截短到允许的范围；如果指定索引不是整数则 TypeError 会被引发
```

#### 102.copy 和 deepcopy 的区别是什么？
copy 即所谓的浅拷贝，赋值的时候非递归地复制子对象的引用；
deepcopy 即所谓的深拷贝，赋值的时候递归复制子对象。
举个栗子，
```python

from copy import deepcopy
xs = [1, 2, [2, 3, 4], 3]
print("xs:", xs)
ys = xs  # 浅拷贝
print("ys:", ys)
zs = deepcopy(xs)  # 深拷贝
print("zs:", zs)
xs[2][0] = 5
print("xs:", xs)
print("ys:", ys)
print("zs:", zs)

输出：
xs: [1, 2, [2, 3, 4], 3]
ys: [1, 2, [2, 3, 4], 3]
zs: [1, 2, [2, 3, 4], 3]

xs: [1, 2, [5, 3, 4], 3]
ys: [1, 2, [5, 3, 4], 3]
zs: [1, 2, [2, 3, 4], 3]


```

#### 103.请阐述代码中经常遇到的 *args, **kwargs 的含义及用法。

```
这两个是python中的可变参数
*args 允许你将任意数量的位置参数传递给函数。这些参数在函数内部被收集到一个元组中。
**kwargs 允许你将任意数量的关键字参数传递给函数。这些参数在函数内部被收集到一个字典中。
```
```python
def print_all(*args, **kwargs):
    print("Positional arguments:")
    for arg in args:
        print(arg)
    
    print("\nKeyword arguments:")
    for key, value in kwargs.items():
        print(f"{key}: {value}")

print_all(1, 2, 3, name="Alice", age=25, city="New York")
```

#### 104.Python 中会有函数或成员变量包含单下划线前缀和结尾，或双下划线前缀结尾，它们的区别是什么？

```markdown
前置单下划线_var:命名约定，用来表示该名称仅在内部使用。一般对 Python 解释器没 有特殊含义(通配符导入除外)，只能作为对程序员的提示。
后置单下划线 var_:命名约定，用于避免与 Python 关键字发生命名冲突。
前置双下划线__var:在类环境中使用时会触发名称改写，对 Python 解释器有特殊含义。
前后双下划线__var__:表示由 Python 语言定义的特殊方法。在自定义的属性中要避免
使用这种命名方式。
```

#### 105.简述 w、a+ 和 wb 文件写入模式的区别。

```
w:写入时会覆盖上一次的写入
a+:追加写入
wb:以二进制文件形式写入
```

#### 106.举例 sort 和 sorted 的区别。

```
sort()与sorted()的不同在于，sort是在原位重新排列列表，而sorted()是产生一个新的列表
```

#### 107.什么是负索引？

```
负索引和正索引不同，它是从右边开始检索。例如：使用负索引取出列表的最后一个数
lis[-1] # 取出列表的最后一个元素
lis[-2] # 取出列表的倒数第二个元素
```

#### 108.pprint 模块是干什么的？

```
print()和pprint()都是python的打印模块，功能基本一样，唯一的区别就是pprint()模块打印出来的数据结构更加完整，每行为一个数据结构，更加方便阅读打印输出结果。
特别是对于特别长的数据打印，print()输出结果都在一行，不方便查看，而pprint()采用分行打印输出，所以对于数据结构比较复杂、数据长度较长的数据，适合采用pprint()打印方式
```

#### 109.解释一下 Python 中的赋值运算符。

```
在python中，使用 = 可以给变量赋值。
在算术运算时，为了简化代码的编写，Python还提供了一系列与算术运算符对应的赋值运算符
例如，c += a 等效于 c=c+a

```

#### 110.解释一下 Python 中的逻辑运算符。

```
and, or, not
```

#### 111.讲讲 Python 中的位运算符。

```
&	按位与运算符：参与运算的两个值,如果两个相应位都为1,则该位的结果为1,否则为0	(a & b) 输出结果 12 ，二进制解释： 0000 1100
|	按位或运算符：只要对应的二个二进位有一个为1时，结果位就为1	(a | b) 输出结果 61 ，二进制解释： 0011 1101
^	按位异或运算符：当两对应的二进位相异时，结果为1	(a ^ b) 输出结果 49 ，二进制解释： 0011 0001
~	按位取反运算符：对数据的每个二进制位取反,即把1变为0,把0变为1	(~a ) 输出结果 -61 ，二进制解释： 1100 0011， 在一个有符号二进制数的补码形式。
<<	左移动运算符：运算数的各二进位全部左移若干位，由”<<”右边的数指定移动的位数，高位丢弃，低位补0	a << 2 输出结果 240 ，二进制解释： 1111 0000
>>	右移动运算符：把”>>”左边的运算数的各二进位全部右移若干位，”>>”右边的数指定移动的位数	a >> 2 输出结果 15 ，二进制解释： 0000 1111
```

#### 112.在 Python 中如何使用多进制数字？

```
1、二进制数字由0和1组成，我们使用0b或0B前缀表示二进制数

print(int(0b1010))#10
2、使用bin()函数将一个数字转换为它的二进制形式

print(bin(0xf))#0b1111
3、八进制数由数字0-7组成，用前缀0o或0O表示8进制数

print(oct(8))#0o10
4、十六进数由数字0-15组成，用前缀0x或者0X表示16进制数

print(hex(16))#0x10
print(hex(15))#0xf
 
```

#### 113.怎样声明多个变量并赋值？

```python
a,b = 1,2
```


### **算法和数据结构**

#### 114.已知：

```Python
AList = [1,2,3]
BSet = {1,2,3}
```

##### (1) 从 AList 和 BSet 中 查找 4，最坏时间复杂度那个大？

```
查找列表最坏时间复杂度是O(n),查找字典是O(1)，因为字典的数据结构是散列表
```

##### (2) 从 AList 和 BSet 中 插入 4，最坏时间复杂度那个大？

```
插入的操作都是O(1)
```

#### 115.用 Python 实现一个二分查找的函数。

```python
def binary_search(item,arr):
    start = 0
    end = len(arr) - 1
    while start <= end:
        mid = (start + end) // 2
        if item == arr[mid]:
            return True
        elif item < arr[mid]:
            end = mid - 1
        else:
            start = mid + 1
array = [1,2,3,4,5,6]
print(binary_search(2,array))
```

#### 116.Python 单例模式的实现方法。

```python
单例模式（Singleton Pattern）是一种常用的软件设计模式，该模式的主要目的是确保某一个类只有一个实例存在。当你希望在整个系统中，某个类只能出现一个实例时，单例对象就能派上用场。

比如，某个服务器程序的配置信息存放在一个文件中，客户端通过一个 AppConfig 的类来读取配置文件的信息。如果在程序运行期间，有很多地方都需要使用配置文件的内容，也就是说，很多地方都需要创建 AppConfig 对象的实例，这就导致系统中存在多个 AppConfig 的实例对象，而这样会严重浪费内存资源，尤其是在配置文件内容很多的情况下。事实上，类似 AppConfig 这样的类，我们希望在程序运行期间只存在一个实例对象
1.使用装饰器实现单例模式
def singleton(cls):
    _instance = {}
    def _singleton(*args,**kargs):
        if cls not in _instance:
            _instance[cls] = cls(*args,**args)
        return _instance[cls]
    return _singleton
  
2.使用类实现单例模式
import threading
class Singleton(object):
    _instance_lock = threading.Lock()

    def __init__(self):
        pass


    def __new__(cls, *args, **kwargs):
        if not hasattr(Singleton, "_instance"):
            with Singleton._instance_lock:
                if not hasattr(Singleton, "_instance"):
                    Singleton._instance = object.__new__(cls)  
        return Singleton._instanc
```

#### 117.使用 Python 实现一个斐波那契数列。

```Python
# 很多人上来就写下面这种解法
def fibnaqie(n):
    if n < 2:
        return n
    return fibnaqie(n - 1) + fibnaqie(n - 2)
# 这种解法时间复杂度高，而且一般不是面试官最想要的答案

# 下面这种优化的版本
def fib2(n):
    fib_n = 0
    fib_one = 1
    fib_two = 0
    res = [0, 1]
    if n < 2:
        return res[n]
    for i in range(2, n + 1):
        fib_n = fib_one + fib_two
        fib_two = fib_one
        fib_one = fib_n
    return fib_n
# 所以适当地选择递归还是迭代，要看具体情况，处理树，或者图的遍历的时候，递归还是比迭代优先考虑的
```

#### 118.找出列表中的重复数字。

```python
def find_duplicate(arr):
    not_dup = set()
    dup = set()
    for x in arr:
        if x not in not_dup:
            not_dup.add(x)
        else:
            dup.add(x)
    return dup


if __name__ == '__main__':
    array = [1, 2, 3, 4, 4, 4, 4]
    print(find_duplicate(array))
```

#### 119.找出列表中的单个数字。

```python
a = ['a', 1, 2, 'b']
for x in a:
    if str(x).isdigit():
        print(x)
```

#### 120.写一个冒泡排序。

```python
def bubble_sort(arr):
    n = len(arr)
    if len(arr) < 2:
        return arr
    for i in range(n - 1):
        count = 0
        for j in range(n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]
                count += 1
        if count == 0:
            return arr
    return arr


if __name__ == '__main__':
    arr = [2, 1, 5, 3, 6]
    arr1 = [1, 2, 3, 4, 5]
    print(bubble_sort(arr1))
```

#### 121.写一个快速排序。

```python
def quick_sort(arr):
    if len(arr) < 2:
        return arr
    else:
        pivot = arr[0]
        less = [i for i in arr[1:] if i <= pivot]
        more = [i for i in arr[1:] if i > pivot]
    return quick_sort(less) + [pivot] + quick_sort(more)


if __name__ == '__main__':
    array = [2, 1, 6, 3, 4, 5]
    print(quick_sort(array))

```

#### 122.写一个拓扑排序。

```python
# 使用循环进行拓扑排序
def topoSort(G):
    # 初始化计算被指向节点的字典
    cnt = dict((u, 0) for u in G.keys())
    import pdb;pdb.set_trace()
    # 若某节点被其他节点指向，该节点计算量+1
    for u in G:
        for v in G[u]:
            cnt[v] += 1
    # 收集被指向数为0的节点,此时Q只有一个节点，即起始节点a
    Q = [u for u in cnt.keys() if cnt[u] == 0]
    # 记录结果
    seq = []
    while Q:
        s = Q.pop()
        seq.append(s)
        for u in G[s]:
            cnt[u] -= 1
            if cnt[u] == 0:
                Q.append(u)
    return seq


# 有向无环图的邻接字典
G = {
    'a': {'b', 'f'},
    'b': {'c', 'd', 'f'},
    'c': {'d'},
    'd': {'e', 'f'},
    'e': {'f'},
    'f': {}
}

res = topoSort(G)
print(res)

```

#### 123.用 Python 实现一个二进制计算。

```python
'''
以实现二进制加法为例
给定两个二进制字符串，返回他们的和（用二进制表示）。
输入为非空字符串且只包含数字 1 和 0。
输入: a = “11”, b = “1”
输出: “100”
'''


def binary_plus(a, b):
    a, b = int('0b' + a, 2), int('0b'+b, 2)
    return bin(a + b)[2:]


if __name__ == '__main__':
    a = '11'
    b = '1'
    print(binary_plus(a, b))

# 解释一下，class int(x, base) 
x–字符串或数字 
base–进制数，默认十进制。 
bin()函数返回一个整型int或者长整数long int的二进制表示，bin()运算返回的是二进制。所以前两位是二进制的标志，需要[2:]去除
```

#### 124.有一组 "+" 和 "-" 符号，要求将 "+" 排到左边，"-" 排到右边，写出具体的实现方法。

```python
def some_sort(arr):
    list_a = []
    list_b = []
    for x in arr:
        if x == '+':
            list_a.append(x)
        else:
            list_b.append(x)
    list_a.extend(list_b)
    print(list_a)
    return list_a
```

#### 125.单链表反转。

```python
class ListNode:
    def __init__(self, val):
        self.val = val
        self.next = None


def reverse_node(head):
    p = head
    q = head.next
    head.next = None
    while q:
        r = q.next
        q.next = p
        p = q
        q = r
    head = p
    return head


if __name__ == '__main__':
    l1 = ListNode(3)
    l1.next = ListNode(2)
    l1.next.next = ListNode(1)

    l = reverse_node(l1)
    print(l.val, l.next.val, l.next.next.val)
# 1,2,3
```

#### 126.交叉链表求交点。

```python
'''先遍历两个链表，获知两个链表各自的长度，往后调整较长链表的指针，使之与较短链表的起始指针对齐，然后两个链表同时往后扫描，直至二者的节点相同，证明该节点是相交节点，否则返回 None，表明两个链表不相交，时间复杂度o(n),空间复杂度0(1)'''
class ListNode:
    def __init__(self, val):
        self.val = val
        self.next = None


def solution(head_a, head_b):
    def get_list_length(head):
        len = 0
        while head:
            len += 1
            head = head.next
        return head

    def forward_long_list(long_len, short_len, head):
        delta = long_len - short_len
        while delta and head:
            head = head.next
            delta -= 1
        return head

    def main_func(head_a, head_b):
        head_a_len = get_list_length(head_a)
        head_b_len = get_list_length(head_b)
        if head_a_len > head_b_len:
            head_a = forward_long_list(head_a_len, head_b_len, head_a)
        else:
            head_b = forward_long_list(head_a_len, head_b_len, head_b)
        while head_a and head_b:
            if head_a == head_b:
                return head_a
            head_a = head_a.next
            head_b = head_b.next
        return None

    return main_func(head_a, head_b)


```

#### 127.用队列实现栈。

```python
class Stack:
    def __init__(self):
        self.queue_a = []
        self.queue_b = []

    def push(self, val):
        self.queue_a.append(val)

    def pop(self):
        if len(self.queue_a) == 0:
            return None
          # 核心思想就是留一个元素在队列a中，最后交换队列a,b，再从b中取栈顶元素
        while len(self.queue_a) != 1:
            self.queue_b.append(self.queue_a.pop(0))
        self.queue_a, self.queue_b = self.queue_b, self.queue_a
        return self.queue_b.pop()


test_stack = Stack()
for i in range(5):
    test_stack.push(i)
for i in range(5):
    print(test_stack.pop())

```

#### 128.找出数据流的中位数。

```python
# 中位数是有序列表中间的数。如果列表长度是偶数，中位数则是中间两个数的平均值
# 如果是奇数，则中位数就是中间的数字
def find_zhongwei(arr):
    arr.sort()
    if len(ar) == 0:
        return
    if len(ar) == 1:
        return ar[0]
    mid = len(arr) // 2
    if len(arr) % 2 == 0:
        return (arr[mid - 1] + arr[len(arr) / 2]) / 2
    else:
        return arr[mid]


if __name__ == '__main__':
    ar = [2, 1, 5, 3, 4]
    print(find_zhongwei(ar))

```

#### 129.二叉搜索树中第 K 小的元素。

```python
# 问题本质：对二叉树进行中序遍历，中序排序后，返回第K-1个值
class Solution(object):
    def kthSmallest(self, root, k):
        """
        :type root: TreeNode
        :type k: int
        :rtype: int
        """
        def inorderTraversal(root):
            if root is None:
                return []
            res = []
            res.extend(inorderTraversal(root.left))
            res.append(root.val)
            res.extend(inorderTraversal(root.right))
            return res
        return inorderTraversal(root)[k - 1]

```

### **爬虫相关**

#### 130.在 requests 模块中，requests.content 和 requests.text 什么区别？

```
resp.text返回的是Unicode型的数据。

resp.content返回的是bytes型也就是二进制的数据。
也就是说，如果你想取文本，可以通过r.text。

如果想取图片，文件，则可以通过r.content。

（resp.json()返回的是json格式数据）
```

#### 131.简要写一下 lxml 模块的使用方法框架。

```markdown
Python 标准库中自带了 xml 模块，但是性能不够好，而且缺乏一些人性化的 API，相比之下，第三方库 lxml 是用 Cython 实现的，而且增加了很多实用的功能，可谓爬虫处理网页数据的一件利器。
lxml 大部分功能都存在 lxml.etree中.
可以看一下官方文档，https://lxml.de/index.html
```

#### 132.说一说 scrapy 的工作流程。

![](http://ww4.sinaimg.cn/large/006tNc79gy1g5vk6vdn28j312w0q4dhd.jpg)

#### 133.简述 scrapy 的去重原理。

```Python
1.需要将dont_filter设置为False开启去重，默认是False，开启去重；

2.对于每一个url的请求，调度器都会根据请求得相关信息加密得到一个指纹信息，并且将指纹信息和set()集合中的指纹信息进行比对，如果set()集合中已经存在这个数据，就不在将这个Request放入队列中。如果set()集合中没有存在这个加密后的数据，就将这个Request对象放入队列中，等待被调度
```

#### 134.scrapy 中间件有几种类，你用过哪些中间件？

```
scrapy自带两种中间件，下载器中间件（DownloaderMiddleware）,爬虫中间件（spiderMiddleware）
DownloaderMiddleware的作用是在request之前或者response之后，对spider进行配置处理，例如动态更换ip，更换user-agent,更换cookie等
Spider中间件是介入到Scrapy的spider处理机制的钩子框架，您可以添加代码来处理发送给 Spiders 的response及spider产生的item和request。
```

#### 135.你写爬虫的时候都遇到过什么反爬虫措施，你是怎么解决的？

```
可以看看这篇博文https://blog.csdn.net/weixin_33768481/article/details/87273454
```

#### 136.为什么会用到代理？

```
单一ip频繁重复请求同一个网站会被封掉
```

#### 137.代理失效了怎么处理？

```
构建代理池，动态更换ip
```

#### 138.列出你知道 header 的内容以及信息。

```
user-agent
referer
content-type
content-length
.....
详情可以看这篇https://kb.cnblogs.com/page/92320/
```

#### 139.说一说如何打开浏览器访问 www.baidu.com 获取到结果，简述整个流程。

```
可参考这篇博文https://www.jianshu.com/p/d616d887953a
```

#### 140.爬取速度过快时，出现了验证码怎么处理？

```
比较简单的验证码，可以用Python的PIL库（from PIL import Image）,tesserocr模块；
比较复杂的话可以引入机器学习模型，但是成本会比较高，最好还是使用高质量的代理ip，避免触发验证码。
```

#### 141.scrapy 和 scrapy-redis 有什么区别？为什么选择 redis 数据库？

```
1) scrapy是一个Python爬虫框架，爬取效率极高，具有高度定制性，但是不支持分布式。而scrapy-redis一套基于redis数据库、运行在scrapy框架之上的组件，
可以让scrapy支持分布式策略，Slaver端共享Master端redis数据库里的item队列、请求队列和请求指纹集合。

2) 为什么选择redis数据库，因为redis支持主从同步，而且数据都是缓存在内存中的，所以基于redis的分布式爬虫，对请求和数据的高频读取效率非常高。
```

#### 142.分布式爬虫主要解决什么问题？

```
1)ip

2)带宽

3）cpu

4）io
```

#### 143.写爬虫是用多进程好还是多线程好？ 为什么？

```
IO密集型代码(文件处理、网络爬虫等)，多线程能够有效提升效率(单线程下有IO操作会进行IO等待，造成不必要的时间浪费，而开启多线程能在线程A等待时，自动切换到线程B，可以不浪费CPU的资源，从而能提升程序执行效率)。
在实际的数据采集过程中，既考虑网速和响应的问题，也需要考虑自身机器的硬件情况，来设置多进程或多线程
```

#### 144.解析网页的解析器使用最多的是哪几个？

```
xpath,css-selector,beautifulSoup
```

#### 145.需要登录的网页，如何在不使用动态爬取的情况下解决 ip、cookie 和 session（其中有一些是动态生成的）的同时限制？

```
解决限制IP可以使用代理IP地址池、服务器；

不适用动态爬取的情况下可以使用反编译JS文件获取相应的文件，或者换用其他平台（比如手机端）看看是否可以获取相应的json文件
```

#### 146.验证码的解决。

```
图形验证码：干扰、杂色不是特别多的图片可以使用开源库Tesseract进行识别，太过复杂的需要借助第三方打码平台

点击和拖动滑块验证码可以借助selenium、无图形界面浏览器（chromedirver或者phantomjs）和pillow包来模拟人的点击和滑动操作，pillow可以根据色差识别需要滑动的位置
```

#### 147.使用的最多的数据库（mysql，mongodb，redis 等）有哪些？并简述对它的理解？

```
这个自由发挥了，多看下MySQL和MongoDB的使用，了解Redis的基本数据结构
```

### **网络编程**

#### 148.TCP 和 UDP 的区别有哪些？

| 特性         | TCP (传输控制协议)                                     | UDP (用户数据报协议)                                     |
| :----------- | :----------------------------------------------------- | :------------------------------------------------------- |
| **连接性**   | **面向连接**。在数据传输前必须建立连接（三次握手），传输结束后要释放连接（四次挥手）。 | **无连接**。发送数据前不需要建立连接，直接发送数据报。             |
| **可靠性**   | **高可靠性**。通过序列号、确认应答、超时重传、流量控制和拥塞控制等机制确保数据按序、无差错、不丢失地到达。 | **不可靠**。不保证数据到达、不保证顺序、不保证不丢失。发送即忘（Send-and-Forget）。 |
| **传输方式** | **流式传输**。将应用层的数据视为字节流，按顺序传输，接收方按顺序接收。 | **数据报式传输**。将应用层的数据封装成独立的数据报（Datagram）发送，每个数据报独立处理，可能乱序到达。 |
| **速度/效率** | **速度相对较慢**。由于需要建立连接、确认应答、重传等机制，有一定的开销。 | **速度快，效率高**。没有连接建立和确认应答等开销，延迟低。         |
| **头部开销** | **较大**。TCP头部通常为20字节（最小）到60字节（最大），包含序列号、确认号、窗口大小等信息。 | **较小**。UDP头部固定为8字节，只包含源端口、目的端口、长度和校验和。 |
| **拥塞控制** | **有**。内置拥塞控制算法（如慢启动、拥塞避免），根据网络状况动态调整发送速率，避免网络拥塞。 | **无**。不进行拥塞控制，发送速率由应用程序决定，可能在网络拥塞时加剧问题。 |
| **流量控制** | **有**。使用滑动窗口机制，让发送方根据接收方的处理能力调整发送速率，防止接收方被淹没。 | **无**。不进行流量控制，如果接收方处理不过来，数据可能会丢失。       |
| **适用场景** | 需要高可靠性、数据完整性和顺序性的应用，如：<br> - Web浏览 (HTTP/HTTPS)<br> - 文件传输 (FTP)<br> - 电子邮件 (SMTP/POP3/IMAP)<br> - 远程登录 (SSH/Telnet) | 对实时性要求高、能容忍少量丢包的应用，如：<br> - 实时视频/音频流 (如直播、视频会议)<br> - 在线游戏<br> - DNS域名解析<br> - DHCP动态主机配置<br> - VoIP语音通话 |
**总结:**
*   **TCP** 像是打电话寄快递，你得先打通电话（建立连接），确认对方收到后才能继续说下一句（确认应答），如果没听到会重说（重传），确保信息准确无误地按顺序传到对方那里。适合重要、需要保证完整性的通信。
*   **UDP** 像是扔纸飞机或发短信，你随手就扔出去了（无连接），也不管对方收到没（不保证可靠），速度快，但可能丢，也可能先到后到。适合对速度要求高、能容忍偶尔丢包的实时通信。
选择使用 TCP 还是 UDP 取决于具体的应用需求，是在可靠性和速度之间做出权衡。


#### 149.简要介绍三次握手和四次挥手。

```p
https://mp.weixin.qq.com/s/jLkhjM7wOpZuWgJdAXis1A
这篇博文讲的不错，可以参考一下

另外，time_wait状态的作用在面试中也是常问的，可以参考下面这篇，https://www.iteblog.com/archives/169.html
```

#### 150.什么是粘包？ socket 中造成粘包的原因是什么？ 哪些情况会发生粘包现象？

```
基于TCP的socket编程中，发送端为了将多个发往接收端的包，更有效的发到对方，使用了优化方法（Nagle算法），将多次间隔较小、数据量小的数据包，合并成一个大的数据包发送(把发送端的缓冲区填满一次性发送)

造成粘包的原因：
1 发送端需要等缓冲区满才发送出去，造成粘包
2 接收方不及时接收缓冲区的包，造成多个包接收

```
### **并发**

#### 151.举例说明 conccurent.future 的中线程池的用法。

```python
concurrent.futures模块的基础是Exectuor，Executor是一个抽象类，它不能被直接使用。但是它提供的两个子类ThreadPoolExecutor和ProcessPoolExecutor却是非常有用，顾名思义两者分别被用来创建线程池和进程池的代码。我们可以将相应的tasks直接放入线程池/进程池，不需要维护Queue来操心死锁的问题，线程池/进程池会自动帮我们调度。
example1.py


from
concurrent.futures
import
ThreadPoolExecutor


import
time


def
return_future_result(message):


    time.sleep(2)


    return
message


pool
=
ThreadPoolExecutor(max_workers=2)  #
 创建一个最大可容纳2个task的线程池


future1
=
pool.submit(return_future_result,
("hello"))  #
 往线程池里面加入一个task


future2
=
pool.submit(return_future_result,
("world"))  #
 往线程池里面加入一个task


print(future1.done())  #
 判断task1是否结束


time.sleep(3)


print(future2.done())  #
 判断task2是否结束


print(future1.result())  #
 查看task1返回的结果


print(future2.result())  #
 查看task2返回的结果
```

#### 152.说一说多线程，多进程 和 协程 的区别。
好的，多线程、多进程和协程是并发编程中常用的三种模型，它们在实现方式、资源占用、切换开销和适用场景上都有显著的区别。
以下是它们的主要区别，以表格形式呈现：
| 特性         | 多进程 (Multi-Process)                       | 多线程 (Multi-Thread)                         | 协程 (Coroutine) / 轻量级线程                |
| :----------- | :------------------------------------------- | :-------------------------------------------- | :------------------------------------------ |
| **基本单位** | 进程 (Process)                               | 线程 (Thread)                                | 协程 (Coroutine)                            |
| **资源占用** | **高**。每个进程拥有独立的内存空间（地址空间）、文件描述符等资源。创建和销毁进程开销大。 | **中**。多个线程共享同一进程的内存空间和资源。创建和销毁线程开销小于进程。 | **极低**。协程是用户态的轻量级线程，共享相同的地址空间，创建和切换开销非常小。 |
| **切换开销** | **大**。进程切换需要切换内存映射、寄存器等，由操作系统内核完成，涉及用户态到内核态的切换。 | **中**。线程切换只需切换寄存器、栈指针等，但也需要内核参与，涉及用户态到内核态的切换。 | **极小**。协程的切换由用户程序控制（协作式），在用户态完成，不涉及内核态切换，速度极快。 |
| **内存共享** | **不共享**。进程间通信 (IPC) 需要特殊机制，如管道、消息队列、共享内存、套接字等，相对复杂。 | **共享**。线程间可以方便地共享数据，但也容易引发竞态条件（Race Condition），需要同步机制（锁、信号量等）。 | **共享**。通常在同一个线程内运行，共享该线程的内存空间，切换时无需保存/恢复太多状态。 |
| **隔离性**   | **高**。一个进程崩溃通常不会影响其他进程。           | **低**。一个线程的错误（如非法内存访问）可能导致整个进程崩溃。       | **低**。协程运行在同一个线程中，一个协程的错误可能影响同一线程中的其他协程。 |
| **CPU 利用** | 操作系统调度，可以真正利用多核CPU实现并行。           | 操作系统调度，可以真正利用多核CPU实现并行（如果进程是多线程的）。但在单核上，线程也是并发（快速切换给人的错觉）。 | **不是并行**。协程本身不是被操作系统调度的，不能利用多核并行。它是在单线程内通过协作让出CPU，实现并发（Concurrency），提高单线程的吞吐量。 |
| **编程模型** | 相对简单，进程间隔离好，但通信复杂。                 | 相对复杂，需处理同步和锁，避免竞态条件。通信方便。           | 非常简单，类似写顺序代码，需要协作点（如 `yield`, `await`）。 |
| **适用场景** | CPU密集型任务、需要隔离的任务、利用多核并行。         | I/O密集型任务、需要共享状态的并发任务、利用多核并行。       | I/O密集型任务、需要高并发的网络服务（如 Web 服务器）、异步编程。 |
**总结:**
1.  **多进程**：像同时打开多个独立的程序，每个程序有自己的内存和资源，互不干扰。开销大，但最稳定，能利用多核。适合需要隔离的任务。
2.  **多线程**：像在一个程序里同时做多件事情（比如前台显示界面，后台计算），它们共享程序的内存。开销中等，通信方便，但一个线程出问题可能搞垮整个程序。适合需要共享数据且能利用多核的任务。
3.  **协程**：像在一个线程里，代码自己主动暂停（协作）让出CPU，让其他协程运行，然后又可以继续。开销极小，切换快，适合处理大量并发但计算量不大的任务（如网络请求），能极大提高单线程的效率。不能利用多核并行，但能实现高并发。
选择哪种模型取决于你的具体需求：是需要强大的并行计算能力（多进程/多线程），还是需要极高的并发效率和低开销（协程）。通常，I/O密集型任务更适合协程或多线程，CPU密集型任务更适合多进程或多线程（取决于是否需要共享状态）。



#### 153.简述 GIL。

```
在CPython解释器中，全局解释锁GIL是在于执行Python字节码时为了保护访问Python对象而阻止多个线程执行的一把互斥锁。这把锁的存在在主要是因为CPython解释器的内存管理不是线程安全的。
然而直到今天GIL依旧存在，现在的很多功能已经习惯于依赖它作为执行的保证
由于GIL的存在，当线程被操作系统唤醒后，必须拿到GIL锁后才能执行代码，也就是说同一时刻永远只有一个线程在执行，这就导致如果我们的程序是CPU密集运算型的任务，那么使用Python多线程是不能提高效率的
```

#### 154.进程之间如何通信？

```
共享内存，信号量，互斥锁，消息队列等
```

#### 155.IO 多路复用的作用？

```
I/O多路复用就通过一种机制，可以监视多个描述符，一旦某个描述符就绪（一般是读就绪或者写就绪），能够通知程序进行相应的读写操作。但select，poll，epoll本质上都是同步I/O，因为他们都需要在读写事件就绪后自己负责进行读写，也就是说这个读写过程是阻塞的，而异步I/O则无需自己负责进行读写，异步I/O的实现会负责把数据从内核拷贝到用户空间
```

#### 156.select、poll 和 epoll 模型的区别。

```
可参考这篇博文，https://www.cnblogs.com/Anker/p/3265058.html
```

#### 157.什么是并发和并行？

简单来说：
*   **并发** 是指**处理**多个任务的能力。它关注的是在一段时间内，系统需要同时处理多个任务，但这些任务可能不是在同一时刻真正地在多个处理单元上执行。
*   **并行** 是指**同时执行**多个任务的能力。它关注的是在同一时刻，系统有多个处理单元在真正地同时执行不同的任务。
下面详细解释：
---
##### 并发 (Concurrency)
1.  **定义**：并发指的是一个时间段内，计算机系统（通常指单个CPU核心）需要处理多个任务，通过某种机制（如时间片轮转、中断等）在这些任务之间进行切换，
   使得从宏观上看，这些任务似乎在同时进行，但从微观的某个极短时间点来看，CPU核心可能只执行其中一个任务。
3.  **核心思想**：**切换** + **重叠**。系统通过快速地在多个任务之间切换，让每个任务都能向前推进一点，从而在整体上实现了“同时处理”多个任务的效果。
4.  **实现方式**：
    *   **多任务操作系统**：这是最常见的并发实现。操作系统调度器会分配CPU时间片给不同的进程或线程，当一个时间片用完或任务阻塞（如等待I/O）时，调度器会切换到另一个任务。
    *   **协程 (Coroutines)**：在单个线程内部，通过协作式调度，让不同的协程可以在需要等待（如I/O）时主动让出控制权，让其他协程运行。
5.  **目的**：
    *   提高资源利用率（CPU不会在某个任务等待时闲着）。
    *   提升用户体验（例如，图形界面程序在执行耗时任务时仍然可以响应用户操作）。
    *   构建能够处理多个客户端请求的服务器。
6.  **例子**：
    *   你在电脑上同时运行了音乐播放器、浏览器和文字处理软件。操作系统通过快速切换CPU时间，让你感觉它们都在运行，但实际上某一刻CPU可能只在做其中一件事。
    *   一个Web服务器处理来自多个客户端的请求，它通过并发机制（如多线程或多路复用I/O）来依次处理这些请求，而不是让后面的请求一直等待。
---
##### 并行 (Parallelism)
1.  **定义**：并行指的是在同一时刻，有多个计算任务同时在不同的处理单元（如CPU核心、GPU核心）上执行。
2.  **核心思想**：**同时执行**。多个任务真正地在不同的物理单元上跑，互不干扰（或者通过同步机制协调）。
3.  **实现方式**：
    *   **多核处理器**：现代CPU通常包含多个核心，每个核心可以独立执行一个线程或进程。
    *   **GPU**：拥有成百上千个处理核心，非常适合大规模并行计算（如图形渲染、机器学习）。
    *   **分布式计算**：利用网络连接的多台计算机共同完成一个任务。
4.  **目的**：
    *   **加速计算**：将一个大的计算任务分解到多个处理单元上同时执行，可以显著缩短总的执行时间。
5.  **例子**：
    *   一个视频编辑软件使用多核CPU同时进行视频编码、解码和特效渲染。
    *   一个科学计算程序将一个大矩阵的运算分解到多个CPU核心上同时计算。
    *   一个机器学习模型训练过程利用GPU的数千个核心并行处理数据。
---
##### 关键区别与联系
| 特性     | 并发 (Concurrency)                  | 并行 (Parallelism)                     |
| :------- | :----------------------------------- | :------------------------------------- |
| **时间点** | 同一时间点通常只做一件事            | 同一时间点做多件事                    |
| **空间**  | 可以在单核上实现                    | 需要多个处理单元（多核、多机）        |
| **本质**  | 处理多个任务的能力（通过切换）      | 同时执行多个任务的能力（物理上同时） |
| **目标**  | 提高响应性、资源利用率              | 提高处理速度、缩短执行时间            |
| **关系**  | 并行是并发的一种特例（物理上同时） | 并行必然是并发（同时处理多个任务）    |
**一个形象的比喻**：
想象你有几项家务要做：洗衣服、做饭、打扫房间。
*   **并发** 就像你：
    *   把衣服放进洗衣机（启动一个任务，然后它自己运行）。
    *   开始做饭，但锅开了需要看一下，然后快速去擦一下桌子，再回来看锅。
    *   在等待水烧开的时候，看看洗衣机有没有好。
    *   你通过在不同的任务之间快速切换，感觉上同时在做几件事，但实际上某一刻你主要在做一件事（比如专心炒菜）。
*   **并行** 就像你：
    *   你自己专心做饭。
    *   你的配偶在同时专心洗衣服。
    *   你的孩子（或者一个机器人）在同时专心打扫房间。
    *   你们三个人（三个处理单元）在同一时间点各自做着不同的家务（不同的任务）。
**联系**：并行是实现并发的一种高效方式。在现代多核处理器上，操作系统可以利用多核实现真正的并行来处理并发任务，这样就能同时执行多个任务，而不仅仅是快速切换。
理解这两个概念对于设计高效的软件系统（尤其是网络服务、高性能计算应用等）至关重要。


#### 158.解释什么是异步非阻塞？

```
异步非阻塞 (Asynchronous Non-blocking)
结合以上两点，“异步非阻塞”指的是：

非阻塞: 调用者发起一个操作请求后，可以立即返回，继续执行后续的代码，不会被这个操作卡住。
异步: 操作的实际执行和完成是独立于调用者当前执行流程的。操作会在后台进行，完成后通过回调函数、事件监听、Future/Promise 等机制通知调用者。
核心优势：

这种模式特别适合处理大量I/O密集型任务（如网络请求、文件读写），因为这些任务通常需要等待外部资源（网络响应、磁盘读写完成），如果使用同步阻塞的方式，线程在等待期间是“空转”的，浪费了宝贵的计算资源。
```

#### 159.简述 threading.local 的作用。

```
Python提供了 threading.local 类，将这个类实例化得到一个全局对象，但是不同的线程使用这个对象存储的数据其它线程不可见(本质上就是不同的线程使用这个对象时为其创建一个独立的字典)
```



### **Git 面试题**

#### 160.说说你知道的 git 命令。
| 功能描述         | 命令                     | 说明                                                                 |
|------------------|--------------------------|----------------------------------------------------------------------|
| **初始化与配置** | `git init`               | 在当前目录初始化一个新的 Git 仓库                                   |
|                  | `git clone <url>`        | 克隆（复制）一个已有的远程仓库到本地                                 |
|                  | `git config --global user.name "Your Name"` | 设置全局用户名                                                       |
|                  | `git config --global user.email "your.email@example.com"` | 设置全局用户邮箱                                                     |
| **状态与查看**   | `git status`             | 查看工作目录和暂存区的状态，哪些文件被修改、新增或删除，以及暂存情况 |
|                  | `git log`                | 查看提交历史记录                                                     |
|                  | `git log --oneline`      | 以简洁的一行形式查看提交历史                                       |
|                  | `git log --graph --oneline --all` | 以图形方式查看分支历史和合并情况                                   |
|                  | `git show <commit_hash>` | 查看特定提交的详细信息（修改内容等）                               |
|                  | `git diff`               | 查看工作目录与暂存区之间的差异                                     |
|                  | `git diff --staged`      | 查看暂存区与上次提交之间的差异                                     |
| **工作区与暂存区** | `git add <file>`         | 将工作区的文件添加到暂存区（跟踪新文件或暂存修改）                   |
|                  | `git add .`              | 将工作区所有修改（包括新文件和已跟踪文件的修改）添加到暂存区         |
|                  | `git rm <file>`          | 删除工作区文件，并提交到暂存区（相当于取消跟踪并删除）               |
|                  | `git mv <old_name> <new_name>` | 移动或重命名文件/目录，并将其记录到暂存区                           |
| **提交**         | `git commit -m "提交信息"` | 将暂存区的修改提交到当前分支的本地仓库                             |
|                  | `git commit -a -m "提交信息"` | 跳过暂存区，直接将所有已跟踪文件的修改提交（不处理新文件）           |
| **分支管理**     | `git branch`             | 列出本地所有分支                                                     |
|                  | `git branch <branch_name>` | 创建一个新的本地分支                                               |
|                  | `git checkout <branch_name>` | 切换到指定的分支                                                   |
|                  | `git checkout -b <branch_name>` | 创建并立即切换到新分支                                             |
|                  | `git branch -d <branch_name>` | 删除指定的本地分支（通常只能删除已完全合并的分支）                   |
|                  | `git merge <branch_name>` | 将指定分支合并到当前分支                                             |
|                  | `git branch -m <new_name>` | 重命名当前分支                                                     |
| **远程仓库**     | `git remote -v`          | 查看远程仓库的名称和地址                                             |
|                  | `git remote add origin <url>` | 添加一个新的远程仓库别名（如 origin）                             |
|                  | `git pull origin <branch_name>` | 从远程仓库拉取最新代码并合并到当前分支（相当于 `git fetch` + `git merge`） |
|                  | `git push origin <branch_name>` | 将当前分支的提交推送到远程仓库                                     |
|                  | `git fetch origin`       | 从远程仓库获取最新代码，但不合并到当前分支                         |
| **撤销与重置**   | `git checkout -- <file>` | 取消工作区对指定文件的修改（丢弃未暂存的修改）                     |
|                  | `git reset HEAD <file>`  | 将指定文件从暂存区移回工作区（取消暂存）                           |
|                  | `git reset --hard <commit_hash>` | 将当前分支重置到指定的提交，丢弃该提交之后的所有提交（谨慎使用！） |
|                  | `git revert <commit_hash>` | 创建一个新的提交，内容是撤销指定提交所做的更改（推荐用于撤销已推送的提交） |
|                  | `git clean -fd`          | 删除工作目录中所有未被跟踪的文件和目录（`-f` 强制，`-d` 删除目录）   |


