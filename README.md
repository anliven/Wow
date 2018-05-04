# Hello, Code！
[anliven - Zen](https://github.com/anliven/Zen)


### 初始能力
让阅读思路保持清晰连贯，主力关注在流程架构和逻辑实现上，不被语法、技巧和业务流程等频繁地阻碍和打断。
- 语言基础：熟悉基础语法，常用的函数、库、技巧等；
- 了解设计模式、编程和构建工具、代码风格；
- 了解业务背景和逻辑；



### 工具使用
- [Source Insight - 具有强劲的代码浏览和分析功能](http://www.cnblogs.com/anliven/p/7545972.html)
- [grep命令 - 用于全局搜索](http://www.cnblogs.com/anliven/articles/6018442.html)
- [IDE - 利用代码结构分析功能或插件生成UML图](http://www.cnblogs.com/anliven/p/7465430.html)
- [浏览器插件Octotree - 树形结构显示Github项目](https://github.com/buunguyen/octotree/)
- [代码转换成流程图 - 在线工具](https://code2flow.com/)
- [Python Call Graph - 生成python函数调用关系图](http://pycallgraph.slowchop.com/)
- [GNU GLOBAL - a source code tagging system](https://www.gnu.org/software/global/)
- ......



### 准备动作
**明确问题与需求:**
```
- 为什么要阅读源代码？要解决什么具体问题？要达到怎样的程度和效果？
- 当前状态（初始能力、资源投入等）如何？是否足够支撑开始并完成这样的代码阅读？
- 没有明确目标，将会导致大量无效的阅读，就难以获得实际的收获；
```
**一些参考步骤：**
```
- 对于知名项目，收集规整已有的代码分析资料；
- 确认辅助信息来源：官方文档、项目文档、搜索引擎等；
- 确认代码版本（早期版本或当前能够理解的版本）和编码风格；
```


### 方法和注意事项
“因地制宜，因人而异”。问题需求、资源投入、项目状态的不同，适用的阅读方法和工具自然也就不同。
直接啃代码的方式适合解决具体的细节问题，简单粗暴，速度快效果好。
但如果想完整而深入地了解一个有规模和难度的项目，又该如何进行呢？

**一些参考方法：**
```
- 阅读“README”；
- 通过查看提交和版本日志，研读所关注的功能和优化；
- 搭建测试环境并运行Demo或示例，观察运行状态，从外部了解核心功能和运行方式，形成总体认知；
- 善用文档：quickstart、tutorial、howto等内容中的示例往往是非常有效的了解途径；
- 分层阅读：先整体后局部，借助工具生成UML图，从整体了解代码结构和调用关系，确定阅读的层次和顺序；
- 寻找程序入口，根据实际情况确定阅读的切入点；
- 为代码写注释，必要时形成文档；
- 问题列表：记录疑问和问题并归纳成表，解决问题的过程也就是代码逐渐清晰的过程；
- 查看单元测试，编写测试用例，抛异常，Debug所关注的执行过程，观察现象和日志，明确调用关系和执行路径；
```
**一些注意事项：**
```
- 带着问题与需求阅读代码，围绕根本和主干，没有必要通读源码，更不应该沉陷于细节；
- 必要时略过难以理解的地方，不过度纠结于某一行某一段；
- 理解项目作者的思考方式，
- 低头专注代码，抬头思考架构，结合业务流程，从整体的角度来看待局部实现的过程；
```



### 下一步
- **关注原型**
```
    最终展现的软件往往是“原型程序”经过精心包装和美化的结果。
    “原型程序”只包括核心和基础功能，是可用的初始化版本，是“软件成长的起点”。
    应该从“起点”开始跟随，而不是从“终点”返回。
```
- **迭代式理解**
```
    软件是成长起来的，而不是一次性搭建完成的，尝试理解代码，也会有一个循序渐进的过程。
    对项目代码的理解，只是当时的理解，受限于当时的技能水平，知识结构，资源投入，甚至是身心状态。
    经过一段时间磨砺和成长，回头再阅读同样的项目代码，往往会有新的发现和理解。
```
- **改善适用性**
```
    “学以致用”是获得知识技能的最有效途径之一。
    实现自己的需求和想法，最终形成更适合的版本。
    在现有“轮子”的基础上去制造“一个更完善轮子”，在这样的二次开发过程中，可以验证代码理解。
```
- **获得建议与批判**
```
    落后的起源是“故步自封”、“自以为是”和“自欺欺人”。
    归纳并分享你的理解，会获得更全面更专业更中肯的建议与批判。
    争议之中，也恰恰隐含着成长与改变的线索与机遇。
```