MyDemo
===================================
该项目是我第一个上传到github上面的项目,只是一个测试项目,之后我把我学到的总结的知识点,一点一点的记录下来,
从最简单的开始。

****
#### Author:JackShao
#### E-mail:androidjack@qq.com
****

## 目录
 * [Markdown语法](#Markdown语法)
     + 标题
     + 横线
     + 文本
     + 图片
     + 链接
     + 列表
     + 块引用
     + 表格
     + 代码高亮
     + 表格
     + 表情
     + diff语法
 * [上传,更新到gitHub](#上传,更新到gitHub)
     * 上传
     * 更新
 * [待续](#待续)

 Markdown语法
------------------------
### 标题
支持两种标题,类Setext 和类atx 形式。

类Setext形式:=(最高阶标题), -(第二阶标题)
> This is an H1
> =============
> This is an H2
> -------------
类atx: (#-######)
> # This is an H1
> ## This is an H2
> ### This is an H3
> #### This is an H4
> ##### This is an H5
> ###### This is an H6

### 横线
***,---,___可以显示横线效果
***
---
___

####  文本

#### 普通文本
这是一段普通的文本
#### 单行文本
    Hello,大家好，我是jackshao。
在一行开头加入1个Tab或者4个空格。
#### 文本块
##### 语法1
在连续几行的文本开头加入1个Tab或者4个空格。

    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安

##### 语法2
使用一对各三个的反引号:
```
欢迎到访
我是Android码农
你可以在CSDN、简书搜索 jackshao
```
该语法也可以实现代码高亮，见[代码高亮](#代码高亮)
### 文字高亮
文字高亮功能能使行内部分文字高亮，使用一对反引号。
语法：
```
`linux` `网络编程` `socket` `epoll`
```
效果：`linux` `网络编程` `socket` `epoll`

#### 斜体、粗体、删除线
|语法|效果|
|----|-----|
|`*斜体1*`|*斜体1*|
|`_斜体2_`| _斜体2_|
|`**粗体1**`|**粗体1**|
|`__粗体2__`|__粗体2__|
|`这是一个 ~~删除线~~`|这是一个 ~~删除线~~|
|`***斜粗体1***`|***斜粗体1***|
|`___斜粗体2___`|___斜粗体2___|
|`***~~斜粗体删除线1~~***`|***~~斜粗体删除线1~~***|
|`~~***斜粗体删除线2***~~`|~~***斜粗体删除线2***~~|

### 图片
基本格式：
```
![alt](URL title)
```
alt和title即对应HTML中的alt和title属性（都可省略）：
- alt表示图片显示失败时的替换文本
- title表示鼠标悬停在图片时的显示文本（注意这里要加引号）

URL即图片的url地址，如果引用本仓库中的图片，直接使用**相对路径**就可了，如果引用其他github仓库中的图片要注意格式，即：`仓库地址/raw/分支名/图片路径`，如：
```
https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
```
|#|语法|效果|
|---|---|----
|1|`![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")`|![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
|2|`![][foryou]`|![][foryou]
|3|`![本地图片](http://www.baidu.com/img/bdlogo.gif "本地图片"))`|![本地图片](https://github.com/LGDAndroid/TestDemo/art/ic_launcher.png)

注意例2的写法使用了**URL标识符**的形式，在[链接](#链接)一节有介绍。
>在文末有foryou的定义：
```
[foryou]:https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif
```




















