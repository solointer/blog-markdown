---
title: 读书笔记：《Web站点优化》
date: 2015-10-07 13:04:34
tags: 读书笔记
---


这书分为两部分。第一部分是搜索引擎市场营销优化，对不起我看不懂，只能从第二部分开始看了。

第二部分是Web性能优化。

#原因

第二部分首先就介绍了加载速度和用户的关系，速度越慢，用户越容易感到不耐烦。与此同时，网速越快的用户，忍耐心越差。所以这就是我们要优化Web性能的原因。

#网页优化
原谅我，这只是笔记，我会将对我有用的东西记下来。深入的东西还需去自己看。

>加快网页速度有以下十种方法：
>
>1. 尽量减少HTTP请求。
>
>2. 调整图片大小并优化
>
>3. 优化多媒体
>
>4. 将Javascript转换成CSS
>
>5. 使用服务器端探测
>
>6. 优化Javascript获得更快的执行速度和更小的文件体积
>
>7. 将表布局转换成CSS布局
>
>8. 用CSS规则替代内联样式
>
>9. 最小化初始显示时间
>
>10. 理智的加载Javascript


#CSS优化
由于这本书有点老， 我也不知道有没有一些优化，现在已经用不上了的。

##建立CSS架构

* 使用重置样式表让渲染行为保持一致（使用重置样式表）
	
		据说这样可以去除浏览器的差异。

* 对主页区域（报头、导航、内容、页脚和边栏）使用标记容器单元格，并以此来设计后代选择器。

* 将外部CSS文件放在head元素里，使之能够渐进渲染。

##CSS优化的十大技巧
>1. 用类型选择器代替内联样式，从而定位相同元素的多个实例。
>
>2. 使用后代选择器，而不要使用内联类。
>
>3. 将存在相同声明的选择器归组。
>
>4. 将相同选择器的不同声明归组。
>
>5. 将相同的样式合并为共享类。
>
>6. 利用继承来消除重复声明。
>
>7. 使用CSS缩写来简化规则和颜色的定义。
>
>8. 缩写较长的类名和ID名。
>
>9. 使用CSS2和CSS3.x技术。
>
>10. 用CSS技术代替Javascript动作。

#Ajax优化

>1. 恰当的使用Ajax解决问题
>
>2. 使用良好构建和支持的Ajax库
>
>3. 最小化Javascript代码
>
>4. 减少HTTP请求的需求
>
>5. 选择正确的传输数据格式
>
>6. 确保网络可用性和性能
>
>7. 使用Javascript缓存
>
>8. 为搜索引擎提供一种兼容机制，保证Javascript被禁用时的可访问性。
>
>9. 使用片段标识符来储存状态

##Javascript优化

>1. 删除Javascript注释
>
>2. 小心删除空白字符
>
>3. 使用字符常量宏
>
>4. 使用缩写形式
>
>5. 去除无用代码
>
>6. 缩短用户自定义变量名与函数名
>
>7. 重映射内置对象
>
>8. 内联局部函数
>
>9. 假定默认值
>
>10. 让每个字节物有所值
>
>11. 合并脚本
>
>12. 延迟加载代码
>
>13. 设计步调
>
>14. 监控用户渲染时间
>
>15. 错误检测实战
>
>16. 清理工作
>
>17. 本地化
>
>18. 计算运行时间


#高级Web性能优化
##服务器端优化
>1. 优化并行下载
>
>2. 缓存频繁使用的对象
>
>3. 使用HTTP压缩
>
>4. 使用delta编码
>
>5. 使用mod_rewrite重写URI


##客户端的性能技术
>1. 延迟脚本加载
>
>2. 在服务器上缓存站外文件并本地加载
>
>3. Javascript优化和打包
>
>4. 用数据URI内联图片

粗略看完了。。0.0




