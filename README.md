# 🎈 Loon 个人配置与插件仓库

[![Loon](https://img.shields.io/badge/Loon-Configuration-blue?style=flat-square&logo=apple)](https://apps.apple.com/us/app/loon/id1373567447)
[![Update](https://img.shields.io/github/last-commit/shuxue-q/loon?style=flat-square)](https://github.com/shuxue-q/loon/commits/main)

这是一个用于存放个人 [Loon](https://apps.apple.com/us/app/loon/id1373567447) 代理工具配置文件、插件 (`.plugin`) 和重写脚本的自用仓库。

> **⚠️ 声明：** 本仓库内的所有脚本及重写规则仅供个人学习与测试使用，部分引用自开源社区。请勿用于商业或非法用途。

---

## 📦 插件列表与一键导入

*注：如果你在 iOS 设备上访问此页面，可以直接点击下方的「一键导入」将插件安装到 Loon 中。*

### 1. 示例插件名称 (请修改为你真实的插件名)
- **描述：** 这里写插件的功能简介（例如：去除某 App 广告、功能增强等）。
- **源码：** [`Plugin_Name.plugin`](./path/to/Plugin_Name.plugin)
- **安装：** [🚀 一键导入到 Loon](loon://import?plugin=https://raw.githubusercontent.com/shuxue-q/loon/main/path/to/Plugin_Name.plugin)

### 2. 备用插件 (按需添加)
- **描述：** 备用描述信息。
- **源码：** [`Another_Plugin.plugin`](./path/to/Another_Plugin.plugin)
- **安装：** [🚀 一键导入到 Loon](loon://import?plugin=https://raw.githubusercontent.com/shuxue-q/loon/main/path/to/Another_Plugin.plugin)

---

## 🛠 手动添加方式

如果你无法使用一键导入链接，或者使用的是其他代理工具（如 Surge / Shadowrocket），可以通过提取 Raw 链接手动添加：

1. 在本仓库找到你需要的 `.plugin` 或 `.js` 文件。
2. 点击右上角的 **"Raw"** 按钮获取真实的网络地址。
3. 打开 Loon -> **配置** -> **插件** -> 点击右上角 `+` -> 选择 **URL**，粘贴链接即可。

### 🔗 常用 Raw 链接根目录前缀：
```text
[https://raw.githubusercontent.com/shuxue-q/loon/main/](https://raw.githubusercontent.com/shuxue-q/loon/main/)
