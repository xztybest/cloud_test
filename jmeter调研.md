# JMeter调研报告

*****

## JMeter介绍

​		Apache JMeter 是Apache组织的开放源代码项目，是一个100%纯Java桌面应用，用于压力测试和性能测试。

*****

## JMeter特点

1. 支持对多种服务类型进行测试
   1. Web-HTTP,HTTPS
   2. SOAP
   3. Database via JDBC
   4. LDAP
   5. JMS
   6. Mail-POP3(S) and IMAP(S)
2. 支持通过录制/回放方式获取测试脚本
3. 具备高可移植性，纯Java程序
4. 采用多线程框架，允许通过多个线程并发取样及通过独立线程组对不同的功能同时取样
5. 支持缓存和离线的方式分析/回放测试结果
6. 具备高扩展性
   1. 拔插式的取样器支持无限制扩充测试功能
   2. 提供各种负载统计表和可拔插的计时器
   3. 数据分析和可视化插件提供了很好的扩展性及个性化
   4. 支持通过预置函数为测试提供动态输入数据，以及通过预置函数对测试数据进行操作

*****

## JMeter与loadrunner区别

详细可参考链接：https://blog.csdn.net/weixin_43214609/article/details/99443357

## JMeter优缺点

### 优点

1. 不依赖于界面,测试脚本不需要编程，熟悉http请求，熟悉业务流程，就可以根据页面中input对象来编写测试用例。
2. 测试脚本维护方便，可以将测试脚本复制，并且可以将某一部分单独保存
3. 可以跳过页面限制，向后台程序添加非法数据，这样可以测试后台程序的健壮性。
4. 利用badboy录制测试脚本，可以快速的形成测试脚本
5. 使用参数化以及Jmeter提供的函数功能，可以快速完成测试数据的添加修改等
6. 功能测试和性能测试均可完成
7. 开源免费
8. 支持多协议
9. 小巧
10. 高效、功能强大

### 缺点

1. 使用Jmeter无法验证JS程序，也无法验证页面，所以需要手工去验证
2. Jmeter的断言功能不是很强大：Jmeter提供的断言功能有限，并且不依赖于界面，无法完成界面相关内容的验证，用Jmeter测试更需要人工测试，人工确认。
3. 就算是jmeter脚本顺利执行，依旧无法确定程序是否正确执行，有时候需要进入程序查看，或者查看Jmeter的响应数据。
4. Jmeter脚本的维护需要保存为本地文件，而每个脚本文件只能保存一个测试用例，不利于脚本的维护。
5. Jmeter的测试脚本的管理不可以纳入版本控制。
6. 不支持前端测试
7. 不支持IP欺骗
8. 使用过程中单位不规范（有时候单位秒、分）

*****

## JMeter工作原理

![](https://github.com/xztybest/cloud_test/blob/picturetmp/%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86%E5%9B%BE%E7%89%87.png)

*****

## JMeter组件图

![](https://github.com/xztybest/cloud_test/blob/picturetmp/JMeter%E7%BB%84%E4%BB%B6%E5%9B%BE.png)

## JMeter作用

1. 接口测试
2. 性能测试：程序算法
3. 压力测试：外在负载
4. web自动化测试
5. 数据库测试
6. java测试

## JMeter功能调研

由于文档过长，请参考链接：https://github.com/xztybest/cloud_test/blob/templatesfile/jmeter%E5%8A%9F%E8%83%BD%E8%B0%83%E7%A0%94.pdf





