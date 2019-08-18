![cover](https://img3.doubanio.com/view/subject/l/public/s28047380.jpg)

    作者: [日] 矢泽久雄 
    出版社: 人民邮电出版社
    译者: 李逢俊 
    出版年: 2015-4
    页数: 272
    定价: 39.00元
    装帧: 平装
    丛书: 图灵程序设计丛书
    ISBN: 9787115385130

[豆瓣链接](https://book.douban.com/subject/26365491/)

- [1.对程序员来说CPU是什么](#1%e5%af%b9%e7%a8%8b%e5%ba%8f%e5%91%98%e6%9d%a5%e8%af%b4cpu%e6%98%af%e4%bb%80%e4%b9%88)
  - [1.1 CPU的内部结构解析](#11-cpu%e7%9a%84%e5%86%85%e9%83%a8%e7%bb%93%e6%9e%84%e8%a7%a3%e6%9e%90)
  - [1.2 CPU是寄存器的集合体](#12-cpu%e6%98%af%e5%af%84%e5%ad%98%e5%99%a8%e7%9a%84%e9%9b%86%e5%90%88%e4%bd%93)
  - [1.3 决定程序流程的程序计数器](#13-%e5%86%b3%e5%ae%9a%e7%a8%8b%e5%ba%8f%e6%b5%81%e7%a8%8b%e7%9a%84%e7%a8%8b%e5%ba%8f%e8%ae%a1%e6%95%b0%e5%99%a8)
  - [1.4 条件分支和循环机制](#14-%e6%9d%a1%e4%bb%b6%e5%88%86%e6%94%af%e5%92%8c%e5%be%aa%e7%8e%af%e6%9c%ba%e5%88%b6)
  - [1.5 函数的调用机制](#15-%e5%87%bd%e6%95%b0%e7%9a%84%e8%b0%83%e7%94%a8%e6%9c%ba%e5%88%b6)
  - [1.6 通过地址和索引实现数组](#16-%e9%80%9a%e8%bf%87%e5%9c%b0%e5%9d%80%e5%92%8c%e7%b4%a2%e5%bc%95%e5%ae%9e%e7%8e%b0%e6%95%b0%e7%bb%84)
  - [1.7 CPU的处理其实很简单](#17-cpu%e7%9a%84%e5%a4%84%e7%90%86%e5%85%b6%e5%ae%9e%e5%be%88%e7%ae%80%e5%8d%95)
- [2.数据是用二进制数表示的](#2%e6%95%b0%e6%8d%ae%e6%98%af%e7%94%a8%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%95%b0%e8%a1%a8%e7%a4%ba%e7%9a%84)
  - [2.1 用二进制数表示计算机信息的原因](#21-%e7%94%a8%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%95%b0%e8%a1%a8%e7%a4%ba%e8%ae%a1%e7%ae%97%e6%9c%ba%e4%bf%a1%e6%81%af%e7%9a%84%e5%8e%9f%e5%9b%a0)
  - [2.2 什么是二进制数](#22-%e4%bb%80%e4%b9%88%e6%98%af%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%95%b0)
  - [2.3 移位运算和乘除运算的关系](#23-%e7%a7%bb%e4%bd%8d%e8%bf%90%e7%ae%97%e5%92%8c%e4%b9%98%e9%99%a4%e8%bf%90%e7%ae%97%e7%9a%84%e5%85%b3%e7%b3%bb)
  - [2.4 便于计算机处理的“补数”](#24-%e4%be%bf%e4%ba%8e%e8%ae%a1%e7%ae%97%e6%9c%ba%e5%a4%84%e7%90%86%e7%9a%84%e8%a1%a5%e6%95%b0)
  - [2.5 逻辑右移和算术右移的区别](#25-%e9%80%bb%e8%be%91%e5%8f%b3%e7%a7%bb%e5%92%8c%e7%ae%97%e6%9c%af%e5%8f%b3%e7%a7%bb%e7%9a%84%e5%8c%ba%e5%88%ab)
  - [2.6 掌握逻辑运算的窍门](#26-%e6%8e%8c%e6%8f%a1%e9%80%bb%e8%be%91%e8%bf%90%e7%ae%97%e7%9a%84%e7%aa%8d%e9%97%a8)
- [3.计算机进行小数运算时出错的原因](#3%e8%ae%a1%e7%ae%97%e6%9c%ba%e8%bf%9b%e8%a1%8c%e5%b0%8f%e6%95%b0%e8%bf%90%e7%ae%97%e6%97%b6%e5%87%ba%e9%94%99%e7%9a%84%e5%8e%9f%e5%9b%a0)
  - [3.1 将0.1累加100次也得不到10](#31-%e5%b0%8601%e7%b4%af%e5%8a%a0100%e6%ac%a1%e4%b9%9f%e5%be%97%e4%b8%8d%e5%88%b010)
  - [3.2 用二进制数表示小数](#32-%e7%94%a8%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%95%b0%e8%a1%a8%e7%a4%ba%e5%b0%8f%e6%95%b0)
  - [3.3 计算机运算出错的原因](#33-%e8%ae%a1%e7%ae%97%e6%9c%ba%e8%bf%90%e7%ae%97%e5%87%ba%e9%94%99%e7%9a%84%e5%8e%9f%e5%9b%a0)
  - [3.4 什么是浮点数](#34-%e4%bb%80%e4%b9%88%e6%98%af%e6%b5%ae%e7%82%b9%e6%95%b0)
  - [3.5 浮点数正规化](#35-%e6%b5%ae%e7%82%b9%e6%95%b0%e6%ad%a3%e8%a7%84%e5%8c%96)
  - [3.6 举个例子](#36-%e4%b8%be%e4%b8%aa%e4%be%8b%e5%ad%90)
  - [3.7 误差](#37-%e8%af%af%e5%b7%ae)
  - [3.8 二进制数和十六进制数](#38-%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%95%b0%e5%92%8c%e5%8d%81%e5%85%ad%e8%bf%9b%e5%88%b6%e6%95%b0)
- [4.熟练使用有棱有角的内存](#4%e7%86%9f%e7%bb%83%e4%bd%bf%e7%94%a8%e6%9c%89%e6%a3%b1%e6%9c%89%e8%a7%92%e7%9a%84%e5%86%85%e5%ad%98)
  - [4.1 内存的物理机制很简单](#41-%e5%86%85%e5%ad%98%e7%9a%84%e7%89%a9%e7%90%86%e6%9c%ba%e5%88%b6%e5%be%88%e7%ae%80%e5%8d%95)

## 1.对程序员来说CPU是什么
### 1.1 CPU的内部结构解析
有的 CPU 在一个集成电路中集成了两个 CPU 芯片，我们称之为`双核（dual core）CPU`。

![](program1.png)

图 1-1　程序运行流程示例

CPU 和内存是由许多晶体管组成的电子部件，通常称为 `IC（Integrated Circuit，集成电路）`。从功能方面来看，如图 1-2 所示，CPU 的内部由`寄存器`、`控制器`、`运算器`和`时钟`四个部分构成，各部分之间由电流信号相互连通。

- `寄存器`可用来暂存指令、数据等处理对象，可以将其看作是内存的一种。根据种类的不同，一个 CPU 内部会有 20～100 个寄存器。
- `控制器`负责把内存上的指令、数据等读入寄存器，并根据指令的执行结果来控制整个计算机。
- `运算器`负责运算从内存读入寄存器的数据。
- `时钟`负责发出 CPU 开始计时的时钟信号。Pentium 2 GHz 表示时钟信号的频率为 2 GHz（1 GHz = 10 亿次 / 秒）。也就是说，时钟信号的频率越高，CPU 的运行速度越快。

![](program2.png)

图 1-2　CPU 的四个构成部分

通常所说的内存指的是计算机的`主存储器（main memory）` ，简称主存。主存通过控制芯片等与 CPU 相连，主要负责存储指令和数据。

主存位于计算机机体内部，是负责存储程序、数据等的装置。主存通常使用 `DRAM（Dynamic Random Access Memory，动态随机存取存储器）`芯片。DRAM 可以对任何地址进行数据的读写操作，但需要保持稳定的电源供给并时常刷新（确保是最新数据），关机后内容将自动清除。

### 1.2 CPU是寄存器的集合体
程序是把寄存器作为对象来描述的。

`汇编语言`采用助记符（memonic）来编写程序，每一个原本是电气信号的机器语言指令都会有一个与其相应的助记符，助记符通常为指令功能的英语单词的简写。通常我们将汇编语言编写的程序转化成机器语言的过程称为`汇编`；反之，机器语言程序转化成汇编语言程序的过程则称为`反汇编`。

把汇编语言转化成机器语言的程序称为`汇编器（assembler）`。

- `机器语言`是指CPU能直接解释和执行的语言。
- `高级编程语言`是指能够使用类似于人类语言（主要是英语）的语法来记述的编程语言的总称。

`编译`是指将使用高级编程语言编写的程序转换为机器语言的过程，其中，用于转换的程序被称为`编译器（compiler）`。

表 1-1　寄存器 的主要种类和功能

种类 | 功能
---|---
累加寄存器（accumulator register） | 存储执行运算的数据和运算后的数据
标志寄存器（flag register）| 存储运算处理后的CPU的状态
程序计数器（program counter） | 存储下一条指令所在内存的地址
基址寄存器（base register）| 存储数据内存的起始地址
变址寄存器（index register） | 存储基址寄存器的相对地址
通用寄存器（general purpose register） | 存储任意数据
指令寄存器（instruction register） | 存储指令。CPU内部使用，程序员无法通过程序对该寄存器进行读写操作
栈寄存器（stack register） | 存储栈区域的起始地址

对程序员来说，CPU 是具有各种功能的寄存器的集合体。其中，程序计数器、累加寄存器、标志寄存器、指令寄存器和栈寄存器都只有一个，其他的寄存器一般有多个。

![](program3.png)

图 1-3　程序员眼中的 CPU（CPU 是寄存器的集合体）

### 1.3 决定程序流程的程序计数器
图 1-4 是程序起动时内存内容的模型。示例中的程序实现的是将 123 和 456 两个数值相加，并将结果输出到显示器上。

`操作系统（operating system）`是指管理和控制计算机硬件与软件资源的计算机程序

![](program4.png)

图 1-4　内存中配置的程序示例（显示相加的结果）

### 1.4 条件分支和循环机制
程序的流程分为顺序执行、条件分支和循环三种。

- `顺序执行`是指按照地址内容的顺序执行指令。
- `条件分支`是指根据条件执行任意地址的指令。
- `循环`是指重复执行同一地址的指令。

条件分支和循环中使用的跳转指令 ，会参照当前执行的运算结果来判断是否跳转。表 1-1 所列出的寄存器中，我们提到了标志寄存器。无论当前累加寄存器的运算结果是负数、零还是正数，标志寄存器都会将其保存（也负责存放溢出和奇偶校验的结果)。

- `溢出（overflow）`是指运算的结果超出了寄存器的长度范围。
- `奇偶校验（parity check）`是指检查运算结果的值是偶数还是奇数。

![](program5.png)

图 1-6　比较运算的结果存储在标志寄存器的三个位中

### 1.5 函数的调用机制
![](program6.png)

图 1-7　程序调用函数示例（这里直接展示了 C 语言的源代码，实际上各地址存储的应该是变换成机器语言后的程序）

`call指令`会把调用函数后要执行的指令地址存储在名为栈的主存内。函数处理完毕后，再通过函数的出口来执行return命令。`return命令`的功能是把保存在栈中的地址设定到程序计数器中。

![](program7.png)

图 1-8　函数调用中程序计数器和栈的职能

在编译高级编程语言的程序后，函数调用的处理会转换成 call 指令，函数结束的处理则会转换成 return 指令。

### 1.6 通过地址和索引实现数组
`基址寄存器`和`变址寄存器`。通过这两个寄存器，我们可以对主内存上特定的内存区域进行划分，从而实现类似于数组的操作。

- `数组`是指同样长度的数据在内存中进行连续排列的数据构造。用一个数组名来表示全体数据，通过索引来区分数组的各个数据（元素）。

![](program8.png)

图 1-9　综合使用地址和索引来决定实际地址

### 1.7 CPU的处理其实很简单
表 1-2　机器 语言指令的主要类型和功能

类型 | 功能
---|---
数据转送指令 | 寄存器和内存、内存和内存、寄存器和外围设备之间的数据读写操作
运算指令 | 用累加寄存器执行算术运算、逻辑运算、比较运算和移位运算
跳转指令 | 实现条件分支、循环、强制跳转等
call/return指令 | 函数的调用/返回调用前的地址

- `外围设备`指的是连接到计算机的键盘、鼠标、显示器、设备装置、打印机等。

## 2.数据是用二进制数表示的
### 2.1 用二进制数表示计算机信息的原因
- `IC`是集成电路（Integrated Circuit）的简称，有模拟 IC 和数字 IC 两种。本章介绍的是数字 IC。
- 大部分 IC 的电源电压都是 +5V。不过，为了控制电量的消耗，有的 IC 也会使用 +5V 以下的电压。如果 IC 使用的电源电压为 +5V，那么引脚状态就不只是 0V 和 +5V，还存在不接收电流信号的高阻抗（high impedance）状态。但在本书中，我们暂时不考虑高阻抗状态。

IC 的这个特性，决定了计算机的信息数据只能用二进制数来处理。

![](program9.png)

图 2-1　IC 的一个引脚表示二进制数的 1 位

### 2.2 什么是二进制数
二进制数 00100111 用十进制数表示的话是 39，因为（0×128）＋（0×64）＋（1×32）＋（0×16）＋（0×8）＋（1×4）＋（1×2）＋（1×1）= 39。

### 2.3 移位运算和乘除运算的关系
移位运算 指的是将二进制数值的各数位进行左右移位（shift = 移位）的运算。移位有左移（向高位方向）和右移（向低位方向）两种。

### 2.4 便于计算机处理的“补数”
二进制数中表示负数值时，一般会把最高位作为符号来使用，因此我们把这个最高位称为符号位。符号位是 0 时表示正数 ，符号位 是 1 时表示负数。

计算机在做减法运算时，实际上内部是在做加法运算。为此，在表示负数时就需要使用`“二进制的补数”`。(将二进制数的各数位的数值全部取反 ，然后再将结果加 1。)

- `取反`是指，把二进制数各数位 的 0 变成 1，1 变成 0。例如 00000001 这个 8 位二进制数取反后就成了 11111110。

例如 1－1，也就是 1＋(－1) 这一运算，

- －1 表示成 1|0000001（二进制）
- －1 表示成 1|1111111（补数，取反加一）

 00000001＋11111111 为 0（= 00000000），对于溢出的位，计算机会直接忽略掉。在 8 位的范围内进行计算时，100000000 这个 9 位二进制数就会被认为是 00000000 这一 8 位二进制数。

3－5 

- 用 8 位二进制数表示 3 时为 00000011
- 5 = 00000101 的补数为“取反＋1”，也就是 11111011。

 3－5 其实就是 00000011＋11111011 的运算，运算结果为 11111110，最高位变成了 1。这就表示结果是一个负数。

编程语言包含的整数数据类型8 中，有的可以处理负数，有的则不能处理。例如，C 语言的数据类型中，既有不能处理负数的 unsigned short 类型，也有能处理负数的 short 类型。这两种类型，都是 2 字节（= 16 位）的变量，都能表示 2 的 16 次幂 = 65536 种值，这一点是相同的。不过，值的范围有所不同，short 类型是－32768～32767，unsigned short 类型是 0～65535。此外，short 类型和 unsigned short 类型的另一个不同点在于，short 类型是将最高位为 1 的数值看作补数，而 unsigned short 类型则是 32768 以上的值。

### 2.5 逻辑右移和算术右移的区别
当二进制数的值表示图形模式而非数值时，移位后需要在最高位补 0。这就称为`逻辑右移`。

将二进制数作为带符号的数值进行运算时，移位后要在最高位填充移位前符号位的值（0 或 1）。这就称为`算术右移`。

![](program10.png)

图 2-10　逻辑右移和算术右移的区别

只有在右移时才必须区分逻辑位移和算术位移。左移时，无论是图形模式（逻辑左移）还是相乘运算（算术左移），都只需在空出来的低位补 0 即可。

以 8 位二进制数为例，`符号扩充`就是指在保持值不变的前提下将其转换成 16 位和 32 位的二进制数。将 01111111 这个正的 8 位二进制数转换成 16 位二进制数时，很容易就能得出 0000000001111111 这个正确结果，像 11111111 这样用补数来表示的数值，将其表示成 1111111111111111 就可以了。也就是说，不管是正数还是用补数表示的负数，都只需用符号位的值（0 或者 1）填充高位即可。

![](program11.png)

图 2-11　由 8 位转换成 16 位的符号扩充方法

### 2.6 掌握逻辑运算的窍门
将二进制数表示的信息作为四则运算的数值来处理就是`算术`。而像图形模式那样，将数值处理为单纯的 0 和 1 的罗列就是`逻辑`。

`算术运算`是指加减乘除四则运算。`逻辑运算`是指对二进制数各数字位的 0 和 1 分别进行处理的运算，包括逻辑非（NOT 运算）、逻辑与（AND 运算）、逻辑或（OR 运算）和逻辑异或（XOR 运算9 ）四种。

- `XOR`是英语 exclusive or 的缩写。有时也将 XOR 称为 EOR。

表 2-1　逻辑非（NOT）的真值表

A的值 | NOT A的运算结果
----|-----------
0 | 1
1 | 0

表 2-2　逻辑与（AND）的真值表

A的值 | B的值 | A AND B的运算结果
----|-----|-------------
0 | 0 | 0
0 | 1 | 0
1 | 0 | 0
1 | 1 | 1

表 2-3　逻辑或 （OR）的真值表

A的值 | B的值 | A OR B 的运算结果
----|-----|-------------
0 | 0 | 0
0 | 1 | 1
1 | 0 | 1
1 | 1 | 1

表 2-4　逻辑异或 （XOR）的真值表

A的值 | B的值 | A XOR B 的运算结果
----|-----|--------------
0 | 0 | 0
0 | 1 | 1
1 | 0 | 1
1 | 1 | 0

## 3.计算机进行小数运算时出错的原因
### 3.1 将0.1累加100次也得不到10

代码清单 3-1　将 0.1 累加 100 次的 C 语言程序

```c
#include <stdio.h>

void main() {
    float sum;
    int i;

    //将保存总和的变量清0
    sum = 0;

    //0.1相加100次
    for (i = 1;  i <= 100; i++) {
        sum += 0.1;
    }

    //显示结果
    printf("%f\n", sum);
}
```

### 3.2 用二进制数表示小数
![](program12.png)

图 3-2　二进制数小数转换成十进制数的方法

### 3.3 计算机运算出错的原因
计算机之所以会出现运算错误，是因为“有一些十进制数的小数无法转换成二进制数”。例如，十进制数 0.1，就无法用二进制数正确表示，小数点后面即使有几百位也无法表示。一个十进制小数要能用浮点数精确地表示，最后一位必须是 5：

![](program13.jpg)

### 3.4 什么是浮点数
很多编程语言中都提供了两种表示小数的数据类型，分别是双精度浮点数和单精度浮点数。双精度浮点数类型 用 64 位、单精度浮点数类型 用 32 位来表示全体小数。

`浮点数`是指用符号、尾数、基数和指数这四部分来表示的小数。

    浮点数=符号位.尾数x2^{阶码}

根据IEEE 754国际标准，常用的浮点数有两种格式：

1. float32位单精度浮点数在机器中表示用 1 位表示数字的符号，用 8 位表示指数，用 23 位表示尾数。
1. double64位双精度浮点数，用 1 位表示符号，用 11 位表示指数，52 位表示尾数。

其中指数域也称为阶码。浮点数存储字节定义如图：

![](program14.png)

### 3.5 浮点数正规化
尾数不为0时，尾数域的最高有效位为1，这称为规格化。否则，以修改阶码同时左右移动小数点位置的办法，使其成为规格化数的形式。

`移码`是真值补码的符号位取反，一般用作浮点数的阶码，目的是便于浮点数运算时的对阶操作。

比如，以一个字节来表示-3，那么[−3]原=10000011 [−3]反=11111100 [−3] 补=11111101  [−3]移=01111101

### 3.6 举个例子
【3.14的单精度浮点数表示】

首先将3.14转成二进制:

- 整数部分3的二进制是11
- 小数部分0.14的二进制是：0.0010001111010111000010[10001111.....]（方括号中表示小数点后第23位及之后）
- 3.14的二进制代码就是：11.0010001111010111000010[10001111....]×2^0
- 那么用`正规化`表示就是：1.10010001111010111000010[10001111....]×2^1

方括号表示的超出23位之后的二进制部分，由于单精度浮点数尾数只有23位，所以需要舍入（舍入方法见后）

由于第24位为1，且之后不全为 0，所以需要向第23位进1完成上舍入：1.10010001111010111000011×2^1

而其指数是1，需要加上移码127，即128，也就是1000 0000

它又是正数，所以符号为0

综上所述，3.14的单精度浮点数表示为：

0 1000-0000 1001-0001-1110-1011-1000-011

- S符号位    0 
- e指数位　1000-0000
- M尾数位  1001-0001-1110-1011-1000-011

### 3.7 误差
通过例子可知，3.14的单精度浮点数表示是0 1000-0000 1001-0001-1110-1011-1000-011。现在我们来还原，看看它的误差：

- 指数是128，那么还原回去（减去移码），实际指数就是1
- 尾数还原也就是：10010001111010111000011，
- 所以正规化形式是：1.10010001111010111000011×2^1
- 也就是11.0010001111010111000011
- 利用二进制转十进制，可得它对应的十进制数是：3.1400001049041748046875  不等于3.14

### 3.8 二进制数和十六进制数
在实际程序中，也经常会用十六进制数来代替二进制数。在 C 语言程序中，只需在数值的开头加上 0x（0 和 x）就可以表示十六进制数。

二进制数的 4 位，正好相当于十六进制数的 1 位。例如，32 位二进制数 00111101110011001100110011001101 用十六进制数来表示的话，就是 3DCCCCCD 这个 8 位数。由此可见，通过使用十六进制数，二进制数的位数能够缩短至原来的 1/4。位数变少之后，看起来也就更清晰了（图 3-9）。

![](program15.png)

图 3-9　通过使用十六进制数使位数变短

![](program16.png)

图 3-10　小数点后的二进制数的 4 位也相当于十六进制数的 1 位

## 4.熟练使用有棱有角的内存
### 4.1 内存的物理机制很简单
内存 IC 中有电源、地址信号、数据信号、控制信号等用于输入输出的大量引脚（IC 的引脚），通过为其指定`地址（address）`，来进行数据的读写。

- `ROM（Read Only Memory）`是一种只能用来读取的内存。
- `RAM（Random Access Memory）`是可被读取和写入的内存，分为需要经常刷新（refresh）以保存数据的 `DRAM（Dynamic RAM）`，以及不需要刷新电路即能保存数据的 `SRAM（Static RAM）`。
























