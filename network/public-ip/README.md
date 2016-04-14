Public IP Displayer
=
Linux Command Translator for icanhazip.com
Go to https://major.io/icanhazip-com-faq/ for more detail.
## Installation
```bash=
git clone http://github.com/HuaiShaoChang/script.git
sudo cp script/network/public-ip/public /usr/bin/
chmod a+x /usr/bin/public
```
## Usages
### Get Public IP
#### Commands
```bash=
public ip
public ipv4
public ipv6
```
#### Outputs
```=
111.243.103.183
111.243.103.183
ipv6 is not support on your machine.
```
### Get rDNS/PTR
#### Commands
```bash=
public rdns
public ptr
```
#### Outputs
```=
111-243-103-183.dynamic.hinet.net
111-243-103-183.dynamic.hinet.net
```
### Trace Route from icanhaztrace.com
#### Command
`public ip traceroute`
#### Output
```=
traceroute to 111.243.103.183 (111.243.103.183), 30 hops max, 60 byte packets
 2  69.20.1.64 (69.20.1.64)  1.324 ms
 3  core7-corea.iad3.rackspace.net (69.20.2.96)  1.340 ms
 4  dcpe2-coreb.iad3.rackspace.net (69.20.2.172)  1.927 ms
 5  be1-mspe2.iad3.rackspace.net (10.25.2.79)  1.561 ms
 6  xe-2-3-1.er2.dca2.us.above.net (208.185.125.153)  2.228 ms
 7  ae-3-80.edge2.LosAngeles9.Level3.net (4.69.144.143)  63.169 ms
 8  ae-3-80.edge2.LosAngeles9.Level3.net (4.69.144.143)  63.149 ms
 9  CHUNGHWA-TE.edge2.LosAngeles9.Level3.net (4.53.230.54)  63.211 ms
10  ae5.cs2.dfw2.us.eth.zayo.com (64.125.28.103)  62.836 ms
11  ae3.cs2.lax112.us.eth.zayo.com (64.125.29.21)  74.258 ms
12  ae27.cr2.lax112.us.zip.zayo.com (64.125.30.187)  63.281 ms
13  tpdt-3308.hinet.net (220.128.2.81)  212.186 ms
14  h5.s25.ts.hinet.net (168.95.25.5)  209.757 ms
15  *
16  111-243-103-183.dynamic.hinet.net (111.243.103.183)  206.630 ms
```
