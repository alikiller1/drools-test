# drools-test
一个简单的drools应用demo

调用步骤
1.maven install 生成jar
2.在pom.xml 文件添加1生成的jar包依赖
3.在pom.xml 文件添加
<!-- https://mvnrepository.com/artifact/org.drools/droolsjbpm-tools-distribution -->
	<dependency>
		<groupId>org.drools</groupId>
		<artifactId>droolsjbpm-tools-distribution</artifactId>
		<version>6.3.0.Final</version>
		<type>pom</type>
	</dependency>