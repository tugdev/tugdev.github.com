---
layout: post
title: 	W�NDOWS G�T KULLAN�M�
---

1)- <a href="http://git-scm.com/downloads" > http://git-scm.com/downloads </a>   adresinde windows se� kurulumu yap.<br>
2)- Ba�lat men�s�nden <code> Git Bash </code> a� komutlar�n� burda yazacaks�n.<br>
3)- <code> ssh </code> olu�turmay� unutma. git bash kabuguna <code> ssh-keygen </code> yaz ve ki�isel klas�r�m�z�n(benim i�in tugdev) i�inde <code>.ssh </code> klas�r�n�n alt�nda <code> id_rsa.pub </code> dosyas�n�n i�eri�ini github'da <code> SSH Keys </code> e yap��t�r.<br>
4)- kim oldu�unu github'a tan�tman laz�m.Bunun i�in;
  - git config --global user.email "mailadresi@example.com"
  - git config --global user.name "kullan�c� ad�"
	
- git komutlar�ndan baz�lar� (depoya herhangi dosya g�nderimi i�in)
  - git add *
  - git commit -a -m "a��klama"
  - git push origin master
- depo klonlama i�lemi yap�l�rken
  - git clone "SSH clone URL 'sini yap��t�r"
<br>
<br> 