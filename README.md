# Cloudflare DNS Updater Script for Alpine Linux
An updater for Alpine Linux. This updater can update the DNS record. It was folked from [yulewang/cloudflare-api-v4-ddns](https://github.com/yulewang/cloudflare-api-v4-ddns)
You should install:
- bash: apk add bash (not default on Alpine Linux)
- perl: apk add perl (for replacing 'grep' with -Po option)
