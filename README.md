# linux--家居控制系统

实现LCD触摸控制LED、继电器、SG90舵机等功能，在LCD上实时显示环境光照数据、温湿度数据、是否有人、有害气体浓度等信息，蓝牙模块可以接收蓝牙APP的指令  
关键字：IMX6ULL、QT、LCD、ap3216c、DHT11、SG90、gpio、I2C、PWM、UART子系统  


文件说明：   
|--01.智能家居     
&ensp;&ensp;&ensp;&ensp;|-- 01_test：QT项目代码    
&ensp;&ensp;&ensp;&ensp;|-- 其他文件夹：对应模块的驱动代码    
&ensp;&ensp;&ensp;&ensp;|-- *.ko：针对所有模块编译出的驱动ko文件    
&ensp;&ensp;&ensp;&ensp;|-- insmod.sh：加载所有驱动模块的脚本    
&ensp;&ensp;&ensp;&ensp;|-- rmmod.sh：卸载所有驱动模块的脚本    
&ensp;&ensp;&ensp;&ensp;|-- imx6ull-alientek-emmc.dtb：设备树dtb文件   
&ensp;&ensp;&ensp;&ensp;|-- imx6ull-alientek-emmc.dts：设备树dts文件  
 
