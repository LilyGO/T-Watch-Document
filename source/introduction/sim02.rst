==================
T-Watch SIM800L
==================

.. image:: ../_static/simcard1.png


1.描述
==================

T-Watch SIM800L是一款基于ESP32的可编程手表套件，由Core PCB和SIM800L底板组成。
您甚至可以通过Arduino,ESP-IDF或MicroPython对T-Watch SIM800L进行编程。

.. image:: ../_static/model4.jpg



2.特征
==================

- 主芯片：ESP32，双核MCU（集成双模蓝牙/wifi ），PMU电源管理
- 显示屏：1.54寸LCD电容触摸屏
- 传感器：BMA423三轴加速度计，内置计步算法，活动识别/跟踪，高级手势识别等功能
- 组合套件：锂电池，设计开模，以及粗线表带，并且有黑、白双色
- 开发平台：ESP-IDF(原生SDK)，Arduino,Lua,MicroPython,Scratch
- 支持SIM卡电话通信功能
- 支持麦克风
- 支持喇叭
- 支持可拓展模块使用


3.引脚详情
==================

屏幕
++++++++++++++++++
=============== ======  ====================================  
 ESP32           属性     描述
=============== ======  ====================================
 GPIO05           CS      屏幕,TFT_CS
 GPIO18           SCLK    屏幕,TFT_SCLK
 GPIO19           MOSI    屏幕,TFT_MOSI
 GPIO27           DC      屏幕,TFT_DC
 GPIO12           BL      屏幕,TFT_BL
=============== ======  ==================================== 

SIM800L
+++++++++++++++++
=============== ======  ====================================  
 ESP32           属性     描述
=============== ======  ====================================
 GPIO33          TX         SIM卡,UART_SIM_TX
 GPIO34          RX         SIM卡,UART_SIM_RX
 GPIO14          RST        SIM卡,SIM_RST
 GPIO15          PWKEY      SIM卡,SIM_PWKEY
 GPIO04          BOOST      SIM卡,SIM_BOOST_CTRL
=============== ======  ==================================== 

4.演示程序
==================
 - `Github源码 <https://github.com/Xinyuan-LilyGO/twatch-series-modules/tree/master/twatch_sim800>`_

