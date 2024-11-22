# intellij IDEA启动项目
- tomcat version: 12.0
- jdk version: 21
- ant version: 1.10.15

1. 标记java目录为source root
2. 执行ant命令: ide-intellij
3. 添加ant.jar到项目依赖包，如果上一步没有加载此jar文件的话
4. 启动项目中的main()方法： `org.apache.catalina.startup.Bootstrap.main`

