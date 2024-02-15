[eğitim hayatım.docx](https://github.com/esraucinar/Tobeto-platform-test-project/files/14296362/egitim.hayatim.docx)
TEST SENARYOSUNUN ADI: TOBETO KULLANICI PROFİL/EĞİTİM HAYATIM BÖLÜMÜ

AÇIKLAMA: Bu senaryo, kullanıcının Tobeto platformuna başarılı bir şekilde giriş yaptıktan sonra, kullanıcının profil bilgilerindeki Eğitim Hayatım bölümünün işlevlerini test etmeyi amaçlamaktadır. 

ÖN KOŞULLAR: 
•	Test ortamı çalışır ve hazır durumda olmalıdır.
•	https://tobeto.com/ sayfasına giriş yapılmalıdır.
•	Kullanıcının login olabileceği bir test hesabı bulunmalıdır.

TEST CASE 1: “Eğitim Hayatım” Bölümündeki Alanların Listelenmesi
Açıklama: Bu case, kullanıcının profil bilgilerindeki Eğitim Hayatım bölümüne tıkladığında https://tobeto.com/profilim/profilimi-duzenle/egitim-hayatim URL’ine ulaşmasını ve bu bölümdeki alanların listelenmesi test etmeyi amaçlamaktadır.

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
5.  https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
       6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerim URL’deki “Eğitim Hayatım” alanına tıklayın.

Beklenen Sonuç: Kullanıcının eğitim bilgilerini girebileceği bir alan olmalıdır. Bu alan “Eğitim Durumu”, “Üniversite”, “Sektör”, “Bölüm”, “Başlangıç Yılı”, “Mezuniyet Yılı” alanları yer almalıdır.
NOT: SEKTÖR BAŞLIĞI LİSTELENMİYOR.

TEST CASE 2: “Doldurulması Zorunlu Alan” Uyarısı
Açıklama: Kullanıcı, “Eğitim Durumu”, “Üniversite”, “Sektör”, “Bölüm”, “Başlangıç Yılı”, “Mezuniyet Yılı” alanlarından birini eksik girdiğinde “Doldurulması Zorunlu Alan” uyarı mesajını alması test edilecektir. 

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
5.	https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.	https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
7.	“Kaydet” butonuna tıklayın.

Beklenen Sonuç: “Eğitim Durumu”, “Üniversite”, “Sektör”, “Bölüm”, “Başlangıç Yılı”, “Mezuniyet Yılı” alanlarından birini eksik girdiğinde “Doldurulması Zorunlu Alan” uyarı mesajı görülmelidir.



 

BUG: Sektör başlığı listelenmediği için bu başlık altında “doldurulması zorunlu alan”uyarsı gösterilemiyor. 

TEST CASE 3: Üniversite Başlığındaki Görünüm ve Uyarılar
Açıklama: Üniversite başlığının altındaki doldurulabilir kutuda default olarak “Kampüs 365” yazısının görünürlüğü; “En az 2 karakter girmelisiniz” ve “En fazla 50 karakter girebilirsiniz” uyarı mesajlarının alınması test edilecektir.

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
5.	https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.	https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
Beklenen Sonuç: Üniversite başlığı altındaki doldurulabilir kutuda “Kampüs 365” yazısı default olarak tanımlanmalıdır.
 

7.	Doldurulabilir kutuya 2 karakterden az olacak şekilde karakter girin.
İnput: ;

 
8.	“Kaydet” butonuna tıklayın.
Beklenen Sonuç:  “En az 2 karakter girmelisiniz” uyarısı görülmelidir. 

9.	  Doldurulabilir kutuya 50 karakterden fazla olacak şekilde karakter girin.
İnput: esraesraesraesraesraesraesraesraesraesraesraesraesraesra
10.	   “Kaydet” butonuna tıklayın.

 

Beklenen Sonuç: “En fazla 50 karakter girebilirsiniz” uyarısı görülmelidir.



TEST CASE 4: Bölüm Başlığındaki Görünüm ve Uyarılar
Açıklama: Bölüm başlığının altındaki doldurulabilir kutuda default olarak “Yazılım” yazısının görünürlüğü; “En az 2 karakter girmelisiniz” ve “En fazla 50 karakter girebilirsiniz” uyarı mesajlarının alınması test edilecektir.

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
5. https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6. https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
Beklenen Sonuç: Bölüm başlığı altındaki doldurulabilir kutuda “Yazılım” yazısı default olarak tanımlanmalıdır.

7. Doldurulabilir kutuya 2 karakterden az olacak şekilde karakter girin.
İnput: ;

8. “Kaydet” butonuna tıklayın.

 
Beklenen Sonuç:  “En az 2 karakter girmelisiniz” uyarısı görülmelidir. 

9.   Doldurulabilir kutuya 50 karakterden fazla olacak şekilde karakter girin.
İnput: esraesraesraesraesraesraesraesraesraesraesraesraesraesra

10.	   “Kaydet” butonuna tıklayın.

 


Beklenen Sonuç: “En fazla 50 karakter girebilirsiniz” uyarısı görülmelidir.


TEST CASE 5: Başlangıç Yılı Başlığındaki Görünüm ve Uyarılar
Açıklama: Başlangıç Yılı  başlığının altındaki doldurulabilir kutuda default olarak “Başlangıç yılınızı seçiniz” yazısının görünürlüğünü ve kullanıcının tarih seçebilmesi test edilecektir.

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
5. https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
Beklenen Sonuç: Başlangıç Yılı başlığı altındaki doldurulabilir kutuda “Başlangıç Yılınızı Seçiniz” yazısı default olarak tanımlanmalıdır.
 

	7. “Başlangıç Yılı” alanına tıkla ve tarih seç.
	İnput: 2025

Beklenen Sonuç: Kullanıcı, eğitime başladığı tarihi seçebilmelidir.

TEST CASE 6: Mezuniyet Yılı Başlığındaki Görünüm ve Uyarılar
Açıklama: Mezuniyet Yılı başlığının altındaki doldurulabilir kutuda default olarak “Mezuniyet Yılınızı Seçiniz” yazısının görünürlüğü, mezuniyet yılının doldurulabilmesi için önce başlangıç yılı bölümünün seçilebilmesi gerekliliği, kullanıcının bu alana tıkladığında mezuniyet tarihini seçebileceği ve Mezuniyet Yılı alanının altında “Devam Ediyorum” yazısını içeren bir onay kutusu işaretlendiğinde “Mezuniyet Yılı” alanı tıklanamaz duruma gelmesi  test edilecektir. 

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
5. https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
Beklenen Sonuç: Mezuniyet Yılı başlığı altındaki doldurulabilir kutuda “Mezuniyet Yılınızı Seçiniz” yazısı default olarak tanımlanmalıdır.

 
	7. Mezuniyet yılı alanına tıklayın.
Beklenen Sonuç: Kullanıcı, başlangıç yılını seçmeden, bu alanı dolduramamalıdır.

	8. Başlangıç Yılı alanından bir tarih seçiniz.
	İnput: 2025
Beklenen Sonuç: Kullanıcı, eğitim başlangıç yılını seçebilmelidir. 
	9. Mezuniyet Yılı alanından bir tarih seçiniz.
	İnput: 2074
Beklenen Sonuç: Kullanıcı, mezuniyet yılını seçebilmelidir.
 
	10. “Devam ediyorum” kutucuğunu işaretleyiniz.
Beklenen Sonuç: Kullanıcı, mezuniyet yılını seçememelidir. 



TEST CASE 7: “Eğitim Bilgisi Eklendi” uyarısı 
Açıklama: Kullanıcının eğitim bilgilerini girebileceği  “Eğitim Durumu”, “Üniversite”, “Bölüm”, “Başlangıç Yılı”, “Mezuniyet Yılı” alanlarını istenildiği şekliyle doldurup, kaydet butonuna bastığında “eğitim bilgisi eklendi” uyarısı alması test edilecektir. 

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
      5. https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
      6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
      7. “Eğitim Durumu” alanını seçin.
	İnput: Yüksek Lisans
      8. “Üniversite” alanını seçin.
	İnput: Marmara Üniversitesi
     9. “Bölüm” alanını seçin.
	İnput: Felsefe ve Din Bilimleri
    10. “Başlangıç Yılı” alanını seçin.
	İnput: 2015
    11. “Mezuniyet Yılı” alanını seçin.
	İnput: 2019
    12. “Kaydet” butonuna tıklayın.

Beklenen Sonuç: “Eğitim bilgisi eklendi” mesajı görülmelidir.
 





TEST CASE 8: “Seçilen Eğitimi Silmek İstediğinize Emin misiniz? Bu İşlem Geri Alınamaz” uyarısı ve Eğitim Bilgisini Silebilme İşlemi
Açıklama: Kullanıcı,  başarılı bir şekilde eklenmiş eğitimi silmek istediğinde, “Seçilen Eğitimi Silmek İstediğinize Emin misiniz? Bu İşlem Geri Alınamaz ” uyarısını alması ve eklenen eğitim bilgisini silebilme işlemi test edilecektir. 

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
      5. https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
      6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Eğitim Hayatım” alanına tıklayın.
      7. “Eğitim Durumu” alanını seçin.
	İnput: Yüksek Lisans
      8. “Üniversite” alanını seçin.
	İnput: Marmara Üniversitesi
     9. “Bölüm” alanını seçin.
	İnput: Felsefe ve Din Bilimleri
    10. “Başlangıç Yılı” alanını seçin.
	İnput: 2015
    11. “Mezuniyet Yılı” alanını seçin.
	İnput: 2019
    12. “Kaydet” butonuna tıklayın.
    13. Başarılı bir şekilde eklenen eğitim bilgilerinin yanında yer alan çöp kutusu işaretine tıklayın. 
 
Beklenen Sonuç: “Seçilen Eğitimi Silmek İstediğinize Emin misiniz? Bu işlem geri alınamaz ” uyarı mesajı alınmalıdır. 
    14. “Evet” butonuna tıklayın.
Beklenen Sonuç: “Eğitim Kaldırıldı” mesajı alınmalıdır.

 



![image](https://github.com/esraucinar/Tobeto-platform-test-project/assets/148894125/e505237c-d5c8-4959-9a3c-c0476eb2d023)

