#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题
**加粗**
*斜体*
***加粗斜体***
~~删除线~~

>引用 这是引用的内容
>>这也是引用的
>>>这还是引用的

>>>>还是


分割线

----
----
***
****


图片

![图片](bf.png)
![图片](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

超链接
[百度](https://baidu.com)


## 无序列表

+ 列表1
- 列表二
++列表三 错误

## 有序列表

1. 列表四
2. 列表无
3. 列表6

列表嵌套

- 一级无序列表
   - 二级无序列表



# 代码

 单行代码
 `单行代码`

 多行代码
 ```
 代码1
 代码2
 代码2
 代码2

 ``` 
 #### 尖角提示框
 ```
 <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .box {
            position: relative;
            margin-top: 100px;
            margin-left: 100px;
            width: 200px;
            height: 200px;
            border: 2px solid red;
        }

        .asd {
            position: absolute;
            left: 50%;
            top: -30px;
            width: 0;
            height: 0;
            border: 10px solid;
            border-color: transparent transparent red transparent;
            border-bottom-width: 20px;
            /* border-top-width: 20px; */
        }

        .asd1 {
            border-color: transparent transparent #ffffff transparent;
            top: -28px;
        }
    </style>
</head>

<body>
    <div class="box">
        <div class="asd">
            <div asd1>

            </div>
        </div>
    </div>
</body>

</html>
 ```

# HTML+CSS基础

# 认识网页
网页主要是由文字/图像和超链接等元素构成,还包含音频/视频以及flash等
![图片](5d355b7ec5ff110369.png)

# 常用浏览器介绍
IE 火狐 谷歌 safari苹果系统

# web标准
主要包括结构  表现和行为三个方面

- 结构
   -是内容更清晰,更有逻辑性
- 表现
   - 用于修饰内容的样式
- 行为
   - 内容的交互及操作效果

# 网页的构成
> 看一段远源码 来自不凡学院
   - 结构:指的时用`html`标签描述网页的结构.比如标题/段落/表格/表单等
   - 表现:指的是`css`控制网页的样式.比如字体颜色和大小/背景颜色等
   - 行为 用`javascript`控制页面的交互行为.比如用户点击时,页面如何相应.
# html介绍

 html超文本标记语言

 #### 骨架
 - html标签
 作用网页的根节点
 - head标签
用于存放`title` `meta` `style` `link`等标签,辅助浏览器解析页面,并不会在页面中展示.
- title标签
作用:让页面拥有一个属于自己的标题.
- body标签
作用:页面的主题部分,用于存放网页要展示的标签`p` `h` `a` `img`等
注意:在`<body>`中多个空格或者换行符,会被当作一个来处理.
# 编辑工具介绍
DW  SUBLIME
WEBSTORM
HBuilder
visual studio code

# vscode 基本使用
[链接](https://jingyan.baidu.com/article/7e44095377c9d12fc1e2ef5b.html)

有很多好用的插件功能可以下载

`!`+回车 自动生成页面骨架

