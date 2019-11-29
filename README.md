# Java-basics
我的java学习笔记

* [基础知识](#基础知识)
    * [常用dos命令](#常用dos命令)
    * [Java运行机制](#Java运行机制)
    * [注释](#注释)
    * [关键字](#关键字)
* [基本语法](#基本语法)
    * [保留字](#保留字)
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
    面向对象（封装 继承 多态）<br>
    健壮性 完美性（去掉指针 内存申请与释放）<br>
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

### 基本语法
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

* 用于定义类 函数 变量修饰符：
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

* 用于异常处理的关键字
```java
try catch finally throw throws
```

* 用于包的关键字
```java
package import
```

* 其他修饰符关键字
```java
native strictfp transient volatile assert
```

#### 保留字
Java保留字：现有Java版本尚未使用，但以后版本可能会作为关键字使用。自己命名标记符时要避免使用这些保留字 
```java
byValue cast future  generic  inner  operator  outer  rest  var   goto  const
```

#### 标识符
标识符：
Java 对各种变量、方法和类等要素命名时使用的字符序列称为标识符
凡是自己可以起名字的地方都叫标识符。
定义合法标识符规则：
由26个英文字母大小写，0-9 ，_或 $ 组成  
数字不可以开头。
不可以使用关键字和保留字，但能包含关键字和保留字。
Java中严格区分大小写，长度无限制。
标识符不能包含空格。

Java中的名称命名规范：
包名：多单词组成时所有字母都小写：xxxyyyzzz
类名、接口名：多单词组成时，所有单词的首字母大写：XxxYyyZzz
变量名、方法名：多单词组成时，第一个单词首字母小写，第二个单词开始每个单词首字母大写：xxxYyyZzz
常量名：所有字母都大写。多单词时每个单词用下划线连接：XXX_YYY_ZZZ


