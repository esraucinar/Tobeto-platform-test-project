[katalog senaryo.docx](https://github.com/esraucinar/Tobeto-platform-test-project/files/14296379/katalog.senaryo.docx)
TEST SENARYOSUNUN ADI: TOBETO KATALOG BÖLÜMÜ FİLTRELEME VE ARAMA İŞLEVSELLİĞİ

AÇIKLAMA: Bu senaryo, tobeto.com’un katalog bölümündeki filtreleme ve arama işlevlerinin doğru çalışıp çalışmadığını test etmeyi amaçlamaktadır. 

ÖN KOŞULLAR: 
•	Test ortamı çalışır ve hazır durumda olmalıdır.
•	https://tobeto.com/ sayfasına giriş yapılmalıdır.
•	Kullanıcının login olabileceği bir test hesabı olmalıdır.


TEST CASE 1: Katalog Bölümü Arama Çubuğu İle Derslerin Listelenmesi

Açıklama: Bu case, kullanıcının katalog bölümüne tıklayarak "Öğrenmeye Başla" başlığı altındaki arama çubuğuna Türkçe karakterlerle giriş yaparak derslerin listelenmesini test etmeyi amaçlar.

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar:
1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş yap” butonuna tıklayın.
URL: https://tobeto.com/giris
4.   Login olabilecek test hesabını girin.
İnput: E-posta: urhan_esra@hotmail.com
İnput: Şifre: 123456
5.   Açılan sayfada “katalog” kısmına tıklayın.
URL: https://tobeto.com/platform
6. “Öğrenmeye Başla” başlığı altındaki arama çubuğuna herhangi bir Türkçe karakterle giriş yapın.
İnput: “a” 
İnput: “mm”
7.1. ENTER tuşuna basın.
7.2. Büyüteç işaretine tıklayın. 

Beklenen Sonuç: Kullanıcı istediği eğitime erişmelidir. 

 



TEST CASE 2: "Aradığınız kriterlere uygun içerik bulunamadı." Uyarısının Kontrolü
Açıklama: Bu case, kullanıcının katalog bölümüne tıklayarak "Öğrenmeye Başla" başlığı altındaki arama çubuğuna ders içeriklerinde olmayan bir harf veya harf kombinasyonuyla giriş yaparak "Aradığınız kriterlere uygun içerik bulunamadı." uyarısını test etmeyi amaçlar.

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar:
1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş yap” butonuna tıklayın.
URL: https://tobeto.com/giris
4.   Login olabilecek test hesabını girin.
İnput: E-posta: urhan_esra@hotmail.com
İnput: Şifre: 123456
5.   Açılan sayfada “katalog” kısmına tıklayın.
URL: https://tobeto.com/platform
6. “Öğrenmeye Başla” başlığı altındaki arama çubuğuna ders içeriklerinde olmayan bir harf veya harf kombinasyonuyla giriş yapın.
İnput: fr
İnput: olk
İnput: x
7.1.   ENTER tuşuna basın.
7.2.   Büyüteç işaretine tıklayın.

Beklenen Sonuç: "Aradığınız kriterlere uygun içerik bulunamadı." uyarısı görülmelidir. 
 

TEST CASE 3: Filtrele Paneli
Açıklama: Kullanıcının filtreleme yapabileceği panelin, filtrele başlığı altında “Bana özel” sabit pencere, “Kategori, Eğitimler, Seviye, Konu, Yazılım Dili, Eğitmen” gibi açılır/ kapanır pencereler halinde alt alta sıralanması test edilecektir.  

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar:
1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş yap” butonuna tıklayın.
URL: https://tobeto.com/giris
4.   Login olabilecek test hesabını girin.
İnput: E-posta: urhan_esra@hotmail.com
İnput: Şifre: 123456
5.   Açılan sayfada “katalog” kısmına tıklayın.
URL: https://tobeto.com/platform
6. 	Filtrele panelindeki kategori kısmına tıklayın.

Beklenen Sonuç: Filtrele paneli altında “Bana özel” sabit pencereyle birlikte “Kategori, Eğitimler, Seviye, Konu, Yazılım Dili, Eğitmen” gibi açılır/ kapanır pencerelerin alt alta sıralanması görülmelidir. 

 


TEST CASE 4: “Bana Özel” Penceresindeki Derslerin Listelenmesi
Açıklama: Filtrele panelindeki “Bana özel” sabit pencereye tıklandığında, kullanıcıya özel derslerin listelenmesi test edilecektir. 

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.
Adımlar:
1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş yap” butonuna tıklayın.
URL: https://tobeto.com/giris
4.	Login olabilecek test hesabını girin.
İnput: E-posta: urhan_esra@hotmail.com
İnput: Şifre: 123456
5.   Açılan sayfada “katalog” kısmına tıklayın.
URL: https://tobeto.com/platform
6.	Filtrele Panelindeki “Bana Özel” butonuna tıkla. 

Beklenen Sonuç: Filtrele panelindeki “Bana özel” sabit pencereye tıklandığında, kullanıcıya özel derslerin listelenmelidir. 

 

NOT: Tüm kullanıcılara aynı dersler listeleniyor.

TEST CASE 5: Filtrele Panelindeki Arama Kriteri
Açıklama: Kullanıcının filtreleme panelinde bulunan başlıkların altındaki arama kutusuna, başlıkların içerdiği maddelerdeki harf veya harf kombinasyonlarını girerek filtreleme yapabilmesi test edilecektir.

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar:
1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş yap” butonuna tıklayın.
URL: https://tobeto.com/giris
4.	Login olabilecek test hesabını girin.
İnput: E-posta: urhan_esra@hotmail.com
İnput: Şifre: 123456
5.	Açılan sayfada “katalog” kısmına tıklayın.
URL: https://tobeto.com/platform
6.	Filtrele panelindeki “kategori” butonuna tıklayın.
7.	Arama kutusuna “Tüm Eğitimler, Ücretli Eğitimler, Ücretsiz Eğitimler” maddelerinde geçen harf veya harf kombinasyonlarından bir veri girin. 
İnput: cret
İnput: z

Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.
  



8.	Filtrele panelindeki “Eğitimler” butonuna tıklayın.
9.	Arama kutusuna “Tüm Eğitimler, Dijital Gelişim, Profesyonel Gelişim” maddelerinde geçen harf veya harf kombinasyonlarından bir veri girin. 
İnput: iji

Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.

 
10.	Filtrele panelindeki “Seviye” butonuna tıklayın.
11.	Arama kutusuna “Tüm Seviyeler, Başlangıç, Orta, İleri” maddelerinde geçen harf veya harf kombinasyonlarından bir veri girin.
İnput: rt
Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.

 
12.	Filtrele panelindeki “Konu” butonuna tıklayın.
13.	Arama kutusuna ‘konu.madde.xlsx’ dosyasındaki maddelerde geçen harf veya harf kombinasyonlarından bir veri girin.
İnput: es

Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.

 
14.	Filtrele panelindeki “Yazılım Dili” butonuna tıklayın.
15.	Arama kutusuna ‘yazılımdili.madde.xlsx’ dosyasındaki maddelerde geçen harf veya harf kombinasyonlarından bir veri girin.
İnput: bo

Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.
 

16.	Filtrele panelindeki “Eğitmen” butonuna tıklayın.
17.	Arama kutusuna ‘eğitmen.madde.xlsx’ dosyasındaki maddelerde geçen harf veya harf kombinasyonlarından bir veri girin.
İnput: bal

Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.
 

18.	Filtrele panelindeki “Durum” butonuna tıklayın.
19.	Arama kutusuna ‘durum.madde.xlsx’ dosyasındaki maddelerde geçen harf veya harf kombinasyonlarından bir veri girin.
İnput: he

Beklenen Sonuç: Girilen verilere uygun filtreleme görülecektir.

 

  
NOT: Konu başlığına tıkladıktan sonra tüm eğitimleri seçip, bana özel başlığını tekrar seçtiğinde içerik değişiyor. Tekrar tıkladığında ise ilk seçildiği haline geliyor. Konu başlığından bir madde seçtiğinde “Bana özel” butonuna tıkladığında “aradığınız kriterlere uygun içerik bulunamadı” uyarısı veriyor. Birkaç değişiklik yapıp, tekrar konu başlığında tüm eğitimleri seçtiğinde “aradığınız kriterlere uygun içerik bulunamadı” uyarısı veriyor.


TEST CASE 6: Filtreleme Panelindeki Arama Kriteri 2
Açıklama: Filtreleme panelinde bulunan başlıklar altındaki filtreleme kriterlerinden sadece bir tanesi seçilebilmesi test edilecektir. 

Ön Koşullar: 
•	Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar: 
1.	Tarayıcıyı açın.
2.	https://tobeto.com/ URL’ine gidin.
3.	“Giriş yap” butonuna tıklayın.
URL: https://tobeto.com/giris
4.	Login olabilecek test hesabını girin.
İnput: E-posta: urhan_esra@hotmail.com
İnput: Şifre: 123456
5.	Açılan sayfada “katalog” kısmına tıklayın.
URL: https://tobeto.com/platform
6.   Filtre panelinde bulunan başlıklardan bir tanesini seçin.
7.	Seçilen başlığın altındaki içeriklerden bir tanesini seçin.
8.	Seçilen madde haricinde bir içerik daha seçmeye çalışın. ?????

Beklenen Sonuç: Kullanıcı her filtreleme başlığından sadece bir tane içerik seçebilmelidir. 




 






![image](https://github.com/esraucinar/Tobeto-platform-test-project/assets/148894125/0c3d4709-cbde-4330-8200-b02be811762f)
