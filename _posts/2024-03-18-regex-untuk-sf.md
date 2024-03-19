---
layout: post
title:  "Daftar Regex untuk Screaming Forg"
description: "List regex untuk Screaming Forg."
---

# **Daftar Regex untuk Screaming Forg**
## Filter column: Mencocokkan dengan karakter apapun (menghindari blank)
```
.+
```
## Filter column: frasa Soft 404 (Column Title)
```
\b(?:Situs\sTidak\sDitemukan|Site\snot\sfound|Internet\sPositif|Attention\sRequired!|Page\snot\sfound|Index\sof|Site\sis\sundergoing\smaintenance|無効なURLです|The\sdomain\sname\s\w+\sis\sfor\ssale|Account\sSuspended|Website\sSuspended|Suspended)\b
```
List frasa Soft 404
- Situs Tidak Ditemukan
- Site not found
- Internet Positif
- Attention Required!
- Page not found
- Index of /
- Site is undergoing maintenance
- 無効なURLです 
- The domain name [domain name] is for sale
- Account Suspended
- Website Suspended
- Suspended
   
## Filter column: frasa Judi Online di Column Title
```
\b(?:slot|judi|togel)\b
```
**List frasa judi online**
- slot
- judi
- togel
   
## Custom Search: Backlink checks
**LP**
```
(?<=<a\s+(?:[^>]*?\s+)?href=")(https?:\/\/(?:www\.)?lifepal\.co\.id\/[^"]*)(?=")
```
**MS**
```
(?<=<a\s+(?:[^>]*?\s+)?href=")(https?:\/\/(?:www\.)?moneysmart\.id\/[^"]*)(?=")
```
**DP**
```
(?<=<a\s+(?:[^>]*?\s+)?href=")(https?:\/\/(?:www\.)?duitpintar\.com\/[^"]*)(?=")
```
**RJ**
```
(?<=<a\s+(?:[^>]*?\s+)?href=")(https?:\/\/(?:www\.)?roojai\.co\.id\/[^"]*)(?=")
```