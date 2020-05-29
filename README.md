rojan一键脚本，开启TLS1.3，系统支持centos7+/debian9+/ubuntu16+
atrandys • 2019年12月30日 pm6:55 • Trojan, 学术上网 • 阅读 30226
最简单的Trojan三合一一键脚本，效率高/速度快/延迟低，系统支持centos7+/debian9+/ubuntu16+，完美支持tls1.3，速度优于V2ray+ws+tls1.3，新手必备。

注意事项
1、如果你用了各种云，记得在控制台把80、443端口开放，如果你不懂怎么开放去谷歌

2、遇到问题去tg群反馈

使用方法
1、执行以下脚本，然后选择1，安装trojan，然后输入解析到VPS的域名，回车安装即可。注意：安装时不要开启CDN，否则会提示IP地址不匹配，如果是多IP VPS遇到这个问题，修改一下本地已经下载的脚本，把$real_addr == $local_addr改为$real_addr == $real_addr，然后在执行脚本。
```bash
curl -O https://raw.githubusercontent.com/atrandys/trojan/master/trojan_mult.sh && chmod +x trojan_mult.sh && ./trojan_mult.sh
```
自己备份：
```bash
wget -N --no-check-certificate "https://raw.githubusercontent.com/gugd123/-Trojan1111/master/trojan-web-panel.sh" && chmod +x trojan-web-panel.sh && ./trojan-web-panel.sh
```
