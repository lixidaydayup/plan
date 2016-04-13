# plan
my study plan

### 2016-04-14 

1.  学习html的100个例子 目标: 走完所有的例子 知道常用标签的含义
    如 
     - button
     - div
     - form
     - input type='submit'
     - input type='text'
     - textarea
     - select
     - img
     - a
     
2.  了解selenium断言 (assertion) 知道如何判断页面上的某个元素是否存在
    
    目标 利用selenium登录进网页以后 断言邮件的数量为4 并打印每个邮件的标题 
    > 提示 这里可以使用By.className来实现 得到一个List 然后遍历这个List 


### 2016-04-15

1. 学习JUnit 
    > 了解单元测试 我写一个类 你可以使用Junit对这个类进行测试并在eclipse中实现
   
2. 了解Junit的各种断言 例如 AssertTrue, AssertNotNull, AssertEquals ...
    > 可以对一个类的方法进行多种断言

3. 了解测试覆盖率 了解覆盖率的含义
    
    ###### 为什么强调覆盖率? 因为从代码层面来说 测试代码能触发被测代码执行更多行数
    ###### 就更有可能发现bug 同样的 如果测试代码能触发被测试代码的各种场景(if-else-if-else-...)
    ###### 那么也就更容易发现bug

    > 安装eclipse测试覆盖率插件 可以执行junit并得到覆盖率 要求行覆盖率50%以上
    
### 2016-04-16
    
1. 了解性能压测的意义，主要方法， 关注的点(rt, qps)
2. 了解并发 模拟并发的常用方法(多线程)
3. 了解java的Runnable接口 会写一个实现Runnable接口的线程程序 每秒打印一个数字

    > 写2个线程 交替打数字

### 2016-04-17

1. 了解jmeter 
> 使用jmeter进行压测我的测试网站 得到测试报告

3. 了解如何使用谷歌浏览器的控制台发现加载很慢的资源 从而找到突破点
> 打开mail.163.com 找到加载慢的资源 分析是因为什么慢


