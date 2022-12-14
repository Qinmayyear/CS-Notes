#2.1 

当你在设计类的时候：
对象已知事物是：instance variable （实例变量）
对象可执行动作：methods（方法）

---

###类跟对象有什么不同？
类是用来创建对象的模型

###创建第一个对象
想要运作对象，需要两个类：操作于对象的类，和测试该类的类。
测试用的类带有 **main()** 并且其中会建立与存取被测的对象

测试类的命名方法：“名称” + TestDrive

###例子：

编写类：
``` java
class Dog {
    int size;
    String breed;
    String name;

    void bark(){
        System.out.println("Ruff! Ruff!")
    }
}
```

测试用的类里面建立对象并存取对象的变量和方法
``` java
class DogTestDrive{
    public static void main(String[] args){
        Dog d = new Dog(); //建立对象
        d.size = 40; //存取变量
        d.bark(); //调用方法
    }
}
```

---

### 离开main
对于OO程序来说，需要用对象与对象交互。
交互，说的是互相调用方法。

---

### 总结：OO的牛逼之处
1. 不需要改动之前测试好的代码
2. 所有java程序都定义在类里面
3. 对象有已知事物，并能执行工作
4. 创建类的时候，可能要创建独立的，测试用的类
5. 类可以继承自较抽象的父类（abstract super）
6. java程序在执行期是一组会互相交谈的对象
   