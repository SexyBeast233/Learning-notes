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
- [1. REPL运行环境](https://github.com/Mutoumiao/Study-Nodejs/issues/1) 
- [2. Node.js 基础](https://github.com/Mutoumiao/Study-Nodejs/issues/2) |  [源码](./2.Node.js-basics)
- 持续更新中
