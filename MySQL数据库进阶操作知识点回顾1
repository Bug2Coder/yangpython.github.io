MySQL数据库进阶操作

一:查询强化

查询所有信息:select * from 表名
查询指定信息:select 字段名1,字段名2 from 表名


二:as 起别名 (AS可省略)

select id as 序号,name as 姓名 from 表名
select id 序号,name 姓名 from 表名  

注:AS起别名在创建视图和自关联时必须使用,以解决在表的合并后表名冲突问题

三:消除重复行
select distinct 字段1,字段2 from 表名 
注: 在 select 后加上 distinct 可消除查询数据的重复性

四:条件查询

select * from 表名 where 条件

注:where 后加条件 进行对数据进行限制
where支持多种运算符:
比较运算符
逻辑运算符
模糊查询
范围查询
空判断

五:比较运算符

等于: =
大于: >
大于等于: >=
小于: <
小于等于: <=
不等于: != 或 <>

六:逻辑运算符

and 和 表示条件并立
or  或 表示条件满足最少一个
not 非 对条件进行否定

七:模糊查询

like
 % 表示任意多个任意字符
 _ 表示一个任意字符
 
 八:范围查询
 
 in 表示在一个非连续的范围内 如: in (1,3,5)
 between ... and ...表示在一个连续的范围内 如: between 3 and 8 表示从 3 到 8
 
 九:空判断
 
 判断空:is null
 判断非空:is not null
 
 十:优先级

优先级由高到低的顺序为：小括号，not，比较运算符，逻辑运算符
and 比 or 先运算，如果同时出现并希望先算 or，需要结合 () 使用
 
 
