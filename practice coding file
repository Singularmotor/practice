#coding utf-8
'''print("please type a number less than 10")
n=input()
if n.isdigit()==True:
	a=int(n)
	print("%d"%(a/10))
else:
	print("error")'''
	
	
'''a=input("please guess my name:")
if a=="xxx":
	print("wrong")
else:
	print("correct")'''
	

'''a=input("please guess my name:")
b="correct"
c="wrong"
d=b if a=="xxx" else c
print(d)	'''
	

'''print("guess my salary:")
a=int(input("please type in"))
y="too less"
z="too larger"
b="correct" if a=='1993' else if a<'1993' y else z
print(b)'''


'''h=int(input("please enter my height:"))
while h!=170:
	if h<170:
		print("too less")
		h=int(input("please re-enter my height:"))
	else:
		print("too more")
		h=int(input("please re-enter my height:"))
if h==170:
	print("correct")'''

'''h=int(input("please enter my height:"))
while True:
	if h<170:
		print("too less")
		h=int(input("please re-enter my height:"))
	else:
		if h==170:
			print("correct")
			break
		else:
			print("too more")
			h=int(input("please re-enter my height:"))'''
		
	
	
'''array=[1,2,5,3,6,8,4]
for i in range(len(array)-1,0,-1):
	print(i)
	for j in range(i):
		print(j)
		if array[j]>array[j+1]:
			array[j],array[j+1]=array[j+1],array[j]
print(array)'''

'''s=0
a=1
while a<10000000000:
	s=s+a
	a=a+1
print(s)'''


'''import random
l=['you','he','her','him','she','i','me','they','them']
print(l[random.randint(0,len(l)-1)])
while True:
	pass'''


'''m=[]
arr=[10,2,3,1,5]
while arr:
	i=0
	o=int(arr[0])
	while i<len(arr):
		if o>=arr[i]:
			i+=1
		else:
			o=int(arr[i])
	m.append(arr.pop(arr.index(o)))
print(m) #correct output but not the right way to complete bubble'''


'''a=int(input("first number:"))
b=int(input("second number:"))
c=int(input("third number:"))
l=[a,b,c]
while l:
	i=0
	o=int(l[0])
	while i<len(l):
		if o<=l[i]:
			i+=1
		else:
			o=int(l[i])
	print(l.pop(l.index(o)))'''


'''for i in range(1, 10):
	for j in range(1, i+1):
		print("%dx%d=%d"%(i,j,i*j),'  ',end='')
	print()'''


'''for i in range(4):
	for j in range(3):
		print(j,end='')
		print(i)'''
	

'''arr=[10,2,3,1,5,66,55,22,88,99,101,50,603]
t=0
for j in range(len(arr)-1):
	for i in range(len(arr)-1-j):
		if arr[i]>arr[i+1]:
			t=arr[i]
			arr[i]=arr[i+1]
			arr[i+1]=t
	
print(arr)#right way to complete the bubble'''


'''def juedu(x):
	if x<0:
		b=-x
	else:
		b=x
	return b
while True:
	a=juedu(int(input()))
	print(a)'''


'''def zuida(a,b,c):
	if a>=b and a>=c:
		return a
	elif b>=a and b>=c:
		return b
	else:
		return c
while True:
	x=int(input())
	y=int(input())
	z=int(input())
	print("max",zuida(x,y,z))'''

	
'''import re

line = "Cats are smarter than dogs"

matchObj = re.match( r'(.*) are (.*?) .*', line, re.M|re.I)

if matchObj:
   print ("matchObj.group() : ", matchObj.group())
   print ("matchObj.group(1) : ", matchObj.group(1))
   print ("matchObj.group(2) : ", matchObj.group(2))
else:
   print ("No match!!")'''
	

'''def ctd(d): #0523作业1
	dx=xx=n=ot=0
	L1='QWERTYUIOPLKJHGFDSAZXCVBNM'
	L2='qwertyuioplkjhgfdsazxcvbnm'
	L3='0123456789'
	for i in d:
		if i in L1:
			dx+=1
		elif i in L2:
			xx+=1
		elif i in L3:
			n+=1
		else:
			ot+=1 #实现字符识别和统计
	return ("大写字母数目",dx),("小写字母数目",xx),("数字数目",n),("其他字符数目",ot)
	#元组显示
x=input()
print(ctd(x))'''
	

'''import random 
i=0
m=[]
while i<20:
	b=random.randint(0,100)
	m.append(b)
	i+=1
print(m)
print(len(m))#生成列表
for j in range(9):
	for i in range(9):
		if m[i]>m[i+1]:
			t=m[i]
			m[i]=m[i+1]
			m[i+1]=t#对前10位数进行升序
for j in range(10,19):
	for i in range(10,19):
		if m[i]<m[i+1]:
			o=m[i]
			m[i]=m[i+1]
			m[i+1]=o#对后10位数进行降序
print(m)'''


'''def smsort(x,y): 
	if y==1: #降序识别
		for j in range(len(x)-1):
			for i in range(len(x)-1-j):
				if x[i]<x[i+1]:
					t=x[i]
					x[i]=x[i+1]
					x[i+1]=t
		return x
	elif y==0: #升序识别
		for j in range(len(x)-1):
			for i in range(len(x)-1-j):
				if x[i]>x[i+1]:
					p=x[i]
					x[i]=x[i+1]
					x[i+1]=p
		return x
	else:
		print("参数定义错误")

print(smsort([1,3,6,5,4,3,9,4,5],1))'''


'''def mult(x,y):
	s=x+y
	d=x-y
	a=x*y
	p=x/y
	return s,d,a,p

print(mult(9,3))'''


'''def power(x):
	return x**3

print(power(5.6))'''


'''def max1(*args):
	t=0
	for j in range(len(args)-1):
		if args[j]>=args[j+1] and args[j]>=t:
			t=args[j]
		elif args[-1]>=t:
			t=args[-1]
	print(t)

max1(3,5,15,-3,2,)'''
		

'''def max2(*arr):
	i=0
	o=int(arr[0])
	while i<len(arr):
		if o>=arr[i]:
			i+=1
		else:
			o=int(arr[i])
	print(o)

max2(3,5,15,-3,2)'''


'''def max3(*args):
	t=args[0]
	for j in args:
		if j>=t:
			t=j
	print(t)
max3(3,5,15,-3,2)'''


'''def test():
	print(666)
	return test()
test()'''


'''def jiec(x):
	t=1
	while x!=0:
		t*=x
		x=x-1
	return t

print(jiec(5))'''


'''def jiec(x):
	a=1
	for i in range(1,x+1):
		a*=i
	print(a)
print(jiec(5))'''


'''import random
w=int(input("guess my weight:"))
w1=random.randint(100,200)
while True:
	if w==w1:
		print("correct")
		print(w1)
		break
	if w>w1:
		print("more")
		print(w1)
		w=int(input("guess my weight:"))
	else:
		print("less")
		print(w1)
		w=int(input("guess my weight:"))'''


'''x = 'iplaypython'
for i in x+5:
	print(i)'''


'''n='x'+
print(n)'''

	
'''a=int()
b=int()
c=int()
d=int()
e=int()
f=int()
y=[a,b,c,d,e,f]
print(y)'''

'''n=input("请输入你的账号：")
p=input("请输入你的密码：")
if n=="test" and p=="mercury":
	print("恭喜你登录成功")
else:
	print("你的账号或密码错误")'''
	
'''print("加密程序")
p=input("你输入的明文：")
m=p+5
print("你发出的密文为：%s"%m)'''


'''df=input()
if df=="加密程序":
	p=input("你输入的明文：")
	l=list(p)
	m=[]
	for i in range(len(l)):
		m.append(chr(ord(l[i])+5))
	o=''.join(m)
	print("你发出的密文为：",o)
elif df=="解密程序":
	p=input("你输入的密文：")
	l=list(p)
	m=[]
	for i in range(len(l)):
		m.append(chr(ord(l[i])-5))
	o=''.join(m)
	print("你发出的明文为：",o)
else:
	print("程序选择错误")'''


'''a=input()
print(end='')
for i in a:
	print(i)'''

	
'''a=input("请你猜我的名字：")
while a!="xxx":
	print("wrong")
	a=input("请你猜我的名字：")
print("correct")'''

'''import urllib.request

url="http://www.baidu.com"
data=urllib.request.urlopen(url).read()
data=data.decode('UTF-8')
print(data)'''


'''import urllib
import urllib.request

data={}
data['word']='Jecvay Notes'
url_values=urllib.parse.urlencode(data)
url="http://www.baidu.com/s?"
full_url=url+url_values

data=urllib.request.urlopen(full_url).read()
data=data.decode('UTF-8')
dt=str(data)


#mydic=open("C:\\Users\\ETC\\Desktop\\1.txt","a+")
#mydic.write("sssss")

def sf(s,p):
	f_obj=open(p,'w')
	f_obj.write(s)
	f_obj.close() #文档备份函数，注意s参数的str输入

sf(dt,'E:\\tmp.txt')'''

'''class human():
	def setname(self,name):
		self.name=name
	
	def getname(self):
		print(self.name)

oo=human()
oo.setname('Joker')
oo.getname()'''


'''for i in range(1,5):
	for j in range(1,i+1):
		print(i,j)
	print()'''

'''import random
ca=random.randint(1,30)
while True:
	age=int(input("猜猜我的年龄:"))
	if age==ca:
		print("猜对了")
		break
	elif age>ca:
		print("猜多了")
	else:
		print("猜少了")'''


'''a=int(input("输入第一个数:"))
b=int(input("输入第二个数:"))
c=int(input("输入第三个数:"))
d=int(input("输入第四个数:"))
e=int(input("输入第五个数:"))
m=[a,b,c,d,e]
for j in range(len(m)-1):
	for i in range(len(m)-1-j):
		if m[i]>m[i+1]:
			t=m[i]
			m[i]=m[i+1]
			m[i+1]=t		
print(m)'''	
		
		
