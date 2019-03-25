
本项目是备份termux可以使用的adb二进制文件。
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
