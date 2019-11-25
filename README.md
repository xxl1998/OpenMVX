# OpenMVX
a customized openmv camera,based on the openmv camera
now only STM32H743+OV7725 FPC version (openMV4)
# OpenMVX is licensed under the GNU General Public Licence (GPL)V 3.0

定制版openmv，现在只有STM32H743VIT6+OV7725（FPC小镜头），一体化设计，兼容原版尺寸接口，去掉不必要的SWD接口，OV7725独立供电，大部分功能已验证过（包括摄像头、TF卡、串口、SPI屏幕、当然肯定有USB连接上位机），在电赛时也使用过，好几个月了没出过问题。
没有key，即“盗版 openmv”，除每次弹窗外不影响使用，固件使用DFU刷入，SWD是没有用的，所以去掉了。
给出原理图、PCB、PCB工程文件、集成封装库等硬件全部文件，Altium Designer 16格式（AD16）。

### 注意，此repository下开源的所有文件使用GPLV3.0协议，如果你用了这里的文件，那么你也要开源你的设计（也必须使用GPL协议）
