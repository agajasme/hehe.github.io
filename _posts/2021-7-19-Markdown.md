---
layout: post
#title: HelloWorld
tags: 
- jekyll theme
- jekyll
math: true

---
Markdown基本语法

转载  
来源：简书  
作者：高鸿祥  
链接：https://www.jianshu.com/p/191d1e21f7ed  

# 一、标题
- # 这是一级标题
- ## 这是二级标题
- ### 这是三级标题
- #### 这是四级标题
- ##### 这是五级标题
- ###### 这是六级标题

# 二、字体
<!--
    加粗
    要加粗的文字左右分别用两个*号包起来

    斜体
    要倾斜的文字左右分别用一个*号包起来

    斜体加粗
    要倾斜和加粗的文字左右分别用三个*号包起来

    删除线
    要加删除线的文字左右分别用两个~~号包起来
-->
- **这是加粗的文字**
- *这是倾斜的文字*
- ***这是斜体加粗的文字***
- ~~这是加删除线的文字~~

# 三、引用
<!--
    在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>
    n个...
    貌似可以一直加下去，但没神马卵用
-->
- >这是引用的内容
- >>这是引用的内容
- >>>>>>>>>>这是引用的内容

# 四、分割线
<!--
    三个或者三个以上的 - 或者 * 都可以。
-->
---
----
***
*****

# 五、图片
<!--
    ![图片alt](图片地址 ''图片title'')

    图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
    图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
-->

![勇敢牛牛](/image/img_brave_ox.gif "不怕困难")  

# 六、超链接
<!--
    [超链接名](超链接地址 "超链接title")
    title可加可不加
-->
[百度](http://baidu.com)
[markdown图床](https://www.jianshu.com/p/ea1eb11db63f)

# 七、列表
##### 无序列表
<!--
    无序列表用 - + * 任何一种都可以 - + * 跟内容之间都要有一个空格
-->
- 列表内容
+ 列表内容
* 列表内容

##### 有序列表
<!--
    数字加点 跟内容之间都要有一个空格
-->
1. 列表内容
2. 列表内容
3. 列表内容

##### 列表嵌套
<!--
    上一级和下一级之间敲三个空格即可
-->
- 一级无序列表内容
   - 二级无序列表内容
   - 二级无序列表内容
   - 二级无序列表内容

- 一级无序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
   3. 二级有序列表内容

1. 一级有序列表内容
   - 二级无序列表内容
   - 二级无序列表内容
   - 二级无序列表内容

2. 一级有序列表内容
   1. 二级有序列表内容
   2. 二级有序列表内容
   3. 二级有序列表内容

# 八、表格
<!--
    表头|表头|表头
    ---|:--:|---:
    内容|内容|内容
    内容|内容|内容

    第二行分割表头和内容。
    - 有一个就行，为了对齐，多加了几个
    文字默认居左
    -两边加：表示文字居中
    -右边加：表示文字居右
    注：原生的语法两边都要用 | 包起来。此处省略
-->

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟

# 九、代码
<!--
    单行代码：代码之间分别用一个反引号包起来 
    `代码内容`

    代码块：代码之间分别用三个反引号包起来，且两边的反引号单独占一行
    ```
        代码...
        代码...
        代码...
    ```
-->

`create database hero;`

```
    function fun(){
         echo "这是一句非常牛逼的代码";
    }
    fun();
```