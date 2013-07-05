---
layout: post
title: NOTLAR
---

<li><a href="#gizli">UBUNTU GİZLİ DOSYALAR</a></li><br>
<li><a href="#git"> WİNDOWS GİT KULLANIMI</a></li><br>
<br>

###<a id="gizli"> 1- UBUNTU GİZLİ DOSYALAR </a>

Bulunduğun dizinde CTRL+H yaparsan gizli dosyaları görebilirsin.

<br>
<br>

###<a id="git"> 1- WİNDOWS GİT KULLANIMI </a>

1)- <a href="http://git-scm.com/downloads" > http://git-scm.com/downloads </a>   adresinde windows seç kurulumu yap.<br>
2)- Başlat menüsünden <code> Git Bash </code> aç komutlarını burda yazacaksın.<br>
3)- <code> ssh </code> oluşturmayı unutma. git bash kabuguna <code> ssh-keygen </code> yaz ve kişisel klasörümüzün(benim için tugdev) içinde <code>.ssh </code> klasörünün altında <code> id_rsa.pub </code> dosyasının içeriğini github'da <code> SSH Keys </code> e yapıştır.<br>
4)- kim olduğunu github'a tanıtman lazım.Bunun için;
  - git config --global user.email "mailadresi@example.com"
  - git config --global user.name "kullanıcı adı"
	
- git komutlarından bazıları (depoya herhangi dosya gönderimi için)
  - git add *
  - git commit -a -m "açıklama"
  - git push origin master
- depo klonlama işlemi yapılırken
  - git clone SSH clone URL 'sini yapıştır
<br>
<br> 



