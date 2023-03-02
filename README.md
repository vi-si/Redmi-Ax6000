## Redmi AX6000 闭源驱动固件 源码来源

- hanwckf-[hanwckf/immortalwrt-mt798x](https://github.com/hanwckf/immortalwrt-mt798x).
```bash
git clone -b openwrt-21.02 --single-branch https://github.com/hanwckf/immortalwrt-mt798x
```

### 感谢所有为OpenWrt无私奉献的大佬们


```bash
运行模式 Fake-IP（TUN）模式

*本地 DNS 劫持 使用 Dnsmasq 转发

自定义上游 DNS 服务器

追加上游 DNS （取消打勾）

追加默认 DNS （取消打勾）

禁止 Dnsmasq 缓存 DNS
```
```bash
NameServer 组

dns.rubyfish.cn/dns-query

dns.alidns.com/dns-query

doh.pub/dns-query

223.5.5.5/dns-query

1.12.12.12/dns-query
```
```bash
FallBack 组

dns.cloudflare.com/dns-query

dns.google/dns-query

1.1.1.1/dns-query

1.0.0.1/dns-query

8.8.8.8/dns-query

8.8.4.4/dns-query
```
```bash
IPv6 流量代理 （打勾选上）
```
