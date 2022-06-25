<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-namelist

_✨ NoneBot 黑白名单 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/A-kirami/nonebot-plugin-namelist.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-namelist">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-namelist.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>


## 📖 介绍

简易黑白用户名单管理插件，可在黑名单与白名单模式中互相切换。

黑名单模式下，机器人不会响应来自黑名单用户的消息。

白名单模式下，机器人不会响应白名单用户之外的消息。

超级用户不受黑白名单影响。

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-namelist

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-namelist
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-namelist
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-namelist
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-namelist
</details>

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('nonebot_plugin_namelist')

</details>


## 🎉 使用
### 指令表
| 指令 | 说明 |
|:-----:|:----:|
| 切换名单 |切换黑白名单模式 |
| 添加黑名单+@用户 |将被艾特的用户加入**黑名单** |
| 删除黑名单+@用户 |将被艾特的用户从**黑名单**删除 |
| 查看黑名单+@用户 |查看**黑名单**中的用户 |
| 添加白名单+@用户 |将被艾特的用户加入**白名单** |
| 删除白名单+@用户 |将被艾特的用户从**白名单**删除 |
| 查看白名单+@用户 |查看**白名单**中的用户 |
