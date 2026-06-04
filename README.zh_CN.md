<p align="center">
  <a href="https://github.com/Geocld/PeaSyo">
    <img src="https://raw.githubusercontent.com/Geocld/PeaSyo-rs/main/images/logo.png" width="100">
  </a>
</p>
<p align="center">
  <a href="https://github.com/Geocld/PeaSyo">
    <img src="https://raw.githubusercontent.com/Geocld/PeaSyo-rs/main/images/logo-text.png" width="300">
  </a>
</p>

<p align="center">
  为Android端打造的下一代PS4/PS5高性能串流客户端，使用Rust实现，给你提供安全、高性能、稳定的串流体验。
</p>

## Intro

PeaSyo，也称貔貅（pixiu），使用中国古代神兽命名，是一款PS4/5串流应用，支持远程唤醒、远程串流、按键映射、手柄振动等丰富的功能，你可以在任意Android设备上使用貔貅游玩PlayStation游戏。


> 声明: PeaSyo与Sony、PlayStation没有关联。所有权和商标属于其各自所有者。

## Windows/MacOS/Linux(steamOS)

如果你在找 Windows/MacOS/Linux(steamOS) 平台的PS5/4串流应用, 请移步PeaSyo桌面版 [PeaSyo4Desk](https://github.com/Geocld/PeaSyo4Desk).

## 功能

- 支持多主机注册
- 支持本地串流和远程串流
- 免网关配置自动远程串流
- 免PIN码远程自动注册主机
- 最高支持1080P(超分后获得更高分辨率体验)，支持HDR
- AMD FidelityFX super resolution v1 [FSRv1]
- 支持按键映射
- 支持串流性能面板
- 支持快捷菜单
- 远程唤醒及休眠
- DualSense5自适应扳机(需要覆盖安卓驱动+OTG有线连接Dualsense5控制器)
- DualSense5原生触觉反馈(需要覆盖安卓驱动+OTG有线连接Dualsense5控制器)
- 雷蛇原生触觉反馈（不是音频振动），不使用DualSense也能体验完整的PS5触觉反馈
- 雷蛇控制器(razer ultra/v3系列)高级配置

<img src="https://raw.githubusercontent.com/Geocld/PeaSyo/main/images/game.jpg" width="400" />
<img src="https://github.com/Geocld/PeaSyo/blob/main/images/home.jpg" width="400" /><img src="https://raw.githubusercontent.com/Geocld/PeaSyo/main/images/settings.jpg" width="400" />

## 有线手柄使用
因为安卓内核驱动限制，并非所有的安卓设备都支持手柄振动，以及如果你使用DualSense5手柄希望得到自适应扳机的支持，PeaSyo内置了Xbox 360、Xbox series x/s手柄及DualSense 5手柄内核，可以在手柄连线连接安卓设备的情况下完全支持振动和自适应扳机功能，具体使用如下：

1. PeaSyo - 设置 - 手柄及振动 - 覆盖安卓手柄支持 - 开启
2. 将Xbox/Dualsense5 手柄有线连接安卓设备
3. 此时会有一个USB访问设备的弹窗出现，点击确定，PeaSyo即进入内置手柄驱动模式。

> 注意需要在进入游戏前连接手柄，否则PeaSyo将无法识别手柄。
