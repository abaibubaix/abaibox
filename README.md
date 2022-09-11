# 阿白 常用脚本工具包
玩机，是不是有很多命令或者脚本记不住，因此我整理了一些我个人常用的脚本。
***

# 使用说明
安装依赖（新机器必须运行一次，此后无需运行）

	yum install -y curl wget 2> /dev/null || apt install -y curl wget

安装并运行脚本




	wget -O abaibox.sh https://raw.githubusercontent.com/abaibubaix/abaibox/main/abaibox.sh && chmod +x abaibox.sh && clear && ./abaibox.sh
英文版，机器翻译English version

	wget -O abaibox-en.sh https://raw.githubusercontent.com/abaibubaix/abaibox/main/abaibox-en.sh && chmod +x abaibox-en.sh && clear && ./abaibox-en.sh
***


# 功能说明
1. 服务器检查：
    - Lemonbench 综合测试
    - 三网Speedtest测速
	- 内存压力测试
	- 回程路由追踪
	- Speedtest测速
	- 获取本机IP
	- 流媒体解锁测试
	- 检测/诊断Youtube地域
2. 服务器功能
	- Linux换源脚本
	- ipv4/6优先级调整
	- 虚拟内存SWAP一键安装
	- 一键安装BBR
	- 系统网络配置优化
	- 宝塔中文官方一键安装
	- 宝塔英文官方一键安装（无需验证）
	- 宝塔破解纯净版
	- Cloudflare WARP 一键配置脚本（2021年7月3日添加）
3. 科学上网工具
	- iptables一键中转
	- gost一键中转
	- MTP&TLS 一键脚本
	- xray一键安装8合一脚本
	- x-ui一键安装
	- wulabing一键xray脚本
	- Ehcoo隧道中转(2021年7月3日添加)

***

# 免责声明
* abaibox属于自用分享工具，请勿用于违背良知与道德之事，否则后果自负。
* 工具中所有脚本均来自互联网，不对脚本安全性负责。如果你比较在意安全，请勿使用各类一键脚本。
***

# 感谢
 * [BlueSkyXN](https://github.com/BlueSkyXN/SKY-BOX)
 * [arloor](https://github.com/arloor/iptablesUtils)
 * [KANIKIG](https://github.com/KANIKIG/Multi-EasyGost)
 * [wulabing](https://github.com/wulabing/Xray_onekey)
 * [mack-a](https://github.com/mack-a/v2ray-agent)
