simpleJPEG
==========

一个简单的bmp转jpg工具，使用C语言完成，可以辅助学习JPEG转换的原理。

程序在Ubuntu 12.04下测试通过。

在Windows下也能正确地编译运行，不过需要配置gcc和mingw环境。建议安装TDM-GCC套件，另外需要寻找一个可用的make程序

** 程序暂时只支持24位BMP图片读取，请使用24位BMP图片作为输入 **

```bash
$ cd simpleJPEG
$ make
$ ./main.exe testcase/in.bmp testcase/out.jpg
```

或者使用cmake生成编译工程(推荐)
```bash
$ cd simpleJPEG
$ mkdir build
$ cd build
$ cmake ..
```

大家对这个程序如果有什么好的意见和建议，欢迎交流
