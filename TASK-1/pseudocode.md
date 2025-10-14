BAŞLA

OKU kart  
OKU PIN  

DÖNGÜ (deneme sayısı < 3 VE PIN yanlış)  
 YAZ "PIN yanlış, tekrar deneyin"  
 OKU PIN  
 deneme sayısını 1 artır  

EĞER (PIN hala yanlış)  
 YAZ "Kart bloke edildi"  
 BİTİR  

OKU bakiye  
OKU çekilmek istenen tutar  

EĞER (tutar > bakiye)  
 YAZ "Yetersiz bakiye"  
 BİTİR  

EĞER (tutar % 20 ≠ 0)  
 YAZ "Tutar 20 TL'nin katı olmalı"  
 BİTİR  

EĞER (tutar > günlük limit)  
 YAZ "Günlük limit aşıldı"  
 BİTİR  

YAZ "Para veriliyor"  
YAZ "Fiş çıkarılıyor"  

OKU "Başka işlem yapmak ister misiniz?" (EVET/HAYIR)  

DÖNGÜ (cevap = EVET)  
 BAŞA dön  

BİTİR
