---
layout: article
title: Tableau
menu_title: Tableau
description: Peakboard Designer Tableau控件相关信息。
lang: cn
ref: con-07
---

您可以使用Tableau视图控件元素在Peakboard上显示Tableau视图。Tabelau视图位于Tableau服务器上，并在那呈现。Peakboard可作为显示器。

![image_1](/assets/images/Controls/Tableau/ControlsTableau01.png)

为了让Peakboard能有效访问Tableau服务器，您必须将服务器上Peakboard的IP地址设置为“可信”：

1.在Tableau服务器上，以管理员身份启动Tableau控件窗口。控制台窗口可以在* * C: \Program Files\Tableau\Tableau Server\9.2\bin* *中找到

2.执行以下命令：

```
tab admin stop
tabadmin set wgserver. trusted_hosts “<IP address of Peakboard >”
tabadmin config
tab admin start
```

更多信息，请访问：[http://onlinehelp.tableau.com/current/server/en-us/trusted_auth.htm](http://onlinehelp.tableau.com/current/server/en-us/trusted_auth.htm)
在Tableau视图控件中，必须在属性窗口中填写以下选项：

**Server：**tableau服务器的IP地址
**Username：**tableau服务器的用户名
**Workbook：**包含视图的tableau工作簿的名称。
**View：**要在Peakboard上显示的视图的名称

以下两张图片显示了tableau服务器上的原始tableau仪表板及在Peakboard面板上的表示形式。

![image_1](/assets/images/Controls/Tableau/ControlsTableau02.png)

![image_1](/assets/images/Controls/Tableau/ControlsTableau03.png)
