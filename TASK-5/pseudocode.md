BAŞLA

OKU kullanıcı adı ve şifre  
EĞER (giriş başarısız)  
 YAZ "Giriş başarısız"  
 BİTİR  

DÖNGÜ (işlem seçilene kadar)  
 YAZ "1-Bakiye Görüntüle, 2-Para Yatır, 3-Para Çek, 4-Çıkış"  
 OKU seçim  

 EĞER (seçim = 1)  
  YAZ "Bakiye: ..."  

 EĞER (seçim = 2)  
  OKU yatırılacak miktar  
  BAKİYE = BAKİYE + miktar  
  YAZ "Yeni bakiye: ..."  

 EĞER (seçim = 3)  
  OKU çekilecek miktar  
  EĞER (miktar > BAKİYE)  
   YAZ "Yetersiz bakiye"  
  DEĞİLSE  
   BAKİYE = BAKİYE - miktar  
   YAZ "Yeni bakiye: ..."  

 EĞER (seçim = 4)  
  YAZ "Çıkış yapıldı"  
  BİTİR  

SON DÖNGÜ

BİTİR
