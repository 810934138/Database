# Database
哈工大数据库实验：2016年

#实验一
	正常的sql语句

#实验二
	Python中链接数据库：执行sql语句并将结果输出

#实验三
	实现一个数据库系统：基于PyQt4写的界面，并实现实验要求

#实验四
	1）实现关系选择算法；
	2）实现关系投影算法；
	3）实现连接操作算法（要求实现三种连接操作算法：Nest-Loop- Join算法，Hash-Join算法）；
	4）实现集合并操作算法（要求实现基于排序的并操作执行算法）；
	
#实验五
	select [ ename = 'marry' & dname = 'research' ] ( employee join department )
	projection [ bdate ] ( select [ ename = 'jhon' & dname = 'research' ] ( employee join department ) )
	select [ essn = '01' ] ( projection [ essn , pname ] ( works_on join project ) )
	