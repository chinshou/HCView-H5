﻿# HCView
一个类似word或wps用于文字排版相关功能的控件，有Delphi、C#、Html5、C++(暂未完成)四个版本，可用在电子病历或其他文书系统里。
[http://hcview.cn/](http://hcview.cn/)是一个在线的示例，你也可以加入QQ群 649023932 来获取更多的技术交流。

![示例截图](https://images.gitee.com/uploads/images/2020/0320/225800_d849f68c_2149334.png "page.png")

友情提示：
1.HCView默认支持藏文等有紧缩字符的文本，这导致文件保存后体积比不支持藏文等要大，如果你只需要中文和英文支持且对体积有敏感，可以关闭全局的条件编译符号 UNPLACEHOLDERCHAR，关闭后文件保存体积较关闭前理论上会减小约50%，注意关闭后打开关闭前保存的文档会不正常。