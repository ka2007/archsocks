# archsocks

SOCKS 代理服务 - 免费加速Google搜索、Gmail、维基百科、Feedly、Inoreader，加速其它网站只需少量费用。


# 特性

* 模拟 HTTP 流量: 完全模拟正常上网流量并采用80端口，无视企业防火墙。
* 多节点: 拥有多个代理节点自动切换，上网更快更稳定。
* 自动流量分类: 只对需要代理的网站使用代理，不会减慢国内网站速度，节省代理流量。
* 本地 SOCKS 代理: 使用本地 SOCKS 代理接口方式，比 VPN 和 SSH 方式更方便和稳定。


# 价格

*所有套餐都可以按月付，付款方式在客户端界面里。*

流量/周期 | Google/Gmail/维基百科 | 12GB/月 | 24GB/月 | 64GB/月
---------- | --------------------- | ------ | ------- | -------
价格      | 永久免费              | 2元/月 | 3元/月（8折）  | 6元/月（5折）


# 下载

[Windows 版](http://104.129.177.141/files/archsocks-setup.exe)

[Linux / OS X 版](http://104.129.177.141/files/archsocks.tar.gz)


# 安装

在安装完成后，用浏览器打开网址 <http://127.0.0.1:9501> 即可查看设置教程/程序运行状态/当前流量用量/购买链接。

## Windows

运行下载的 `.exe` 安装程序。安装完后服务会自动启动，同时添加自身到 Windows 启动组（会随 Windows 启动而自启动）。

* 使用 Chrome 时可能和迅雷有冲突，如果无法正常使用需要卸载迅雷。
* 之装之前，如果之前已经安装过 archsocks 了，需要先卸载程序：打开开始菜单，找到 archsocks 程序组，点击里面的“卸载 archsocks”菜单条目。
如果还有问题就用进程管理器结束二个 `archsocks.exe` 进程。

## Linux / OS X

程序以 Python 源码形式发布，需要确保系统已安装[Python 3.4或以上版本](https://www.python.org)。
解压下载的压缩文件后运行里面的 `archsocks` 文件以启动程序。


# 技巧

* 如果你需要转 SOCKS 代理成 HTTP 代理，或架设在内网（或者公网），为其他设备提供智能分流代理，可以使用 [MEOW](https://github.com/renzhn/MEOW/)。


# 客户端操作界面

![截图](https://raw.githubusercontent.com/archsocks/archsocks/master/screenshot.png)


# 联系方式

请发[Issue](https://github.com/archsocks/archsocks/issues)或发邮件至`archsocks [at] gmail.com`。
