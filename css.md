# css面试题

## 1.水平垂直居中
- 定位:三种
- display:flex
- javaScript
- display:table-cell
  
### 定位
必须知道宽高
![](img/%E5%AE%9A%E4%BD%8D1.png)
![](img/%E5%AE%9A%E4%BD%8D2.png)

不需要具体宽高,兼容性不好
![](img/%E5%AE%9A%E4%BD%8D3.png)

### display:flex
![](img/flex.png)

### js写法
![](img/js%E5%AE%9E%E7%8E%B0.png)

### table-cell

![](img/table-cell.png)


## 2.css 盒模型

box-sizing: content-box  标准盒模型
![](img/%E6%A0%87%E5%87%86%E7%9B%92%E6%A8%A1%E5%9E%8B.png)

box-sizing: border-box  IE盒模型
![](img/ie%E7%9B%92%E6%A8%A1%E5%9E%8B.png)

flex盒模型
![](img/flex%E7%9B%92%E6%A8%A1%E5%9E%8B.png)

## 3.左右固定,中间自适应(float+负的margin)

![](img/html1.png)

![](img/HTML2.png)

calc:

![](img/calc.png)

flex

![](img/flexhtml.png)
![](img/flex1.png)

定位:

![](img/%E5%AE%9A%E4%BD%8D.png)

## 4.移动端响应布局开发三大方案

- media
- rem
- flex
- vh/vw
  
## 5.z-index工作原理

脱离文档流:absolute,float

## 6.谈谈对H5 的理解

## 7.如何使一个div里面的文字垂直居中,且该文字的大小根据屏幕大小自适应

## 5.下边哪个渲染性能更高

第二个:从右向左解析

![](img/%E6%B8%B2%E6%9F%93.png)