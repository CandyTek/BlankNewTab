# 空白标签页 浏览器插件
目的：解决 Chrome 使用商店的第三方空白标签扩展时，“仅在新标签页显示书签”功能不可用问题

扩展仅 802 字节大小

本扩展的预备安装操作可能会带来风险，如果你接受不了，请关闭此页面右转
> #### 步骤
# 一、
> 打开 chrome://flags/#extensions-on-chrome-urls

> 设置 Extensions on chrome:// URLs 为 Enabled

> 重启浏览器

风险说明：

1. 此选项为(允许第三方扩展访问 Chrome:// 链接)。需第三方扩展自身请求权限(Chrome://)才允许访问

2. 在没开启此flags 项前，声明了此权限(Chrome://)的扩展，是无法安装的；也就是说这种特殊扩展一般是接触不到的，因为扩展声明了此权限一般用户就安装不了；

3. 开启此项后请务必安装正常来源的扩展，或者查看来源扩展是否声明了此权限，声明了此权限就一定要看看该扩展到底干了些什么）

# 二、
> 打开 chrome://extensions

> 点击右上角 开发者模式，设置为启用状态

> 下载本项目文件并解压，记住文件夹位置

> 点击左上角 加载已解压的扩展程序，选择文件夹位置

# 完成

<br>

<br>

# License

Copyright (C) 2022 HolyshitOvO

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html

Please do not contact me except on this Github project issues.
