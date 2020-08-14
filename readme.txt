安装说明：
1. 下载安装python3.8 64bit

2. 下载安装Pycharm 64bit
已经放到下列共享目录中 \\172.11.100.2\部门及个人$\部门目录\传感器\Tools\Python

3. 新建Pycharm工程，不要使用虚拟环境，而使用存在exist interpreter的python3.8，避免新工程都需要下载模块

4. 安装 pyqt5及其tools
pip install pyqt5 pyqt5-tools

5. 增加外部工具配置：QtDesigner和PyUIC，完成ui的编辑和编译
$PyInterpreterDirectory$\Lib\site-packages\pyqt5_tools\Qt\bin\designer.exe
$FileName$
$FileDir$
$PyInterpreterDirectory$\Scripts\pyuic5.exe
$FileName$ -o $FileNameWithoutExtension$.py
$FileDir$

6. 安装pyinstaller,支持exe打包
pip install https://github.com/pyinstaller/pyinstaller/archive/develop.tar.gz

7. 增加外部工具配置：ToEXE
$PyInterpreterDirectory$\Scripts\pyinstaller
-F -w $FileName$
$FileDir$

8. 安装剪切板： pip install pyperclip

9. 安装execl写模块：  pip install xlsxwriter


入门学习网站：
https://www.runoob.com/python3/python3-tutorial.html