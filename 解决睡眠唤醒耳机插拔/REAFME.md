19.11.1
解决了睡眠后耳机需要重新插拔才能正常使用的问题
（但重启开机后依然需要插拔一次），方法：
删除了other下FakePCIID\_Intel\_HDMI\_Audio.kext，\\\_
修改Devices下的inject=Detect,勾选左侧USB inject

ps:在10.14时我只是将更新AppleAlc和Lilu并复制CodecCommander到SLE下便无耳机插拔问题包括开机时。