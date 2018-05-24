# Halcon-Study

## 开发环境配置

- 首先尝试修改了环境变量，发现并不能解决问题。
- 接下来修改了项目内部的配置
  + 根据代码include的文件，添加“VC++目录”一栏内“包含目录”、“库目录”中的对应路径
  + 对应的添加“链接器”-“输入”一栏内的“附加依赖项”中的lib
- 插入 USB Dongle

程序可以编译通过并顺利运行，运行的第一个测试程序是“TestHalcon01.cpp”

## 3D-Matching

halcon的3D Matching的例子似乎都是以扩展名hdev的文件给出的，这应该是它自己的IDE：HDevelop。关于如何使用它，HALCON有一个说明文档：“hdevelop_users_guide.pdf”。从这篇文档中，我们不幸的得知，HALCON的hdevelop中使用得代码其语法规则是HALCON自己制定的而非目前已经存在的某种语法。所以基本上说是要重新学习。关于3D Matching的部分，做一个PPT来进行总结。

