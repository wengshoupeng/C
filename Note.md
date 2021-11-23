# C
C++
书籍：C++ Primer plus #6
第一章 预备知识--个人总结

一、绪论部分：
(1)C++具有高效，简洁，快速，可移植性特点
(2)面向对象
(3)泛型编程

第二章 初学C++

2.1 
(1) cout => 字符输出
(2) 对大小写敏感
(3) 注释使用//开头
(4) 文件拓展名cpp
(5) 声明加入 stdio.h可以使用C语言的函数
(6) 以分号结束，不能省略
(7) int main 变式 -> int main(void) -> 函数不接受任何参数 () <=> （void）
(8) main()函数中，默认以return 0结束
(9) c++程序必须含有一个main()函数，必须为main()命名，并由main()开始执行
(10) 在编写DLL(动态链接库)时可以不需要main()函数
例子： Myfirst.cpp
#include <iostream>                            //预处理编译指令
  int main()                                   // 函数头
  {                                            // 函数体{}
      using namespace std;                     // 编译指令
      cout << "Come up and C++ me some time."; // 输出一句话
      cout << endl;                            // 结束 
      cout << "You won't regret it!" << endl;  // 补充一句话并结束
      return 0;                                // 返回 0
  
  }
简化后
  int main()      //函数头 int为函数返回类型->整型
  {               //括号内为 参数列表 or 形参列表
      statements  //声明   //此两行为函数体 
      return 0;             
  }
  ==> 函数定义(function definition)的构成如上,意为：一个名为main()的函数并且描述了该函数的行为。
  

  
