# vpn
安装shadowsocks：
	pip install shadowsocks

启动shadowscoks:
	sslocal -c /etc/shadowsocks.json(仅支持socks5)

chrome安装:
	 打开chrome://extensions/ 把SwitchyOmega_Chromium.crx插件拖进去

配置switchyOmega：
	协议：socks5，代理服务器：localhost 端口：1080

安装shadowsocks图形化界面：
dnf install shadowsocks-qt5
（安装不上添加源dnf copr enable librehat/shadowsocks）
	
