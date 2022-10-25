# 如何安装
## Windows
在[Gitee](https://gitee.com/XmacsLabs/mogan/releases)下载安装包，然后双击按照提示安装即可。

> 说明：GNU TeXmacs是独立于LaTeX/TeX实现的，不需要再安装TeXLive。

## macOS
在[Gitee](https://gitee.com/XmacsLabs/mogan/releases)下载安装包，然后按照macOS平台通用的步骤安装即可。因为我们没有购买苹果的开发者认证，所以需要在苹果系统的安全设置中选择仍然打开。

TODO: 完整的步骤。

## GNU/Linux
### OpenSUSE

对于 openSUSE Tumbleweed，请以根用户 root 运行下面命令：
``` bash
zypper addrepo https://download.opensuse.org/repositories/home:iphelf/openSUSE_Tumbleweed/home:iphelf.repo
zypper refresh
zypper install Mogan
```
更多信息：https://software.opensuse.org/download/package?package=Mogan&project=home%3Aiphelf
