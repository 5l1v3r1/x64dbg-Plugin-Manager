x64dbg Plugin Manager
=======

![alt text](https://github.com/horsicq/x64dbg-Plugin-Manager/blob/master/docs/screenshot_gui.jpg "Screenshot gui")
![alt text](https://github.com/horsicq/x64dbg-Plugin-Manager/blob/master/docs/screenshot_console.jpg "Screenshot console")

Console example
=======

x64plgmnrc.exe -G "C:\x64dbg_root"  // Set root path for x64dbg

x64plgmnrc.exe -U                   // Update list from server

x64plgmnrc.exe -S                   // Show list of plugins

x64plgmnrc.exe -i x64core           // Install last version of x64dbg

x64plgmnrc.exe -i AdvancedScript    // install AdvancedScript


How to build on Windows
=======

Install Visual Studio 2013: https://docs.microsoft.com/en-us/visualstudio/releasenotes/vs2013-community-vs

Install Qt 5.6.3 for VS2013: https://download.qt.io/archive/qt/5.6/5.6.3/qt-opensource-windows-x86-msvc2013-5.6.3.exe

Install 7-Zip: https://www.7-zip.org/

Clone project: git clone --recursive https://github.com/horsicq/x64dbg-Plugin-Manager.git

Edit build_win32.bat ( check VS_PATH,  SEVENZIP_PATH, QT_PATH variables)

Run build_win32.bat
