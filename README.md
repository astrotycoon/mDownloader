# mDownloader
mDownloader: A Cross-Platform Multiple-Threads GUI Download Accelerator Based on Qt, and the torrent program in Qt Examples.
It is fast, with maximum 99 threads do the downloading job at the same time, takes full advantage of your network resources when does HTTP/HTTPS/FTP downloading. 
And it supports BitTorrent protocol(in the BitTorrent branch).

# How to build

Under Windows:

1. Tools that you will need

	a) Visual Studio Community 2013, download from http://www.visualstudio.com/en-us/news/vs2013-community-vs.aspx or google this: vs2013.4_ce_enu.iso;

	b) Qt 5.4.0 for Windows 32-bit (VS 2013), download from http://download.qt-project.org/official_releases/qt/5.4/5.4.0/qt-opensource-windows-x86-msvc2013-5.4.0.exe;

	c) OpenSSL for Windows 32-bit, download from http://slproweb.com/download/Win32OpenSSL-1_0_1L.exe.

2. Install OpenSSL for Widnows 32-bit to C:/OpenSSL-Win32/

3. Use Qt Creator to open mDownloader.pro and build

Under Ubuntu 14.04:

1. Sudo apt-get install qtcreator
2. Use Qt Creator to open mDownloader.pro and build

# Automated Testing

All tests are under folder test. You'd better run the tests under Windows 7, because some wierd random errors happen when I run them under Ubuntu 14.04.

# Latest official build 

http://qinchuan.me/downloads/mDownloader-Setup-1.0.1Build005.exe

