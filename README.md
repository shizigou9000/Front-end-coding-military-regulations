# 前端编码军规

一：永远把安全放在第一位。  
二：时刻考虑性能的问题。   
&emsp;&emsp;1：赋值运算或者定义变量的时候，把相关关联的变量可以定义在一起（一个对象下面或者数组里面）,下面的例子：    	
 ```
Good code

var personal = {
	name: 'Tom',
   age: 30,
   sex: 'male'
} 
```
 ```
Bad code

var personalName = 'Tom' 
var personalAge = 30 
var personalSex = 'male' 
```
三：让你的代码或者团队的代码保持格式统一。  
四：一个操作如果有较长时间的停顿，考虑添加过渡行为。
