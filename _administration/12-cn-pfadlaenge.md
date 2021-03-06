---
layout: article
title: 不受限制的路径长度
menu_title: 不受限制的路径长度
description: 不受限制的路径长度
lang: cn
ref: admin-12
---

在某些情况下，有必要取消Windows IoT路径长度的限制。

例如，使用文件名过长的OPC UA证书时就会出现这种情况。

如要消除此限制，请执行以下步骤：

首先单击Peakboard Designer中的“管理”，并为相应的Peakboard box选择菜单项“打开设备门户”。

![Manage Dialog Open Device Portal](/assets/images/admin/pathlength/manage-dialog-open-device-portal.png)

现在，浏览器窗口将会打开。输入“Administrator”作为Peakboard-Box的用户名和密码。

现在选择左侧的进程，然后选择运行命令以查看命令窗口，您可以在其中输入以下命令：

```
Reg add HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FileSystem /v LongPathsEnabled /t REG_DWORD /d 1 /f
```

最后，点击“电源”– “重启”来重启盒子。

![Run Command Windows Device Portal](/assets/images/admin/pathlength/run-command-windows-device-portal.png)
