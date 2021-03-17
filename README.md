## 极客时间课后作业

### 第三周

##### 作业运行说明

```shell
mvn clean package -U
java -jar .\user-web\target\user-web-v1-SNAPSHOT-war-exec.jar
```

运行成功后，可访问 http://localhost:8080/jolokia/read/jolokia:type=User 查看jolokia注册的MBean User

Microprofile config API 待实现
