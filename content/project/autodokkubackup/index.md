---
title: AutoDokkuBackup
summary: Dokku sunucusundaki PostgreSQL ve MariaDB veritabanlarının günlük haftalık ve aylık yedeklerini alır.
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

url_code: "https://github.com/ecylmz/autodokkubackup"
url_pdf: ""
url_slides: ""
url_video: ""

---

AutoDokkuBackup, whose name is inspired by `automysqlbackup`, is a simple tool
for Dokku that allows you to automatically take daily, weekly and monthly
backups of MariaDB and PostgreSQL databases.

Note that it is still in beta. Therefore, you should be careful when using it
in production.

Installation
------------

```sh
sudo curl -L https://raw.githubusercontent.com/ecylmz/autodokkubackup/master/autodokkubackup -o /usr/local/bin/autodokkubackup
sudo chmod +x /usr/local/bin/autodokkubackup
```
