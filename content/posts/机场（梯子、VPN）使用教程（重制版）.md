+++
date = '2026-09-05T23:54:22+08:00'
draft = false
title = 'VPN使用教程（重制版）'
tags = [ "VPN", "clash","shadowshocket"]
categories = ["说明书"]
image = "/images/Shadowrocket.png"

+++
## iOS/iPadOS 设备教程

1. 登录你的美区Apple ID，如果没有请自行注册，或搜索 **Apple ID共享**，这里是一个可能有用的链接：[https://idshare001.me/goso.html](https://idshare001.me/goso.html)

![](/images/2701.webp)

2. 搜索 **Clash Mi**（免费） 或**Shadowrocket**并下载（付费）

![](/images/2704.webp)

![](/images/2702.webp)

![](/images/2703.webp)

3. 如果你使用的是**Shadowrocket**，请复制你的订阅链接后，打开应用（可能会索要权限，请给予；可能会要求安装VPN，请允许并输入锁屏密码），点击右上角加号，在剪贴板有订阅链接的情况下，链接会自动填充，此时只要点击右上角保存即可
   
![](/images/2705.webp)

![](/images/2706.webp)

若有多个链接，可通过此方法依次添加

---

如果你使用的是**Clash Mi**，请复制你的订阅链接后，打开应用（可能会索要权限，请给予；可能会要求安装VPN，请允许并输入锁屏密码），点击**我的配置**，然后点击右上角加号，在剪贴板有订阅链接的情况下，点击**从剪贴板导入**链接会自动填充，此时只要点击右上角对钩即可

![](/images/2707.webp)

![](/images/2708.webp)

![](/images/2709.webp)

![](/images/2710.webp)

若有多个链接，可通过此方法依次添加

4. 如果你使用的是**Shadowrocket**，在导入完链接之后，就可以点击屏幕上部**未连接**右侧的开关启动VPN的链接*（可能会索要权限，请给予；可能会要求安装VPN，请允许并输入锁屏密码）*，然后点击屏幕上部的**全局路由**选择**代理**选项，回到首页，在所有订阅链接都展开的情况下（不展开的链接默认不检测），点击屏幕上部**连通性测试**进行测速（建议同时打开应用内设置-->向下滚动到**订阅**-->打开**根据ping值排序**开关），然后选择速度与国家合适的节点

![](/images/2711.webp)

![](/images/2712.webp)

![](/images/2713.webp)

![](/images/2714.webp)

---

如果你使用的是**Clash Mi**，在导入完链接之后，点击点击屏幕上部**未连接**右侧的开关启动VPN的链接（可能会索要权限，请给予；可能会要求安装VPN，请允许并输入锁屏密码），然后点击屏幕中下部的**代理**，点击屏幕右上角的闪电图标进行测速，并等待测速完成，完成后点击屏幕上部**节点选择**，然后选择速度与国家合适的节点

![](/images/2715.webp)

![](/images/2716.webp)

![](/images/2717.webp)

5. 如果你想深入探索上面两个应用，可自行搜索相关知识，同时推荐项目 [[Shadowrocket 使用手册 补完计划](https://lowertop.github.io/Shadowrocket/)](https://lowertop.github.io/Shadowrocket/)，可自行学习。同时推荐该项目的**懒人配置**，在配置页面下载并切换配置，并将全局代理切换为**配置**，效果比**代理**好

## Android 设备教程

1. 下载 **Flclash** 并安装 

   下载链接：[https://github.com/chen08209/FlClash/releases/download/v0.8.96/FlClash-0.8.96-android-arm64-v8a.apk](https://github.com/chen08209/FlClash/releases/download/v0.8.96/FlClash-0.8.96-android-arm64-v8a.apk)，该链接为GitHub链接，指向教程编写时的最新版

2. 打开**Flclash** 

![](/images/2718.webp)

3. 点击下方**配置**

![](/images/2719.webp)

4. 点击下方**添加配置**

![](/images/2720.webp)

5. 点击**URL**

![](/images/2721.webp)

6. 输入订阅链接并确定，结果如图2

![](/images/2722.webp)

![](/images/2723.webp)

7. 点击**仪表盘**以回到首页，然后点击右下角三角形按钮以开起VPN（可能会索要权限，请允许）

![](/images/2724.webp)

8. 点击**代理**，然后点击**延迟测试**以测速，然后选择速度与国家合适的节点

![](/images/2725.webp)

## Windows 设备教程

1. [下载Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_x64-setup.exe)，双击安装包并安装（若申请管理员权限则允许），步骤如下

- 选择语言（推荐中文简体），点击**OK**
- 点击**下一步**
- 点击**下一步**
- 点击**安装**
- 等待
- 点击**下一步**
- 点击**完成**
- 后续可能会申请两次管理员权限，**允许**即可

2. 导入配置文件

- 若配置文件需从链接下载，则点击左侧**订阅**，在页面上方**订阅文件链接**处输入链接，点击右侧**导入**即可。
- 若配置文件在本地，则只需将**文件**拖拽进**窗口**即可

使用

- 点击左侧**设置**，点击左列**系统代理**即可使用，不需要时可直接**关闭系统代理**

3. 推荐打开：**开机自启**；**静默启动**；**局域网链接**

- 局域网链接说明：对于部分无法使用clash客户端的设备*（iPhone 4s亲测可用）*，可通过这种方式实现曲线救国，具体操作如下：
- 点进设置并与电脑链接在同一局域网，点进网络详情，将**http代理**切换为**手动**，服务器填写为电脑的内网**IP地址**，可点击clash设置中**局域网链接**旁边的有三个连接在一起的方块的**图标**查看，上面的**IP地址**即为所要
- 端口默认是**7897**
- 关闭鉴定

## Linux 设备教程（适用于Ubuntu/Debian系）

1. 下载[Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_amd64.deb)
2. 安装（可双击启动应用商店安装或  `sudo apt install ./Clash Verge_2.5.2_amd64.deb`)
3. 导入配置文件

- 若配置文件需从链接下载，则点击左侧**订阅**，在页面上方**订阅文件链接**处输入链接，点击右侧**导入**即可。
- 若配置文件在本地，则只需将**文件**拖拽进**窗口**即可

使用

- 点击左侧**设置**，点击左列**系统代理**即可使用，不需要时可直接**关闭系统代理**，同时推荐打开**Tun模式**，需输入用户密码安装服务

## Linux 设备教程（适用于Arch系）

1. 添加 **archlinuxcn源**

   编辑 pacman 配置文件添加 archlinuxcn 源

   ```
   sudo vim /etc/pacman.conf
   ```

   文件底部写入

   ```
   [archlinuxcn]
   Server = https://mirrors.ustc.edu.cn/archlinuxcn/$arch
   Server = https://mirrors.tuna.tsinghua.edu.cn/archlinuxcn/$arch               
   ```

   上面这两个是国内镜像，ustc（中科大）和 tuna（清华），如果你在海外的话可以直接使用官方：

   ```
   Server = https://repo.archlinuxcn.org/$arch               
   ```

   同步数据库并安装 archlinuxcn 密钥

   ```
   sudo pacman -Sy archlinuxcn-keyring
   sudo pacman -Syu 
   ```

2. 安装

   ```
   sudo pacman -S flclash
   ```

 3. 启动

    ```
    flclash
    ```

4. 在主页开启 TUN（虚拟网卡）

5. 导入链接

6. 主页右下角有个三角，点击可以启动代理

7. 测试是否生效

## Linux 设备教程（适用于Fedora系）

1. 安装 [**Throne**](https://parhelia512.github.io/)（需添加COPR）
2. 打开 **Throne**
3. 请复制你的订阅链接后，点击 **程序**-->**添加剪贴板的配置档**，然后按照需要选择添加到当前分组或新建分组
4. 开启 TUN（虚拟网卡）
5. 添加完所有链接后，使用 `ctrl + a`全选节点，并右键，选择**URL测试选定项**，然后选择速度与国家合适的节点。

注：在Fedora上，由于**selinux**的存在，**Clash**以及**mihomo内核**的代理软件在**Tun**模式下总是会有问题，因此推荐使用**sing-box**内核的代理软件。在使用中遇到问题，可尝试切换**Tun设置**的**stack**模式，或重启软件