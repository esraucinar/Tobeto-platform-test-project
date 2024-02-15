[Sifre_Yenileme.docx](https://github.com/esraucinar/Tobeto-platform-test-project/files/14296366/Sifre_Yenileme.docx)
Test Senaryosu Adı: Şifre Yenileme
Açıklama: Şifresini unutan kullanıcı bu sayfayı kullanarak şifresini yenileyebilmelidir.

Ön Koşullar: 
1.Test ortamı çalışır ve hazır durumda bulunmalıdır.
2. Kayıtlı bir e-posta adresi olmalıdır. 




Case 1: Şifre Değiştirme
Açıklama: Kullanıcı şifre sıfırlama linkine erişebilmek için e-posta kısmına e-posta adresini girebilmesi kontrol edilecektir. 
Ön Koşul:
1.Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar:
1. Tarayıcıyı Açın.
2. tobeto.com/sifremi-unuttum url’sine git.
3. Şifre sıfırlama linki için geçerli bir e-posta adresi gir.
İnput: esra@hotmail.com
4. Gönder butonuna tıkla.

Beklenen Sonuç: Kullanıcı şifre sıfırlama linkine erişebilmek için e-posta kısmına e-posta adresini girebilecektir.

 





Case 2: Başarılı Link Gönderim İşlemi

Açıklama: Kullanıcı gönder tuşuna bastığında girilen e-posta adresi sistemde bulunursa pop up şeklinde açılan “Şifre sıfırlama linkini e-posta adresinize gönderdik. Lütfen gelen kutunuzu kontrol edin.”  mesajı ile  karşılaşması kontrol edilecektir. 

Ön Koşul:
1. Test ortamı çalışır ve hazır durumda bulunmalıdır.

Adımlar:
1. Tarayıcıyı Açın.
2. tobeto.com/sifremi-unuttum url’sine git.
3. Şifre sıfırlama linki için kayıtlı e-posta adresini gir.
İnput: urhan_esra@hotmail.com 
4. Gönder butonuna tıkla.
Beklenen Sonuç: Kullanıcı gönder tuşuna bastığında girilen e-posta adresi sistemde bulunursa pop up şeklinde açılan “Şifre sıfırlama linkini e-posta adresinize gönderdik. Lütfen gelen kutunuzu kontrol edin.”  mesajı görülecektir.

 


BUG: Şifre sıfırlama linkine erişebilmek için girilen mail adresinde sisteme kayıtlı olmayan mail girilmiş olsa da başarılı bir şekilde mail gönderildi pop up bildirimi geliyor.

Case 3: Başarısız Şifre Yenileme İşlemi

Açıklama: Kullanıcı gönder tuşuna bastığında girilen e-posta adresi geçersiz bir e-posta adresi ise pop- up şeklinde açılan “Girdiğiniz e-posta geçersizdir.” mesajı ile karşılaşması test edilecektir. 
Ön Koşullar:
1. Test ortamı çalışır ve hazır durumda bulunmalıdır.
2. Geçersiz bir e-posta adresi olmalıdır.

Adımlar: 
1. Tarayıcıyı Açın.
2. tobeto.com/sifremi-unuttum url’sine git.
3. Şifre sıfırlama linki için geçersiz e-posta adresini gir.
İnput: e@u
4. Gönder butonuna tıkla. 

Beklenen Sonuç: Kullanıcı gönder tuşuna bastığında girilen e-posta adresi geçersiz bir e-posta adresi ise pop- up şeklinde açılan “Girdiğiniz e-posta geçersizdir.” mesajı ile karşılaşacaktır.

 

![image](https://github.com/esraucinar/Tobeto-platform-test-project/assets/148894125/05da7894-f713-4a37-8eb7-e4700f1b6c9b)

