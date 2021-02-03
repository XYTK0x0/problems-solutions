1、 error LNK2019	无法解析的外部符号 _WinMain@16，该符号在函数 "int __cdecl invoke_main(void)"
属性->连接器->系统->子系统->改为窗口

2、vs2015生成exe，到xp中运行，需要设置环境
（1）属性->常规->平台工具集->windows xp
（2）属性->C/C++->代码生成->多线程(/MT)

3、编写 windows下的 kernel driver程序
新建kernel  driver 空项目，删去多余的文件
driver程序编译较为严格，要把 警告视为错误  设为 否
general 设置 target OS & platform

4、

