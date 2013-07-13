---
layout: post
title: 	WÝNDOWS GÝT KULLANÝMÝ
---

1)- <a href="http://git-scm.com/downloads" > http://git-scm.com/downloads </a>   adresinde windows seç kurulumu yap.<br>
2)- Baþlat menüsünden <code> Git Bash </code> aç komutlarýný burda yazacaksýn.<br>
3)- <code> ssh </code> oluþturmayý unutma. git bash kabuguna <code> ssh-keygen </code> yaz ve kiþisel klasörümüzün(benim için tugdev) içinde <code>.ssh </code> klasörünün altýnda <code> id_rsa.pub </code> dosyasýnýn içeriðini github'da <code> SSH Keys </code> e yapýþtýr.<br>
4)- kim olduðunu github'a tanýtman lazým.Bunun için;
  - git config --global user.email "mailadresi@example.com"
  - git config --global user.name "kullanýcý adý"
	
- git komutlarýndan bazýlarý (depoya herhangi dosya gönderimi için)
  - git add *
  - git commit -a -m "açýklama"
  - git push origin master
- depo klonlama iþlemi yapýlýrken
  - git clone "SSH clone URL 'sini yapýþtýr"
<br>
<br> 