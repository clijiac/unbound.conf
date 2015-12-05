# unbound.conf

使用说明可参考[Unbound+DNSCrypt双保险防DNS污染及劫持](https://goo.gl/IG3K27)

国内域名默认由114.114.114.114和223.5.5.5解析，配置在unbound.forward-zone.China.conf。
其他域名默认由监听在9999端口的DNSCrypt解析，配置在unbound.forward-zone.Global.conf。

国内域名列表取自[dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)，如果你有其他国内域名需要添加，请直接向dnsmasq-china-list项目反馈。
