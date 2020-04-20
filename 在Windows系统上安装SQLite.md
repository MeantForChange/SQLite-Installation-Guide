# 在Windows系统上安装SQLite

>本章将讲解如何在Windows系统上安装SQLite。

## 步骤

按照以下步骤将SQLite安装到Windows系统上：

1. 打开SQLite官方网站的[下载页面](https://sqlite.org/download.html)。

2. 下载预编译的Windows二进制文件包：SQLite DLL包（内有`sqlite-dll`和`sqlite-shell`文件）以及`sqlite-tools-win32-x86-xxxxxxx.zip`。根据电脑系统位数，选择相应的DLL文件包。比如，对于64位的操作系统，请下载下图红框中两个文件包。


3. 解压下载好的文件包。文件包中包含一个名为sqlite3.exe文件，你可以从解压文件所在位置使用SQLite。如果想要从任何目录下运行SQLite，请参考以下步骤。

4. 在系统根目录下创建一个文件夹例如`C:\sqlite`，将解压后的文件放入创建的文件夹下。


5. 将`C:\sqlite`添加为系统变量，如图所示。


6. 打开运行窗口，输入CMD，调出Windows命令行窗口，输入sqlite3命令并按回车，显示如下即可以使用SQLite了。
 




