###
RP2040を使ったマイコン基板で、基本的にはRaspberry-pi pico互換。

24V系の機器を制御するのが目的で、そのために東芝のDMOS-SINKドライバTBD62064が載っている。本当ならカプラで分離するのが適当なのだろうが、こんなもんで問題なく動いてる

電源は24VをXHコネクタから入れる想定。それをTIのUA78M05で5V/0.5Aに落とし、それを更にMicrochipのMIC5504で3.3V/0.3Aに落としている。3.3VはMCU用、5VはLEDと冷却ファンの駆動用

SchematicsとPCB-LayoutはAutodesk-Eagle無償版を使用し、elecrowで製造することを想定したガーバーを作成している

![HandCream](https://github.com/alpha010101/HandCream/blob/master/IMG_20241230_130622925.jpg)
