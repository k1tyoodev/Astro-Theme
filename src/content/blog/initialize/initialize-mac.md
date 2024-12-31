---
title: '从零开始配置 Mac'
publishDate: '2024-09-16 11:25:00'
description: '统一的环境配置指南~'
tags: [mac, initialize]
language: '中文'
draft: false
---

## App 列表

### Homebrew

[Homebrew](https://brew.sh/) 是一个 macOS 下的包管理器，可以通过它安装许多软件。

- git：代码版本控制
- gpg：git 提交加密工具


### SetApp

[SetApp](https://setapp.com/) 是 macOS 的一个基础软件订阅服务，它类似于 AppStore，但不同的是，你只需要为它支付一个统一的费用，便可以免费使用其中的所有软件。

- [AlDento Pro](https://apphousekitchen.com/)：macOS 电池管理
- [CleanShotX](https://cleanshot.com/)：优秀的截图工具
- [Downie](https://software.charliemonroe.net/downie/)：视频下载工具，如果想要下载高分辨率 Bilibili 视频，推荐使用 [BBDown](https://github.com/nilaoda/BBDown)
- [Permute](https://software.charliemonroe.net/permute/)：视频、照片等文件转码工具
- [ForkLift](https://binarynights.com/)：FTP 文件管理器，有着接近原生的 UI 设计
- [Squash](https://www.realmacsoftware.com/squash/)：图片压缩工具，可以批量处理，界面好看，有开源平替 [Clop](https://github.com/FuzzyIdeas/Clop)
- [Sip](https://sipapp.io)：颜色选取工具，有开源平替 [Pika](https://github.com/superhighfives/pika)

### AppStore

- [Bob](https://bobtranslate.com/) [付费]：macOS OCR、划词翻译工具。有开源平替 [EasyDict](https://github.com/tisfeng/Easydict)
- [Immersive Translate](https://immersivetranslate.com/)：最强的网页翻译工具，也可以配合 OpenAI 等多家服务使用
- [Pure Paste](https://apps.apple.com/cn/app/pure-paste/id1611378436?mt=12)：剪贴板格式移除工具。或者你也可以使用 <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>v</kbd> 来粘贴
- [滴答清单](https://dida365.com) [付费]：任务管理，日程安排，番茄钟
- [xSearch](https://apps.apple.com/us/app/xsearch-for-safari/id1579902068) [付费]：搜索引擎切换工具

### Github

先放一份 Star List 在这里：[K1tyoo / Mac](https://github.com/stars/cn-danieldev/lists/mac)

- [Rectangle](https://github.com/rxhanson/Rectangle)：窗口管理工具
- [Sequel Ace](https://github.com/Sequel-Ace/Sequel-Ace)：好看的 MySQL 数据库管理工具
- [IINA](https://iina.io/)：macOS 下最好的视频播放器
- [PicGo](https://github.com/Molunerfinn/PicGo)：图床工具，与 Typora 配合使用
- [Local Send](https://github.com/localsend/localsend)：局域网文件传输工具
- [Upscayl](https://github.com/upscayl/upscayl)：macOS 下的图片 AI 放大工具

### Other

- [VS Code](https://code.visualstudio.com/)：最好的 IDE
- [Cursor](https://www.cursor.com/)：基于 VS Code 开源代码的 AI IDE
- [obsidian](https://obsidian.md/)：笔记软件
- [Warp](https://warp.dev/)：最好的终端
- [Raycast](https://www.raycast.com/)：macOS 下最好用的快捷启动工具
- [MacZip](https://ezip.awehunt.com)：压缩解压工具
- [Arc](https://arc.net/)：macOS 下好看、新颖的浏览器，Chromium 内核，垂直标签页，多 profile 切换
- [Itsycal](https://www.mowglii.com/itsycal/)：菜单栏日历，简洁可爱
- [Hoppscotch](https://hoppscotch.io/)：好看的 API 调试工具
- [RightFont](https://rightfontapp.com/) [付费]：字体管理工具，界面好看
- [Surge](https://surge.mitsea.com/overview) [付费]：macOS 下最好的网络调试工具
- [Mihomo](https://github.com/mihomo-party-org/mihomo-party)：一个更好看的 Clash 客户端
- [Tailscale](https://tailscale.com/)：让你的多个设备处于同一局域网内
- [Parsec](https://parsec.app/)：优秀的远程桌面工具
- [Screen Studio](https://screen.studio/)：颜值很高的录屏软件，也可使用免费平替 [Loom](https://www.loom.com/products/mac-screen-recorder)
- [Orb Stack](https://orbstack.dev/)：macOS 下颜值很高、功能强大的 Docker Desktop 替代品
- [LookAway](https://lookaway.app/) [付费]：智能休息提醒工具
- [YesPlayMusic](https://github.com/qier222/YesPlayMusic)：高颜值网易云播放器

## VS Code 插件

### 主题 & 图标

- Moegi Theme
- Symbols

### 其他

- Ruff：Rust 编写的 Python 代码检查器和格式化工具
- CodeGeeX：免费的 AI 代码补全工具
- Slidev：幻灯片制作工具

## Raycast 插件

- Gitmoji
- Kill Process
- Port Manager
- Coffee

## CLI

先放一份 Star List 在这里：[K1tyoo / Tools](https://github.com/stars/cn-danieldev/lists/tools)

我使用 [ZSH](https://www.zsh.org/) 作为默认的 Shell，配合 [Oh My ZSH](https://ohmyz.sh/) 来管理配置。 我使用的部分 CLI 工具：

- [starship](https://github.com/starship/starship)：终端美化工具
- [bat](https://github.com/sharkdp/bat)：支持语法高亮的 cat 平替
- [fd](https://github.com/sharkdp/fd)：简单、快速、友好的 find 平替
- [zoxide](https://github.com/ajeetdsouza/zoxide)：目录导航工具
- [btop](https://github.com/aristocratos/btop)：类似 htop 的资源监控工具
- [tldr](https://github.com/tldr-pages/tldr)：命令行工具的使用指南
- [tmux](https://github.com/tmux/tmux)：终端多窗口管理工具，较 pm2 相比，可以在启动后仍然进行交互操作
- [gh](https://github.com/cli/cli#installation)：GitHub CLI
- [lobe-cli-toolbox](https://github.com/lobehub/lobe-cli-toolbox)：标准化 git commit 信息生成工具，支持 AI 生成

### Miniconda

我使用 [Minoconda](https://docs.anaconda.com/miniconda/index.html) 来管理 Python 的虚拟环境。


### Nvm

我使用 [Nvm](https://github.com/nvm-sh/nvm) 来管理 Node.js 版本环境。安装完成后，换源，将如下命令追加到 `~/.zshrc~`。

```shell
export NVM_NODEJS_ORG_MIRROR=http://npm.taobao.org/mirrors/node
```

- [pm2](https://pm2.keymetrics.io/)：守护进程
- [pnpm](https://pnpm.io/)：Node 包管理器

## Font

- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) / [MonoLisa](https://www.monolisa.dev/)
- [Poppin](https://fonts.google.com/specimen/Poppins?query=Poppin)
