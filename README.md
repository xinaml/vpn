# vpn：

linux下使用流程：

1.安装shadowsocks：
	pip install shadowsocks

2.启动shadowscoks:
	sslocal -c /etc/shadowsocks.json(仅支持socks5)（shadowsocks必须配置正确的服务器，加密方式，密码）

3.chrome 安装插件 :
	 打开chrome://extensions/ 把SwitchyOmega_Chromium.crx插件拖进去

配置switchyOmega：
	协议：socks5，代理服务器：localhost 端口：1080

（此步可忽略）安装shadowsocks图形化界面：
dnf install shadowsocks-qt5
（安装不上添加源dnf copr enable librehat/shadowsocks）


window 下使用：

解压：Shadowsocks-4.1.3.1-window.zip，启动配置正确的服务器，加密方式(aes-256-cfb)，密码即可

	
	
