# Java-basics
我的java学习笔记

* [基础知识](基础知识)
    * [常用dos命令](常用dos命令)

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
    jdk包含jre
    java文件名必须与public class 类名相同
    程序入口：
    ```java
        public static void main(String[] args) {
        
        }
    ```