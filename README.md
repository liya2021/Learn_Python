# Learn_Python - bobin education
## Variables
### name - no keywords
	import keyword
	print(keyword.kwlist)
### string
	.title()
	.upper()
	.lower()
	.strip()
 	\n \t
 	type()
### int & float
	str()
### python rules
	import this
### python terminal
	python (command line)
	print('hello world')
	exit()
## contorl flow
### if - elif - else
	if:
	if: - else:
	if: - elif: - else:
only one branch can be excuted

block should indendant

if bool:

	False
	0
	''
	[]
	{}
	func()	#return 0
### while 
	while:
	while: - else:
注意while的True条件，不要变成死循环，while需要索引变量i

### continue & break

	i = 1
	while i < 10:
		i += 1
		if i % 2 > 0:
			continue
		print(i)	#continue 奇数跳过

	i = 1
	while 1:
		print(i)
		i += 1
		if i > 10:
			break	#break i > 10 跳出循环
		
### for 遍历列表元素
	for i in []
#### string - 格式化
	
	{}.format()
	print('%d'%a)  %d, %f, %s   # 只能是这三种数据类型
	print(f'the value is { 10 + 10}')    #在字符串中使用函数&表达式
	print(r'\n转义符还原成raw string, or \\t, \\n')
	
#### list - []

	li = [1, 3, 5]
	li.append()    #只能一个数据,自动赋值给li
	s = li.pop()    #删除的值可以弹出来
	del li[0]    #删除的值扔掉了
	li.remove()    #根据值，删除元素
	li[0]    #下标取值
	li.index()    #下标
	print(fruit[开始下标:结束下标:步长])
	print(fruit[::-1])  #reverse
	.sort(reverse=True)
	.sorted
	.reverse
	
#### tuple - () - 元素无法修改

	tup_1[0]
	
#### dict - key 不允许重复, 不可变类型

	{key:value,key_1:value_1}
	
	for a in range(100):
    new_alien = {'color':'green','points':5,'speed':'slow'}
    aliens.append(new_alien)
	
	cars = [['BMW', 8.5], ['BENS', 8.3], ['AUDI', 7.9]]
	dict4 = dict(cars)
	print(dict4) # {'BMW': 8.5, 'BENS': 8.3, 'AUDI': 7.9}
	


	
### Index of Python Enhancement Proposals - PEP 8
缩进 - 制表符 -（空格和制表符不能混用）
行长 - 79 个字符
空行

## web
### A-class IP
web.zhuji.zhuji.zhuji
12.0.0.1

#### well known ports
0 - 1023

80 - http
21 - ftp

root

PID - bendi lable

## 函数
变量范围

mutable - variant
immutable - variant


	def changeme(mylist):
    "修改传入的列表"
    	mylist.append([1, 2, 3, 4])
    	print("函数内取值: ", mylist)
    	return


	# 调用changeme函数
	mylist = [10, 20, 30]
	changeme(mylist)
	print("函数外取值: ", mylist)

	*args  #tuple
	**kargs #dict


	
	
	
