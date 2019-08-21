# k2p-openwrt-mt7615_5.0.2.0
For openwrt 18.06
Put directory mtk into /pacagke



Make menuconfig

中文版编译选项：https://www.right.com.cn/forum/thread-572784-1-1.html
为了稳定性，用lean源码的，去掉默认选中的带宽监控和开源mt7615驱动。也不要去选什么QOS NFTABLES

编译时遇到的错误参考了hanwckf的patch https://github.com/hanwckf/openwrt-mt7615
