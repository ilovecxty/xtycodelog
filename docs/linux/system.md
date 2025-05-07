# System-操作系统

linux操作系统选取

# Linux 基础知识

Linux是一种自由和开源的操作系统，以Unix为基础。它支持多种硬件平台，并具有稳定、安全和灵活的特点。Linux由一个核心（内核）和一系列周边的工具和应用程序组成。Linux的内核由芬兰的开发者Linus Torvalds在1991年创建，并在全球范围内得到了广泛的开发和支持。Linux内核提供了操作系统的核心功能，包括进程管理、文件系统、设备驱动和网络功能等。在Linux操作系统上，用户可以使用命令行界面或图形化界面进行操作。Linux拥有丰富的命令行工具和脚本语言，使用户可以通过编写脚本和命令来自动化任务和定制操作系统。

Linux有许多不同的发行版，如Ubuntu、Debian、Fedora和CentOS等。这些发行版在某种程度上基于Linux内核，并添加了特定的软件包和配置，以满足不同用户的需求。Linux以其稳定性、安全性和灵活性而备受赞誉，并被广泛用于各种设备，包括个人电脑、服务器、嵌入式系统、移动设备和超级计算机等。它也被广泛应用于云计算、大数据和人工智能等领域。

[Linux教程  https://www.runoob.com/linux/linux-tutorial.html](https://www.runoob.com/linux/linux-tutorial.html)

## Linux 系统结构

Linux 是一种自由和开放源代码的 Unix-like 操作系统内核。它被设计为多用户、多任务和支持多种处理器架构。Linux 内核是操作系统的核心部分，负责管理计算机硬件和软件资源的分配。Linux 系统是基于 Linux 内核构建的完整操作系统。

Linux 系统有许多不同的发行版，如 Ubuntu、Debian、Red Hat 等。这些发行版是基于 Linux 内核，并包含了一套软件包和工具集，以便用户方便地安装和管理系统。不同的发行版可能有不同的软件包管理系统、文件系统和用户界面，以满足不同用户的需求。

内核和系统之间的区别在于，内核是操作系统的核心组件，负责管理硬件和资源，提供系统调用接口供应用程序使用。而操作系统则包括了内核以及其他各种组件，如文件系统、驱动程序、图形界面等。内核是操作系统的核心，而系统是由内核及其相关组件构成的完整软件。

## Linux发行版

Arch系发行版：**EndeavourOS  Manjaro  Arch**

轻量级发行版：**[Lubuntu](https://lubuntu.net/)  [EndeavourOS](https://endeavouros.com/)  [Linux Lite](https://www.linuxliteos.com/)**

超小发行版： **[Puppy Linux](https://distrowatch.com/puppy) [Tiny Core Linux](https://distrowatch.com/tinycore)**

### 老电脑

**1. [antiX](https://distrowatch.com/antix)**
antiX 是一个快速、轻量级且易于安装的 Linux live CD 发行版，基于 Debian 的 x86 兼容系统的“稳定”分支。antiX在适合旧计算机的环境中为用户提供“antiX魔术”。antiX的目标是为Linux的新手和有经验的用户提供一个轻量级的，但功能齐全且灵活的免费操作系统。对于 antiX，建议至少使用 256 MB RAM。安装程序至少需要 2.7 GB 的硬盘大小。

**4. [Bodhi Linux](https://distrowatch.com/bodhi)**
Bodhi Linux是一个优雅而轻量级的基于Debian / Ubuntu的发行版，具有Moksha，一个基于Enlightenment-17的桌面环境。该项目采用绝对简约的方法，提供模块化、高水平的定制和主题选择。Bodhi版本有几个版本，包括标准版（64位）和Legacy版（32位），它们是极简主义的，仅包括Web浏览器，终端，文件管理器，文本编辑器和照片GUI应用程序，而AppPack版本包括更多预装的应用程序和工具。其他软件可以通过Bodhi基于Web的AppCenter，Synaptic和APT添加。

树莓派

**[Manjaro](https://distrowatch.com/manjaro)**

**[Pop!_OS](https://distrowatch.com/popos)**

### 新手

1. **[Manjaro](https://manjaro.org/)** 

2. **[Ubuntu](https://ubuntu.com/download/desktop)** 

3. **[Pop!_OS](https://pop.system76.com/)**

  **[100’s of informative videos](https://www.youtube.com/user/System76Video) and [growing list of help articles](https://support.system76.com/articles/)**. 

4. **[Linux Mint](http://linuxmint.com/)**

Best Linux Distros for Experienced Users:

5. **[Fedora](http://fedoraproject.org/)**

6. **[Debian](http://www.debian.org/)**

7. **[openSUSE](https://www.opensuse.org/)**

Best Linux Distros for Experts:

8. **[Arch Linux](http://www.archlinux.org/)**

9. **[Gentoo](http://www.gentoo.org/)**

10. **[Kali Linux](https://www.kali.org/)**

Bonus: Unique Linux distros

- **[Linux from scratch](http://www.linuxfromscratch.org/)** – Not a distro, but a challenging project that provides step-by-step instructions for building your own custom Linux system entirely from source code.

- **[Void Linux](https://voidlinux.org/)**: Void offers a unique Linux experience with its own package management system called xbps. It’s known for speed, simplicity, and providing a rolling release model similar to Arch.

- **[Calculate Linux](https://www.calculate-linux.org/)**: Based on Gentoo, Calculate is a collection of several distributions that are designed to be fast, optimized, and bootable directly from a USB stick or CD/DVD.

- **[Alpine Linux](https://alpinelinux.org/)**: While not as similar, Alpine is worth mentioning for its security, simplicity, and resource efficiency. It uses musl libc and busybox to keep its size small, which is something that advanced users who like minimal systems might appreciate.

NixOS

NixOS Guix

Nix手册：[Nixos手册](https://nixos.org/nixos/manual/)

Nix查看系统版本：`nixos-version` or `nix-info -m`

Nix系统更新包与配置：`sudo nixos-rebuild switch`

## 一些Linux发行版的评价

热门发行版：

Ubuntu：经典和新手必备

Arch Linux：没有桌面，难用，arch确实舒服

Manjaro：不知道为啥大家推荐，没找到特点，应该是因为Arch系但比arch友好？pac舒服，友好的Arch，很舒服

EndeavoursOS：比manjaro友好一些 在线安装比较狗屎 i3很好用

KDE Neon：原生包管理器没有镜像，连接不上

Linux Lite：没啥特点

Linux Mint：没啥特点

---

精简发行版：

Tiny Core：小，低配核心

Puppy Linux：小，新手友好

Lubuntu：没啥特点

antiX：不是很行，自带的包管理器不能安装新的桌面环境

bodhi Linux：没啥特点，界面很丑

