==============
T-Watch简介
==============

.. image:: ../_static/image3.jpg

产品分类
==============

.. toctree::
   :hidden:
   介绍 <introduce>
   MAX30102 <max04> 
   SIM800L <sim02>
   GPS <gps8m03>
   Basic <basic01> 
   Lora+GPS <s76g05>

==================  ==================  ==================
|MAX30102|_           |SIM800L|_         |GPS|_
------------------  ------------------  ------------------
`MAX30102`_           `SIM800L`_         `GPS`_
------------------  ------------------  ------------------
|Basic|_              |Lora+GPS|_         |敬请关注后续|_
------------------  ------------------  ------------------
`Basic`_              `Lora+GPS`_         `敬请关注后续`_
==================  ==================  ==================

.. |MAX30102| image:: ../_static/max30102.png
.. _MAX30102: ../introduction/max04.html

.. |Basic| image:: ../_static/basic01.png
.. _Basic: ../introduction/basic01.html

.. |SIM800L| image:: ../_static/SIM02.png
.. _SIM800L: ../introduction/sim02.html

.. |GPS| image:: ../_static/GPS3.png
.. _GPS: ../introduction/gps8m03.html

.. |Lora+GPS| image:: ../_static/s76g05.png
.. _Lora+GPS: ../introduction/s76g05.html

.. |敬请关注后续| image:: ../_static/tobe06.png
.. _敬请关注后续: ../introduction/tobe06.html

.. toctree::
   :hidden:
   介绍 <introduce>
   MAX30102 <max04> 
   SIM800L <sim02>
   GPS <gps8m03>
   Basic <basic01> 
   Lora+GPS <s76g05>
   
硬件概述
==============

类别
--------------

* :ref:`technical-parameters`
* :ref:`appearance-specification`
* :ref:`component-layout`
* :ref:`pin-definition`


.. _technical-parameters:

1.技术参数
==============

.. figure:: ../_static/get_started2.jpg 
   :scale: 40
   :align: center


- **ESP-32** 主控：

  - CPU：Xtensa双核32位LX6微处理器，工作频率为240 MHz，最高可达600 DMIPS
  - 超低功耗（ULP）协处理器
  - 内存：520 KiB SRAM
  - 无线连接：
  - Wi-Fi：802.11 b / g / n
  - 蓝牙：v4.2 BR / EDR和BLE
- 供电方式：Type-C USB/锂电池
- 工作电压：3.3V

.. note::
  
  ESP32 由总部位于上海的中国公司乐鑫信息科技创建和开发，由台积电采用40纳米技术制造。
  它是ESP8266微控制器的后继产品。


开机演示视频
--------------
.. figure:: ../_static/gif4.gif 
   :scale: 100
   :align: left

界面切换视频
--------------
.. figure:: ../_static/gif5.gif 
   :scale: 100
   :align: left


- T-Watch板载：

  - 1.54寸LCD电容触摸屏:ST7789V
  - 触摸屏芯片：FT5206
  - 三轴加速度计:BMA423
  - PMU电源管理：AXP202
  - RTC时钟模块：PCF8563

  - 拓展接口：

    - 支持麦克风:MSM261S4030H0
    - 支持SPI TF内存卡
    - 2个数字I/O：GPIO25，GPIO26 (支持ADC,DAC)
    - 支持I2C、UART、SPI通讯协议

.. important::
  
  拓展功能为升级款以及拓展模块，基础款无下列功能

- 拓展功能：

  - Lora模块：SX1276
  - GPS通讯模块：NEO M8N/6M
  - GPRS通信模块：SIM800L
  - 心率血氧传感器：MAX30102
  - 电容触摸传感器：MRP121Q
  - 六轴传感器：MPU6050
  - 无线充电
.. _appearance-specification:

2.外观规格
==============

.. image:: ../_static/model1.jpg

.. _component-layout:

3.元件布局
==============

.. image:: ../_static/model2.jpg

.. image:: ../_static/model3.jpg
.. _pin-definition:

4.引脚定义
==============

.. image:: ../_static/model4.jpg
