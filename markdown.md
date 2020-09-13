# markdown 常用语法

## 1.各级标题

# 一级别标题 （一级标题下面会有线 根据编辑器的不同有所区别）
## 二级标题 （二级标题下面会有线 根据编辑器的不同有所区别）
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 2.列表
### 2.1无序列表 （* + - 都可以表示无序列表，推荐*）
* 1
* 2
* 3
+ 1 
+ 2
+ 3
- 1
- 2
- 3

### 2.2有序列表 
1. 1
2. 2
3. 3

#### 有序列表的序号是根据第一行列表的数字顺序来的
2. 2
5. 6
3. 7

### 3.区块引用
* 使用>进行区块引用
    > 这是伟大的列宁说过的话

* 嵌套引用
> 一级引用    
>> 二级引用
>>> 三级引用
>>>> 四级引用
>>>>> 五级引用      

### 4.分割线
* 分割线可以由* - _（星号，减号，底线）这3个符号的至少3个符号表示，注意至少要3个，且不需要连续，有空格也可以

***
1
- - -
2
___
3

### 5.链接
#### 5.1行内式链接
* 点击查看成语[妙语株连](http://www.baidu.com)


#### 5.2参数式链接
[name]: http://www.baidu.com "名称"
[home]: http://www.baidu.com "首页"
这里是[name],这是里[home]


### 6.图片
#### 行内式图片
![我是图片](https://www.cnblogs.com/images/logo_small.gif)


#### 参数式图片
[博客园]:https://www.cnblogs.com/images/logo_small.gif
![博客园]


### 7.代码框
#### 7.1单行代码框
`<property name="minIdle" value="${alipay.initialPoolSize}" />`


#### 7.2多行代码框
```
<bean id="jdbcTemplate" class="org.springframework.jdbc.core.JdbcTemplate">
	<property name="dataSource" ref="dataSource"></property>
</bean>
```

### 8.表格
表头1 | 表头2
--- | ----
Content Cell | ContentCell
Content Cell | ContentCell

* 在idea中不行，但用其他md编辑器打开是可以的

学号|姓名|分数
-|-|-
20023|小名|20
20024|小红|45
20067|小黑|54

* :表示对齐方式，写在左侧表示左对齐，写在右侧表示右对齐，两边都写表示居中对齐

name | age | sex
:---: | : --- | ---:
tony | 20 | male
lucy | 99 | female

### 9.强调
> 一个星号或者是一个下划线包起来，会转换为<em>倾斜，如果是2个，会转换为<strong>加粗

*斜体*
_斜体2_
**加粗**
__加粗__

### 10.转义
* \\
* \`
* \~
* \_
* \+
* \.
* \!

### 11.删除线
~~这是删除线~~

