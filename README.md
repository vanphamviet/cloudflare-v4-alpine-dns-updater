# Cloudflare DNS Updater Script for Alpine Linux
An updater for Alpine Linux. This updater can update the DNS record. It was inspired of [yulewang/cloudflare-api-v4-ddns](https://github.com/yulewang/cloudflare-api-v4-ddns)
--
You should install:

- bash #(for running sh file, bash is not default on Alpine Linux):
```
 doas apk add bash 
```
- perl #(for replacing 'grep' with -Po option):
```
 doas apk add perl
```

Using:
---
```
 doas wget https://raw.githubusercontent.com/vanphamviet/cloudflare-v4-alpine-dns-updater/main/cf-v4-ddns.sh 
```

```
 doas mv cf-v4-ddns.sh /usr/local/bin/cf-v4-ddns.sh 
```

```
 cd /usr/local/bin
```

```
 doas chmod +x ./cf-v4-ddns.sh
```
Then you can set the variable CFKEY,  CFZONE_NAME, CFRECORD_NAME, CFRECORD_TYPE,..
