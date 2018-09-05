# 单元测试异常情况排除

#介绍

代码增加单元测试的时候，对依赖需要修改，显示的依赖已经增加，少量的隐形依赖需要根据运行态的异常增加。下面的内容都是血的教训而来的，珍贵无比。喜欢就支持一下，给个STAR吧。

# Error_1

SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".

SLF4J: Defaulting to no-operation (NOP) logger implementation

SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.

增加下面内容

	<dependency>
	
		<groupId>ch.qos.logback</groupId>
		
			<artifactId>logback-classic</artifactId>
			
			<version>1.2.3</version>
			
			<scope>test</scope>
			
		</dependency>
