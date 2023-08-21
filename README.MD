<!--! mkdir--->

klasor olusturma --->mkdir app -->

<!--! touch--->

dosya olusrurma --->touch index.html -->

<!--! ls--->

icinde bulundugu dizindeki dosyalari klasorleri listleme --->ls -->

<!--! ls -a--->

icinde bulundugu dizindeki gizli dosyalar dahil herseyi gosterir --->ls -a -->

<!--! cd dosya--->

dosyalar arasinda gezinme, dosya klasorune girer --->cd dosya -->

<!--! cd ..--->

bulundugu klasorden bir ust klasore cikar --->cd .. -->

<!--! clear--->

terminal ekranini temizler -->

<!--! git init--->

bos bir git repository olusuturur --->git init -->

<!--! git status--->

değişikliklerin izlenmemiş, değiştirilmiş veya aşamalı olarak durumunu gösterir.--->git status -->

<!--! git add -->

This command updates the index using the current content found in the working tree, to prepare
the content staged for the next commit
Bu komut, bir sonraki commit için hazırlanan içeriği hazırlamak için çalışan ağaçta bulunan
mevcut içeriği kullanarak dizini günceller.
git add index.html--->sadece index.html dosyasini staging area atar
git add .--->uzerinde degisiklik yapilan herseyi staing areaya atar

<!--! git commit -m 'commit mesaji' -->

Create a new commit containing the current contents of the index and the given log message
describing the changes.
Dizinin mevcut içeriğini ve değişiklikleri açıklayan verilen günlük mesajını içeren yeni
bir commit oluşturun.

<!--! git log -->

Git log yapilmis olan commitlerin bir listesini gosteriyor. Loglarda kimin tarafindan hangi branch a
hangi tarihte yapildigi commit mesaji ile ilgili loglari iceriyor

<!--! git log --oneline -->

Yapilmis commitleri tek satir seklinde gosteriyor
