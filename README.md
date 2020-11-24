![vimplus-logo][1]

An automatic configuration program for vim
===============================================

![main][2]

## 安装

### Mac OS X

#### 安装[HomeBrew][3]
 
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

#### 安装vimplus

    git clone https://github.com/chxuan/vimplus.git ~/.vimplus
    cd ~/.vimplus
    ./install.sh
    
#### 设置Nerd Font

为防止vimplus显示乱码，需设置mac终端字体为`Fira Code Nerd Font`。

#### 更新vimplus

紧跟vimplus的步伐，尝鲜新特性

    ./update.sh
    

### Linux 64-bit

#### 支持以下发行版

<table>
<tr>
<td><a href="https://distrowatch.com/table.php?distribution=ubuntu"><img src="https://distrowatch.com/images/yvzhuwbpy/ubuntu.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=ubuntukylin"><img src="https://distrowatch.com/images/yvzhuwbpy/ubuntukylin.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=debian"><img src="https://distrowatch.com/images/yvzhuwbpy/debian.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=kali"><img src="https://distrowatch.com/images/yvzhuwbpy/kali.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=deepin"><img src="https://distrowatch.com/images/yvzhuwbpy/deepin.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=mint"><img src="https://distrowatch.com/images/yvzhuwbpy/mint.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=elementary"><img src="https://distrowatch.com/images/yvzhuwbpy/elementary.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=centos"><img src="https://distrowatch.com/images/yvzhuwbpy/centos.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=fedora"><img src="https://distrowatch.com/images/yvzhuwbpy/fedora.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=arch"><img src="https://distrowatch.com/images/yvzhuwbpy/arch.png"/></a><p align="center"></p></td>
</tr>
<tr>
<td><a href="https://distrowatch.com/table.php?distribution=manjaro"><img src="https://distrowatch.com/images/yvzhuwbpy/manjaro.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=opensuse"><img src="https://distrowatch.com/images/yvzhuwbpy/opensuse.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=gentoo"><img src="https://distrowatch.com/images/yvzhuwbpy/gentoo.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=raspios"><img src="https://distrowatch.com/images/yvzhuwbpy/raspios.png"/></a><p align="center"></p></td>
</tr>
</table>


#### 安装vimplus

    git clone https://github.com/chxuan/vimplus.git ~/.vimplus
    cd ~/.vimplus
    ./install.sh //不加sudo
    
#### 设置Nerd Font

为防止vimplus显示乱码，需设置linux终端字体为`Droid Sans Mono Nerd Font`。

#### 多用户支持

将vimplus在某个用户下安装好后，若需要在其他用户也能够使用vimplus，则执行

    sudo ./install_to_user.sh username1 username2 //替换为真实用户名
    
#### 更新vimplus

紧跟vimplus的步伐，尝鲜新特性

    ./update.sh


### Android 64-bit([Termux][87])

#### 安装vimplus

    git clone https://github.com/chxuan/vimplus.git ~/.vimplus
    cd ~/.vimplus
    ./install.sh
    
#### 更新vimplus

紧跟vimplus的步伐，尝鲜新特性

    ./update.sh

#### 说明

这是我从chxuan/vimplus修改而来，基本与原来一致，
但去除了一些不必要的插件，更改了默认字体为Fira Code。
同时为了节约时间，去掉了YCM。

这里面的代码、文档、图片等均归原作者所有。仅供学习使用。

最后感谢原作者大大chxuan！
