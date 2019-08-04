1.环境搭建
anaconda环境配置
登录https://www.anaconda.com 下载python3.7 版本,或者进python官方网站下载

解释器
http://www.jetbrains.com/pycharm/download/#section=windows 下载了PyCharm编译器

2.python初体验

print 和 input
print输出字符串
a = 1 
b = 2 
c = 3
print(a*b*c)
6

input输入字符串 
a = input('你想说什么呢：')
print(a)

3.python基础讲解

python变量特性+命名规则
变量特性
变量的概念基本上和初中代数的方程变量是一致的，只是在计算机程序中，变量不仅可以是数字，还可以是任意数据类型。
命名规则
变量在程序中就是用一个变量名表示了，变量名必须是大小写英文、数字和_的组合，且不能用数字开头。

注释方法
#表示单行注释，例
#print('hello world')
'''表示多行注释,例
'''
print（'hello,world'）
'''

python中“：”作用
Python中用冒号和缩进来区分代码层次
Python中用冒号来进行切片


学会使用dir( )及和help( )
dir()用来查询一个类或者对象所有属性
help()函数帮助我们了解模块、类型、对象、方法、属性的详细信息

import使用
直接使用import来导入模块

pep8介绍
PEP8是针对python代码格式而编订的风格指南，采用一致的编码风格可以令代码更加易懂易读！

4.python数值基本知识

python中数值类型，int，float，bool，e记法等
int整数型
float浮点型
bool布尔型
e记法 1.23e-7表示1.23*10**（-7）

算数运算符
+	加 - 两个对象相加	
-	减 - 得到负数或是一个数减去另一个数	
*	乘 - 两个数相乘或是返回一个被重复若干次的字符串	
/	除 - x除以y	
%	取模 - 返回除法的余数	
**	幂 - 返回x的y次幂	
//	取整除 - 返回商的整数部分（向下取整）

逻辑运算符
and	x and y	布尔"与" - 如果 x 为 False，x and y 返回 False，否则它返回 y 的计算值。
or	x or y	布尔"或"	- 如果 x 是非 0，它返回 x 的值，否则它返回 y 的计算值。	
not	not x	布尔"非" - 如果 x 为 True，返回 False 。如果 x 为 False，它返回 True。

成员运算符
in	如果在指定的序列中找到值返回 True，否则返回 False。	x 在 y 序列中 , 如果 x 在 y 序列中返回 True。
not in	如果在指定的序列中没有找到值返回 True，否则返回 False。	x 不在 y 序列中 , 如果 x 不在 y 序列中返回 True。

身份运算符
s	is 是判断两个标识符是不是引用自一个对象	x is y, 类似 id(x) == id(y) , 如果引用的是同一个对象则返回 True，否则返回 False
is not	is not 是判断两个标识符是不是引用自不同对象	x is not y ， 类似 id(a) != id(b)。如果引用的不是同一个对象则返回结果 True，否则返回 False。

运算符优先级（从高到底）
**	指数 (最高优先级)
~ + -	按位翻转, 一元加号和减号 (最后两个的方法名为 +@ 和 -@)
* / % //	乘，除，取模和取整除
+ -	加法减法
>> <<	右移，左移运算符
&	位 'AND'
^ |	位运算符
<= < > >=	比较运算符
<> == !=	等于运算符
= %= /= //= -= += *= **=	赋值运算符
is is not	身份运算符
in not in	成员运算符
not and or	逻辑运算符
