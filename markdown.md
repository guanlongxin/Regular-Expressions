***Markdown 标题***

1.使用'='和'-'标记一级和二级标题  

一级标题
=======
二级标题
-------

2.使用#表示1~6级标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

***Markdown 段落格式***  
*斜体文本*  
_斜体文本_  
**粗体文本**  
__粗体文本__  
***粗斜体文本***  
___粗斜体文本___  

***Markdown 列表***  
1.Markdown 支持有序列表和无序列表  
无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容

* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项

- 第一项
- 第二项
- 第三项

2.有序列表使用数字并加上 . 号来表示，如 
1. 第一项
2. 第二项
3. 第三项

3.列表嵌套
* 第一项
    - 嵌套第一项
* 第二项
    - 嵌套第二项
* 第三项
    - 嵌套第三项

***Markdown 区块***  
区块
> 区块引用  
> 菜鸟教程  
> 学的不仅是技术更是梦想  

区块嵌套
> 最外层
> > 第一层嵌套
> > > 第二层嵌套

区块列表  
> 区块表头  
> 1.item1  
> 2.item2
> > * item2.1  
> > * item2.2  
> > * item2.2  

列表区块
* 1.item1
    > item1.1  
    > item1.2
* 2.item2

***Markdown 代码***  

`printf()` 函数  

代码块  
```
#include<stdio.h>

INT32 TestMarkDownFunction()
{
    printf("test markdown\n");
}
```

***Markdown 链接***  

[链接名称](链接地址)

或者

<链接地址>

[GitHub](https://github.com/guanlongxin/)

或者

<https://github.com/guanlongxin/>

高级链接G

这个链接用 1 作为网址变量 [Github][1]  
这个链接用 guanlongxin 作为网址变量 [guanlongxin][Guanlongxin]

[1]: https://github.com
[Guanlongxin]: https://github.com/guanlongxin/


***Markdown 图片***  
![alt 属性文本](图片地址)  
![alt 属性文本](图片地址 "可选标题")  
开头一个感叹号 !  
接着一个方括号，里面放上图片的替代文字  
接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。  
![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

这个链接用 1 作为网址变量 ![RUNOOB]([1]).  
然后在文档的结尾为变量赋值（网址）

[1]: http://static.runoob.com/images/runoob-logo.png  

***Markdown 表格***

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |

| 元字符 | 使用说明 |
| :----: | :-----  |
| * | 星号|
|\b | 单词的|
|\w | 字母|

***Markdown 高级技巧***

[菜鸟教程-markdown高级技巧](https://www.runoob.com/markdown/md-advance.html)