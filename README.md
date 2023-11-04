Linux RTL8188GU网卡驱动
===============================================================

### 安装git、make、gcc、linux-header

> sudo apt install git make gcc
>
> sudo apt install linux-headers-$(uname -r)

### 安装RTL8188GU驱动

> git clone https://github.com/harrisww/rtl8188gu.git

### 编译

> cd rtl8xxxu/
>
> sudo make ARCH=arm64

### 安装

> sudo make install

### 重启，即可成功识别无线网卡

> sudo reboot



### 环境

> 设备：香橙派5 Orange Pi5
>
> 系统：ubuntu-22.04.3-desktop-arm64 rockchip
