[![Cloudflare IP Updater](https://github.com/ertugrulturan/Mikrotik-Cloudflare-Adresslist/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/ertugrulturan/Mikrotik-Cloudflare-Adresslist/actions/workflows/main.yml)
## USE,
```
/system scheduler add interval=24h name=CloudflareUpdate on-event="/import url=https://raw.githubusercontent.com/ertugrulturan/Mikrotik-Cloudflare-Adresslist/main/CloudflareRoute.rsc" policy=read,write start-time=startup
```
