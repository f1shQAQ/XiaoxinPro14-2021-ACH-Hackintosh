# Xiaoxin Pro14-2021-ACH-Hackintosh
本项目基于 [thinkbook14p-Gen2-ACH-hackintosh](https://github.com/Kingtous/thinkbook14p-Gen2-ACH-hackintosh) 进行二次修改，使用的 OpenCore 版本为 0.9.7

请注意：在使用这个 EFI 之前记得自己重新生成一个序列号和 UUID

![](./preview.png)

我自己使用的是 Ventura 13.5.2，Sonoma 兼容性请自行测试

因为我自己也是一个黑苹果小白，所以如果你使用了这个 EFI 出现了问题我可能没办法帮助你（

详细的使用体验可以前往[我的博客](https://qqquq.com/article/AMD-Laptop-Hackintosh)观看

目前已知 Bug：
- 休眠
- 重启有概率触控板不可用，再次重启即可修复
- 内置键盘上的亮度调节快捷键有概率不可用

我自己的配置：
| 项目 | 详情 |
|  ----  | ----  |
| CPU | AMD Ryzen 5 5600H |
| GPU | AMD Vega 7 核显 |
| 内存 | 16GB (8GB*2 3200MHz DDR4) |
| 硬盘 | KIOXIA RC20 1TB |
| 网卡 | Intel AX200 |
| 声卡 | Realtek ALC287 (layout 11, 21) |
