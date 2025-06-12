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
```markdown
 **添加元素**：
- append(item)：在列表末尾添加一个元素。
- extend(iterable)：将可迭代对象中的所有元素添加到列表末尾。
- insert(index, item)：在指定位置插入元素。
**删除元素**：
- remove(item)：删除列表中的第一个匹配项。
- pop(index)：删除指定位置的元素，并返回它。如果不指定索引，则删除并返回最后一个元素。
- clear()：清空列表。
**访问元素**：
- index(item)：返回列表中第一个匹配项的索引。
- count(item)：返回列表中某元素的个数。
**排序**：
- sort()：对列表进行原地排序。
- reverse()：反转列表中元素的位置。

**复制**：
- copy()：返回列表的浅复制。
**其他操作**：
- len(list)：返回列表的长度。
- min(list)、max(list)：返回列表中的最小值和最大值。
- sum(list)：返回列表中所有元素的总和（仅适用于数字列表）。
- list(iterable)：将可迭代对象转换为列表。
- in 关键字：检查元素是否在列表中。
- 列表切片：例如 list[1:3] 返回列表中从索引1到索引2的元素。
**列表推导式**：
- 提供了一种简洁的方式来创建列表。例如，[x**2 for x in range(10)] 创建一个包含0到9的平方的列表。

```

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
```markdown

搜索历史对话/智能体
ChatGLM
AI搜索
AI画图
AI阅读
Beta
AutoGLM沉思
清影-AI生视频
清言PPT
数据分析
最近对话

python 是一种解释型语言，什么是解释型
git忽略文件
import torch.functional as F 在 'functional.py' 中找不到引用 'max_pool2d'
用户进程表建表语句如下： CREATE TABLE vd.vd_process_test_flc ( createtime timestamp NULL, nodeid varchar(64) NULL, "time" timestamp NULL, uuid varchar(255) NULL, "source" int2 NULL, "name" varchar(255) NULL, pid float4 NULL, "type" int2 NULL, cpu float4 NULL, mem float4 NULL, handle int4 NULL, groupid varchar(255) NULL, message varchar(512) NULL, vops_insert_time timestamp NULL ) PARTITION BY RANGE (createtime); 用户信息表建表语句如下： CREATE TABLE vd.user_info_test_flc ( uuid varchar(255) NOT NULL, user_name varchar(255) NULL, working_years int4 NOT NULL DEFAULT 0, is_vip int4 NULL DEFAULT 0, working_place varchar(255) NULL, job_position varchar(255) NULL, dept_id varchar(255) NULL, node_id varchar(255) NULL, email varchar(255) NULL, telephone varchar(255) NULL, update_time timestamptz NULL, CONSTRAINT user_info_test_flc_pkey PRIMARY KEY (uuid) ); 现在需要做查询性能测试，请仿照下述方式生成查询语句，要求覆盖普通查询、条件查询、分组聚合、关联查询等各种场景： 示例： "Q1": f"select uuid, cpu, handle, nodeid from {table_name} limit 1000;", "Q2": f"select uuid, cpu, handle, nodeid from {table_name} where nodeid='node_2'",
不使用浮点类型（FLOAT、DOUBLE） 没有充分的理由，不要使用浮点数。 例如金额可以用分为单位，然后采用 INT。如果依然要以元为单位，可以采用 DECIMAL。 数据库规范如上，为什么
gp_vmem_protect_segworker_cache_limit参数介绍
from torch import Tensor, Generator, strided, memory_format, contiguous_format, strided from typing import List, Tuple, Optional, Union, Any, ContextManager, Callable, overload, Iterator, NamedTuple, Sequence, TypeVar from typing_extensions import Literal from torch._six import inf from torch.types import _int, _float, _bool, Number, _dtype, _device, _qscheme, _size, _layout, SymInt import torch import builtins @overload def __and__(input: Tensor, other: Tensor) -> Tensor: ... @overload def __and__(input: Tensor, other: Number) -> Tensor: ...代码解释
数据库字段类型为int，长度为8其范围是多少
翻译Use gp_vmem_protect_limit to set the maximum memory that the instance can allocate for all work being done in each segment database. Never set this value larger than the physical RAM on the system. If gp_vmem_protect_limit is too high, it is possible for memory to become exhausted on the system and normal operations may fail, causing segment failures. If gp_vmem_protect_limit is set to a safe lower value, true memory exhaustion on the system is prevented; queries may fail for hitting the limit, but system disruption and segment failures are avoided, which is the desired behavior.
详细介绍下述greenPlum数据库参数的作用 gp_vmem_idle_resource_timeout gp_vmem_protect_limit gp_vmem_protect_segworker_cache_limit gp_workfile_limit_files_per_query gp_workfile_limit_per_query gp_workfile_limit_per_segment max_appendonly_tables max_prepared_transactions
全部对话...
智能体中心
云知识库
德鲁大叔
python 是一种解释型语言，什么是解释型
好的，我们来详细解释一下“解释型语言”是什么意思，以及为什么说 Python 是一种解释型语言。

什么是“解释型语言”？

解释型语言（Interpreted Language）指的是一种编程语言的执行方式。它的核心特点是：程序代码在运行时由一个称为“解释器”（Interpreter）的特殊程序直接执行，而不是像编译型语言那样先全部编译成机器码再运行。

可以这样理解这个过程：

源代码：你用 Python 写的 .py 文件，就是源代码。它是由人类可读的文本（如 print("Hello, World!")）组成的。
解释器：当你运行 Python 程序时，你需要先安装 Python 解释器（比如 python.exe 在 Windows 上，或者 python 命令在 Linux/macOS 上）。这个解释器就是专门用来“理解”和“执行” Python 代码的程序。
执行过程：
解释器读取源代码中的一行或多行（具体多少行取决于解释器的实现，但通常不是整个文件）。
它将这一行代码“翻译”成计算机能够理解的指令（通常是某种中间形式，如字节码 Bytecode）。
立即执行这些指令。
然后继续读取下一行代码，重复这个过程，直到程序结束。
与编译型语言的区别

为了更好地理解，我们对比一下编译型语言（如 C, C++, Go, Rust 等）：

编译型语言：
编译阶段：首先，有一个称为“编译器”（Compiler）的程序，它会读取整个源代码文件，将其全部转换成特定计算机架构可以直接执行的机器码（或接近机器码的目标代码）。
生成可执行文件：编译完成后，会生成一个独立的可执行文件（例如 .exe 文件）。
运行阶段：要运行程序时，操作系统直接加载并执行这个可执行文件，不再需要源代码或编译器。
优点：通常执行速度更快，因为机器码是直接运行的。
缺点：开发周期可能较长（需要编译），代码通常不能直接跨平台运行（需要为每个平台重新编译）。
解释型语言：
没有独立的编译阶段：源代码在运行时才被逐行（或逐块）翻译和执行。
需要解释器：程序运行时，必须同时拥有源代码和对应的解释器。
优点：开发调试更方便（修改代码后通常可以直接运行，无需等待编译），更容易实现跨平台（只要目标平台有对应的解释器即可）。
缺点：通常执行速度相对较慢，因为每次运行都需要进行翻译步骤。
Python 是如何“解释”的？—— 一个更精确的图景

严格来说，现代 Python 的执行过程稍微复杂一些，它结合了编译和解释的元素：

编译成字节码：当你运行一个 Python 脚本时，Python 解释器（准确地说是 CPython，即标准的 Python 实现）首先会将你的源代码（.py 文件）编译成一种称为“字节码”（Bytecode）的中间形式。字节码是一种平台无关的低级代码，类似于汇编语言。
解释字节码：然后，一个称为“Python 虚拟机”（Python Virtual Machine, PVM）的组件会解释并执行这些字节码。PVM 可以看作是一个专门运行 Python 字节码的“微型计算机”。
所以，虽然 Python 通常被称为“解释型语言”，但更准确的说法是：Python 是一种“字节码解释型语言”。它先编译源代码为字节码，然后由虚拟机解释执行字节码。

为什么还是常被称为解释型语言？

主要是因为：

源代码到执行的直接性：用户感觉上是从源代码直接运行，中间的编译（到字节码）和解释（字节码）过程对用户是透明的。
依赖解释器：程序运行离不开 Python 解释器（包含编译器和 PVM）。
与编译型语言的对比：相对于需要预先完整编译成机器码的 C 或 C++，Python 的执行方式更符合“解释”的定义。
总结一下“解释型”的核心要点：

逐行/逐块处理：代码不是一次性全部转换，而是运行时逐步处理。
需要解释器：运行时必须有解释器参与。
通常更灵活、开发更快：适合快速原型开发、脚本编写等场景。
因此，说 Python 是一种解释型语言，主要是因为它的执行依赖于解释器在运行时对代码（或其字节码形式）进行翻译和执行，而不是预先完全编译成机器码。

德鲁大叔
jupyter notebook使用的是哪种解释器
Jupyter Notebook 使用的解释器取决于你选择的内核（Kernel）。

最常见的内核是 IPython，它是 Python 的一个交互式 Shell（外壳），提供了比标准 Python 解释器更丰富的功能，比如：

语法高亮
自动补全
内置文档查看
丰富的输入/输出历史记录
更好的错误信息显示
内置的绘图和可视化支持
当你在 Jupyter Notebook 中创建一个新的 Python 笔记本时，默认选择的内核通常是 Python [default]，而这个内核底层运行的就是 IPython 解释器。

总结:

Jupyter Notebook 本身是一个 Web 应用程序框架，它本身不直接包含解释器。它通过加载不同的内核来支持多种编程语言。对于 Python，它主要使用 IPython 作为其解释器，以提供更好的交互式体验。

当然，你也可以在 Jupyter Notebook 中安装和使用其他 Python 内核，或者甚至使用其他语言的内核（如 R、Julia、Scala 等），但这取决于你的具体配置和安装。

德鲁大叔
pypy 和cPython的区别
好的，我们来详细比较一下 PyPy 和 CPython 的主要区别。它们都是 Python 语言的实现，但底层机制和设计目标有所不同。

核心概念：

CPython: 这是最经典、最广泛使用的 Python 实现。它是由 Python 语言本身的创建者 Guido van Rossum 及其团队维护的。它的名字来源于它是用 C 语言编写的。绝大多数 Python 标准库、第三方库都是针对 CPython 设计和编译的。当你安装 Python 时，默认安装的就是 CPython。
PyPy: 这是 Python 语言的另一个实现，它的主要目标是提高 Python 代码的执行速度。PyPy 项目使用了一种称为“即时编译”（Just-In-Time Compilation, JIT）的技术，并且 PyPy 解释器本身是用一种受限的 Python 子集（称为 RPython）编写的，然后 RPython 被编译成机器码。
主要区别：

实现语言与架构：
CPython: 主要用 C 语言编写，Python 代码在 CPython 中是通过解释器逐行解释执行的（虽然它也进行一些优化）。
PyPy: 解释器本身是用 RPython（Restricted Python）编写的，然后被转换成机器码。RPython 是一种静态类型的 Python 子集，这使得编译器可以对其进行更有效的优化。
性能：
CPython: 执行速度相对较慢，因为它主要是解释执行。对于 CPU 密集型任务，性能可能不够理想。
PyPy: 核心优势在于性能。PyPy 内置了 JIT 编译器。JIT 编译器会在程序运行时分析热点代码（频繁执行的代码段），并将它们编译成本地机器码，从而大大提高执行速度。对于许多应用，PyPy 的速度可以比 CPython 快 4 到 6 倍，甚至更快，尤其是在长时间运行的应用中。然而，对于非常短的脚本或 I/O 密集型任务，性能提升可能不那么明显。
内存使用：
CPython: 内存管理相对简单，但有时可能不够高效。
PyPy: 由于其更复杂的垃圾回收机制（如增量垃圾回收），PyPy 在启动时和运行时通常需要更多的内存。这是为了实现其高性能和更好的内存管理特性（例如，处理循环引用更有效）。对于内存非常敏感的应用，这可能是一个需要考虑的缺点。
兼容性：
CPython: 拥有最广泛的兼容性。几乎所有的 Python 标准库和第三方 C 扩展（用 C 语言编写的 Python 模块）都只能在 CPython 上运行。
PyPy: PyPy 的目标是实现与 CPython 的完全兼容。对于纯 Python 代码，兼容性非常好。对于用 C 语言编写的扩展（C extensions），PyPy 通过其 cffi 和 ctypes 模块提供了支持，但并非所有 C 扩展都能完美工作，有时需要进行适配或等待 PyPy 团队更新支持。这是 PyPy 面临的主要挑战之一。
启动时间：
CPython: 启动速度快。
PyPy: 由于需要加载 JIT 编译器并进行一些初始化工作，PyPy 的启动时间通常比 CPython 慢。但对于长时间运行的服务或应用，这个启动时间的代价很快就能通过运行时的速度提升来弥补。
错误报告：
CPython: 错误信息是大家熟悉的样式。
PyPy: PyPy 的错误报告有时可能略有不同，尤其是在涉及内存管理或 C 扩展交互时。
总结：

选择 CPython 的情况：
你需要使用那些尚未被 PyPy 完全兼容的 C 扩展。
你的应用对内存使用非常敏感。
脚本非常短，运行时间极短，启动时间很重要。
你不想处理潜在的兼容性问题，希望使用最稳定、最广泛支持的版本。
选择 PyPy 的情况：
你的应用是 CPU 密集型的，并且需要长时间运行（服务器、后台任务等）。
性能是首要考虑因素，并且你的代码库（包括依赖库）在 PyPy 上运行良好。
你愿意接受稍慢的启动时间和可能稍高的内存消耗以换取运行时的巨大速度提升。
总的来说，PyPy 是一个非常有价值的 Python 实现，特别是在性能优化方面。但随着 PyPy 对 C 扩展兼容性的不断提高，它在更多场景下成为了 CPython 的一个强大替代品。

德鲁大叔
说说你知道的 Python3 和 Python2 之间的区别？
好的，Python 3 和 Python 2 之间存在着许多重要的区别，这些区别使得 Python 3 成为更现代、更一致、更强大的版本。Python 2 在 2020 年 1 月 1 日已经停止官方维护，强烈建议所有用户迁移到 Python 3。

以下是一些主要的区别：

打印函数 (print)
Python 2: print 是一个语句，不是函数。例如：print "Hello World"
Python 3: print 是一个函数，需要使用括号。例如：print("Hello World")。这使得 print 可以接受更多参数，如 sep（分隔符）、end（结束符）等。
整数除法
Python 2: 当两个整数相除时，结果会被截断为整数（地板除）。例如：5 / 2 的结果是 2。
Python 3: 整数相除会得到一个浮点数，结果是精确的除法结果。例如：5 / 2 的结果是 2.5。如果需要地板除，可以使用 // 运算符，例如 5 // 2 结果是 2。
Unicode 字符串
Python 2: 默认字符串是字节串（str），而 Unicode 字符串需要用 unicode 类型或前缀 u 来表示，例如 u"你好"。
Python 3: 所有字符串都是 Unicode 字符串（str 类型），处理文本更简单直观。字节数据使用 bytes 类型。例如："你好" 就是 Unicode 字符串。
xrange vs range
Python 2: 有 range 和 xrange 两个函数。range 生成一个实际的列表，如果范围很大会占用大量内存。xrange 生成一个迭代器，按需生成数字，节省内存。
Python 3: 只有 range，它的工作方式类似于 Python 2 中的 xrange，返回一个惰性求值的范围对象（类似迭代器），不会一次性生成所有数字，内存效率高。Python 2 中的 range 功能可以通过生成列表的列表推导式或 list(range(...)) 来实现。
异常处理语法
Python 2: 捕获异常的语法是：try...except ExceptionType, e:。
Python 3: 捕获异常的语法是：try...except ExceptionType as e:。更清晰，避免了变量名冲突。
字典方法
Python 2: 字典的 iterkeys()、itervalues()、iteritems() 方法返回迭代器，用于节省内存。
Python 3: 移除了 iterkeys()、itervalues()、iteritems()，直接使用 keys()、values()、items() 方法，它们现在也返回视图对象（view objects），类似于迭代器，是动态的，更能反映字典的当前状态。
input() vs raw_input()
Python 2: raw_input() 读取输入并将其作为字符串返回。input() 实际上会执行 eval(raw_input(prompt))，即尝试将输入解析为 Python 表达式。
Python 3: 移除了 raw_input()，只保留 input()，它的行为与 Python 2 中的 raw_input() 相同，总是返回字符串。如果需要其他类型，需要手动转换（如 int(input())）。
模块重命名和移除
Python 3 对许多标准库模块进行了重命名或移除，引入了新的模块，以使结构更清晰、命名更一致。例如：
Queue -> queue
ConfigParser -> configparser
Tkinter -> tkinter
移除了 httplib, cookielib 等，统一到 http.client 和 http.cookiejar。
新增了 asyncio 模块用于异步 I/O。
range、map、filter 等的返回类型
Python 2: map() 和 filter() 返回列表。range() 返回列表。
Python 3: map() 和 filter() 返回迭代器。range() 返回范围对象。这更节省内存，尤其适用于大数据处理。
函数参数语法
Python 3 增加了对关键字-only 参数 (*args 后的参数必须用关键字指定) 和仅限关键字参数 (*, param) 的支持。
整数类型
Python 3 的 int 类型是统一且无大小限制的（仅受内存限制），取代了 Python 2 中的 int（有固定大小，通常 32 或 64 位）和 long（任意精度长整数）。Python 3 中不再需要区分 int 和 long。
round 函数的行为
Python 2: round(2.675, 2) 可能会返回 2.67 或 2.68，因为浮点数精度问题。
Python 3: round 函数采用“银行家舍入法”（四舍六入五成双），即当小数部分为 0.5 时，会向最近的偶数舍入。例如 round(2.675, 2) 会返回 2.68，round(2.5) 返回 2，round(3.5) 返回 4。
这些只是其中的一部分主要区别。Python 3 的设计目标是为了解决 Python 2 中的一些长期存在的痛点，并引入了现代化的特性，使其成为一个更强大、更易维护的语言。尽管迁移可能需要一些工作，但长远来看，使用 Python 3 是更好的选择。

德鲁大叔
5.Python3 和 Python2 中 int 和 long 的区别？
好的，我们来详细说说 Python 2 和 Python 3 中 int 和 long 类型的区别。

Python 2 中的 int 和 long

在 Python 2 中，整数类型分为两种：

int (整数):
这是一种固定大小的整数类型。它的大小通常与你的操作系统和硬件架构有关（例如，在 32 位系统上通常是 32 位，在 64 位系统上通常是 64 位）。
它的范围是有限的。例如，在 32 位系统上，int 的范围大约是 -2,147,483,648 到 2,147,483,647。超过这个范围就会发生溢出错误。
Python 2 的 int 类似于 C 语言中的 int 或 long 类型。
long (长整数):
这是一种任意精度的整数类型。这意味着它的值可以非常大，只要你的计算机内存允许，理论上没有上限（除了内存限制）。
在 Python 2 中，当你给一个 int 赋予一个超出其范围的值时，Python 会自动将其转换为一个 long 类型。long 类型在表示时会自动在数字末尾添加一个字母 L（大写或小写都可以，但通常用大写 L 以便与数字 1 区分）。
例如：


        # Python 2
        x = 10          # x 是 int 类型
        y = 12345678901234567890  # y 是 long 类型，会自动添加 L
        print y         # 输出: 12345678901234567890L
        z = 2**100      # z 是 long 类型
        print z         # 输出: 1267650600228229401496703205376L
*   `long` 类型在内部使用不同的表示方法来支持大数运算。
Python 3 中的 int

在 Python 3 中，int 和 long 被统一了。只有一个整数类型，就是 int。

Python 3 的 int 类型完全取代了 Python 2 中的 long 类型。
Python 3 的 int 是任意精度的。它不再有像 Python 2 int 那样的固定大小限制。你可以创建任意大的整数，只要内存允许，都不会自动转换或溢出。
不再有 L 后缀：当你创建一个大整数时，不需要也不应该添加 L 后缀。


    # Python 3
    x = 10          # x 是 int 类型
    y = 12345678901234567890  # y 也是 int 类型，没有 L
    print(y)        # 输出: 12345678901234567890
    z = 2**100      # z 也是 int 类型
    print(z)        # 输出: 1267650600228229401496703205376
Python 3 的 int 类型更简洁，也更符合大多数编程场景的需求，因为你通常不希望因为数字太大而遇到类型转换的问题。
总结:

特性	Python 2	Python 3
整数类型	int (固定大小) 和 long (任意精度)	只有 int (任意精度)
自动转换	int 超出范围会自动转为 long	int 本身就是任意精度，无需转换
表示形式	long 类型数字末尾有 L (如 123L)	没有 L 后缀
范围限制	int 有固定范围，long 理论上无限制(内存够)	int 理论上无限制(内存够)
类型检查	需要检查 isinstance(x, (int, long))	只需检查 isinstance(x, int)
简单来说，Python 3 合并了 Python 2 中的 int 和 long，提供了一个更强大、更一致的整数类型，简化了编程。

德鲁大叔
介绍一下python之禅.
好的，我们来介绍一下“Python之禅”（The Zen of Python）。

“Python之禅”是 Python 语言中一条非常著名且备受推崇的指导原则，它由 Python 的创始人 Guido van Rossum 及其他核心开发者共同编写。它概括了 Python 语言的设计哲学和开发者们所推崇的编程风格。

你可以通过在 Python 解释器中输入 import this 来查看它。

以下是“Python之禅”的内容及其简要解释：



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
总结来说，“Python之禅”强调了：

代码的可读性和简洁性： 鼓励编写清晰、易于理解的代码。
一致性和明确性： 避免模糊不清的表达，保持风格统一。
实用主义： 在理论 purity 和实际 applicability 之间找到平衡。
错误处理： 不要忽视错误，要妥善处理。
避免过度设计： 优先选择简单直接的方法。
这些原则深刻地影响了 Python 语言的设计和社区的开发习惯，使得 Python 以其优雅、清晰和强大的表达能力而闻名。理解并遵循“Python之禅”有助于写出更符合 Python 风格、更易于维护和协作的优秀代码。

德鲁大叔
介绍一下docstring
好的，我们来介绍一下 Python 中的 docstring（文档字符串）。

什么是 Docstring？

Docstring 是 Python 中一种特殊的字符串，它出现在函数、方法、类或模块的开头，用于记录其用途、功能、参数、返回值、作者、示例等信息。它不是注释（虽然它的内容与注释类似），而是代码的一部分，并且可以通过 Python 的内置函数 help() 或对象的 .__doc__ 属性来访问。

为什么使用 Docstring？

自动生成文档： 这是 Docstring 最主要的优势。许多工具（如 Sphinx、pydoc）可以解析代码中的 Docstring，自动生成格式化的、详细的代码文档（如 HTML 文档、PDF 手册等），大大减轻了手动编写和维护文档的工作量。
代码自解释： 好的 Docstring 能让其他开发者（或未来的你自己）快速理解这段代码是做什么的，如何使用它，以及需要注意什么，而无需深入阅读实现细节。
IDE 支持： 现代集成开发环境（IDE）和代码编辑器（如 PyCharm, VS Code）通常能识别 Docstring，并在你调用函数或方法时提供参数提示和说明，提升开发效率。
代码可维护性： 清晰的文档有助于代码的长期维护和团队协作。
如何编写 Docstring？

Docstring 必须是字符串字面量，并且紧随被注释对象（函数、类、模块等）的定义之后，没有其他代码行。



def calculate_area(radius):
    """计算圆的面积。

    这是一个简单的函数，根据给定的半径计算圆的面积。

    Args:
        radius (float): 圆的半径，必须为正数。

    Returns:
        float: 计算得到的圆的面积。

    Raises:
        ValueError: 如果半径不是正数。
    """
    if radius <= 0:
        raise ValueError("半径必须为正数")
    return 3.141592653589793 * radius ** 2
Docstring 的结构（常用风格 - NumPy/Google 风格）：

虽然 Docstring 没有严格强制统一格式，但社区中存在一些广泛接受的风格指南，如 NumPy 风格、Google 风格、reStructuredText 风格等。它们通常包含以下部分（根据需要）：

概述/摘要行： 第一行是对对象用途的简短描述，以句号、问号或感叹号结尾。如果需要，可以换行并添加更详细的说明。
参数 (Args/Parameters)： 列出函数或方法的所有参数，包括参数名和类型，并简要说明其含义。
返回值 (Returns)： 说明函数返回什么，包括返回值的类型和含义。
异常 (Raises)： 说明函数可能抛出的异常及其原因。
示例 (Examples)： 提供使用该函数/方法的代码示例，通常使用 >>> 符号（模仿 Python 交互式解释器的输入）。
上面的例子使用的是类似 NumPy/Google 的风格：

第一行是摘要。
Args: 部分描述了参数。
Returns: 部分描述了返回值。
Raises: 部分描述了可能抛出的异常。
如何访问 Docstring？

你可以使用 help() 函数或访问 .__doc__ 属性来查看对象的 Docstring。



# 使用 help() 函数
help(calculate_area)

# 访问 .__doc__ 属性
print(calculate_area.__doc__)
执行上述代码，你会看到 calculate_area 函数的完整 Docstring 内容。

总结：

Docstring 是 Python 中一种重要的文档记录方式，它将文档直接嵌入到代码中，不仅有助于自动生成高质量文档，还能提升代码的可读性、可维护性和开发效率。编写清晰、规范的 Docstring 是编写专业 Python 代码的良好实践。

德鲁大叔
介绍一下类型注解
好的，我们来介绍一下 Python 中的类型注解（Type Annotations）。

什么是类型注解？

类型注解是 Python 3.5 引入的一个特性，它允许你为变量、函数参数和返回值指定预期的数据类型。这些注解是可选的，并且默认情况下 Python 解释器在运行时不会强制执行这些类型。它们主要是为了静态类型检查和代码可读性而设计的。

为什么使用类型注解？

提高代码可读性和可维护性：明确地看到变量、参数和返回值的预期类型，可以让代码逻辑更清晰，更容易理解。特别是对于大型项目或团队协作，这非常有帮助。
静态类型检查：虽然 Python 是动态类型语言，但你可以使用像 mypy、pyright、pylint（部分支持）这样的静态类型检查工具。这些工具会在代码运行之前扫描代码，根据你提供的类型注解来检查类型是否可能不匹配（例如，将字符串传递给期望整数参数的函数），从而在开发早期发现潜在的错误。
更好的 IDE 和编辑器支持：现代 Python IDE（如 PyCharm, VS Code）可以利用类型注解提供更智能的代码补全、跳转定义、重构建议以及参数提示等功能。
文档作用：类型注解本身也起到了一定的文档作用，说明了某个函数期望接收什么类型的输入以及会返回什么类型的输出。
如何使用类型注解？

Python 使用 : 后跟类型来注解变量和函数参数，使用 -> 后跟类型来注解函数的返回值。

1. 变量注解：



age: int = 25
name: str = "Alice"
is_active: bool = True
prices: list[float] = [10.5, 20.3, 15.0]  # Python 3.9+ 可以直接用 list[float]
# Python 3.8 及更早版本需要从 typing 模块导入
from typing import List, Dict, Tuple
prices_legacy: List[float] = [10.5, 20.3, 15.0]
coordinates: Tuple[int, int] = (10, 20)
person: Dict[str, str] = {"name": "Bob", "city": "New York"}
2. 函数参数和返回值注解：



from typing import List, Optional  # Python 3.8 及更早版本需要导入

def greet(name: str, times: int = 1) -> str:
    """打印问候语多次并返回结果字符串"""
    result = ""
    for _ in range(times):
        result += f"Hello, {name}!\n"
    return result

def find_index(lst: List[int], target: int) -> Optional[int]:
    """在列表中查找目标值的索引，找不到则返回 None"""
    for index, value in enumerate(lst):
        if value == target:
            return index
    return None

# Python 3.9+ 可以直接使用内置类型作为泛型
def find_index_modern(lst: list[int], target: int) -> int | None: # 使用 | 表示联合类型 (Python 3.10+)
    """现代写法"""
    try:
        return lst.index(target)
    except ValueError:
        return None
常见类型注解说明：

int, float, str, bool: 基本数据类型。
List[T] / list[T]: 表示元素类型为 T 的列表。T 可以是任何类型，如 List[int] 或 list[str]。
Dict[K, V] / dict[K, V]: 表示键类型为 K、值类型为 V 的字典。如 Dict[str, int] 或 dict[str, float]。
Tuple[T1, T2, ...] / tuple[T1, T2, ...]: 表示具有特定类型元素的元组。如 Tuple[int, str] 或 tuple[str, ...]（表示第一个元素是 str，后面可以有任意数量的 str 元素）。
Optional[T] / T | None (Python 3.10+): 表示类型可以是 T 或者 None。例如 Optional[str] 或 str | None。
Union[T1, T2, ...] / T1 | T2 | ... (Python 3.10+): 表示类型可以是 T1、T2 等中的任意一个。Optional[T] 等价于 Union[T, None] 或 T | None。
Any: 表示任意类型。当不确定或不想限制类型时使用，但过度使用会削弱类型检查的效果。
Callable[[ParamType1, ParamType2], ReturnType]: 表示可调用对象（函数）。例如 Callable[[int, str], bool] 表示一个接受一个 int 和一个 str 参数，并返回 bool 的函数。
重要提示：

类型注解是可选的，Python 解释器不会因为缺少类型注解而报错。
类型注解本身不会改变 Python 的动态特性。你可以仍然给一个 age: int 变量赋一个字符串值，Python 运行时不会阻止你。
类型注解的主要价值在于静态分析工具。要真正利用类型注解的好处，你需要安装并运行如 mypy 这样的工具。
总之，类型注解是 Python 一个强大的特性，它通过引入静态类型检查的元素，帮助开发者编写更健壮、更易于理解和维护的代码。

德鲁大叔
#### 11.例举你知道 Python 对象的命名规范，例如方法或者类等。

```
类名都使用首字母大写开头(Pascal命名风格)的规范；
全局变量全用大写字母，单词之间用 _分割；
普通变量用小写字母，单词之间用 _分割；
普通函数和普通变量一样；
私有函数以 __ 开头（2个下划线），其他和普通函数一样；
还有其他命名规范吗
你提到的这些命名规范是 Python 中非常常见和推荐的实践，遵循了 PEP 8（Python 的官方风格指南）。你总结得很好！除了这些，还有一些其他的命名规范和约定：

常量 (Constants):
规范: 全部使用大写字母，单词之间用下划线 _ 分隔。
示例: MAX_CONNECTIONS, DEFAULT_TIMEOUT
含义: 表示在整个程序运行期间其值不应改变的变量。虽然 Python 中没有真正的常量，但约定俗成使用全大写来表示。
实例变量/属性 (Instance Attributes):
规范: 通常使用小写字母和下划线 _。如果希望表示一个受保护的（protected）属性（即不建议外部直接访问，但可以通过继承访问），可以在名称前加一个下划线 _。
示例: self.name, self._age
含义: 对象自身的状态数据。
类属性 (Class Attributes):
规范: 通常也使用小写字母和下划线 _，但有时为了区分实例属性，可能会使用类似实例变量的命名方式，或者根据其用途决定。如果希望表示一个受保护的类属性，同样可以用一个下划线 _ 开头。
示例: class_var, class._protected_var
私有属性/方法 (Private Attributes/Methods):
规范: 以两个下划线 __ 开头（注意：不是三个）。这会触发 Python 的名称修饰（name mangling），使得从外部直接访问变得困难（但并非完全不可能）。
示例: self.__secret_data, self.__internal_method()
含义: 表示强烈不建议（甚至不希望）外部代码直接访问的属性或方法。通常用于实现细节，防止子类意外覆盖。
单下划线 _:
规范: 单独使用时，通常表示一个“临时变量”或“不关心的值”。在循环或函数调用中，如果某个返回值你暂时不需要，可以用 _ 来接收它。
示例: for _ in range(10):, data = func()[0], _ = func()[1]
含义: 表示这个变量名不重要，可以忽略。
双下划线 __ (开头和结尾):
规范: 用于特殊方法（也称为魔术方法，magic methods），如 __init__, __str__, __len__ 等。这些方法定义了类的默认行为（如对象的初始化、字符串表示、长度计算等）。
示例: def __init__(self, value):, def __str__(self):
含义: Python 内部会调用这些方法，用户也可以自定义这些方法来改变类的行为。
模块名 (Module Names):
规范: 使用短小、全小写的名称。可以包含下划线 _ 来提高可读性，但通常建议保持简短。
示例: utils.py, config.py, http_client.py
含义: Python 文件（.py）的名称。
包名 (Package Names):
规范: 同样使用短小、全小写的名称。避免使用下划线，因为一些包管理系统可能不支持带下划线的包名。
示例: mypackage, django, requests
含义: 包含多个模块的目录，通常包含一个 __init__.py 文件。
避免使用的名称:
规范: 不要使用 Python 关键字（如 class, def, if, else, import 等）作为变量名或函数名。
规范: 避免使用内置函数或类型的名称（如 list, str, open, print 等），除非你有特殊且明确的目的（不推荐）。
总而言之，Python 的命名规范核心是：清晰、一致、可读。PEP 8 是最重要的参考，遵循它能让你的代码更容易被其他 Python 开发者理解。你列出的那些是最基础和最常用的部分。

德鲁大叔
文档注释和多行注释的区别
好的，文档注释（Docstring）和多行注释（Multi-line Comment）在 Python 中虽然看起来都使用三引号（""" 或 '''），但它们的用途、处理方式和重要性有着本质的区别。

以下是它们的主要区别：

1. 用途和目的 (Purpose):

文档注释 (Docstring):
目的: 用于记录代码（模块、函数、类、方法）的功能、用途、参数、返回值、作者、示例等信息。它是代码的自我文档，旨在帮助开发者理解代码的作用，而无需深入阅读其实现细节。
位置: 通常出现在被注释对象的开头，即在 def、class 或模块级别代码的第一行。
重要性: 是 Python 官方推荐的文档编写方式，是 PEP 257 的标准。许多工具（如 pydoc、Sphinx、help() 函数、IDE 的代码提示）会自动提取 docstring 来生成文档或提供内联帮助。
多行注释 (Multi-line Comment):
目的: 用于解释代码片段、添加说明、标记待办事项（TODO）、或者临时禁用多行代码。它主要是给阅读代码的人看的，帮助理解代码的逻辑或背景。
位置: 可以出现在代码的任何地方，用来注释掉一段代码或者解释某部分逻辑。
重要性: 主要服务于代码的可读性和维护性，对程序的运行没有直接影响（因为解释器会忽略它们）。
2. 处理方式 (How Interpreter Treats Them):

文档注释 (Docstring):
Python 解释器会保留 docstring，并将其存储在对象的 __doc__ 属性中。
可以在运行时通过 obj.__doc__ 来访问（例如 function.__doc__ 或 class.__doc__）。
可以被各种文档生成工具解析和利用。
多行注释 (Multi-line Comment):
Python 解释器在执行代码时完全忽略被三引号括起来的、且不是作为第一个语句出现的字符串字面量。它们在字节码生成阶段就被移除了，不会以任何形式存在于运行时的程序中。
3. 语法和约定 (Syntax and Convention):

文档注释 (Docstring):
必须是字符串字面量，并且是对象的第一个语句。
通常使用 """（双引号三重）来包裹，这是 PEP 257 的推荐做法，尤其是在多行 docstring 时，可以避免单引号和字符串内容中的单引号冲突。
遵循特定的格式规范（虽然不是强制性的，但推荐），例如首行总结功能，后面可以有空行，然后详细描述参数、返回值等。
多行注释 (Multi-line Comment):
严格来说，Python 没有专门的“多行注释”语法。我们利用字符串字面量（用 """ 或 ''' 包裹）这个特性，因为解释器会忽略这些未赋值的字符串。
关键区别: 只有当这个字符串字面量出现在函数、类或模块的开头作为第一个语句时，它才被视为 docstring。否则，它就只是一个被忽略的字符串，起到了多行注释的作用。
因此，技术上它们使用相同的语法（三引号），但位置和用途决定了它们的“身份”。
总结表格:

特性	文档注释 (Docstring)	多行注释 (Multi-line Comment)
主要目的	记录代码功能，生成文档	解释代码逻辑，临时禁用代码
位置	函数/类/模块定义后的第一行	代码的任何地方
处理方式	保留在 __doc__ 属性中，可被工具利用	完全被解释器忽略
访问方式	obj.__doc__, help(obj), Sphinx等工具	无（无法在运行时访问）
语法	"""docstring""" (推荐用双引号)	"""comment""" 或 '''comment'''
标准/规范	PEP 257 标准	非标准，是字符串字面量的“副作用”
重要性	高（代码可维护性和自动文档的关键）	中等（提高代码可读性）
简单例子:



# 这是多行注释（或者说是被忽略的字符串）
"""
这个函数计算两个数的和。
作者: Alice
日期: 2023-10-27
"""
def add(a, b):
    """这是函数 add 的文档注释。
    它描述了这个函数的功能。
    参数:
        a: 第一个加数
        b: 第二个加数
    返回:
        a 和 b 的和
    """
    return a + b

# 这是另一个多行注释
"""
TODO: 未来需要添加减法功能
"""
print(add(3, 5))  # 输出 8

# 可以通过 help() 查看文档注释
help(add)
# 也可以通过 __doc__ 属性访问
print(add.__doc__)
在这个例子中，第一个 """...""" 是多行注释（因为它出现在函数定义之前），而 def add(a, b): 后面的 """...""" 是函数 add 的文档注释。最后一个 """...""" 也是多行注释。

德鲁大叔
python有哪些基本数据类型
Python 提供了多种基本数据类型，用于存储不同种类的数据。以下是 Python 中最常用和最基本的数据类型：

数字类型 (Numeric Types):
整数 (int): 表示没有小数部分的数字，可以是正数、负数或零。例如：42, -10, 0。
浮点数 (float): 表示带有小数部分的数字。在 Python 中通常用科学计数法表示非常大的或非常小的数。例如：3.14, -0.001, 2.5e2 (表示 2.5 * 10^2)。
复数 (complex): 表示具有实部和虚部的数字。虚部后面必须跟字母 j 或 J。例如：3 4j, -1 2.5j。
布尔类型 (Boolean Type):
布尔值 (bool): 表示逻辑值，只有两个可能的值：True (真) 和 False (假)。通常用于条件判断。例如：x > 10 的结果可能是 True 或 False。
序列类型 (Sequence Types): 用于存储一系列的值，并且通常支持索引和切片操作。
字符串 (str): 表示文本数据，由零个或多个字符组成，使用单引号 ('...') 或双引号 ("...") 包裹。例如："hello", 'Python', "123" (注意，即使是数字组成的字符串，它也是字符串类型)。
列表 (list): 一个有序的、可变的集合，可以包含不同类型的元素。使用方括号 [...] 定义。例如：[1, 2, 3], ["apple", "banana", 10]。
元组 (tuple): 一个有序的、不可变的集合，一旦创建就不能修改其内容。使用圆括号 (...) 定义（或者不加括号，用逗号分隔）。例如：(1, 2, 3), "hello", "world"。
映射类型 (Mapping Type):
字典 (dict): 一个可变的、无序的（Python 3.7+ 实际上是有序的，按插入顺序）键值对 (key-value pair) 集合。使用花括号 {...} 定义，键和值用冒号 : 分隔，键值对之间用逗号 , 分隔。键必须是不可变类型（如字符串、数字、元组）。例如：{"name": "Alice", "age": 25}。
集合类型 (Set Types): 用于存储不重复的元素集合。
集合 (set): 一个无序的、可变的唯一元素集合。使用花括号 {...} 定义（但必须包含元素，空集合用 set() 创建）或 set() 构造函数。例如：{1, 2, 3}, set([1, 2, 2, 3]) 结果是 {1, 2, 3}。
冻结集合 (frozenset): 一个无序的、不可变的唯一元素集合。类似于集合，但一旦创建就不能修改。使用 frozenset() 构造函数创建。例如：frozenset({1, 2, 3})。
总结一下最核心的基本类型：

数字: int, float, complex
布尔: bool
字符串: str
列表: list
元组: tuple
字典: dict
集合: set, frozenset
这些数据类型构成了 Python 编程的基础，你可以使用它们来存储和处理各种信息。Python 还有一些其他类型，比如 None (表示空值或无值) 等，但以上这些是最常用和最基本的数据类型。

德鲁大叔
re.match(r'[+-]?\d+$',a)解释
re.match(r'[+-]?\d+$', a) 是一个使用 Python 的 re 模块进行正则表达式匹配的示例。让我们逐步解释这个表达式的各个部分：

re.match: 这是 Python re 模块中的一个函数，用于从字符串的起始位置匹配一个模式。如果字符串的起始位置不符合模式，则返回 None。
r'[+-]?\d+$': 这是一个正则表达式模式，用于匹配特定格式的字符串。让我们分解这个模式：
[+-]?: 匹配一个可选的 + 或 - 符号。? 表示前面的字符（这里是 [+-]）是可选的，即可以出现 0 次或 1 次。
\d+: 匹配一个或多个数字。\d 表示一个数字字符（0-9），+ 表示前面的字符（这里是 \d）可以出现 1 次或多次。
$: 表示字符串的结束位置。确保匹配的数字部分是字符串的结尾。
综合起来，r'[+-]?\d+$' 这个正则表达式模式用于匹配一个可选的正负号后跟一个或多个数字的字符串，并且这个数字部分必须是字符串的结尾。

a: 这是你要匹配的字符串变量。
因此，re.match(r'[+-]?\d+$', a) 的作用是检查字符串 a 是否以一个可选的正负号开头，后跟一个或多个数字，并且这些数字是字符串的结尾。如果匹配成功，则返回一个匹配对象；否则返回 None。

例如：



import re

a = "+123"
result = re.match(r'[+-]?\d+$', a)
if result:
    print("匹配成功:", result.group())
else:
    print("匹配失败")
输出：


匹配成功: +123
再例如：



import re

a = "-456"
result = re.match(r'[+-]?\d+$', a)
if result:
    print("匹配成功:", result.group())
else:
    print("匹配失败")
输出：


匹配成功: -456
而如果字符串不符合这个模式，例如：



import re

a = "123abc"
result = re.match(r'[+-]?\d+$', a)
if result:
    print("匹配成功:", result.group())
else:
    print("匹配失败")
输出：


匹配失败
因为字符串 "123abc" 在数字后面还有其他字符，不符合模式 r'[+-]?\d+$'。

德鲁大叔
a = "你好     中国  "
    s = ' '.join(a.strip().split(''))
在这段代码中，你对字符串 a 进行了一系列操作，目的是去除字符串首尾的空白字符，并将字符串中的连续空白字符替换为单个空格。然而，代码中存在一些小错误，我会先指出这些错误，然后解释修正后的代码。

错误：

split('') 中的参数是空字符串，这是不正确的。split() 函数默认会按照空白字符（包括空格、换行符\n、制表符\t等）进行分割，如果需要按照空格分割，应该使用 split(' ') 或直接 split()。
修正后的代码：



a = "你好     中国  "
s = ' '.join(a.strip().split())
解释：

a.strip()：这个方法会去除字符串 a 首尾的空白字符，包括空格、换行符等。对于字符串 "你好     中国  "，strip() 会去除开头和结尾的空格，结果变为 "你好     中国"。
a.strip().split()：在去除首尾空白字符后，split() 会将字符串按照空白字符进行分割，返回一个列表。对于字符串 "你好     中国"，split() 会将其分割为 ["你好", "中国"]。这里中间的多个空格被视为一个分隔符。
' '.join(...)：这个方法会将列表中的元素连接成一个字符串，元素之间用单个空格分隔。对于列表 ["你好", "中国"]，' '.join() 会将其连接为字符串 "你好 中国"。
最终，变量 s 的值将是 "你好 中国"，其中单词之间的空格数量被标准化为一个。

德鲁大叔
给定两个 list，A 和 B，找出相同元素和不同元素。
要找出两个列表 A 和 B 中的相同元素和不同元素，我们可以使用 Python 的集合操作。这里是如何做到的：

相同元素：我们可以将两个列表转换为集合，然后使用交集操作找出相同元素。
不同元素：我们可以使用对称差集操作找出只存在于其中一个列表中的元素。
下面是具体的代码实现：



# 定义两个列表 A 和 B
A = [1, 2, 3, 4, 5]
B = [4, 5, 6, 7, 8]

# 找出相同元素
same_elements = set(A) & set(B)

# 找出不同元素
different_elements = set(A) ^ set(B)

same_elements, different_elements
结果

({4, 5}, {1, 2, 3, 6, 7, 8})

两个列表 A 和 B 中的相同元素是 {4, 5}，而不同元素是 {1, 2, 3, 6, 7, 8}。

相同元素指的是在两个列表中都出现的元素。
不同元素指的是只在一个列表中出现，而不在另一个列表中出现的元素。
德鲁大叔
用一行代码展开该列表 [[1,2],[3,4],[5,6]]，得出[1,2,3,4,5,6]。


# 展开列表 [[1,2],[3,4],[5,6]] 得到 [1,2,3,4,5,6]
flattened_list = [item for sublist in [[1,2],[3,4],[5,6]] for item in sublist]
flattened_list
结果

[1, 2, 3, 4, 5, 6]

使用一行代码展开列表 [[1,2],[3,4],[5,6]] 得到的结果是 [1, 2, 3, 4, 5, 6]。这里使用了列表推导式，它是一种简洁的方式来处理列表的展开。

德鲁大叔
还有其他方式吗
当然，除了列表推导式之外，还有其他几种方法可以用来展开列表。以下是几种常见的方法：

使用 itertools.chain 方法：


import itertools
flattened_list = list(itertools.chain(*[[1,2],[3,4],[5,6]]))
使用 sum 函数（不推荐，因为 sum 的本意是求和，用于此目的可能会使代码可读性降低）：


flattened_list = sum([[1,2],[3,4],[5,6]], [])
使用 for 循环扩展列表：


flattened_list = []
for sublist in [[1,2],[3,4],[5,6]]:
    flattened_list.extend(sublist)
使用 reduce 函数：


from functools import reduce
flattened_list = reduce(lambda x, y: x + y, [[1,2],[3,4],[5,6]])
使用 numpy 库（如果列表中的元素都是数字）：


import numpy as np
flattened_list = np.concatenate([[1,2],[3,4],[5,6]]).tolist()
每种方法都有其适用场景，可以根据具体需求选择合适的方法。

德鲁大叔
extend和append的区别
好的，extend 和 append 都是 Python 列表（list）的方法，它们都用于向列表中添加元素，但它们的工作方式有显著的区别。

append 方法：

添加对象本身： append 方法将你传递给它的整个对象（无论是单个元素、另一个列表、元组、字典等）添加到列表的末尾。
作为一个元素： 如果你传递一个列表给 append，那么这个列表会被当作列表中的一个单个元素添加进去。
改变原列表： 它会直接修改原列表，而不是返回一个新的列表。
语法：



list.append(item)
例子：



my_list = [1, 2, 3]

# 添加一个整数
my_list.append(4)
print(my_list)  # 输出: [1, 2, 3, 4]

# 添加一个列表
my_list.append(['a', 'b'])
print(my_list)  # 输出: [1, 2, 3, 4, ['a', 'b']]  # 注意：['a', 'b'] 是一个元素

# 添加一个字符串
my_list.append("hello")
print(my_list)  # 输出: [1, 2, 3, 4, ['a', 'b'], 'hello']
extend 方法：

展开并添加元素： extend 方法将你传递给它的可迭代对象（如列表、元组、字符串等）“展开”，然后将其中每一个元素逐个添加到原列表的末尾。
多个元素： 如果你传递一个列表给 extend，那么这个列表中的每个元素都会被单独添加到原列表中。
改变原列表： 它也会直接修改原列表。
语法：



list.extend(iterable)
例子：



my_list = [1, 2, 3]

# 添加一个整数（虽然可以，但不推荐，因为整数不是可迭代对象，会报错）
# my_list.extend(4)  # 这会抛出 TypeError: 'int' object is not iterable

# 添加一个列表
my_list.extend(['a', 'b'])
print(my_list)  # 输出: [1, 2, 3, 'a', 'b']  # 注意：'a' 和 'b' 是两个独立的元素

# 添加一个元组
my_list.extend(('x', 'y'))
print(my_list)  # 输出: [1, 2, 3, 'a', 'b', 'x', 'y']

# 添加一个字符串（字符串也是可迭代的，每个字符作为一个元素）
my_list.extend("hello")
print(my_list)  # 输出: [1, 2, 3, 'a', 'b', 'x', 'y', 'h', 'e', 'l', 'l', 'o']
总结：

方法	添加方式	结果（如果添加 ['a', 'b']）	适用场景
append	添加对象本身作为一个元素	[..., ['a', 'b']]	想把一个整体（如另一个列表）加进来
extend	展开可迭代对象，添加每个元素	[..., 'a', 'b']	想把另一个可迭代对象里的元素逐个加进来
简单记：

append：塞一个“包裹”。
extend：把“包裹”里的东西都拿出来，再塞进去。
德鲁大叔
列表有哪些常用的函数或者操作
Python 列表（list）是一种非常灵活和强大的数据结构，它提供了许多常用的函数和操作。以下是一些常用的列表函数和操作：

添加元素：
append(item)：在列表末尾添加一个元素。
extend(iterable)：将可迭代对象中的所有元素添加到列表末尾。
insert(index, item)：在指定位置插入元素。
删除元素：
remove(item)：删除列表中的第一个匹配项。
pop(index)：删除指定位置的元素，并返回它。如果不指定索引，则删除并返回最后一个元素。
clear()：清空列表。
访问元素：
index(item)：返回列表中第一个匹配项的索引。
count(item)：返回列表中某元素的个数。
排序：
sort()：对列表进行原地排序。
reverse()：反转列表中元素的位置。
复制：
copy()：返回列表的浅复制。
其他操作：
len(list)：返回列表的长度。
min(list)、max(list)：返回列表中的最小值和最大值。
sum(list)：返回列表中所有元素的总和（仅适用于数字列表）。
list(iterable)：将可迭代对象转换为列表。
in 关键字：检查元素是否在列表中。
列表切片：例如 list[1:3] 返回列表中从索引1到索引2的元素。
列表推导式：
提供了一种简洁的方式来创建列表。例如，[x**2 for x in range(10)] 创建一个包含0到9的平方的列表。
迭代和遍历：
使用 for 循环遍历列表中的每个元素。
这些只是列表的一些基本和常用操作。Python 列表非常强大，支持更多的方法和操作，可以根据需要进行探索和使用。

德鲁大叔
字典有哪些常用的函数或者操作
好的，Python 字典（dict）是一种非常常用的数据结构，用于存储键值对（key-value pairs）。它也提供了许多常用的函数和操作。以下是一些字典常用的函数和操作：

添加和修改元素：
dict[key] = value：如果键 key 不存在，则添加这个键值对；如果键 key 已存在，则更新其对应的值为 value。
获取元素：
dict[key]：根据键获取对应的值。如果键不存在，会抛出 KeyError 异常。
dict.get(key, default=None)：根据键获取对应的值。如果键不存在，不会抛出异常，而是返回指定的默认值（default 参数，默认为 None）。
dict.setdefault(key, default=None)：如果键存在，返回其对应的值；如果键不存在，则插入这个键值对（值为 default），并返回 default。
删除元素：
del dict[key]：删除指定键的键值对。如果键不存在，会抛出 KeyError 异常。
dict.pop(key, default)：删除指定键的键值对，并返回其对应的值。如果键不存在，且提供了 default 参数，则返回 default；如果没有提供 default 参数，则抛出 KeyError。
dict.popitem()：随机弹出一个键值对（在 Python 3.7+ 中，实际上是弹出最后一个插入的键值对），并返回一个包含键和值的元组 (key, value)。如果字典为空，会抛出 KeyError。
dict.clear()：删除字典中的所有键值对，清空字典。
检查键是否存在：
key in dict：检查键 key 是否存在于字典中，返回 True 或 False。
key not in dict：检查键 key 是否不存在于字典中，返回 True 或 False。
获取视图（Python 3）：
dict.keys()：返回一个动态视图对象，包含字典中的所有键。视图对象会随着字典的变化而变化。
dict.values()：返回一个动态视图对象，包含字典中的所有值。
dict.items()：返回一个动态视图对象，包含字典中的所有键值对（以 (key, value) 元组的形式）。
更新字典：
dict.update(other_dict)：使用来自另一个字典 other_dict 的键值对来更新当前字典。如果键冲突，other_dict 中的值会覆盖当前字典中的值。也可以接受键值对元组列表等。
复制字典：
dict.copy()：返回字典的一个浅拷贝。
其他常用操作：
len(dict)：返回字典中键值对的数量。
遍历：可以直接遍历字典的键、值或键值对。例如：


        # 遍历键
        for key in my_dict:
            print(key)

        # 遍历值
        for value in my_dict.values():
            print(value)

        # 遍历键值对
        for key, value in my_dict.items():
            print(key, ":", value)
这些是字典最常用的一些操作。字典因其快速的查找、插入和删除性能（平均时间复杂度为 O(1)）而在 Python 编程中扮演着至关重要的角色。

德鲁大叔
字典有哪些常用的函数或者操作，使用markdown 输出
好的，以下是以 Markdown 格式列出的 Python 字典的常用函数和操作：

代码生成完成

MARKDOWN代码

python

遍历键
for key in my_dict:
print(key)

遍历值
for value in my_dict.values():
print(value)

遍历键值对
for key, value in my_dict.items():
print(key, “:”, value)


这些是字典最常用的一些操作，以 Markdown 列表的形式呈现，方便阅读和参考。


新建对话
和我聊聊天吧
推理
沉思
联网


以上内容均由AI生成, 仅供参考和借鉴
   
2024 ChatGLM4 京公网安备11010802041394号
 
用户协议
 
|
 
隐私政策
 
|
 
开源模型
 
markdown

代码

预览

# Python 字典常用函数和操作

## 1. 添加和修改元素
- `dict[key] = value`：如果键 `key` 不存在，则添加这个键值对；如果键 `key` 已存在，则更新其对应的值为 `value`。

## 2. 获取元素
- `dict[key]`：根据键获取对应的值。如果键不存在，会抛出 `KeyError` 异常。
- `dict.get(key, default=None)`：根据键获取对应的值。如果键不存在，不会抛出异常，而是返回指定的默认值（`default` 参数，默认为 `None`）。
- `dict.setdefault(key, default=None)`：如果键存在，返回其对应的值；如果键不存在，则插入这个键值对（值为 `default`），并返回 `default`。

## 3. 删除元素
- `del dict[key]`：删除指定键的键值对。如果键不存在，会抛出 `KeyError` 异常。
- `dict.pop(key, default)`：删除指定键的键值对，并返回其对应的值。如果键不存在，且提供了 `default` 参数，则返回 `default`；如果没有提供 `default` 参数，则抛出 `KeyError` 异常。

## 4. 检查键是否存在
- `key in dict`：检查字典中是否存在键 `key`，返回 `True` 或 `False`。
- `key not in dict`：检查字典中是否不存在键 `key`，返回 `True` 或 `False`。

## 5. 字典视图
- `dict.keys()`：返回一个动态视图对象，包含字典中的所有键。视图对象会随着字典的变化而变化。
- `dict.values()`：返回一个动态视图对象，包含字典中的所有值。
- `dict.items()`：返回一个动态视图对象，包含字典中的所有键值对（以 `(key, value)` 元组的形式）。

## 6. 更新字典
- `dict.update(other_dict)`：使用来自另一个字典 `other_dict` 的键值对来更新当前字典。如果键冲突，`other_dict` 中的值会覆盖当前字典中的值。也可以接受键值对元组列表等。

## 7. 复制字典
- `dict.copy()`：返回字典的一个浅拷贝。

## 8. 其他常用操作
- `len(dict)`：返回字典中键值对的数量。
- 遍历：可以直接遍历字典的键、值或键值对。例如：

```

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
List,tuple,dict,set是比较常用的数据结构，queue,heap,deque,ProrityQueue，multiprocessing.Queue等进阶的数据结构类型。特性就去查查吧，写在这里太长了。
```

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
import datetime
def getday(n):
    y,m,d = 2019,5,30
    the_date = datetime.datetime(y,m,d)
    result_date = the_date + datetime.timedelta(days=n)
    target_date = result_date.strftime('%Y%m%d')
    return target_date
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

```Python
def strappend(num):
    str='first'
    for i in range(num):
        str+=str(i)
    return str
  # 将str(i)改为str[i]
```

#### 59.一行代码输出 1-100 之间的所有偶数。

```python
[x for x in range(101) if x %2 ==0]
```

#### 60.with 语句的作用，并用它写一段代码。

```python
# with语句用来管理资源，及时关闭文件等操作，避免资源的泄漏
with open('a.txt','r') as f:
    f.read()
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

```python
函数装饰器可以在不修改原函数的条件下，为原函数添加额外的功能，例如记录日志，运行性能，缓存等
以记录函数运行时间为例，实现一个装饰器
import time
def time_it(func):
    def wrapper(func):
        start_time = time.time()
        res = func()
        end_time = time.time()
        return start_time - end_time
    return wrapper
    
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

```python
class Bar:
    def __call__(self, *args, **kwargs):
        print('i am instance method')

b = Bar()  # 实例化
b()  # 实例对象b 可以作为函数调用 等同于b.__call__ 使用


# OUT: i am instance method



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
判断对象是函数或方法应该使用type(obj)
```

#### 67.简述 @classmethod 和 @staticmethod 用法和区别。

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

```python
#抽象类加抽象方法就等于面向对象编程中的接口
from abc import ABCMeta,abstractmethod

class interface(object):
    __metaclass__ = ABCMeta #指定这是一个抽象类
    @abstractmethod  #抽象方法
    def Lee(self):
        pass

    def Marlon(self):
        pass


class RelalizeInterfaceLee(interface):#必须实现interface中的所有函数，否则会编译错误
    def __init__(self):    
        print '这是接口interface的实现'
    def Lee(self):
        print '实现Lee功能'        
    def Marlon(self):
        pass   
```

#### 69.你了解 Python 中的反射吗？

```python
通过字符串映射object对象的方法或者属性
hasattr(obj,name_str): 判断objec是否有name_str这个方法或者属性
getattr(obj,name_str): 获取object对象中与name_str同名的方法或者函数
setattr(obj,name_str,value): 为object对象设置一个以name_str为名的value方法或者属性
delattr(obj,name_str): 删除object对象中的name_str方法或者属性

举个栗子
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

```
metaclass我没怎么用过，不能乱说误人子弟，可以看下这篇博文https://www.cnblogs.com/xybaby/p/7927407.html
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

```
参考77.
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
参考71.
```

#### 79.当退出 Python 时是否释放所有内存分配？

```
答案是否定的。那些具有对象循环引用或者全局命名空间引用的变量，在 Python 退出是往往不会被释放

另外不会释放 C 库保留的部分内容。
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
对于支持继承的编程语言来说，其方法（属性）可能定义在当前类，也可能来自于基类，所以在方法调用时就需要对当前类和基类进行搜索以确定方法所在的位置。而搜索的顺序就是所谓的「方法解析顺序」（Method Resolution Order，或MRO）。对于只支持单继承的语言来说，MRO 一般比较简单；而对于 Python 这种支持多继承的语言来说，MRO 就复杂很多。
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

```python
d = {'a':2,'b':1,'c':3,'d':'4'}
sorted(d,key=lambda x :x[1]) 
# 将字典d按照值排序
```

#### 98.新式类和旧式类的区别有哪些？

```
Python 有两种类：经典类（classic class）和新式类（new-style class）。两者的不同之处在于新式类继承自 object。在 Python 2.1 以前，经典类是唯一可用的形式；Python 2.2 引入了新式类，使得类和内置类型更加统一；在 Python 3 中，新式类是唯一支持的类。
```

#### 99.dir() 是用来干什么的？

```
dir() 函数不带参数时，返回当前范围内的变量、方法和定义的类型列表；带参数时，返回参数的属性、方法列表。如果参数包含方法__dir__()，该方法将被调用。如果参数不包含__dir__()，该方法将最大限度地收集参数信息。
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

```python
copy 即所谓的浅拷贝，赋值的时候非递归地复制子对象的引用；
deepcopy 即所谓的深拷贝，赋值的时候递归复制子对象。
举个栗子，
xs = [1,2,[2,3,4],3]
ys = xs # 浅拷贝
zs = deepcopy(xs) # 深拷贝
xs[2][0] = 5
print(ys)
[1,2,[2,3,4],3]
print(xs)
[1,2,[5,3,4],3]

print(zs)
[1,2,[5,3,4],3] # 由于深拷贝已经递归复制了子对象，所以内部的List也发生改变

```

#### 103.请阐述代码中经常遇到的 *args, **kwargs 的含义及用法。

```
这两个是python中的可变参数。*args表示任何多个位置参数，它是一个tuple；**kwargs表示关键字参数，它是一个dict。并且同时使用*args和**kwargs时，必须*args参数列要在**kwargs前
```

#### 104.Python 中会有函数或成员变量包含单下划线前缀和结尾，或双下划线前缀结尾，它们的区别是什么？

```python
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
print()和pprint()都是python的打印模块，功能基本一样，唯一的区别就是pprint()模块打印出来的数据结构更加完整，每行为一个数据结构，更加方便阅读打印输出结果。特别是对于特别长的数据打印，print()输出结果都在一行，不方便查看，而pprint()采用分行打印输出，所以对于数据结构比较复杂、数据长度较长的数据，适合采用pprint()打印方式
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

#### 112.**在 Python 中如何使用多进制数字？**

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
Python 标准库中自带了 xml 模块，但是性能不够好，而且缺乏一些人性化的 API，相比之下，第三方库 lxml 是用 Cython 实现的，而且增加了很多实用的功能，可谓爬虫处理网页数据的一件利器。lxml 大部分功能都存在 lxml.etree中.
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
1) scrapy是一个Python爬虫框架，爬取效率极高，具有高度定制性，但是不支持分布式。而scrapy-redis一套基于redis数据库、运行在scrapy框架之上的组件，可以让scrapy支持分布式策略，Slaver端共享Master端redis数据库里的item队列、请求队列和请求指纹集合。

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
IO密集型代码(文件处理、网络爬虫等)，多线程能够有效提升效率(单线程下有IO操作会进行IO等待，造成不必要的时间浪费，而开启多线程能在线程A等待时，自动切换到线程B，可以不浪费CPU的资源，从而能提升程序执行效率)。在实际的数据采集过程中，既考虑网速和响应的问题，也需要考虑自身机器的硬件情况，来设置多进程或多线程
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

```markdown
TCP协议和UDP协议特性区别总结：
     1. TCP协议在传送数据段的时候要给段标号；UDP协议不
     2. TCP协议可靠；UDP协议不可靠
     3. TCP协议是面向连接；UDP协议采用无连接
     4. TCP协议负载较高，采用虚电路；UDP采用无连接
     5. TCP协议的发送方要确认接收方是否收到数据段（3次握手协议）
     6. TCP协议采用窗口技术和流控制
```

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

```
这个问题虽然被问烂了，但是还是可能会问，不过网上都是答案，搜搜看下就行
```

#### 153.简述 GIL。

```
在CPython解释器中，全局解释锁GIL是在于执行Python字节码时为了保护访问Python对象而阻止多个线程执行的一把互斥锁。这把锁的存在在主要是因为CPython解释器的内存管理不是线程安全的。然而直到今天GIL依旧存在，现在的很多功能已经习惯于依赖它作为执行的保证
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

```
并发的实质是一个物理CPU(也可以多个物理CPU) 在若干道程序之间多路复用，并发性是对有限物理资源强制行使多用户共享以提高效率
并行”指两个或两个以上事件或活动在同一时刻发生。在多道程序环境下，并行性使多个程序同一时刻可在不同CPU上同时执行
```

#### 158.解释什么是异步非阻塞？

```
当一个异步过程调用发出后，调用者不会立刻得到结果。
实际处理这个调用的部件是在调用发出后，
通过状态、通知来通知调用者，或通过回调函数处理这个调用
非阻塞的意思是，不能立刻得到结果之前，该函数不会阻塞当前线程，而会立刻返回
```

#### 159.简述 threading.local 的作用。

```
Python提供了 threading.local 类，将这个类实例化得到一个全局对象，但是不同的线程使用这个对象存储的数据其它线程不可见(本质上就是不同的线程使用这个对象时为其创建一个独立的字典)
```



### **Git 面试题**

#### 160.说说你知道的 git 命令。

```git
git clone;
git push
git status;
git commit;
...
```

#### 161.git 如何查看某次提交修改的内容？

```Git
知道commit id的情况下:
1. 获取commit id
   git log 

2. 查看commit内容
   git show commit_id

查看最近n次提交的修改
   git log -p -n
指定n为1则可以查看最近一次修改的内容
```


