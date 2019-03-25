
本项目是备份termux可以使用的adb二进制文件，可以在没有计算机的情况下使用安卓手机termux给时间刷入recovery,恢复系统等等。


  1.下载
  ```
  git clone git@gitee.com:pzb123/termux-adb.git
  ```
  2.进入下载的项目目录
  ```
  cd termux-adb
  ```
  3.安装
  ```
  mv adb $PREFIX/bin
  ```
  4.给adb添加可执行权限
  ```
  chomd +X $PREFIX/bin/adb
  ```
