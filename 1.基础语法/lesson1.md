# [TOC]

一级标题
========

二级标题
----  

最多支持六级标题：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 粗体

**我是粗体**  
__我也是粗体__

## 斜体

*我是斜体*  
_我也是斜体_

## 没有空行

我是第一行
我是第二行

## 有空行

我是第一行

我是第二行

## 段内换行

我是第一行，如果段内想换行，需要在结尾插入两个以上**空格+回车**  
我是第二行  


## 有序列表

1. 我有一个梦想
2. 我有两个梦想
3. 我有三个梦想

## 无序列表

### 使用星号

* 使用【星号】标识无序列表
* 使用【星号】标识无序列表
* 使用【星号】标识无序列表

### 使用加号

+ 使用【加号】标识无序列表
+ 使用【加号】标识无序列表
+ 使用【加号】标识无序列表

### 使用减号

- 使用【减号】标识无序列表
- 使用【减号】标识无序列表
- 使用【减号】标识无序列表

### 嵌套列表

- 第一层列表
    + 第二层列表
        + 第三层列表
            + 第四层列表  

### 有序列表和无序列表相互嵌套

1. 我是第一层列表哦
    - 我是第二层列表
        1. 我是第三层列表
        2. 我也是第三层列表
            - 我是第四层了哦

 ## 分割线
 ### 星号

 ***

 * * *

 ********

 ### 减号

 ---

 - - - 

 ------------

 ### 下划线

 ___

 _ _ _

 __________

## 图片

### 本地图片：无文字版

![](./I%20Love%20Markdown.jpg)

### 本地图片：有文字版

![本地图片](./I%20Love%20Markdown.jpg)

### 网络图片

![网络图片](https://pics5.baidu.com/feed/4ec2d5628535e5dd9969051de0ea78e4cf1b6267.jpeg@f_auto?token=94903c013d7cc6926dd8b9942d31a1ab)

## 文字链接

在日常工作中我们经常使用的网址有[Google](https://www.google.com/)、[GitHub](https://github.com/)、[Stack Overflow](https://stackoverflow.com/?utm_source=rss&utm_medium=rss)

## 引用链接

在日常工作中我们经常使用的网址有[谷歌][Google]、[GitHub]、[Stack Overflow]

[Google]:https://www.google.com/
[github]:https://github.com
[Stack Overflow]:https://stackoverflow.com/?utm_source=rss&utm_medium=rss

## 网址链接

<https://www.baidu.com>

<761709849@qq.com>

## 代码块

### 行内代码

使用`cd ..`命令切换到上一级目录

使用`mkdir name`命令创建文件夹

### 代码块:以TAB开头
    #include <iostream>
    using namespace std;

    int main()
    {
        cout << "Hello Markdown" << endl;
        return0;
    }

### 代码块：以4个空格开头
    #include <stdio.h>

    int main()
    {
        printf("Hello Markdown\n");
        return 0;
    }

### 围栏代码块
```pyhton
def printf_name():
    printf("Markdown")
```

### 使用规范

如果你想跑路可以执行`rm -f * /`命令

如果你不想`跑路`请限制执行删除命令的权限

根本更多信息请查看`README.md`

## 引用
> 我是引用的句子，请在我前面加上>(小于号)

正常的句子其实是这样的

## 多行引用1

> 这是多行引用中的第一行，我的最后有两个空格  
这是多行引用的第二行

## 多行引用2

> 这是多行引用中的第一行  

> 这是多行引用中的第二行

## 引用中嵌套引用

> 引用中是可以嵌套的
>> 我是引用中嵌套

## 引用中使用其他Markdown标记
> 来点击查看[百度](https://www.baidu.com)  
> **加粗**和*斜体*也可以使用

## 转义

\\  
\*  
\`
\_  
\{}  
\[]  
\()




            
    

