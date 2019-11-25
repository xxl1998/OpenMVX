# OpenMVX
a customized openmv camera,based on the openmv camera
now only STM32H743+OV7725 FPC version (openMV4)
# OpenMVX is licensed under the GNU General Public Licence (GPL)V3.0
# 注意，此repository下开源的所有文件使用GPL V3.0协议，如果你用了这里的文件，那么你也要开源你的设计（也必须使用GPL协议）

个人定制版openmv，使用官方原版openmv4硬件文件修改而来，三次打样（修改两次）后实现全部功能，使用国内常用元件，保证都是淘宝容易买到的，并且简化一部分电路设计，去掉BTB接口，直接单板实现，使用FPC镜头，焊接个FPC座就行，免得焊BGA的感光元件，现在只有STM32H743VIT6+OV7725（FPC小镜头），一体化设计，兼容原版尺寸接口，去掉不必要的SWD接口，OV7725独立供电，大部分功能已验证过（包括摄像头、TF卡、串口、SPI屏幕、当然肯定有USB连接上位机），在电赛时也使用过，好几个月了没出过问题。
没有key，即“盗版 openmv”，除每次弹窗外不影响使用，固件使用DFU刷入，SWD是没有用的，所以去掉了。
给出原理图、PCB、PCB工程文件、集成封装库等硬件全部文件，Altium Designer 16格式（AD16）。

### 有任何技术问题，可加QQ群 923703530
### 更多技术分享和作品开源分享，可关注微信公众号： 飞觞醉月    
![Image text](https://raw.githubusercontent.com/xxl1998/OpenMVX/master/qrcode_QQ_group.png)

