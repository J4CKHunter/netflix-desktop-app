## netflix desktop application with java

Projede gerçekleştirilmesi istenenleri [dökümantasyon dosyasında](https://github.com/J4CKHunter/netflix-desktop-app/blob/master/BLM210%20PRO%20LAB_II_3.proje.docx.pdf) bulabilirsiniz.

Projede gerçekleştirilen isterler ile ilgili detaylı açıklamalar [proje raporunun](https://github.com/J4CKHunter/netflix-desktop-app/blob/master/Rapor.pdf) içerisindedir.

UYARILAR:

* Eğer daha önce kimse herhangi bir programa oy vermediyse, kullanıcı kayıt olurken herhangi bir tavsiye çıkmaz.

* Sadece programı izleme butonuna bastıysanız oy verme kısmı açılır yani programı izlemeden oy veremezsiniz ve her izlemenizde tekrar oy verebilirsiniz, verdiğiniz oylar veritabanında güncellenir.
 
* Kaldığınız yerden devam edebilmek için açtığınız program film ise direkt filmi başlatmanız yeterlidir, film değilse önceki kaldığınız bölümün bilgisini arayüzden görüp ilgili bölümü seçip başlatmanız yeterlidir. Eğer kaldığınız bölümü seçmezseniz seçtiğiniz bölüme baştan başlayacaksınız ve databasedeki kaldığınız bölüm ve süre ona göre  güncellenecektir.  

* Veritabanında sadece önceden kaydedilmiş 2 kullanıcı vardır. Kullanıcıprogramtablosu ise tamamen boştur.

* Bir programı izleyip durdurduktan sonra son kaldığınız bölüm yazısı belirmez.'Bölüm numarası'ndan izleyeceğiniz veya izlediğiniz bölüm numarasını takip edebilirsiniz. Eğer başka bir programı seçip daha sonra tekrar eski programa gelirseniz en son kaldığınız bölüm yazısı ekrana gelicektir.

* Aksiyon ve Macera kategorisi kısa tutmak için Aksiyon olarak kısaltılmıştır.

### NASIL ÇALIŞIR?

1. Cmd üzerinden proje dosyasının bulunduğu yere geliniz

2. java -jar Prolab23.jar yazarak projeyi çalıştırınız.

- (Alternatif olarak proje klasörünün direkt içinde yer alan Prolab23.jar Jar dosyasını çift tıklayarak açmaya çalışabilirsiniz.)

3. Açılan uygulama ekranında 2 seçeneğiniz vardır. Kaydol butonuna basıp Kayıt olmak yada Bulunduğunuz Ekranda Eğer önceden açtığınız bir hesabınız varsa o hesabın bilgilerini girerek giriş yapabilirsiniz.
4. Eğer Kayıt ekranını açarsanız; Öncelikle Bütün bilgilerinizi dikkatli bir şekilde giriniz,ardından ise En sevdiğiniz 3 türü seçiniz. 
Kayıt ol butonuna bastığınızda Size seçtiğiniz her türden en fazla Puan alan 2 program tavsiye edilecektir.
Kayıt olurken girdiğiniz bilgilerin yapısında bir hata varsa veya doldurulması zorunlu alanları doldurmadıysanız hata mesajıyla karşılacaksınız ve kaydınız eklenmeyecektir.

5. Uygulamaya giriş yaptıktan sonra Sol taraftaki programlardan istediğinizi seçebilirsiniz, hatta sol üstteki kısımdan tercihinize göre isim veya tür olarak,arayacağınız program
veya türün yazılışına dikkat ederek (The Witcher != the witcher) arama yapabilirisiniz.

6. Bir programı seçtikten sonra eğer Dizi veya Reality program ise ilk önce izleyeceğiniz bölümü seçerek sonra açılan izle butonuna basarak izleyebilirsiniz.
Eğer açtığınız program film ise direkt olarak izle butonuna basabilirsiniz.

7. İzle tuşuna bastıktan sonra Puan kısmı ve duraklat kısmı açılacaktır. Eğer puan vermek isterseniz, istediğiniz puanı seçerek verebilirsiniz.
Başka bir program izlemek istiyorsanız durdur butonuna basmanız yeterli olacaktır.

8. Eğer bir programı tekrar açarsanız Kaldığınız bölümü seçerek kaldığınız yerden devam edebilirsiniz.
