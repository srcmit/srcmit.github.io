---
layout: post
title:  "Java知识点"
date:   2017-02-26
desc: "details"
keywords: "Java, details"
categories: [Java]
tags: [private]
icon: icon-ruby
---
# <b>Java-Details</b>
``` java
>1.输出字符串时不能串行

>2.一般直接数默认类型
   123    ——————————>int
   123.32 ——————————>double
     一般赋值时经常会出现不一致问题，但是如果范围小的赋值给范围大的回自动隐式
   转换数据类型
   such as   short a=123;

>3.但是已经定义的整型变量就没有这么好的机制了
   such as
   int i=123;
   short a=i;//ERROR

>4.JAVA的截断机制[显示类型转换]
   such as
  char a=(char)65.25
  
>5.注意隐式转换没有截断机制

>6.string数据类型是引用类型而不是基本类型

>7.数据类型的相互转换
   string to int
   Integer.parseInt();
   string to doble
   Double.parseDouble();
   
>8.循环跳出
   outer:
		for(int i=0;i<10;i++){
			for(int j=0;j<10;j++){
				System.out.println("LOOP Statement!!!");
			//	break outer;
			//	continue outer;
			}
		}

>9.返回值不为空的叫做函数(function) 
   返回值为空的叫做过程(procedure)[void]
   
>10.
   call(调用)
   invoke(引用)

>11.记住什么叫做方法签名：
   方法签名=方法名+参数列表
   参数列表=参数类型+参数顺序+参数数量
   记住这些有什么用处？
   当进行函数重载的时候就知道了
   函数重载的时候是根据签名指定的
   缩小范围来说是方法签名中的参数列表中的参数类型

>12.添加类路径

>13.foreach(for+)
   语法：
   for(elementType element: arrayReferVar){
   //process the element
   }
```



