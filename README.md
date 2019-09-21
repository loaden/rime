# 中州韵输入法

## 前言
RIME 是一款跨平台的优秀输入法框架，基于该框架在不同平台有不同的输入法实现方案。这个源码库基于官方中州韵输入法框架和各平台官方输入法实现，经过精心配置，尽可能实现面向大多数用户习惯的简体中文拼音、五笔输入方案。中州韵输入法非常优秀，但阻碍应用的一个很大原因是配置繁琐。本源码库可以大幅度降低中州韵输入法使用门槛。
- Windows - 小狼毫
- macOS - 鼠须管
- Linux - 中州韵（ibus-rime）

## 功能用法与配置说明
- Control+\` 或 Control+Shift+\` 或 Control+0 或 F4 实现输入法及功能切换
- Shift 键临时切换到英文输入，再次按下Shift键返回到中文输入
- 逗号、句号前后翻页，兼容减号、加号前后翻页
- 分号、单引号选择第二、第三候选字/词
- Control+, 实现“半角/全角”切换，Control+.　实现“.,/。，”切换
- 支持斜杠开头的特殊符号输入，例如/sx输入数学符号，详情请参考symbols.yaml
- 支持五笔、五笔拼音、五笔简入繁出，五笔z键可临时切换到拼音
- 五笔支持扩展词库，用户可自行编辑wubi86_extended.dict.yaml
- 输入法界面字符完全采用简体中文，拼音默认输出简体
- 所有从官方拷贝的词库、配置都不做任何修改，原汁原味，方便升级

### 输出系统时间和日期
- date 输出日期，格式 `2019年06月19日`
- time 输出时间，格式 `10:00`

## 安装配置
首先请访问[rime.im](https://rime.im)，根据提示说明下载安装各平台RIME输入法，然后从本站打包下载词库配置，分别解压缩到各平台用户数据目录后重新部署。
- Linux平台请解压到：~/.config/ibus/rime
- macOS平台请压到：~/Library/Rime
- Windows平台请解压到：%APPDATA%\Rime

### macOS 需要安装opencc
```shell
brew install opencc
```

## 相关链接
- RIME github 地址：https://github.com/rime
- RIME 官方五笔码表：https://github.com/rime/rime-wubi
- RIME 拼音反查词库：https://github.com/rime/rime-pinyin-simp
- RIME 官方网站：https://rime.im

## 使用反馈
- https://github.com/loaden/rime
- https://github.com/loaden/rime/issues
