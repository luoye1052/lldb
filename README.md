# lldb
1.quit//退出

2.b//输出断点信息

            事例：6: file = '/Users/yubing/Desktop/sdimage1/sdimage/ViewController.m', line = 45,    exact_match = 0, locations = 1, resolved = 1, hit count = 1 
              6.1: where = sdimage`-[ViewController btn:] + 42 at ViewController.m:45, address = 0x000000010807106a, resolved, hit count = 1 
              
3. b  test    //设置断点在test函数下

4. bt        //打印栈信息

5. call      //调用函数self.view.backgroundColor=[UIColor yellowcolor];

6. c        //程序继续执行。

7. n        //单步执行不进入子函数。

8. s         //单步运行进入子函数。

9. si        //汇编指令。

10. ni       //汇编指令。

11. image    //展示各种模块信息。

12.watchpoint //内存数据发生改变时触发。

13.mem read 0x7fbfe0d38240 0x7fbfe0d38240+90    //读出内存中的信息。

14.memory  write  0x7fbfe0d38240 99           //把99写入内存。

15.register read //寄存器读取 真机x1读取寄存器里边的内容 模拟器eax（能获取参数和调用对象）。
