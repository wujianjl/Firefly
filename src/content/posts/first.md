---
title: 教程
published: 2026-09-27
updated: 2026-09-27
description: python安装教程
category: 教程
draft: false
pinned: false
---
# 关于安装 Python 踩坑的提示（其实是自己踩过的坑）

> 书山有路勤为径，学海无涯苦作舟

这篇文章主要讲述本蠢人以前在学习 Python 时安装解释器的时候的趣事。

## 1. Python 的下载地址

[Download Python | [Python.org](http://Python.org)]([https://www.python.org/){target="_blank"}](https://www.python.org/){target="_blank"})

## 2. 选择版本

如图所示，打开网页下拉找到 Python 版本选择区域：

![屏幕截图 2026-09-27 000053.png]([https:/img.jiuluo.ccwu.cc/file/jiucheng/1790438555192_屏幕截图_2026-09-27_000053.png){target="_blank"}](https://img.jiuluo.ccwu.cc/file/jiucheng/1790438555192_屏幕截图_2026-09-27_000053.png){target="_blank"})

请根据自己的要求选择版本。

> &zwnj;**注意**&zwnj;：新版本 Python 解释器不支持老版本系统，下载前请自行查询兼容性。

## 3. 选择安装程序

以 Windows 为例，选择对应的安装包：

![屏幕截图 2026-09-27 000859.png]([https:/img.jiuluo.ccwu.cc/file/jiucheng/1790438985664_屏幕截图_2026-09-27_000859.png){target="_blank"}](https://img.jiuluo.ccwu.cc/file/jiucheng/1790438985664_屏幕截图_2026-09-27_000859.png){target="_blank"})

## 4. 运行安装程序

下载后，右键以管理员身份运行。界面如下：

![屏幕截图 2026-09-27 001249.png]([https:/img.jiuluo.ccwu.cc/file/jiucheng/1790439220233_屏幕截图_2026-09-27_001249.png){target="_blank"}](https://img.jiuluo.ccwu.cc/file/jiucheng/1790439220233_屏幕截图_2026-09-27_001249.png){target="_blank"})

> &zwnj;**注**&zwnj;：务必勾选 &zwnj;**"Add python.exe to PATH"**&zwnj;，然后点击第二个选项（Customize Installation 或 Install Now，视具体版本而定，通常建议自定义安装以便控制路径）。

## 5. 组件选择

在第二个页面，建议全选所需组件。

## 6. 安装路径设置

在第三个页面，默认设置即可。你可以选择更改安装位置：

- 推荐安装在 D 盘。

- 自行新建一个 `Python Code` 文件夹。

- 在该文件夹中新建一个 `venv` 文件夹。

- 将 Python 安装在此路径下（后期若想使用 PyCharm，这样方便配置虚拟环境）。

## 7. 验证安装

按下 `Win + R` 打开运行，输入 `cmd` 回车，再输入 `python`。

- 如果正常进入 Python 命令行，即安装成功。

- 若失败，请检查环境变量或重新安装。

*(若仍失败，我给你装😠😠😠)*

