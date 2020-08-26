# Opencore
自用台式电脑macOS 10.13.6 配置

## 电脑配置

## 用到的软件
1. [ProperTree](https://github.com/corpnewt/ProperTree)
2. [clover配置软件](https://mackie100projects.altervista.org/download-clover-configurator/）

只用来挂载efi分区， 千万不能用来编辑

opencore的config.plist

opencore的需要用ProperTree编辑
## opencore引导配置
参考：
1. [Intel Coffee Lake平台完美黑苹果系统安装教程](https://www.bilibili.com/video/BV1hA411t7dr)
2. [OpenCore-Desktop-Guide](https://dortania.github.io/OpenCore-Desktop-Guide/)
## 一些系统设置
1. 解除安装限制
```shell script
sudo spctl --master-disable
```
2. 鼠标滚动方向保持与windows一致
设置--> 鼠标 --> 滚动方向：自然。 取消勾选

## 驱动安装
1. nvidia web driver
因为我安装的这个macOS版本的问题, nvidia官方没这个驱动

用下面的替代

https://github.com/Benjamin-Dobell/nvidia-update

- 先安装shadowsocksX-Ng-R8
https://github.com/paradiseduo/ShadowsocksX-NG-R8/releases
- 设置mac终端代理
- 运行上面github的脚本
- 重启电脑
我第一次重启失败了， 再次重启成功

## 声卡驱动


