---
layout: post
title: 编程语言简史
tags: 编程语言
---
![编程语言]({{site.baseurl}}/images/posts/bcyypic.jpg)

**什么时候，都有必要了解一下发展史，与众不同的感受**

### 机器语言

机器语言,   
- 只有数字`0`和`1`
- 并不代表任何'数量', 而是代表'模式(pattern)'的信号

指令,   
- 给计算机输入的相当于'命令'的数字, 称为'指令'
- 通过指令来操作, 让计算机做一些事, 就是编程的本质活动

指令集,   
- '模式'到'指令'的映射的集合
- 通过金属引脚接受0和1输入的CPU的所谓'指令集', 本质上就是由芯片制造厂商给出的数字组合定义
- 芯片设计结构不同, 每种芯片的指令集也就不同

### 汇编语言

汇编语言,   
- 机器语言编程难度很大, 且不可读, 从数字到助记符号的转译很快随之出现, 形成了汇编语言
- `0010 0000` --> `ADD X, Y`
- 汇编语言由专门的小程序'翻译'成二进制的机器码(只有二进制的机器码才是真正可以输入处理器去按下晶体管的程序电子信号)
- 每种处理器的汇编语言仍旧是不同的

机器语言, 汇编语言的优点,   
- 每条指令都几乎对应于芯片能做的一件事, 直接对一块芯片下命令, 效率非常高
缺点,    
- 指令集不同, 操作重复枯燥

### 高级语言

'高级'机器语言,   
- 倾向于描述需要解决的问题, 而不是描述计算机具体进行何种操作, 封装了那些不需要关心的细节, 把细小步骤想要达成的意图抽象出来

最古来的高级语言,    
- FORTRAN, ALGOL, COBOL, LISP
- 目前流行的一切计算机语言, 几乎全都是上述四种古老语言的综合演进

编程语言演进,    
- 编程语言的'修饰, 扩展和融合'的动机和幅度, 主要取决于程序员的实际需求
- 计算机逐步小型化, 廉价化, 应用范围大幅度扩展, 新的语言特性需求与日俱增

范式(paradigm),   
- 语言设计者不可能一下子追踪, 汇总所有的需求, 总要有所侧重
- 新发明的语言往往会侧重于一种特定的方法, 制作特定的语言功能, 来是的编写某种特定性是的程序特别便利

### 高级计算机语言简史

Fortran,   
- **第一个**计算机语言, 诞生于1957年, 由IBM设计
- 设计思想基于冯.诺依曼体系结构, 是**命令式语言的鼻祖**

Lisp,   
- 源于数学的计算机语言, 诞生于1960年, 由麦卡锡和其学生设计实现
- 区别于冯.诺依曼体系结构
- 建立在列表和lambda盐酸和基础上, 是**函数式编程的鼻祖**

Algol,   
- 通用科学计算语言, 诞生于1958年, 由苏黎世会议制定
- 是后来所有计算机语言**语法的鼻祖**, 除Cobol外

COBOL,
- 通用商务语言, 发布于1960年, 在商务领域被广泛的使用

PL/I,    
- 跨领域语言, 诞生于1964年, 是跨科学计算和商务应用领域的计算机语言

SIMULA 67,    
- 1967年改进的64年诞生的SIMULA I
- **第一个定义类结构的语言**, 被认为是面向对象的起源
> 将命令式编程中的数据和数据的有关函数集成在一起, 就形成了面向对象编程中的对象, 而对象的类型就是类. 将命令式编程中主程序调用子程序的`从属关系`, 变为面向对象编程中对象之间互相发送消息的`平等关系`

BASIC,    
- 初学者的语言, 诞生于1971年
- **第一个被广泛使用的分时处理语言**
- 来自于Fortran IV, 语法受Algol 60影响

Pascal,    
- 学院派语言, 诞生与1971年, 来自于Algol 68
- 重大影响来自于程序设计教学, 取代了Fortran作为程序设计入门语言的地位

C,    
- **系统语言**, 一个可移植系统的程序语言
- 丹尼斯.李奇主导, 和肯.汤普森(UNIX作者)共同完成

Prolog,    
- 逻辑语言, 诞生于1972年, **逻辑是变成的鼻祖**
- 逻辑式编程, 就是以形式逻辑的方式将计算过程传递给计算机

Scheme,    
- 极简主义语言, 一种Lisp方言, 诞生于1975年, MIT
- **第一个引入词法作用域, 延续体, 闭包等概念**
- 将数据和函数等同对待
- Scheme是`函数式语言`主要用于数学算法教学, Pascal是`命令式语言`主要用于程序设计教学

ML,    
- 诞生于1979年, 开创了以Algol做语法的函数式语言的先河

Haskell,    
- 强类型惰性纯函数式语言, 1990年标准化Mirada语言(86年部分基于ML语言诞生)的结果
- 最大特点是惰性求值

OCaml,    
- Caml, 支持面型对象的函数式语言, 诞生于1996年, 基于ML和Haskell
- OCaml是Caml的面向对象版本, 发布于2006年
- F#是基于OCaml的.NET平台版本, 发布于2010年

Ada,    
- 嵌入式语言, 诞生于1980年
- 广泛的用于商务, 国防航空和交通运输领域

Smalltalk,    
- 纯面向对象语言, 诞生于1980年, **第一个完全支持面向对象编程的语言**
- 源于SIMAL 67, 完善并定义了消息发送, 和对象的继承关系
- 在Smalltalk中, 所有数据都是对象. 对象的类型是类. 类中可以定义方法, 属性等

C++,    
- 命令式面向对象语言, 诞生于1983年
- 是在C的基础上, 以SIMUAL 67的方式对命令式编程的面向对象扩展
- C++的成功在于完全兼容C的情况下支持了面向对象, 从而使面向对象编程成为了命令式编程的一个子类, `传统的命令式编程`被叫做`面向过程编程`
- C/C++吸收了太多的语言特性, 成为了**世界上最难精通的语言**, 目前使用人数最多的语言, 竞争对手是Java

Self,    
- 原型面向对象语言, 诞生于1986年, 源自于Smalltakl
- 提出了"万物皆对象"的思想
> 它删除了面向对象概念中的类的概念, 认为类也是一种对象; 消息仍然作为最基本操作; 把对象的属性理解为获取或更改属性这两种方法, 从而把属性的概念简化位方法; 取消了变量和赋值, 替代它们的是通过消息来读槽和写槽.
- Self中对象创建对象的方式是自我拷贝, 叫做原型
- **原型面向对象语言的鼻祖**, 就像SIMUAL 67是类面向对象语言的鼻祖.

Objective-C,    
- 另一个对C进行面向对象扩展的语言, 诞生于1983年
- 以Smalltalk的面向对象为基础(C++是以SIMUAL 67的面向对象基础)
- 苹果公司的

Delphi,    
- 对Pascal进行面向对象扩展的语言

Perl,   
- 脚本语言, 发布于1987年, 起源于操作系统的控制台(shell)的命令
- sh文件就叫做`脚本`, 脚本只是一些命令行, 但是Perl时已经是一个相当成熟的语言了

Lua,     
- 关联列表函数式面向对象脚本语言, 诞生于1993年, 设计目的是嵌入应用程序, 成为其脚本
- 基于Self和Scheme, **第一个以关联列表作为主要数据的函数式语言**

Java,    
- 虚拟机面向对象语言, 诞生于1995年,  由Sun公司开发, **第一个在虚拟机上运行的语言**
> 在此之前的计算机语言,   
> 动态语言, 由解释器解释执行源代码(大多数命令式语言)
> 静态语言, 将源代码编译连接成实际的计算机指令后再由计算机执行(大多数命令式语言)
- Java运行于JM(Java虚拟机)上
> JM和解释器的区别,    
> JM会将java源代码编程成字节码, 然后再由JM解释执行. 由于编译和执行过程是交错的, 所以从外部来看就像是JM直接执行Java源代码一样
- Java是面向对象编程使用人数最多的语言, 强力竞争对手是C#

Python,    
- 面向对象解释式脚本语言, 诞生于1989年, 是`面向过程+面向对象`语言

Ruby,    
- 纯粹面向对象解释式脚本语言, 诞生于1996年
- 基本等于Smalltalk + Lisp

PHP,   
- Web服务器基本语言, 诞生于1994年
- 和JavaScript的语法相似, 都是嵌入在HTML中, 只不过一个在服务器端, 一个在浏览器端

JavaScript,   
- 浏览器脚本语言
- 表面上是一个命令式编程语言, 本质是一个以关联列表位数据格式的函数式编程语言

C#,   
- .NET平台主语言, 于2000年和.NET平台一起由微软发布

参考链接:     
[为什么会有那么多编程语言](https://www.zhihu.com/question/20104312/answer/33419526)