# 开发工具 #

Linux开发工具被切割成一个个独立的小工具。各自处理不同的问题。

例如

	编辑器（emacs, vim)用来进行编辑程序的
	调试器（gdb)用来调试程序
	编译器（GCC）用来编译和链接程序的
	性能分析工具（gcov, gprof)用来优化程序的
	文档生成器（doxygen）用来生成文档的

# 系统工具和系统知识 #

	程序自动化机制 makefile
	系统粘合剂shell
	系统查找工具grep, locate, find
	其它的工具（例如ctags， OCI公司的MPC等等）

# 常用软件 #

.tar.gz

1.chromium

	pacman -S chromium
	pacman -S pepper-flash

2.输入法

执行：

	pacman -S fcitx-im fcitx-configtool

执行：

	nano ~/.xprofile

添加一下内容

	export GTK_IM_MODULE=fcitx

	export QT_IM_MODULE=fcitx

	export XMODIFIERS="@im=fcitx"

安装搜狗输入法

fcitx-googlepinyin

安装googlepinyin

pacman -S fcitx-sogoupinyin

3.software

	pacman -S libreoffice
	pacman -S libreoffice-still-zh-cn

	pacman -S vim
	pacman -S atom

	pacman -S deadbeef

	pacman -S dragon

	pacman -S uget

	pacman -S goldendict
