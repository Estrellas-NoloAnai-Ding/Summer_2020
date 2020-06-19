# Summer_2020
Nolo在这个仓库里存放了2020年夏季小学期的各种文件。Nolo会不定期更新的。
<h3>Summer 2019 PPT</h3>
这个文件夹里包含了去年的PPT，仅供预习。
<h3>Nolo's QC Theme</h3>
    IDE长得难看，会导致Nolo的编程效率大大降低。但QT Creator的默认界面又确实太难看了。于是Nolo自行处理了一下这个问题，“把它改得好看了一些”。这个folder里面包含了所有有关的文件，以及一份readme.md作为说明。
<h3>附注：QT Creator的下载和使用（基于64位win10）</h3>
    如果仍然按照去年PPT里的方式进行下载，最多只能follow到5.14.2这个版本。5.15.0及以后的版本，已被QT禁用了这种下载方式。我下载了5.14.2。<br>
    找到qt-opensource-windows-x86-5.14.2.exe这个文件，即可下载。此后再运行它，以安装QT。按照PPT里的建议（反正我也不用VS Code哈哈哈），我安装了Mingw64版本。不知VSC版本行不行。另外，安装过程中会要求注册一个QT账号，用邮箱注册似乎就行。<br>
    安装完成后可能会发现很多程序，其中Logo为‘QC’的程序就是QT Creator。<br>
    Ctrl+n新建一个文件，选择other project里的Empty Qmake Project。接下来要起名，同时要选择文件存放路径。再往后一路跳过直到finish就行了。<br>
    这样就创建了一个QT工程。右键点击代码区左边工程树最上端的文件夹，可以在Add New中加入c++ source file。写好之后，Ctrl+r就可以run了。<br>
    PS：记得在.pro文件中加入"QT += widgets"这一行，否则c++文件中的"#include <QApplication>"行将无法编译。
