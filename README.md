## Linksys-WRT32X-Openwrt  

squashfs-factory.img 适用于从原厂系统刷openwrt系统；

squashfs-sysupgrade.bin 适用于从openwrt系统刷openwrt系统(变更升级)；

initramfs-kernel.bin 一般用于移植openwrt系统的时候与没有设备上的flash闪存的驱动的时候使用；

详细配置参考：https://www.infvie.com/ops-notes/linksys-wrt32x-openwrt.html   

##### 可实现链路聚合(新增LAN 1口为WAN口)  

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/interface.png)  

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/vlan2.png)  

### 定制功能：  

一、新增USB驱动、负载均衡

二、新增额外软件:  

   1) WireGuard  

   2) ShadowSocksR Plus+ （支持SS/SSR/V2RAY）  
   
   3) MWAN3 分流助手

### 截图如下：  

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/slb-status.png)  

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/slb-setting.png)  

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/ssr-plus++.png)  

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/usb.png) 

![Image text](https://github.com/Einic/Linksys-WRT32X-Openwrt/blob/master/img/reboot.png)  




