# markdown
# 手机端实现、电脑端实现离线公众号书写并且带入格式
# markdown写作完毕一键复制，无需排版！！！
![](https://mmbiz.qpic.cn/mmbiz_jpg/mIibV0dojFpA35Sfc97VUeEOBWShAfSnxlyvuzjicKia3cCmBjca3ib1HyLmfib7FaiciadpraFr2oDMsDicWztJDkzBnA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

请使用 **Chrome** 浏览器。

请阅读下方文本熟悉工具使用方法，本文可直接点击一键复制到微信中预览。

## 1 工具 简介

- 支持自定义样式的 Markdown 编辑器(样式在css文件中自行更改)
- 支持微信公众号 手机编辑排版
- 欢迎扫码关注公众号
![](https://mmbiz.qpic.cn/mmbiz_jpg/mIibV0dojFpA35Sfc97VUeEOBWShAfSnxlyvuzjicKia3cCmBjca3ib1HyLmfib7FaiciadpraFr2oDMsDicWztJDkzBnA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)

## 2 主题在css文件中，如有能力自行更改

## 3 通用语法

### 3.1 标题

在文字写书写不同数量的`#`可以完成不同的标题，如下：

# 一级标题

## 二级标题

### 三级标题

### 3.2 无序列表

无序列表的使用，在符号`-`后加空格使用。如下：

- 无序列表 1
- 无序列表 2
- 无序列表 3

如果要控制列表的层级，则需要在符号`-`前使用空格。如下：

- 无序列表 1
- 无序列表 2
  - 无序列表 2.1
  - 无序列表 2.2


### 3.3 有序列表

有序列表的使用，在数字及符号`.`后加空格后输入内容，如下：

1. 有序列表 1
2. 有序列表 2
3. 有序列表 3

### 3.4 引用

引用的格式是在符号`>`后面书写文字。如下：

> 读一本好书，就是在和高尚的人谈话。 ——歌德

> 雇用制度对工人不利，但工人根本无力摆脱这个制度。 ——阮一峰

### 3.5 粗体和斜体

粗体的使用是在需要加粗的文字前后各加两个`*`。

而斜体的使用则是在需要斜体的文字前后各加一个`*`。

如果要使用粗体和斜体，那么就是在需要操作的文字前后加三个`*`。如下：

**这个是粗体**

_这个是斜体_

**_这个是粗体加斜体_**


### 3.6 链接

微信公众号仅支持公众号文章链接，即域名为`https://mp.weixin.qq.com/`的合法链接。使用方法如下所示：

对于该论述，欢迎读者查阅之前发过的文章，[]()

### 3.7 分割线

可以在一行中用三个以上的减号来建立一个分隔线，同时需要在分隔线的上面空一行。如下：

---

### 3.8 删除线

删除线的使用，在需要删除的文字前后各使用两个`~`，如下：

~~这是要被删除的内容。~~

### 3.9 表格

可以使用冒号来定义表格的对齐方式，如下：

| 姓名       | 年龄 |         工作 |
| :--------- | :--: | -----------: |
| 小可爱     |  18  |     吃可爱多 |
| 小小勇敢   |  20  |   爬棵勇敢树 |
| 小小小机智 |  22  | 看一本机智书 |



### 3.10 图片

插入图片，如果是行内图片则无图例，否则有图例，格式如下：

![这里写图片描述](https://mmbiz.qpic.cn/mmbiz_jpg/mIibV0dojFpA35Sfc97VUeEOBWShAfSnxlyvuzjicKia3cCmBjca3ib1HyLmfib7FaiciadpraFr2oDMsDicWztJDkzBnA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)



图片还可以和链接嵌套使用，能够实现推荐卡片的效果，用法如下：

[![Markdown Nice 最全功能介绍](https://mmbiz.qpic.cn/mmbiz_jpg/mIibV0dojFpA35Sfc97VUeEOBWShAfSnxlyvuzjicKia3cCmBjca3ib1HyLmfib7FaiciadpraFr2oDMsDicWztJDkzBnA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1&wx_co=1&tp=webp)](https://mp.weixin.qq.com/s?__biz=MzI5NjU1ODM2Mg==&mid=2247484904&idx=1&sn=c6cc548ebb9cb8525e0f6f7a29af2e74&chksm=ec43cf9ddb34468b6c55c7f1fb9c1e9c33f199946a378c6d85e55d66f0c4cf081b3932996741&token=1200332396&lang=zh_CN#rd)

## 4. 特殊语法

### 4.1 脚注

> 支持平台：微信公众号。

脚注与链接的区别如下所示：

```markdown
链接：[文字](链接)
脚注：[文字](脚注解释 "脚注名字")
```

例子：[方程式必背指南](https://mp.weixin.qq.com/s?__biz=MzI5NjU1ODM2Mg==&mid=2247484904&idx=1&sn=c6cc548ebb9cb8525e0f6f7a29af2e74&chksm=ec43cf9ddb34468b6c55c7f1fb9c1e9c33f199946a378c6d85e55d66f0c4cf081b3932996741&token=1200332396&lang=zh_CN#rd "Front-end web development")赶紧背过来吧。



### 4.2 代码块



如果在一个行内需要引用代码，只要用反引号引起来就好，如下：

Use the `printf()` function.

在需要高亮的代码块的前一行及后一行使用三个反引号，同时**第一行反引号后面表示代码块所使用的语言**，如下：

```java
// FileName: HelloWorld.java
public class HelloWorld {
  // Java 入口程序，程序从此入口
  public static void main(String[] args) {
    System.out.println("Hello,World!"); // 向控制台打印一条语句
  }
}
```

支持以下语言种类：

```
bash
clojure，cpp，cs，css
dart，dockerfile, diff
erlang
go，gradle，groovy
haskell
java，javascript，json，julia
kotlin
lisp，lua
makefile，markdown，matlab
objectivec
perl，php，python
r，ruby，rust
scala，shell，sql，swift
tex，typescript
verilog，vhdl
xml
yaml
```

如果想要更换代码主题，可在上方挑选，不支持代码主题自定义。

其中**微信代码主题与微信官方一致**，有以下注意事项：

- 带行号且不换行，代码大小与官方一致
- 需要在代码块处标志语言，否则无法高亮
- 粘贴到公众号后，用鼠标点代码块内外一次，完成高亮

diff 不能同时和其他语言的高亮同时显示，且需要调整代码主题为微信代码主题以外的代码主题才能看到 diff 效果，使用效果如下:

```diff
+ 新增项
- 删除项
```

**其他主题不带行号，可自定义是否换行，代码大小与当前编辑器一致**

### 4.3 数学公式

> 支持平台：微信公众号。

行内公式使用方法，比如这个化学公式：$\ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-}$

块公式使用方法如下：

$$H(D_2) = -\left(\frac{2}{4}\log_2 \frac{2}{4} + \frac{2}{4}\log_2 \frac{2}{4}\right) = 1$$

矩阵：

$$
  \begin{pmatrix}
  1 & a_1 & a_1^2 & \cdots & a_1^n \\
  1 & a_2 & a_2^2 & \cdots & a_2^n \\
  \vdots & \vdots & \vdots & \ddots & \vdots \\
  1 & a_m & a_m^2 & \cdots & a_m^n \\
  \end{pmatrix}
$$

公式由于微信不支持，目前的解决方案是转成 svg 放到微信中，无需调整，矢量不失真。

### 4.4 TOC

> 支持平台：微信公众号、知乎。

TOC 全称为 Table of Content，列出全部标题。由于示例标题过多，需要使用将下方代码段去除即可。

```
[TOC]
```

由于微信只支持到二级列表，本工具仅支持二级标题和三级标题的显示。

### 4.5 注音符号

> 支持平台：微信公众号。

支持注音符号，用法如下：

这个工具 这么好用，简直是{喜大普奔|hā há hǎ hà}呀！




