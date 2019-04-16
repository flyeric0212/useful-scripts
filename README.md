## useful scripts

### java 相关

1.show-busy-java-threads  

用于快速排查`Java`的`CPU`性能问题(`top us`值过高)，自动查出运行的`Java`进程中消耗`CPU`多的线程，并打印出其线程栈，从而确定导致性能问题的方法调用。

2. show-duplicate-java-classes

找出`jar`文件和`class`目录中的重复类。用于排查`Java`类冲突问题。

3. find-in-jars  
    
在目录下所有`jar`文件里，查找类或资源文件。

### MySQL 相关

1. show-mysql-qps

用于显示已经连接的MySQL服务器的QPS

### Shell 相关

1. tcp-connection-state-counter

统计各个`TCP`连接状态的个数。用于方便排查系统连接负荷问题。

## Project Shell

用于定义project相关的shell
