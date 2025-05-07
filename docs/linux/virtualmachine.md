# VirtualMachine-虚拟机

虚拟机相关

## 虚拟机事项

如何安装虚拟机

VMWARE安装

VirtualBox安装

VirtualBox拓展包

操作系统安装

共享剪切板

拖放操作

共享文件夹：Virtualbox的共享文件夹一般都挂载在/media下面，用ll查看会发现文件夹的所有者是root，所有组是vboxsf，所以文件管理去无法访问是正常的，解决方法是把自己加入到vboxsf组里面 `sudo usermod -a -G vboxsf username`

Virtural Box虚拟机扩容：工具/介质/选择对应硬盘-属性-大小可以扩容


## 虚拟机

在 VirtualBox 中配置共享文件夹后，如果在虚拟机（如 Ubuntu 或其他 Linux 发行版）中遇到没有权限访问共享文件夹的问题，通常是因为共享文件夹的所有权和权限设置不正确。以下是一些步骤来解决这个问题：

1. **确认共享文件夹已启用**：
确保在 VirtualBox 的虚拟机设置中，共享文件夹已被正确设置并且处于启用状态。

2. **添加用户到 vboxsf 组**：
在 Linux 虚拟机中，你需要将你的用户账户添加到 `vboxsf` 组中。这是因为 VirtualBox 使用这个特定的组来管理对共享文件夹的访问。你可以通过终端执行以下命令：

  ```Shell
sudo usermod -a -G vboxsf <your_username>
```


  将 `<your_username>` 替换为你的用户名。

3. **重启虚拟机**：
添加用户到 `vboxsf` 组后，需要重启虚拟机以便用户组的更改生效。

4. **检查共享文件夹权限**：
登录到虚拟机后，检查共享文件夹的权限是否允许你的用户访问。你可以使用 `ls -ld /media/sf_<folder_name>` 命令来查看权限，其中 `<folder_name>` 是你共享文件夹的名字。

  如果所有权是 `root:vboxsf` 并且权限不允许你的用户访问，你可以尝试更改权限：

  ```Shell
sudo chown -R <your_username>:vboxsf /media/sf_<folder_name>
sudo chmod -R 775 /media/sf_<folder_name>
```


  这将更改文件夹的所有权并设置权限，使你和其他 `vboxsf` 组的成员能够读写访问。

5. **检查自动挂载设置**：
如果你希望每次启动虚拟机时自动挂载共享文件夹，确保 `/etc/vboxaddautofs` 文件中有正确的条目。如果该文件不存在，你可能需要安装 VirtualBox Guest Additions。

6. **安装 VirtualBox Guest Additions**：
如果尚未安装，应安装 VirtualBox Guest Additions，这将提供额外的功能，包括更好的共享文件夹支持。

请根据上述步骤逐一检查和解决问题。如果还有问题，可以提供更多关于你的具体环境和错误信息，以便进一步诊断。

