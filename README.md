<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>


<div align="center">


# novabot-plugin-word-bank

_✨ NoneBot 插件简单描述 ✨_

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/Nova-Noir/novabot-plugin-word-bank.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/novabot-plugin-word-bank">
    <img src="https://img.shields.io/pypi/v/novabot-plugin-word-bank.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

魔改自 [nonebot-plugin-wordbank2](https://github.com/kexue-z/nonebot-plugin-word-bank2)，用法相同~~（毕竟基本是 Copy 的）~~

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 Nova-Bot 的根目录下打开命令行, 输入以下指令即可安装


```sh
nb plugin install novabot-plugin-word-bank
```

</details>

<details>
<summary>使用包管理器安装</summary>
在 Nova-Bot 的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令


<details>
<summary>pip</summary>


```sh
pip install novabot-plugin-word-bank
```

</details>

<details>
<summary>pdm</summary>


```sh
pdm add novabot-plugin-word-bank
```

</details>

<details>
<summary>poetry</summary>


```sh
poetry add novabot-plugin-word-bank
```

</details>

<details>
<summary>conda</summary>


```sh
conda install novabot-plugin-word-bank
```

</details>

打开 Nova-Bot 的 `bot.py` 文件, 在其中写入

```python
nonebot.load_plugin('novabot_plugin_word-bank')
```

</details>

<details>
<summary>从 github 安装</summary>
在 Nova-Bot 项目的插件目录下, 打开命令行, 输入以下命令克隆此储存库



```sh
git clone https://github.com/Nova-Noir/novabot-plugin-word-bank.git
```

打开 Nova-Bot 项目的 `bot.py` 文件, 在其中写入

```python
nonebot.load_plugin('path.to.novabot.novabot-plugin-word-bank.novabot_plugin_word-bank')
```

</details>

> 在默认情况下，它应该是
>
> ```python
> nonebot.load_plugin('novabot.plugins.novabot-plugin-word-bank.novabot_plugin_word-bank')
> ```
>
> 

## ⚙️ 配置

目前无，参考源代码。

可修改代码更改问答文件的地址

## 🎉 使用

### 指令表

 看 [nonebot-plugin-wordbank2](https://github.com/kexue-z/nonebot-plugin-word-bank2)