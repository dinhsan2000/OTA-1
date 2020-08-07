# Cherish #

### device_codename.json template ###
```bash

{
  "error": false,
  "id": "b4683561a00022dc12847939990b273607fed6c879fac55ed86ffb5d4bcbf23f",
  "filename": "Cherish-OS-v1.x-{device}-{YYYYmmdd}-{HHMM}-OFFICIAL.zip",
  "datetime": 1974574271,
  "version": "v1.x",
  "size": 1321094201,
  "url": "https://sourceforge.net/projects/cherish-os/files/device/{brand}/{device}/Cherish-OS-v1.x-{device}-{YYYYmmdd}-{HHMM}-OFFICIAL.zip/download",
  "filehash": "722160da4ae76a288f71b2fbdbc2576d",
  "website_url": "https://sourceforge.net/projects/cherish-os/files/device",
  "news_url": "https://t.me/cherishos",
  "donate_url": "https://Paypal.me/hungphan2001",
  "maintainer": "Hung Phan",
  "maintainer_url": "https://github.com/hungphan2001",
  "forum_url": "https://t.me/cherishos_chat"
}

```
### device_codename.json ###
| Param | Description | Required |
### See ###
Before you compile a build, you need to type this into your terminal:
```bash
date +%s
```
It will generate a number, it is used in your "json" file in the local datetime.

datetime = number generate

filename = Name file zip rom

id = sha256sum

filehash = Build file (.zip) md5 hash

version = Cherish version 

size = Build file (.zip) size (in bytes) (use terminal wc -c Rom.zip)

url = Direct link for download

website_url = https://sourceforge.net/projects/cherish-os/files/device

news_url = https://t.me/CherishOS

maintainer = your name

forum_url  = XDA Thread 

### device_codename.md template ###
```bash

^Cherish
 "Changelog"

```

Note: Add Changelog from second line only
