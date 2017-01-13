源工程的maven坐标
```xml
<dependency>
    <groupId>com.github.albfernandez</groupId>
    <artifactId>javadbf</artifactId>
    <version>0.8.0</version>
</dependency>
```

### 修改如下
 - 修改因dbf文件head不是标准的结束符(0D)而引发的读取字段数量不正确