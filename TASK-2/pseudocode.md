BAŞLA

OKU kullanıcı adı ve şifre  
EĞER (giriş başarılı değilse)  
 YAZ "Giriş başarısız"  
 BİTİR  

DÖNGÜ (kullanıcı ürün arıyor)  
 OKU kategori seçimi  
 OKU ürün seçimi  
 EĞER (stok yoksa)  
  YAZ "Stokta yok"  
  DEVAM ET  
 YAZ "Ürün sepete eklendi"  

DÖNGÜ (kullanıcı sepeti düzenliyor)  
 OKU sepet görüntüleme  
 OKU ürün çıkarma veya miktar değiştirme  

OKU indirim kodu  
EĞER (kod geçerli değilse)  
 YAZ "Kod geçersiz"  

OKU toplam tutar  
EĞER (toplam < 50 TL)  
 YAZ "Minimum tutar 50 TL olmalı"  
 BİTİR  

EĞER (toplam ≥ 200 TL)  
 YAZ "Kargo ücretsiz"  
DEĞİLSE  
 YAZ "Kargo ücreti eklendi"  

OKU ödeme yöntemi  
YAZ "Sipariş onaylandı"

BİTİR
