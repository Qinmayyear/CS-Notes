# 1.1 基本概念

## java的工作方式

1. source
2. compiler
3. output
4. virtual machines

---

### code sturcture in Java
> 等待补充图片

Source file?
holds class definition

Class？
A class has one or more methods, holding instructions. 
**Methods must declared inside a class**

Method?
write instructions for what it should do. 
Think it like a function or procedure.

---
### Main

java执行的时候，会锁定这个方法：

``` java
public static void main (String[] args) {
   // your code goes here
}
```
**Java application** have one main per application

You type source code file, and compile it into a new class file. So when you run program you are running a class.
Thus, running a program is tell virtual machine to "**Load the class** and **executing its main** til finished."

---
> ### 小知识
> System.out.print 和 System.out.println 的区别在于，后者会在最后面插入换行，前者的话后续输出也在同一行
---












