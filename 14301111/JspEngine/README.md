本次作业启动方法：
  1.将项目导入到eclipse 其中注意JRE的buildpath配置正确，因为不同机器可能会有偏差
  2.启动server包里的Server.java文件
  3.在浏览器端访问 http://localhost:8080/test.jsp 测试jsp的效果
  4.在浏览器端访问 http://localhost:8080/index.html 测试html的效果
  
注意：
  如果在启动Server.java时出现空指针异常，需要将jdk中lib目录下的tools.jar包复制到当前Eclipse使用的jre路径下的lib里，因为多数eclipse不支持动态编译java
