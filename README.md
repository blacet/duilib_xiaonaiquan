# duilib_xiaonaiquan
duilib

1.修复的菜单无法使用bug
2.修复鼠标手势的改变
3.修复托盘图标

修复方案：
http://blog.csdn.net/xiaonaiquan/article/category/6986587

修改了js和C++的交互，数据传递的正确性，C++调用js函数用什么数据类型将数据传递过去，之前写的存在数据对象可能已经不在的bug，编译的是debug版本。

增加了Dpi Demo，来适应各种DPi 下的程序状态
