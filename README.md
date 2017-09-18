# Node.js学习笔记

### Node.js简单概述
  用于创建高性能服务器及可在该服务器中运行的各种应用程序的开发工具(技术)
  在Node.js服务器中运行的是高性能V8 Javascipt脚本语言

### Node.js特点
 为了实现高性能,Node.js中采用了以下两种机制
 - 非阻塞型I/O
    >在执行了访问数据库的代码之后将立即转而执行其后面的代码,把数据库返回结果的处理代码放在回调函数中执行,从而提高了程序的执行效率(异步执行)
 - 事件环
    >在一个时刻只能执行一个事件回调函数,但是在执行一个事件回调函数的中途可以转而处理其他事件(包括触发新的事件,声明该事件的回调函数等),
 然后返回继续执行原事件回调函数

### Node.js适合开发的应用程序
>当应用程序需要处理大量并发的输入/输出,而在向客服端发出响应之前,应用程序内部并不需要进行非常复杂的处理的时候,我们应该考虑使用Node.js来进行该应用程序开发,例如,我们可以开发如下应用程序:
>> - 聊天服务器
>> - 综合服务类或电子商务网站的服务器

## 目录
- [1. REPL运行环境](./Nodejs/1.%20REPL) 
- [2. Node.js 基础](./Nodejs/2.%20Node.js) |  [源码](./Nodejs/2.%20Node.js/code/)
- 持续更新中

#### 内容参考: 
> Node.js 权威指南/陆凌牛著.-北京: 机械工业出版社, 2014.4(2016.10重印)
---------------------------------------------------------------------------
# JavaScipt设计模式学习笔记

### 设计模式的简单概述
 设计模式是解决软件设计中常见问题的可复用方
 
### 设计模式的三大好处
 - 模式是已经验证的解决方案
 > 他们为解决软件开发中遇到的问题提供可靠的方法,也就是试用已经验证的解决方案,这些解决方案提现了开发人员的经验及见解,他们所定义和改进这些方法提供了帮助,从而形成现在的模式
 - 模式很容易被复用
 > 模式通常是指一种立即可用的解决方案, 可用对其进行修改以满足个人需求, 该特性使得这些模式的功能非常的强大
 - 模式富有表达力
 > 看到模式时,通常就会表示有一个设置好的结构和表达解决方案的词汇,以帮助我们非常轻松地表达出所实现的大型解决方案
 
 ## 目录
- [Constructor (构造器) 模式](./Design%20patterns/Constructor)
- [Module (模块) 模式](./Design%20patterns/Module)  
  
  
#### 内容参考: 
> Learning JavaScript Design Patterns by Addy Osmani(O'Reilly). Copyright 2012 Addy Osmani, 978-1-449-33181-8
