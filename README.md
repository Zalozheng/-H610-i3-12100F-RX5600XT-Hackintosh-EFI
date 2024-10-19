# -H610-i3-12100F-RX5600XT-Hackintosh-EFI
install macOS Sonoma on Intel H610 Mainboard with Intel i3-12100F.
硬件信息
#主板：精粤H610M Wifi Plus (Wifi自己换了Ax201 需要用Wifi6，这主板是用不了PCI的博通网卡 也就是无法隔空投送）
#CPU I3-12100F
#显卡5600XT迪兰

现在系统
![image](https://github.com/user-attachments/assets/2896abc4-6bb0-464c-9fe0-c2fd6fd3b6fa)

现在用的是mac 15.1系统 无法wifi 
蓝牙正常（不过需要接外置天线不然信号不够，哪怕只有0.5m）

用这个EFI的时候把这几个改一下 不然无法登陆icloud
![](assets/17293435377578.jpg)

这个主板的USB 已经定制 我把自己的机型写进这个kext了
你如果用请自己更新机型 或者直接用USBMAp 也可以
![](assets/17293436664614.jpg)
这样更改：右击显示包内容打开Contents 打开Info.plist

![](assets/17293438076379.jpg)
![](assets/17293440626138.jpg)
这里是端口号0 是USB2.0 3是USB2.0  255是内置
