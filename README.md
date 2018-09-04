# What is spring_unittest?

spring unittest 单元测试 样例


# Using spring_unittest

spring 的单元测试相对比较复杂
1 不同的项目有不同的用法
2 spring 本身的注解方式，用标准的单元测试无法实列化对象
3 spring 本身提供的内容很多，如WEB，CONTROL 层，不同的用途方法还不同。
4 使用@RunWith(SpringJUnit4ClassRunner.class)
5 使用@ContextConfiguration("file:src/main/webapp/WEB-INF/spring/appServlet/servlet-context.xml") 
6 使用@WebAppConfiguration

不同的使用方法对应不同的自动化生产配置。这个需要人为指定参数。

by wupf@asiainfo.com
