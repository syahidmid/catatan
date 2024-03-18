---
layout: post
title:  "Daftar Regex untuk Screaming Forg"
---

# Daftar Regex untuk Screaming Forg 
**Filter untuk col Title yang tidak blank**
```
.+
```
**Filter frasa di Col Title untuk Menemukan Soft 404**
```
\b(?:Situs\sTidak\sDitemukan|Site\snot\sfound|Internet\sPositif|Attention\sRequired!|Page\snot\sfound|Index\sof)\b
```
List frasa Soft 404
- Situs Tidak Ditemukan
- Site not found
- Internet Positif
- Attention Required!
- Page not found
- Index of /
