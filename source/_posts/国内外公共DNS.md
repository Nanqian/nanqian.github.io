---
title: 国内外公共DNS
date: 2024-02-17 22:48:33
tags:
---
## 国内公共DNS

### 1. 阿里DNS
[官网](https://alidns.com/)
```
IPv4: 223.5.5.5
IPv4: 223.6.6.6
IPv6: 2400:3200::1
IPv6: 2400:3200:baba::1
DoH: https://223.5.5.dns-query
DoH: https://223.6.6.dns-query
DoH: https://dnalidns.com/dns-query
DoT: dns.alidns.com
DoQ: quic://dns.alidns.com
```

### 2. 腾讯DNS
[官网](https://www.dnspod.cn/Products/publicdns)
```
IPv4: 119.29.29.29
IPv4: 182.254.116.116
IPv6: 2402:4e00::
DoH: https://doh.pub/dns-query
DoH: https://1.12.12.12/dns-query
DoH: https://120.53.53.53/dns-query
DoH (国密): https://sm2.doh.pub/dns-quer
DoT: dot.pub
DoT: 1.12.12.12
DoT: 120.53.53.53
```

### 3. CNNIC DNS
```
IPV4: 1.2.4.8
IPV4: 210.2.4.8
IPV6: 2001:dc7:1000::1
```

### 4. CFIEC DNS
```
IPv6: 240c::6666
IPv6: 240C::6644
DoH: https://dns.cfiec.net/dns-query
DoT: dns.cfiec.net
```

### 5. 360DNS
[官网](https://sdns.360.net/)
```
电信/铁通/移动IPv4: 101.226.4.6
电信/铁通/移动IPv4: 218.30.118.6
联通IPv4: 123.125.81.6
联通IPv4: 140.207.198.6
DoH: https://doh.360.cn/dns-query	
DoT: dot.360.cn
```

### 6. 百度DNS
```
IPv4: 180.76.76.76
IPv6: 2400:da00::6666
```

### 7. iQDNS
[TG频道](https://t.me/iQDNS)
```
TCP/UDP: cn-a.ovo.glass:777
DoH: https://cn-a.iqiqz.com/dns-query
DoH: https://cn-a.iqiqz.com/cdn
DoT: tls://cn-a.iqiqz.com
DoQ: quic://cn-a.ovo.glass
```

### 8. 台湾Quad 101(twnic)
[官网](https://101.101.101.101/)
```
IPV4: 101.101.101.101
IPV4: 101.102.103.104
IPV6: 2001:de4::101
IPV6: 2001:de4::102
DoH: https://dns.twnic.tw/dns-query
DoT: dns.twnic.tw
```


## 国外公共DNS

### 1. Google Public DNS
[官网](https://developers.google.com/speed/public-dns?hl=zh-cn)
```
IPv4: 8.8.8.8
IPv4: 8.8.4.4
DoH: https://dns.google/dns-query
DoT: dns.google
```

### 2. Cloudflare DNS
[官网](https://1.1.1.1/zh-Hans/dns/)
```
IPv4: 1.0.0.1
IPv4: 1.1.1.1
IPv6: 2606:4700:4700::1111
IPv6: 2606:4700:4700::1001
DoH: https://1.1.1.1/dns-query
DoH: https://1.0.0.1/dns-query
DoH: https://1dot1dot1dot1.cloudflare-dns.com/
DoT: one.one.one.one
DoT: cloudflare-dns.com
```
### 3. Quad9
[官网](https://www.quad9.net/service/service-addresses-and-features)
```
IPv4: 9.9.9.9
IPv4: 149.112.112.112
IPv6: 2620:fe::fe
IPv6: 2620:fe::9
DoH: https://dns.quad9.net/dns-query
DoT: dns.quad9.net
```
### 4. DNS.SB
[官网](https://dns.sb/)
```
IPv4: 185.222.222.222
IPv4: 45.11.45.11
IPv6: 2a09::
IPv6: 2a11::
DoH: https://doh.dns.sb/dns-query
DoH: https://doh.sb/dns-query
DoT: dot.sb
```
### 5. CleanBrowsing DNS
[官网](https://cleanbrowsing.org/)
```
#安全保护：阻止对网络钓鱼、垃圾邮件、恶意软件和恶意域的访问。
IPv4：185.228.168.9
IPv4：185.228.169.9
DoH：https://doh.cleanbrowsing.org/doh/security-filter/
DoT：dns.cleanbrowsing.org
     
#成人保护：阻止访问所有成人、恶意和网络钓鱼网站。它不会阻止代理、混合内容网站（如 Reddit）
IPv4：185.228.168.10
IPv4：185.228.169.11
DOH：https://doh.cleanbrowsing.org/doh/adult-filter/
DOT：dns.cleanbrowsing.org
     
#家庭保护:阻止访问所有成人、恶意、网络钓鱼、混合内容网站（如 Reddit）、阻止用于绕过过滤器的代理、Google、Bing 和 Youtube 设置为安全模式。
IPv4：185.228.168.168
IPv4：185.228.169.168
DoH：https://doh.cleanbrowsing.org/doh/family-filter/
DoT：dns.cleanbrowsing.org
```

### 6. AdGuard DNS
[官网](https://adguard-dns.io/zh_cn/public-dns.html)
```
#无过滤，不拦截
IPv4：94.140.14.140
IPv4：94.140.15.15
DoH：https://dns-unfiltered.adguard.com/dns-query
DoT：dns-unfiltered.adguard.com
DoQ：dns-unfiltered.adguard.com
     
#过滤广告和跟踪
IPv4：94.140.14.14
IPv4：94.140.15.15
DoH：https://dns.adguard.com/dns-query
DoT：dns.adguard.com
DoQ：dns.adguard.com
     
#家庭过滤：开启安全搜索和安全模式选项、拦截成人内容，并且屏蔽广告和跟踪器
IPv4：94.140.14.15
IPv4：94.140.15.16
DoH：https://dns-family.adguard.com/dns-query
DoT：dns-family.adguard.com
DoQ：quic://dns-family.adguard.com
```