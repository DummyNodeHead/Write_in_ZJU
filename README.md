# Write_in_ZJU
写在浙大
## 更新细节一览
### 更新分支dev-Back
添加了使用脚手架搭建的后端项目，在项目中配置了相关依赖，并导入了对应jar包
依赖相关版本见pom.xml
并确定了相关工具版本：
+ Maven 4.0.0
+ Spring Boot 2.6.4
+ JDK 11
#### 使用说明：
+ JDK与Maven需要手动安装， 其余依赖通过Maven导入， Intellij Idea环境下可以通过单击侧边栏上的Maven，刷新后点击下载标识进行下载
+ 启动类位置在Write_in_ZJU\back-end\demo\src\main\java\com\example\demo\CoordinationApplication.java
+ 启动项目方式为运行启动类，默认端口为8080， 目前只有一个localhost:8080/hello可以访问
