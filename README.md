# Calculator 简易数学表达式计算器
Stack, Calculator, C/C++, MFC. 通过栈的结构，有界面，能计算表达式（考虑优先级，包括括号）。

> Vincent Zhang
>
> language: `C语言`  
>
> IDE: `Visual Studio 2017`  
>
> Time: 2017/04/19 - 2017/04/20


## 核心算法

1. 将中缀表达式通过栈的结构转化为后缀表达式。

2. 通过栈的结构计算后缀表达式。

3. 结构体存储栈的结构

## 其他说明

1. 窗体使用MFC制作，可以实现基本的计算器功能。

2. 之后会继续完善，包括界面的美化和图标的更改。

3. 对于异常输入的处理还不到位，之后会继续优化。

## 附件说明

1. `Calculation`文件夹中为完整工程和有关文件，工程为`.sln`文件，请用`Visual Studio`打开。

2. `Calculation.exe`文件为编译完成的可执行文件，请在Windows平台上执行。

3. `doubleCount.cpp`为核心程序，实现了中缀表达式转后缀表达式和计算数值，已经写了测试主函数。


---

代码上传：https://github.com/VincentJYZhang/Calculator
