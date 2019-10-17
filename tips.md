# Tips Here

> Anyone can add more tips into this file.

## Word Analysis
---

+ 判断空白字符，需使用 **<ctype.h>**中的**isspace()**函数，否则会疯狂错误。--ylxy

+ 文法分析中允许**空字符串**出现。 --skywalker007008

+ 注意**文件结束**后的控制，不要出现异常。 --ylxy

## Grammar Analysis
---

+ 分析程序时，要注意**跳过全局变量和常量定义**的测试程序，建议使用*前读*判断具体哪部分。 --ylxy, skywalker007008

+ 注意文法中的 
   - {} ：任意整数
   - [] ：0或1

+ 注意任何可能出现 **“空”** 的文法，分析时要做准备判断。 --skywalker007008