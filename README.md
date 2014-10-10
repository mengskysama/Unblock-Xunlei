Unblock-Xunlei
=============

(就是这个)https://github.com/mengskysama/Unblock-Youku

如何部署
=============

需要SAE(或者国内服务器)和另一台80端口服务器

bae_xunlei_proxy.py部署在国内服务器上sinapp py环境测试通过

xunlei_proxy.py部署在一台服务器上，修改代码中的

```proxy = 'seaaddress.sinaapp.com'

eth = ('server_ip', 80)```

这个例子需要独占80端口。当然你可以通过配置nginx判断Host进行反代，但是这样会很麻烦你需要做urls.py很多的正则匹配。


如何使用
=============

如果只是需要解锁迅雷，请在Hosts中添加

`hub5btmain.sandai.net  xunlei_proxy.py的IP`



使用我提供的proxy
=============

Hosts

`hub5btmain.sandai.net  23.95.50.139`