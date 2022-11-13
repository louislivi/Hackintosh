# 黑苹果引导
黑苹果ASUS-Z390-H_i9-9900K_5700XT EFI，自用全驱动有需要可以使用。

适用于 `MAC OS` 13.0.1
![13.0.1](https://github.com/louislivi/Hackintosh/blob/master/1668313719781.jpg)

## 配置
- 主板: 华硕ROG STRIX Z390-H GAMING
- CPU: Intel® Core™ i9-9900K Processor
- 核显: Intel® UHD Graphics 630
- 独显: 蓝宝石RX 5700 XT超白金极光特别版
- 固态硬盘: Intel 660P

## BIOS设置

- 高级-CPU设置--Intel(VMX) Virtualization Technology -enable
- 高级-北桥-显示设置--首选显卡-Auto，初始化IGPU-enable，DVMT Pre-Allocated-128M，RC6-enable
- 高级-USB Configuration--XHCI Hand-off -enable
- 启动-启动设置--快速启动-disable
> 快速启动一定要关闭否则会导致无法正常进入bios等问题。
