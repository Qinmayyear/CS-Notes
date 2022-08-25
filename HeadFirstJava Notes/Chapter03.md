# Chapter3 认识变量
### 声明变量
为了让类型安全发挥作用，需要先声明变量类型
**variables must have a type**
**variables must have a name**

### Primitive主数据类型
存放数值的permitive主数据类型有六种大小：

**数值（带正负号）：**
* byte 8
* short 16
* int 32
* long 64

**浮点数（带正负号）：**
* float 32
* double 64

---

### 确保变量能保存下所保存的值
小杯子装大值不行，当所处容器不足以装载时，会出现spillage。编译器会阻止这种情况发生，比如：

``` java
int x = 24;
byte b = x;
// 会报错！
```
不过，反过来，大杯子装小值可以。

给变量赋值很简单，你可以
* 等号后直接打出
* 指派其他变量



