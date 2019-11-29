# Java-basics
我的java学习笔记

* [基础知识](#基础知识)
    * [常用dos命令](#常用dos命令)
    * [Java运行机制](#Java运行机制)
    * [注释](#注释)
    * [关键字](#关键字)
### 基础知识
#### 常用dos命令
dir：列出当前目录下的文件及文件夹<br>
md：创建目录<br>
rd：删除目录<br>
cd：进入指定目录<br>
cd..：退回到上一级目录<br>
cd\：退回到根目录<br>
del：删除文件<br>
exit：退出dos命令行<br>
#### Java运行机制
特点：
    面向对象（封装、继承、多态）<br>
    健壮性、完美性（去掉指针、内存申请与释放）<br>
    跨平台(jvm)<br>
    Java核心机制：jvm,gc<br>
    jdk包含jre<br>
    java文件名必须与public class 类名相同<br>
    helloworld：
```java
    public static void main(String[] args) {
    
    }
```
[helloworld.java](src/helloworld.java)

#### 注释
```java
// 单行注释
/* 
    多行注释
*/ 
/** 按回车 文档注释
*
*  @author hycdog
*  @version 1.0.0
*/
```
#### 关键字
被Java语言赋予了特殊含义，用作专门用途的字符串<br>
特点：全为小写

* 用于定义数据类型：
```java
class interface enum byte short
int long float double char
boolean void
```

* 用于定义数据类型的关键字：
```java
true false null
```

* 用于流程控制:
```java
if else switch case default
while do for break continue
return
```

* 用于定义访问权限：
```java
private protected public
```

* 用于定义类、函数、变量修饰符：
```java
abstract final static synchronized
```

* 类之间关系：
```java
extends implements
```

* 建立和引用实例，判断实例：
```java
new this super instanceof
```