---
layout: post
title:  "Daftar Formula Regex untuk Spreadsheets"
---

# Daftar Formula Regex untuk Spreadsheets
**Formula Regex untuk memisahkan domain dengan Slug URL**
```
=REGEXEXTRACT(A2, "^(https?://[^/]+)")
```
**Formula Regex untuk Mendeteksi Wildcard Subdomain ww38, ww16, ww23**
```
```
=REGEXMATCH(A237, "\.(w\d+)\.|(ww\d+)\.")
```


