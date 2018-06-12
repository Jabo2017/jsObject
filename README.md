## 1、什么是对象？
  --> 对象可以有自己的私有属性

  --> 只要是new 出来的都是对象

  --> 不同对象肯定不相等

  --> 对象都会有引用机制：* 如果不想引用就从新赋值
  	
  	* 扩展：
  	  ————内存机制
  	  ————回收机制  
  	  		>null	 可以删除对象
  	  		>delete  只可以删除对象的属性
  	  ————生命周期


## 2、
字面量 -- ：无法挂载私有属性，字面上就能显示

包装类 -- ：没有new的函数声明就是包装类 


## 3、typeof : 类型判断

function、 string、object、symbol、 undefined、boolean、*null
typeof symbol() //es6 新增



真正的数据类型

undefined、null、布尔值、字符串、数值、对象、symbol


*面向对象最有用的就是私有属性


-->在普通函数下this指向window

-->有事件源的指向事件源本身

-->在定时器下除es6 this 指向window

-->在对象下this 指向本身



类     --浏览器分类

原型   --类的方法prototype

原型链 --继承

		 -- 自定义类的继承
		 a.prototype = new b();


		 call 改变this指向的，并且调用了一次这个函数

		 第一个参数是指定的对象

		 从第二个参数到之后的参数就是调用函数的形参


		 apply 改变this指向

		 第一个参数和call一样

		 第二个参数：是个对象数组

		 数组的第一个参数到最后就是调用函数的从第二个参数之后的到最后


'__proto__' 与 prototype 的区别

	https://blog.csdn.net/ligang2585116/article/details/53522741



String.prototype







