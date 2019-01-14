# GFM

Markdown 基本语法。

## Content

- [1.Title](#1.title)
- [2.Wrap](#2.wrap)
- [3.Show](#3.show)
- [4.Part Hightlight](#4.part-hightlight)
- [5.Herf](#5.herf)
- [6.List](#6.list)
- [7.Table](#7.table)
- [8.Indent](#8.indent)
- [9.Insert Picture](#9.insert-picture)
- [10.Insert Code](#10.insert-code)
- [11.Text Format](#11.text-format)
- [12.Back To Top](#12.back-to-top)
- [13.Math Formula](#13.math-formula)


## 1.Title

```Markdown
Big Title
===
Middle Title
---
# Level 1 title
## Level 2 title
### Level 3 title
#### Level 4 title
##### Level 5 title
###### Level 6 title
```
表示为：

Big Title
===
Middle Title
---
# Level 1 title
## Level 2 title
### Level 3 title
#### Level 4 title
##### Level 5 title
###### Level 6 title

[回到顶部](#readme)


## 2.Wrap

`like this <br> there is a wrap` 表示为：

like this <br> there is a wrap.

[回到顶部](#readme)

## 3.Show

### 3-1.Single Show

        Hello erveryone,my name is ian.Thats is this?

### 3-2.Mulity Show

        hello
        hello
        hello

[回到顶部](#readme)

## 4.Part Hightlight
```Markdown
`like this`
```
表示为：`like this`

[回到顶部](#readme)

## 5.Herf

[My Github](https://github.com/i0Ek3) <br>
[My Github with hover](https://github.com/i0Ek3 "悬停显示") <br>

[回到顶部](#readme)


## List

### 6-1.Order List

* can show you this
* like this
* pay attention there is space after '*'

### 6-2.Disorder List

* please add tab on other lines
    * like this
        * like this

[回到顶部](#readme)

## 7.Table

| # | Title | Link | Details |
|---| ----- | ---- | ------- |
|---| ----- | ---- | ------- |
|---| ----- | ---- | ------- |

[回到顶部](#readme)

## 8.Indent

>like this
>>like this
>>>like this
>>>>like this
>>>>>like this

[回到顶部](#readme)

## 9.Insert Picture

![](https://avatars1.githubusercontent.com/u/9475646?s=96&v=4)

[回到顶部](#readme)

## 10.Insert Code

```C++
#include <iostream> //C++
vector<string> svec;
```

```Java
puclic static void main(String[] args) //Java
```

[回到顶部](#readme)


## 11.Text Format

*This is italic1*<br>
_This is italic2_<br>

**This is bold1**<br>
**This is bold2**<br>

~~This is delete line~~<br>
~~Like this~~<br>

***This is bold italic1***<br>
___This is bold italic2___<br>

***~~~This is bold italic delete line1~~~*** <br>
~~~***This is bold italic delete line2***~~~ <br>

[回到顶部](#readme)

## 12.Back To Top

[回到顶部](#readme)

## 13.Math Formula

> [ref1](https://juejin.im/post/5a6721bd518825733201c4a2), [ref2](http://jzqt.github.io/2015/06/30/Markdown中写数学公式/), [ref3](https://www.jianshu.com/p/e74eb43960a1)

Markdown 中的数学公式用`$数学公式$`和`$$数学公式$$`表示，前者为左对齐，后者为居中。

如`$E = mc^2$`表示为$E = mc^2$。

上下标的表示：`$A = B_{i}^n$`表示为$A = B_{i}^n$。

括号的表示：`$f(x,y) = 100 * \lbrace[(x+y)^e] + 5 \rbrace$`表示为$f(x,y) = 100 * \lbrace[(x+y)^e] + 5 \rbrace$。

分数的表示：`$A = \frac{分子}{分母}$`，如$A = \frac{分子}{分母}$。

根号的表示：`$\sqrt[次数]{被开方数}$`，如$\sqrt[n]{10.5}$。

求和的表示：`$\sum_{k=1}^{n}\frac{1}{k}$`表示为$\sum_{k=1}^{n}\frac{1}{k}$。

积分的表示：`$\int_a^b f(x,y)dx$`表示为$\int_a^b f(x,y)dx$。

其他运算符和希腊字母等请参考上述三个链接。

[回到顶部](#readme)
