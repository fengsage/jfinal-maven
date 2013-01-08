Jfinal是个不错的框架～ 但因为还未被收入maven仓库，maven用户比较麻烦。

加入本地仓库

	git clone https://github.com/fengsage/jfinal-maven.git
	cd jfinal-maven
	mvn clean install
	
引用

	<dependency>
		<groupId>com.jfinal</groupId>
		<artifactId>jfinal</artifactId>
		<version>1.1.6</version>
	</dependency>
