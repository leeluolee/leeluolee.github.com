# 简介

一看这题目，发现大家都被骗了，  我发现之前的分享，包括DSL、预处理器， 准备了很多内容，但是反响却不佳， 这次我转换思路， 精简下内容， 看是不是接受度会更好，沙龙一般会提前几个月报名，但是PPT内容我是最近几天才开始准备，所以题目真的不要在意。

我一般在社交网站就这两个头像， 分辨率超低。  id，  看到记得给我打个招呼。

# 首先我肯定要来解答下，什么是Regularjs， 我知道在场的有一些人接触过它，但是大

这里不是为了装B， 而是因为英文真的很方便排版。


- living-template
- data-driven component
- framework 框架. 但是Regularjs框架的定义是无侵入的与其它框架有所不同。

# 

- 提供类似jst的写法, 当然当时飞哥的要求其实很宽松， 但事实上我发现首先模板语法的， 而来除了jst的差值与statement的开关符号不统一， 所以后来我基本沿用了jst的语法。
然后呢，让模板动态化。

但事实上如果不引入指令等类似最佳时间， 你一份模板动态化之后， 仍然避免不了在更新后，去手动绑定某些事件或，这个时候， 我引入了指令。在指令之后， 出现component也就是自然而然。 所以当Regularjs的第一版出现之后， 就从一个模板引擎变成了一个组件级别的框架。


# Regularjs 是框架还是库？

实现是框架， 使用组件是库. 

我很在意引入API，所以你现在去看regularjs的实例方法 仍然维持在10个左右， 50kb的大小也足以对得起库的定义。  React这种动辄，还不包括它臃肿的jsx依赖

# 未来的

国人的框架很喜欢， 秒杀xx的定义，  我记得我刚来的时候，写个选择器使用的秒杀Sizzle的口号，  too young to simple.  想

- 提供一个第三方模块，达到与NEJ的module兼容，使其可以作为一个特殊的
- SEO， 这个会在当前的， 目前当然是一份配置就可以完成 NODEjs作为后台的前提下
- 性能、  与 Webcomponent相关概念的融合
- 在解析时，动态修改局部内容的能力， 这个基本也是其它模板不直接提供的， 因为一份模板是一个整体， 你可以全局替换，但是无法进行局部修改。