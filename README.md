# I.MX6U Qt综合例程源码

#### 介绍
正点原子I.MX6U Qt综合例程源码

#### 使用说明

1、Windows下编译，安装Qt 5.12.9，可以在Windows编译，打开工程，编译完成后把src文件夹放到可执行程序exe同级目录下。
2、Ubuntu Linux下编译，安装Qt 5.12.9，可以在Linux Ubuntu 编译，打开工程，编译完成后把src文件夹放到可执行程序同级目录下。
3、ARM下编译，在Ubuntu下安装交叉编译器，详细请看【正点原子】I.MX6U用户快速体验V1.x.pdf文档的第4.6小节。或者看【正点原子】I.MX6U Qt交叉编译环境搭建V1.x.pdf文档。编译完成后把src文件夹放到可执行程序同级目录下

重要提示：不能在winodws/linux下将工程放在中文路径下编译与运行！

备注：1.Windows下使用此Demo时，播放音乐需要安装此目录下的LAVFilters-0.68.1.exe（解码用的软件）。
      2.Ubuntu 16.04下使用此Demo时，播放音乐需要安装Gst解码。需要在终端输入sudo apt-get install gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-ugly gstreamer1.0-pulseaudio安装GST解码库。