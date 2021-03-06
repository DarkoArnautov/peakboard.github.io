---
layout: article
title: 添加证书
menu_title: 添加证书
description: 添加证书
lang: cn
ref: admin-09
---

首先，证书必须作为文件存在于文件系统中。

例如，从Chrome上下载，是存储它的最简单方法。



转到相应的https页面；按Ctrl+Shift+I键，在“安全性”选项卡中显示证书。

您可以在“详细信息”选项卡将其保存为文件。对于这种情况，“DER（*.cer）就足够了。

![Zertifikat Details](/assets/images/admin/certificates/zertifikat-details.png)

将导出的文件复制到设备。

如要执行此操作，请在Windows资源管理器中访问管理员共享\\\<ip>\c$in，并将其存储于c:\users\public\文件夹中。

输入管理员用户名和密码。

![Window Explorer](/assets/images/admin/certificates/windows-explorer.png)

然后通过PowerShell连接到设备。

以管理员身份在本地运行PowerShell

* net start WinRM
* Set-Item WSMan:\localhost\Client\TrustedHosts -Value <ip-address>
* Enter-PSSession -ComputerName <ip address> -Credential localhost\administrator
When connected, import the certificate into the certificate store:
* $cert = “c:\users\public\demo.cer”
* Import Certificate -FilePath $cert -CertStoreLocation Cert:\LocalMachine\Root

![PowerShell](/assets/images/admin/certificates/powershell.png)

现在，在调用证书时应该自动将其归类为可信。

但前提条件是它必须是正确颁发的证书，即不能再用SHA-1创建，且URL中服务器的主机名称必须与证书中的名称相匹配。
