# qsmi
 Questions in Spider Man Interview 爬虫工程师面试常见问题
 
 目前问题与答案正在收集中，请大家踊跃参与。在 issues 处提交你的问题与答案即可，我会每天定时收录到文档中
 
 # 一、Python 基础部分
## 1.1 Python 基本功
### 1.1.1 简述Python 的特点和优点
答：
### 1.1.1 Python 有哪些数据类型？
答：
### 1.1.3 列表和元组的区别
答：
### 1.1.4 Python 是如何运行的
答：
### 1.1.5 Python 运行速度慢的原因
答：

### 1.1.6 面对 Python 慢的问题，有什么解决办法
答：

### 1.1.7 描述一下全局解释器锁 GIL
答：

### 1.1.8 深拷贝 浅拷贝
答：

### 1.1.9 is 和 == 的区别
答：

### 1.1.10 文件读写
答：
### 1.1.11 请用一行代码实现
请分别使用匿名函数和推导式这两种方式将 [0, 1, 2, 3, 4, 5] 中的元素求乘积，并打印输出元组。

### 1.1.12 请用一行代码实现
用 reduce 计算 n 的阶乘（n!=1×2×3×...×n）

### 1.1.13 请用一行代码实现
筛选并打印输出 100 以内能被 3 整除的数的集合

### 1.1.14 请用一行代码实现
```
text = 'Obj{"Name": "pic", "data": [{"name": "async", "number": 9, "price": "$3500"}, {"name": "Wade", "number": 3, "price": "$5500"}], "Team": "Hot"'
```
打印文本中的球员身价元组，如 ($3500, $5500)


### 1.1.15 请写出递归的基本骨架

### 1.1.16 切片
请写出下方代码输出结果
```
tpl = [0, 5, 10, 15, 20, 25, 30, 35, 40, 45, 50, 55, 60, 65, 70, 75, 80, 85, 90, 95]

print(tpl[3:])
print(tpl[:3])
print(tpl[::5])
print(tpl[-3])
print(tpl[3])
print(tpl[::-5])
print(tpl[:])
del tpl[3:]
print(tpl)
print(tpl.pop())
tpl.insert(3, 3)
print(tpl)
```
### 1.1.6 文件路径
打印输出当前文件所在目录路径

打印输出当前文件路径

打印输出当前文件上两层文件目录路径

### 1.1.17 请写出运行结果，并回答问题
```
tpl = (1, 2, 3, 4, 5)
apl = (6, 7, 8, 9)
print(tpl.__add__(apl))
```
问题：tpl 的值发生变化了吗？

答：

### 1.1.18 请写出运行结果，并回答问题
```
name = ('James', 'Wade', 'Kobe')
team = ['A', 'B', 'C']

tpl = {name: team}
print(tpl)
apl = {team: name}
print(apl)
```
问题：这段代码能运行完毕吗？为什么？它的运行结果是？
答：
### 1.1.19 装饰器
请写出装饰器代码骨架

简述装饰器在 Python 中的作用


### 1.1.20 多进程 多线程
多进程更稳定还是多线程更稳定？为什么？

多线程的致命缺点是什么？

进程间通信有哪些方式？

## 1.2 Python 细节问题
### 1.2.1 **连接字符串用join还是+**


### 1.2.2 Python 垃圾回收机制


### 1.2.3 递归
Python 递归深度默认是多少？递归深度限制的原因是什么？




# 二、Python 进阶知识
2.1
2.1.1 __new__  __init__ 的区别

2.2

2.2.1 请编写一个用于文件读写的上下文管理器

2.2.2 请编写一个用于文件读写的异步上下文管理器，并编写 propty 提供外部访问
# 
# 三、爬虫基础部分
# 
# 四、爬虫框架部分
# 
# 五、爬虫进阶知识
# 
# 六、数据库部分
# 
# 七、算法与数据结构
## 7.1
### 7.1.1 时间复杂度
假设现有腾讯体育中热火队 11 名球员、搜狐体育中热火队 13 名球员要将两个队伍中球员依次拿出来进行属性匹配，以确定同一球员在两个网站中的不同 url id。
请说明比对的时间复杂度并画出比对思路
# 
# 八、HTTP 协议 WebSocket 协议
# 
# 九、爬虫工作的见解与展望
 
