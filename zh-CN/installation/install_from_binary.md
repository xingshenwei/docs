---
name: 二进制安装
---

# 二进制安装

**目前只提供最近发布的小版本二进制下载，更多版本下载请前往 [GitHub](https://github.com/gogs/gogs/releases) 查看。**

所有的版本都支持 **MySQL**、**PostgreSQL**、**MSSQL** 和 **TiDB**（使用 MySQL 协议）作为数据库，并且均使用构建标签（build tags）**`cert`** 进行构建。需要注意的是，不同的版本的支持状态有所不同，请根据实际的 Gogs 提示进行操作。

## 备注

- `mws` 表示提供内置 Windows 服务支持，如果您使用 NSSM 请使用另外一个版本。

## 如何使用下载好的压缩包？

1. 解压压缩包。
2. 使用命令 `cd` 进入到刚刚创建的目录。
3. 执行命令 `./gogs web`，然后，就没有然后了。

## 如何通过二进制升级？

1. 下载最新版的压缩包。
2. 删除当前的 `templates` 目录。
3. 解压压缩包并将所有内容复制粘贴到相应（当前）的位置。

### 0.11.66 @ 2018-09-16

|系统名称|系统类型|SQLite|PAM|下载（[GitHub](https://github.com/gogs/gogs/releases/tag/v0.11.66)）|
|------|----|------|---|--------|
|Linux|386|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.66/gogs_0.11.66_linux_386.tar.gz) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_linux_386.zip) \| [TAR.GZ](http://gogs.dn.qbox.me/gogs_0.11.66_linux_386.tar.gz)|
|Linux|amd64|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.66/gogs_0.11.66_linux_amd64.tar.gz) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_linux_amd64.zip) \| [TAR.GZ](http://gogs.dn.qbox.me/gogs_0.11.66_linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_linux_armv5.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_linux_armv5.zip)|
|Raspberry Pi|v2&v3 / armv6|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_raspi2_armv6.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_raspi2_armv6.zip)|
|Windows|386|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.66/gogs_0.11.66_windows_386_mws.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_windows_386.zip) \| [ZIP w/mws](http://gogs.dn.qbox.me/gogs_0.11.66_windows_386_mws.zip)|
|Windows|amd64|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.66/gogs_0.11.66_windows_amd64_mws.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_windows_amd64.zip) \| [ZIP w/ mws](http://gogs.dn.qbox.me/gogs_0.11.66_windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.66/gogs_0.11.66_darwin_amd64.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.66_darwin_amd64.zip)|

### 0.11.53 @ 2018-06-05

|系统名称|系统类型|SQLite|PAM|下载（[GitHub](https://github.com/gogs/gogs/releases/tag/v0.11.53)）|
|------|----|------|---|--------|
|Linux|386|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.53/gogs_0.11.53_linux_386.tar.gz) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_linux_386.zip) \| [TAR.GZ](http://gogs.dn.qbox.me/gogs_0.11.53_linux_386.tar.gz)|
|Linux|amd64|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.53/gogs_0.11.53_linux_amd64.tar.gz) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_linux_amd64.zip) \| [TAR.GZ](http://gogs.dn.qbox.me/gogs_0.11.53_linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_linux_armv5.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_linux_armv5.zip)|
|Raspberry Pi|v2&v3 / armv6|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_raspi2_armv6.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_raspi2_armv6.zip)|
|Windows|386|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.53/gogs_0.11.53_windows_386_mws.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_windows_386.zip) \| [ZIP w/mws](http://gogs.dn.qbox.me/gogs_0.11.53_windows_386_mws.zip)|
|Windows|amd64|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.53/gogs_0.11.53_windows_amd64_mws.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_windows_amd64.zip) \| [ZIP w/ mws](http://gogs.dn.qbox.me/gogs_0.11.53_windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.53/gogs_0.11.53_darwin_amd64.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.53_darwin_amd64.zip)|

### 0.11.43 @ 2018-03-31

|系统名称|系统类型|SQLite|PAM|下载（[GitHub](https://github.com/gogs/gogs/releases/tag/v0.11.43)）|
|------|----|------|---|--------|
|Linux|386|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_386.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_386.tar.gz) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_linux_386.zip) \| [TAR.GZ](http://gogs.dn.qbox.me/gogs_0.11.43_linux_386.tar.gz)|
|Linux|amd64|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_amd64.zip) \| [TAR.GZ](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_amd64.tar.gz) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_linux_amd64.zip) \| [TAR.GZ](http://gogs.dn.qbox.me/gogs_0.11.43_linux_amd64.tar.gz)|
|Linux|armv5|❌|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_linux_armv5.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_linux_armv5.zip)|
|Raspberry Pi|v2&v3 / armv6|✅|✅|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_raspi2_armv6.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_raspi2_armv6.zip)|
|Windows|386|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_386.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_386_mws.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_windows_386.zip) \| [ZIP w/mws](http://gogs.dn.qbox.me/gogs_0.11.43_windows_386_mws.zip)|
|Windows|amd64|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_amd64.zip) \| [ZIP w/ mws](https://dl.gogs.io/0.11.43/gogs_0.11.43_windows_amd64_mws.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_windows_amd64.zip) \| [ZIP w/ mws](http://gogs.dn.qbox.me/gogs_0.11.43_windows_amd64_mws.zip)|
|Mac OS|amd64|✅|❌|HTTPS: [ZIP](https://dl.gogs.io/0.11.43/gogs_0.11.43_darwin_amd64.zip) - CDN: [ZIP](http://gogs.dn.qbox.me/gogs_0.11.43_darwin_amd64.zip)|

安装完成后可继续参照 [配置与运行](configuration_and_run.html)。
