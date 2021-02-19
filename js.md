# js


## 1.对象(数组)的深克隆浅克隆

![](img/%E6%95%B0%E7%BB%841.png)

打印:培训

原因: 对象的键值可以是基本数据类型,数字与字符串是一样的键值

堆内存与栈内存

![](img/%E6%95%B0%E5%AD%97%E4%B8%8E%E5%AD%97%E7%AC%A6%E4%B8%B2.png)

数组与object的区别

----
Symbol

![](img/symbol.png)

自己实现一个symbol

---
对象的toString()

![](img/tostring.png)

打印培训

Object.prototype.toString()/valueOf

----
## 2.自执行函数

![](img/%E8%87%AA%E6%89%A7%E8%A1%8C%E5%87%BD%E6%95%B0.png)

输出 '4'

alert 打印的都是字符串

浏览器一执行就是形成栈内存,函数执行把函数执行的上下文压入栈

函数也是对象

![](img/%E6%89%A7%E8%A1%8C.png)

闭包:闭包的作用是保存私有变量

![](img/%E9%97%AD%E5%8C%851.png)

## 3.变态题:闭包

![](img/%E5%8F%98%E6%80%81%E9%A2%98A.png)

解释:

![](img/%E5%8F%98%E6%80%81%E9%A2%98%E8%A7%A3%E9%87%8A.png)

## 4.浅拷贝

![](img/%E6%B5%85%E6%8B%B7%E8%B4%9D.png)

## 5.深克隆

- JSON.stringify() 函数,正则,日期会有问题

![](img/%E6%B7%B1%E5%85%8B%E9%9A%86.png)

- 递归

![](img/%E9%80%92%E5%BD%92%E6%B7%B1%E5%85%8B%E9%9A%86.png)

for...in循环对象的所有枚举属性，然后再使用hasOwnProperty()方法来忽略继承属性。
