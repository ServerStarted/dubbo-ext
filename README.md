### dubbo 扩展包

使用dubbo，直接依赖这个这个包，不需要再引入dubbo 依赖。

在pom.xml 文件中加入依赖：
```xml
<dependency>
	<groupId>com.serverstarted</groupId>
	<artifactId>dubbo-ext</artifactId>
	<version>${dubbo-ext.version}</version>
</dependency>
``` 

在spring 的配置中加入dubbo-ext 的配置：
```xml
<import resource="classpath*:dubbo-ext-appcontext.xml" />
```

#### dubbo 加入cat filter

这样在cat 中可以监控dubbo 服务

