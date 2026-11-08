# kod_-asistanim
Proje Yazarı: MYT
# Projenin Adı: Kod-Asistan v0.1
##  Projenin  Amacı:  Kullanıcılara  günlük  işlerinde  (hesaplama,  selamlama  vb.)  yardımcı olacak bir dijital asistan tasarlamak
##  Projenin  Hedefleri:  Akıllı baraj otomasyonunda su seviyesi saatlik sensörlerle izlenmektedir. Su seviyesi 50 metreyi aşmadığı sürece kapaklar kapalı tutularak saat sayacı artırılır. Eşik aşıldığında ise döngü kırılarak tahliye saati ve kritik su seviyesi ekrana yazdırılmalıdır. v1.0 Akıllı Menü, v2.0 Veri Saklama
KRİTİK  EŞİK  sözde  kod  mantığını
1.	başla
2.	saat=0 
3.	ekrana kapaklar kapalı yaz
4.	saat=saat+1
5.	su_seviyesi değerini sensörden oku 
6.	Eğer su_seviyesi <= 50 ise 3.adıma git
7.	değilse ekrana “kapaklar açıldı”, saat ve su_seviyesini yazdır
8.	bitir
![Şema Açıklaması](isim.jpg)
