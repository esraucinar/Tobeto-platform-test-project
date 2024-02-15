TEST SENARYOSUNUN ADI: SENKRON EĞİTİM İÇERİKLERİ BÖLÜMÜ

AÇIKLAMA: Bu senaryo, kullanıcının Tobeto platformuna başarılı bir şekilde giriş yaptıktan sonra, eğitimlerim bölümündeki senkron eğitimlerin işlevlerini test etmeyi amaçlamaktadır. 

ÖN KOŞULLAR: 
•	Test ortamı çalışır ve hazır durumda olmalıdır.
•	https://tobeto.com/ sayfasına giriş yapılmalıdır.
•	Kullanıcının login olabileceği bir test hesabı bulunmalıdır.
•	
TEST CASE 1: “Eğitimi nasıl tamamlayabilirim?” ve “Eğitimi nasıl başarabilirim?” Ek Bilgilendirilmeleri
Açıklama: Bu case, senkron eğitimlerin süresini gösteren bildirinin yanında yer alan soru işareti kısmına gelindiğinde açılan ek bilgilendirmelerin, kullanıcının videoları bitirmesine göre güncellenmesini test etmeyi amaçlamaktadır.

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.
•	Kullanıcının login olabileceği bir test hesabı olmalıdır.

Adımlar:

1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş Yap” butonuna tıklayın.
4.	Kullanıcı e-posta adresini ve şifreyi girin.
İnput: E-Posta: 96wyssplag@rfcdrive.com
İnput: Şifre: 123456
5.   “Eğitimlerim” bölümüne tıklayın.
6.	“Daha Fazla Göster” seçeneğine tıklayın.
7. 	Açılan https://tobeto.com/egitimlerim sayfasında, Yazılım Kalite ve Test Uzmanı 1A senkron dersini seçiniz.
8. 	“29 Şubat 2024 tarihine kadar bitirebilirsin?” bildiriminin yanındaki soru işaretine tıklayın.
Beklenen Sonuç: “Eğitimi nasıl tamamlayabilirim?” ve “Eğitimi nasıl başarabilirim?” Ek bilgilendirilmeleriyle birlikte sayfadaki video sayısı ve kullanıcının izleme oranı “Eğitimde yer alan tüm içerikler tamamlandığında(0/1)” bilgisi ile birlikte görülmelidir. 

 

BUG: Video sayısı görünmüyor, kullanıcı 15 videonun hepsine katılmış bu oran da görünmüyor.

TEST CASE 2: Kullanıcının Canlı Oturumlara Göre Aldığı Puanlama Sistemi ve  Beğeni- Favori İkonu İşlevleri
Açıklama: Bu case, kullanıcının senkron eğitimlere katılımına göre hesaplanması planlanan puanlama sistemini test etmeyi amaçlamakla birlikte, beğeni ve favori ikonunun işlevlerini de kontrol edecektir.  

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.
•	Kullanıcının login olabileceği bir test hesabı olmalıdır.

Adımlar:

1. Tarayıcıyı açın.
2. https://tobeto.com/ URL’ine gidin.
3. “Giriş Yap” butonuna tıklayın.
4. Kullanıcı e-posta adresini ve şifreyi girin.
İnput: E-Posta: 96wyssplag@rfcdrive.com
İnput: Şifre: 123456
5.   “Eğitimlerim” bölümüne tıklayın.
6.	“Daha Fazla Göster” seçeneğine tıklayın.
7. 	Açılan https://tobeto.com/egitimlerim sayfasında, Yazılım Kalite ve Test Uzmanı 1A senkron dersini seçiniz.
Beklenen Sonuç: Kalp ve favori ikonunun yanında, izlenen canlı derslerin oranını gösteren bir puanlama sistemi olmalıdır. 

BUG: Böyle bir puanlama görünmemektedir.
       8. Beğeni ikonunu tıkla.
Beklenen Sonuç: Beğeni ikonundaki sayı güncellenmelidir.


  
       9. Beğeni ikonunun yanındaki sayıya tıklayın.
Beklenen Sonuç: Beğenen sayısı ile birlikte beğenenlerin isim soy isimlerini gösteren,  10’arlı listelenmiş pop-up ekranı açılmalı ve çarpı ekranı ile kapanmalıdır.  

	10. Açılan Pop-up ekranındaki bir kullanıcıya tıklayın.
İnput: Zehra Temizel
	11. Açılan profildeki “takip et” butonuna tıklayın.
Beklenen Sonuç: “Zehra Temizel isimli kullanıcıyı başarıyla takip ettin.” Mesajı görülmelidir.
 
	12. Takip edilen kullanıcıya tekrar tıklayıp, ”takip ediliyor” yazısına tıklayın. 
Beklenen Sonuç: “Zehra Temizel isimli kullanıcıyı başarıyla takipten çıktın.” mesajı görülmelidir.
 
	 13. Favori ikonuna tıklayın.
Beklenen Sonuç: “Favorilere ekleme işlemin başarıyla gerçekleşti.” mesajı görülmelidir. 
	
 
14. Favori ikonuna tekrar tıklayın.
Beklenen Sonuç: “Favorilerden çıkarma işlemin başarıyla gerçekleşti.” mesajı görülmelidir.
	
 

TEST CASE 3: İlerleme Çubuğunun İşlevi

Açıklama: Bu case, kullanıcının eğitim içeriğini tamamlama durumunu gösteren, ilerleme çubuğunun ilerleme oranı ile eş zamanlı güncellenmesini test edecektir.

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.
•	Kullanıcının login olabileceği bir test hesabı olmalıdır.

Adımlar:

1. Tarayıcıyı açın.
2. https://tobeto.com/ URL’ine gidin.
3. “Giriş Yap” butonuna tıklayın.
4. Kullanıcı e-posta adresini ve şifreyi girin.
İnput: E-Posta: 96wyssplag@rfcdrive.com
İnput: Şifre: 123456
5.   “Eğitimlerim” bölümüne tıklayın.
6.	“Daha Fazla Göster” seçeneğine tıklayın.
7. 	Açılan https://tobeto.com/egitimlerim sayfasında, Yazılım Kalite ve Test Uzmanı 1A senkron dersini seçiniz.
8. İlerleme Çubuğunun üstüne tıklayın. 
Beklenen Sonuç: “Eğitim Tamamlama Oranı” yazısı görülmelidir. Bu mesajla birlikte, kullanıcının tamamlama oranına göre, ilerleme çubuğunda renk değişimi ve oran gösterilmelidir.

 

BUG: Kullanıcı videoları izlediği halde, böyle bir durum söz konusu değildir.



![image](https://github.com/esraucinar/Tobeto-platform-test-project/assets/148894125/ee1a0180-d7f9-4f50-b37e-1a07a91696b3)
