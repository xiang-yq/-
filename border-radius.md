`boeder`属性的几种变化,通过对这几种基本变化的延伸引用,可以变化出各种丰富的案例出来
![案例](https://images.cnblogs.com/cnblogs_com/binyong/bordr1.gif)
这些变化其实就是基于如下的基本原理:
```
border-left:20px transparent dotted;

border-top:20px green solid;

border-right:20px transparent dotted;

border-bottom:20px orange solid;

width:0px;

height:0px;

overflow:hidden;
```
注意:`transparent`是用来透明的,并且要设置的线条的样式为点线`dotted`.
宽高为0 就只会显示边框部分
斜角的组合规律如下:
1 `border-left`和`border-top`组成从左上到右下的斜线
2 border-right和border-top组成从右上到左下的斜线
3 border-right和border-bottom组成从右上到左上的斜线
4 border-left和border-bottom组成从左下到右上的斜线
做三角形
宽高为0 其他边界线颜色设置各不同就为三角形.
```
width:0px;
height:0px;
border:10px solid;
border-color:#ff3300 #0000ff #339966 #00ff00;
```
设置宽度不为0时没会出现梯形:
```{
    width:10px; 
    height:10px; 
    border:10px solid; 
    border-color:#ff3300 #0000ff #339966 #00ff00;
}
```
只想出现一个梯形或者三角形的时候,只需要设置边框颜色为transparent;
做圆或者圆角边框
`border-raidus: 50%  / xxpx;`
`transform`: rotate(xxdeg)  指定 元素的 偏移  和 旋转  和 拉伸  和  缩放 