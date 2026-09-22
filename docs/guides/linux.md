# Linux：配置与使用

推荐客户端：**Mihomo Party**

## 一、安装（示例：deb）

以下为文档中的安装示例；版本号请以 [客户端下载站](https://colacloud.app) 当前发布为准。

```bash
sudo apt-get update -y
sudo apt-get install -y wget curl libasound2
# 从官网或 colacloud.app 获取最新 .deb 后安装，例如：
# wget <官方提供的 mihomo-party-linux-amd64.deb 链接>
# sudo apt install ./mihomo-party-linux-*-amd64.deb
```

安装成功后可在终端执行：

```bash
mihomo-party
```

## 二、添加订阅

1. 用浏览器打开 [官网](https://colacloud.net)
2. 复制 Clash 订阅链接
3. 在 Mihomo Party 订阅界面粘贴地址，等待下载完成

也可使用官网「一键导入」能力（若当前桌面环境支持）。

## 三、启动系统代理

打开系统代理开关后即可连接。

## 四、验证

连接后访问需要代理的网站进行测试。
