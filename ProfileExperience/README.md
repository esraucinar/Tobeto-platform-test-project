[profil deneyimler.docx](https://github.com/esraucinar/Tobeto-platform-test-project/files/14296346/profil.deneyimler.docx)
TEST SENARYOSUNUN ADI: TOBETO KULLANICI PROFİL/DENEYİMLERİM BÖLÜMÜ

AÇIKLAMA: Bu senaryo, kullanıcının Tobeto platformuna başarılı bir şekilde giriş yaptıktan sonra, kullanıcının profil bilgilerindeki deneyimlerim bölümünün işlevlerini test etmeyi amaçlamaktadır. 

ÖN KOŞULLAR: 
•	Test ortamı çalışır ve hazır durumda olmalıdır.
•	https://tobeto.com/ sayfasına giriş yapılmalıdır.
•	Kullanıcının login olabileceği bir test hesabı bulunmalıdır.

TEST CASE 1: “Deneyimlerim” Bölümündeki Alanların Listelenmesi
Açıklama: Bu case, kullanıcının profil bilgilerindeki deneyimlerim bölümüne tıkladığında https://tobeto.com/profilim/profilimi-duzenle/deneyimlerim URL’ine ulaşmasını ve bu bölümdeki alanların listelenmesi test etmeyi amaçlamaktadır.

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
       6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerim URL’deki “Deneyimlerim” alanına tıklayın.

Beklenen Sonuç: Kullanıcının deneyimlerini girebileceği bir alan olmalıdır. Bu alan “Kurum Adı”, “Pozisyon”, “Sektör”, “İş başlangıcı” ve “İş Bitiş” alanları yer almalıdır.

 


TEST CASE 2: “Doldurulması Zorunlu Alan” Uyarısı
Açıklama: Kullanıcı, “Kurum Adı”, “Pozisyon”, “Sektör”, “İş başlangıcı” ve “İş Bitiş” alanlarından birini eksik girdiğinde “Doldurulması Zorunlu Alan” uyarı mesajını alması test edilecektir. 

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
6.	https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.
7.	“Kaydet” butonuna tıklayın.

Beklenen Sonuç: “Kurum Adı”, “Pozisyon”, “Sektör”, “İş başlangıcı” ve “İş Bitiş” alanlarından birini eksik girdiğinde “Doldurulması Zorunlu Alan” uyarı mesajı görülmelidir.






 



TEST CASE 3: Kurum Adı Başlığındaki Görünüm ve Uyarılar
Açıklama: Kurum Adı başlığının altındaki doldurulabilir kutuda default olarak “Kampüs 365” yazısının görünürlüğü; “En az 5 karakter girmelisiniz” ve “En fazla 50 karakter girebilirsiniz” uyarı mesajlarının alınması test edilecektir.

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
6.	https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.
Beklenen Sonuç: Kurum Adı başlığı altındaki doldurulabilir kutuda “Kampüs 365” yazısı default olarak tanımlanmalıdır.

 
7.	Doldurulabilir kutuya 5 karakterden az olacak şekilde karakter girin.
İnput: e(boşluk)s
8.	“Kaydet” butonuna tıklayın.
Beklenen Sonuç:  “En az 5 karakter girmelisiniz” uyarısı görülmelidir.  
9.	  Doldurulabilir kutuya 50 karakterden fazla olacak şekilde karakter girin.
İnput: esraesraesraesraesraesraesraesraesraesraesraesraesraesra
10.	   “Kaydet” butonuna tıklayın.

Beklenen Sonuç: “En fazla 50 karakter girebilirsiniz” uyarısı görülmelidir.

 

Not: Kaydet butonuna bir kere tıkladıktan sonra, bu alandaki uyarıyı alabilmek için silmek yeterli.

TEST CASE 4: Pozisyon Başlığındaki Görünüm ve Uyarılar
Açıklama: Pozisyon başlığının altındaki doldurulabilir kutuda default olarak “Front-End Developer” yazısının görünürlüğü; “En az 5 karakter girmelisiniz” ve “En fazla 50 karakter girebilirsiniz” uyarı mesajlarının alınması test edilecektir.

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
6.	https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.
Beklenen Sonuç: Pozisyon başlığı altındaki doldurulabilir kutuda “Front-End Developer” yazısı default olarak tanımlanmalıdır.
7.	Doldurulabilir kutuya 5 karakterden az olacak şekilde karakter girin.
İnput: e;a
8.	“Kaydet” butonuna tıklayın.
Beklenen Sonuç: “En az 5 karakter girmelisiniz” uyarısı görülmelidir.


 

9.  Doldurulabilir kutuya 50 karakterden fazla olacak şekilde karakter girin.
İnput: esraesraesraesraesraesraesraesraesraesraesraesraesraesra
10. “Kaydet” butonuna tıklayın.

Beklenen Sonuç: “En fazla 50 karakter girebilirsiniz” uyarısı görülmelidir.


 
TEST CASE 5: Sektör Başlığındaki Görünüm ve Uyarılar
Açıklama: Sektör başlığının altındaki doldurulabilir kutuda default olarak “Yazılım” yazısının görünürlüğü; “En az 5 karakter girmelisiniz” ve “En fazla 50 karakter girebilirsiniz” uyarı mesajlarının alınması test edilecektir.

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
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.

Beklenen Sonuç: Sektör başlığı altındaki doldurulabilir kutuda “Yazılım” yazısı default olarak tanımlanmalıdır.
7. Doldurulabilir kutuya 5 karakterden az olacak şekilde karakter girin.
İnput: e;a
8. “Kaydet” butonuna tıklayın.
Beklenen Sonuç: “En az 5 karakter girmelisiniz” uyarısı görülmelidir.


 

9. Doldurulabilir kutuya 50 karakterden fazla olacak şekilde karakter girin.
İnput: esraesraesraesraesraesraesraesraesraesraesraesraesraesra

10. “Kaydet” butonuna tıklayın.

Beklenen Sonuç: “En fazla 50 karakter girebilirsiniz” uyarısı görülmelidir.


 

TEST CASE 6: Şehir Seçiniz Başlığındaki Görünüm ve Uyarılar
Açıklama: Şehir Seçiniz başlığının altındaki doldurulabilir kutuda default olarak “İl seçiniz” yazısının görünürlüğü; seçim yapılması zorunlu alan, durumu test edilecektir.

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
5.  https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.

Beklenen Sonuç: Şehir Seçiniz başlığı altındaki doldurulabilir kutuda “İl Seçiniz” yazısı default olarak tanımlanmalıdır.
       7.  Seçim yapmadan “kaydet” butonuna tıklayın.
Beklenen Sonuç: Kaydetme işlemi gerçekleşmemelidir. İl Seçimi zorunlu olmalıdır. “Doldurulması zorunlu alandır” uyarısı vermelidir.

BUG: “Doldurulması zorunlu alandır.” Uyarısı gösterilmiyor.


TEST CASE 7: İş Başlangıcı 
Açıklama: İş Başlangıcı başlığının altındaki seçilebilir kutuda default olarak “gg.aa.yyyy” yazısının görünürlüğü ve işlevi test edilecektir. 

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
5.  https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.

Beklenen Sonuç: İş Başlangıcı başlığı altındaki seçilebilir kutuda “gg.aa.yyyy” yazısı default olarak tanımlanmalıdır.

 
        7. Doldurulabilir alana tıklayın.
  Beklenen Sonuç: Takvim açılmalıdır. 


 
      8.  Takvimden seçim yapın.
İnput: 10.01.2024
Beklenen Sonuç: Kullanıcı takvimden seçim yapabilmelidir.


 


TEST CASE 8: İş Bitiş 
Açıklama: İş Bitiş başlığının altındaki seçilebilir kutuda default olarak “gg.aa.yyyy” yazısının görünürlüğü ve işlevi test edilecektir. 

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
5.  https://tobeto.com/platform açılan URL’deki kullanıcı adının ve soyadının yazdığı butona tıklayıp, “Profil Bilgileri” kısmını seçin.
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.

Beklenen Sonuç: İş Bitiş başlığı altındaki seçilebilir kutuda “gg.aa.yyyy” yazısı default olarak tanımlanmalıdır.
 
      7. İş Başlangıcı alanını doldurun.
      İnput: 10.01.1976
     8.  İş Bitiş başlığı altındaki seçilebilir alana tıklayın.
Beklenen Sonuç: Takvim açılmalıdır.
 
    9. Takvimden seçim yapın.
    İnput: 10.01.1992
Beklenen Sonuç: Kullanıcı takvimden seçim yapabilmelidir.

 
BUG: Gereksinimde iş bitiş seçim yılları sadece 2023-2024 olmalıdır, yazıyor. İş başlangıç tarihine göre iş bitiş tarihleri de değişmektedir. Buna göre 1974-2024 yılları arasını kapsıyor. 

    10.  “Çalışmaya devam ediyorum” butonuna tıklayın.
Beklenen Sonuç: Kullanıcı İş Bitiş alanında seçim yapamamalıdır.

TEST CASE 9: İş Açıklaması 
Açıklama: İş Açıklaması başlığı altındaki bölüm için “En fazla 300 karakter girebilirsiniz.” Uyarı mesajı test edilecektir. 

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
6.https://tobeto.com/profilim/profilimi-duzenle/kisisel-bilgilerimURL’deki “Deneyimlerim” alanına tıklayın.
7. İş Açıklaması bölümüne 300 karakterden fazla olacak şekilde karakter girin.
İnput: basjbdjabdjsajdbsjdbajsbsdjsabjdbsajdbsjadbjsabdjsabdjsbjdbsjdbsjabdjbdjbsjdbjsdbsjbdbjs
jsbjdbsjd;!31ı3u12y826476743289NK"*0*DASĞXSA*D0S*D0*S0D*S0D*S0D*S*********************************************************************************************************************************************************************,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,    
8. “Kaydet” butonuna tıklayın.
Beklenen Sonuç: “En fazla 300 karakter girebilirsiniz.” Uyarı mesajı görülecektir.


 

![image](https://github.com/esraucinar/Tobeto-platform-test-project/assets/148894125/e20fa430-b225-4c55-a22b-fbf31d26fe7d)
