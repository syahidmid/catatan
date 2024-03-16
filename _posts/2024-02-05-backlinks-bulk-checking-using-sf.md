---
layout: post
title:  "Welcome to Jekyll!"
---

# How to Backlink Checking in Bulk Using Screaming Forg

Goals: 

- Cari internal link /asuransi-mobil/ yang ada di Content Area 

Problem: 

Mengapa Internal link /asuransi-mobil/ yang ada di content area, tapi ada Summary Box tidak terdeteksi di Screaming Forg. Sebaga informasi, berikut code di dalam summary box.  

Regex: 
https:\/\/lifepal\.co\.id\/asuransi\/mobil\/(\?.*)?...

Content Area: 
//*[@id="__next"]/div/div[1]/div[1]/div/div[1]/div[1]/div

Summary Box: 

div id=\"shortcode-summary\" class=\"shortcode-summary blue\" data-json=\"{\u0026quot;variant\u0026quot;:\u0026quot;blue\u0026quot;}\"\u003eJangan sampai biaya perbaikan mobil kesayanganmu justru membebani pengeluaran. Manfaatkan \u003ca class=\"gtm_redirectionclick_inarticlelink gtm_el__perbaikan-kendaraan\" href=\"https://lifepal.co.id/asuransi/all-risk/?utm_campaign=MEDIA_perbaikan-kendaraan_ketok-magic\u0026amp;utm_source=media\u0026amp;utm_medium=inarticle_text\u0026amp;utm_content=ketok-magic\" target=\"_blank\" rel=\"noopener\"\u003e\u003cspan style=\"font-weight: 400\"\u003easuransi mobil all risk\u003c/span\u003e\u003c/a\u003e\u003cspan style=\"font-weight: 400\"\u003e untuk mendapatkan jaminan ganti rugi atas biaya perbaikan mobil secara menyeluruh di bengkel terbaik.\u003c/div
