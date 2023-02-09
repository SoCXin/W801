# [W801](https://doc.soc.xin/W801)

* [winnermicro](http://www.winnermicro.com/): [XT804](https://github.com/SoCXin/RISC-V)
* [L3R2](https://github.com/SoCXin/Level): 240 MHz , [￥6.38](https://item.szlcsc.com/3266650.html)

## [简介](https://github.com/SoCXin/W801/wiki)

[W801](https://www.winnermicro.com/html/1/156/158/569.html) 是一款安全 IoT Wi-Fi/蓝牙 双模 SoC芯片。芯片提供丰富的数字功能接口。支持2.4G IEEE802.11b/g/n Wi-Fi 通讯协议；支持 BT/BLE 双模工作模式，支持 BT/BLE4.2 协议。芯片集成32位 CPU 处理器，内置UART、GPIO、SPI、I2C、I2S、7816、SDIO、ADC、PSRAM、LCD、TouchSendor等数字接口；支持TEE安全引擎，支持多种硬件加解密算法，内置DSP、浮点运算单元与安全引擎，支持代码安全权限设置，内置2MBFlash存储器，支持固件加密存储、固件签名、安全调试、安全升级等多项安全措施，保证产品安全特性。适用于用于智能家电、智能家居、智能玩具、无线音视频、工业控制、医疗监护等广泛的物联网领域。


### 关键参数

* 240 MHz XT804，内置DSP、浮点运算单元与安全引擎
* 288KB SRAM + 2MB Flash，支持最高64MB外置PSRAM存储器
* Wi-Fi4
    * 支持GB15629.11-2006，IEEE802.11 b/g/n
    * 支持Wi-Fi WMM/WMM-PS/WPA/WPA2/WPS
    * 支持EDCA信道接入方式
    * 支持20/40M带宽工作模式
    * 支持STBC、GreenField、Short-GI、支持反向传输
    * 支持AMPDU、AMSDU
    * 支持IEEE802.11n MCS 0~7、MCS32物理层传输速率档位，传输速率最高到150Mbps
    * 2/5.5/11Mbps速率发送时支持Short Preamble
    * 支持HT-immediate Compressed Block Ack、Normal Ack、No Ack应答方式
    * 支持CTS to self
    * 支持Station、Soft-AP、Soft-AP/Station功能
* 支持BT/BLE 双模工作模式，支持BT/BLE4.2 协议，支持蓝牙配网
* 集成6路 UART 高速接口
* 集成4路12比特 ADC，最高采样率1KHz
* 集成1个高速SPI接口，支持最高50MHz
* 集成1个主/从 SPI 接口
* 集成1个SDIO_HOST接口，支持SDIO2.0、SDHC、MMC4.2
* 集成1个SDIO_DEVICE，支持SDIO2.0，最高吞吐率200Mbps
* 集成PSRAM扩展接口，最大支持64Mbyte
* 集成1个I2C控制器
* 集成GPIO控制器，最多支持44个GPIO
* 集成5路PWM接口
* 集成1路 Duplex I2S控制器
* 集成LCD控制器，支持4x32接口
* 集成1个7816接口
* 集成15个Touch Sensor
* MCU内置 Tee 安全引擎，代码可区分安全世界/非安全世界
* 集成 SASC/TIPC，内存及内部模块/接口可配置安全属性，防止非安全代码访问
* 启用固件签名机制，实现安全Boot/升级
* 具备固件加密功能，增强代码安全
* 固件加密密钥使用非对称算法分发，增强密钥安全性
* 硬件加密模块：RC4256、AES128、DES/3DES、SHA1/MD5、CRC32、2048 RSA,真随机数发生器
* 低功耗模式
    * 3.3V单电源供电
    * 支持Wi-Fi节能模式功耗管理
    * 支持工作、睡眠、待机、关机工作模式
    * 待机功耗小于10uA




## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/W801)

[W801](https://github.com/SoCXin/W801)与W800的主要区别在于，W801的接口和管脚更加丰富。
W801为QFN56封装(6mmx6mm)，和[ESP32-S3](https://github.com/SoCXin/ESP32S3)相似，而W800为QFN32封装(4mmx4mm)，和[ESP32-C3](https://github.com/SoCXin/ESP32C3)相似。

W801不仅将W800原有的UART、Touch Sensor、ADC等接口的数量增加，而且新增了主/从SPI接口、PSRAM扩展接口、LCD控制器接口和7816接口。

## [www.SoC.xin](http://www.SoC.Xin)
