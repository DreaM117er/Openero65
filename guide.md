# 組裝說明 Building Guide

- 電路板及定位板。
- PCB and plate.
![](pic/001.jpg)

## 一、韌體燒錄（Firmware）

- 首先將韌體燒錄進MCU中預備，方法如下：
- First you need to flash firmware into MCU, please follow step below：

> **Note**
>
> RP2040 SuperMini/Zero have same `bootloader` way, you need to keep pushing switch on the MCU `before` plug USB-C cable to the PC. After that, you can see a `disk` on your device, then put `.uf2` firmware file into disk.

![](pic/003.jpg)
![](pic/004.jpg)

## 二、二極體&熱插拔座&排針（Diodes and Hotswap sockets and Pin headers）

- 接著準備好PCB、二極體及熱插拔座，並且依序按照電路板上的方向焊接固定起來。
- Prepared the PCB, diodes and hotswap sockets, soldering and fixing in the direction of the PCB.

![](pic/diodes.jpg)
![](pic/005.jpg)
![](pic/006.jpg)

- 接下來準備排針及MCU，對照好PCB上的腳位，將排針安裝在PCB的背面。
- Prepare pin headers and MCU, following and installing them in the direction of the PCB on back side.
![](pic/002.jpg)
![](pic/RP2040SueprMiniFoot1.png)

- 推薦先安裝母排針，再安裝公排針，再將MCU放上去固定好後再進行焊接。
- It is recommended to install the female pins first, then the male pins, then put the MCU on it and fix it before soldering.
![](pic/008.jpg)
![](pic/009.jpg)
![](pic/010.jpg)
![](pic/011.jpg)

- 熱插拔座、二極體、MCU安裝好之後會是這個樣子。
- IF you finished installing hotswap sockets, diodes and MCU, check picture below, it looks like the picture below.
![](pic/012.jpg)

## 三、衛星軸&定位板（Stablizers and Plate）













## 四、外殼組裝（Install Case）