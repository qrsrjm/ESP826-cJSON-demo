# ESP826-cJSON-demo

移植[cJOSN](https://github.com/DaveGamble/cJSON)到ESP8266，基于ESP8266_NONOS_SDKv2.0编译测试。

# 使用步骤

1. 首先到[这里](https://github.com/espressif/ESP8266_NONOS_SDK)或者[官网](http://espressif.com/zh-hans/products/hardware/esp8266ex/resources)下载SDK。
2. 然后拷贝该app到主目录，类似于ESP8266_NONOS_SDK/examples里面的工程文件。
3. 最后编译下载即可。

# 效果图

![效果图](https://github.com/AngelLiang/ESP826-cJSON-demo/blob/master/img/demo.jpg)

# 其他说明

由于ESP8266不支持浮点数，修改了cJSON中有关double的函数。

# 相关博客

http://blog.csdn.net/yannanxiu/article/details/52713746

