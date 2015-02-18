操作系统（Operating System，简称OS）是管理和控制计算机硬件与软件资源的计算机程序，是直接运行在“裸机”上的最基本的系统软件，任何其他软件都必须在操作系统的支持下才能运行。
操作系统是用户和计算机的接口，同时也是计算机硬件和其他软件的接口。操作系统的功能包括管理计算机系统的硬件、软件及数据资源，控制程序运行，改善人机界面，为其它应用软件提供支持，让计算机系统所有资源最大限度地发挥作用，提供各种形式的用户界面，使用户有一个好的工作环境，为其它软件的开发提供必要的服务和相应的接口等。实际上，用户是不用接触操作系统的，操作系统管理着计算机硬件资源，同时按照应用程序的资源请求，分配资源，如：划分CPU时间，内存空间的开辟，调用打印机等。

版权声明：
   本代码为开源代码，作者拥有代码版权，但你可以在任何非商业用途程序中引用，但请标注出处，你
 也可以对代码进行更改。作者对代码中所包括的错误以及所造成的一切后果将不负任何责任。如果你发
 现代码中有任何问题或错误，请与我联系。
  联系方法：QQ 2367051920，Email：nvwa-xt@qq.com
                                                     －－－－－作者：朱晓辉 2013年11月11日

本来想自己搞个中文版Ｃ，网上一搜竟然已经有＂习语言＂做到了，这里很感谢，习语言的开发者．．．．．由于水平有限，暂时只能写个内核出来(而且还有很多功能没写完)，其他驱动的写法还在学习摸索中．．．．．我希望，对于这系统有兴趣的程序员，加入这场新的编写中来，不管是对已有内核的意见修改还续写还没完成的驱动程序，都十分欢迎，在系统的更新时，会在程序开头标明写程序的人和修改人．．．．．．．．



额．．．只有内核里有程序，其他的都没，有兴趣，一起来写吧，谁写的，开头就会命名谁写的，，，，，还有我写这个内核的目的，只是想一步一步的弄个，真正全部代码都是用中文写的，别跟我讨论什么，中文写的代码没英文的快，，，你觉的快可以离开，我没求你用，我找的是那些对开发中文操作系统有兴趣的人吧，不想和人讨论什么什么的，我没那没多时间，谢谢．．．

．．．．还有，不管以后有没有真的开发出操作系统来，，，永久开源．．．．我只想有更多的人了解操作系统，那些喜欢程序却英语不是很好的人，也能玩出自己的代码．．．而不是赚钱．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．

下面就介绍下习语言吧．．．．
．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．．

习语言即中文版的C语言。作为一种新起步的中文编程语言，了解的人可能还很少，但是开发者一直在不断完善。也许很多人都听说过易语言，易语言其实看起来像中文版的VB，但两者在许多方面不同。而习语言，则是中文版的C语言。

中文C（习）语言中文编程系统（简称:习语言）：是一款主要用于教育和学习的中文编程软件系统。基于现有C语言系统实现并有扩充。

习语言由一套完备的编程语法和相配套的工具组成，旨在将计算机及软件编程大众化，普及化，中文化，提高程序的维护性而诞生。习语言还很年轻，可作为学习工具。作为一种中文编程语言，习语言中所有的关键字和函数都为中文。习语言有可能成为将来中文系统的开发语言。目前习语言已经完全支持汇编和C语言，并向windows图形处理发展。

历史经验证明，英文写的代码大部分都会遗忘的。而习语言则避免了这一点。真正符合汉语言特色。而且支持全角和半角的标点符号，编程时输入符号类时不用切换为英文输入法。

习语言软件特点
1、完全兼容现有的C语言系统，在设置好头文件路径的条件下，可以编译现存大部分C代码。
2、完全支持全中文编程 
3、综合了PASCAL和C的优点实现，支持 “开始”“结束”扩起语句块。支持更多注释方法，方便程序组织。 　　4、支持多字节字直观表示。如 我, abcd都可以作为字(符). 
5、支持中文标点符号，中文标点符号和英文标点符号混合使用等。 　　6、支持文章式的程序组织，中文文章中嵌入程序，直接编译。
7、支持中文运算符，支持全角，半角混合使用。
8、体积小巧，单一接口文件，使用理解容易。

习语言用途：
1、开发底层软件如操作系统等
2、写控制台程序（俗称DOS程序）
3、写纯图形界面程序（通常的WINDOWS程序 ）
4、写控制台和图形界面同时存在的混合程序。
5、编写游戏程序( DirectX 2D 实现)

习语言 v1.85.6更新：
1、修复1.85版在系统库函数中引入的一个内存访问异常问题。废弃1.85.6之前的最近几个1.85分支版本。
2、整理完善习语言图形、视窗函数，对函数列表进行分类整理。 更改部分函数名。
3、完善图形处理接口函数，支持绘制无背景的图片，支持保存内容为图片。
4、完善习语言编辑器。


还有收费版是最新的２０１３版，淘宝有卖．．．