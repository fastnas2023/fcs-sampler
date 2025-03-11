# FCS_Sampler_Tool

FCS_Sampler_Tool是一个用于处理流式细胞仪数据的应用程序。它可以帮助您从大型FCS文件中提取样本，支持多种采样模式。

## 功能特点

- 支持多种采样模式：随机采样、均匀采样、分层采样等
- 批量处理多个FCS文件
- 可视化采样结果
- 支持插件系统，可扩展功能

## 下载

### Windows
- [Windows安装程序(.exe)](https://github.com/fastnas2023/fcs-sampler-test/releases/download/v1.0.3/FCS_Sampler_Tool_v1.0.3_Setup.exe)
- [Windows可执行文件(.exe)](https://github.com/fastnas2023/fcs-sampler-test/releases/download/v1.0.3/FCS_Sampler_Tool_v1.0.3.exe)

### macOS
- [macOS安装包(.dmg)](https://github.com/fastnas2023/fcs-sampler-test/releases/download/v1.0.3/FCS_Sampler_Tool_v1.0.3.dmg)

## 系统要求

### Windows
- Windows 10 或更高版本
- 4GB RAM (推荐8GB或更多)
- 500MB可用磁盘空间

### macOS
- macOS 10.14 (Mojave) 或更高版本
- 4GB RAM (推荐8GB或更多)
- 500MB可用磁盘空间

## 安装指南

### Windows

1. 下载最新的[安装包(.exe)](https://github.com/fastnas2023/fcs-sampler-test/releases/download/v1.0.3/FCS_Sampler_Tool_v1.0.3_Setup.exe)
2. 双击安装包并按照安装向导进行操作
3. 安装完成后，从开始菜单或桌面快捷方式启动应用程序

### macOS

1. 下载最新的[应用包(.dmg)](https://github.com/fastnas2023/fcs-sampler-test/releases/download/v1.0.3/FCS_Sampler_Tool_v1.0.3.dmg)
2. 双击.dmg文件打开
3. 将应用程序拖到Applications文件夹
4. 从Applications文件夹或Launchpad启动应用程序

## 使用方法

1. 启动应用程序
2. 点击"打开文件"按钮选择FCS文件
3. 选择采样模式和参数
4. 点击"开始采样"按钮
5. 采样完成后，可以保存结果或进行可视化分析

## 采样模式

### 随机采样

从原始数据中随机选择指定数量或比例的细胞。

参数:
- 采样数量/比例
- 是否使用随机种子

### 均匀采样

按照固定间隔从原始数据中选择细胞。

参数:
- 采样间隔
- 起始位置

### 分层采样

根据指定参数将数据分成多个层，然后从每层中采样。

参数:
- 分层参数
- 每层采样数量/比例
- 是否使用随机种子

## 批处理

应用程序支持批量处理多个FCS文件:

1. 点击"批处理"按钮
2. 选择包含FCS文件的文件夹
3. 设置采样参数
4. 点击"开始批处理"
5. 处理完成后，结果将保存在指定文件夹中

## 可视化

应用程序提供多种可视化工具:

- 散点图
- 直方图
- 密度图
- 热图

## 插件系统

FCS_Sampler_Tool支持插件系统，允许用户扩展软件功能，实现更多FCS数据处理功能。

详情请参阅[插件文档](plugins/README.md)。

## 许可证

本软件采用MIT许可证。详情请参阅[LICENSE](LICENSE)文件。

## 联系方式

如有问题或建议，请通过以下方式联系我们:

- GitHub Issues: [https://github.com/fastnas2023/fcs-sampler/issues](https://github.com/fastnas2023/fcs-sampler/issues)
- 电子邮件: support@example.com
