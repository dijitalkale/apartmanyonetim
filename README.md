# Kotlin ile yapılmış aynısını flutter ile yapabiliriz
# apartmanyonetim
Apartman Yönetim Sistemi
# Manager
* Apartman yöneticelerinin apartman yönetimini kolaylaştırmak ve apartman sakinlerinin yönetimin yaptıklarından daha rahat haberdar olabilmesi için geliştirilmiştir.
  (Geliştirme aşamasında)
* Veritabanı olarak Firebase Firestore ve Storage kullanılmıştır

* <a href="https://www.notion.so/leventsrr/Manager-Geli-tirme-Hedefleri-fca2d25c08694bff9733919d8148a56f?pvs=4" target="_blank">Geliştirme Plan Ve Takibi</a>

* <a href="https://www.notion.so/leventsrr/Yeni-Kazan-mlar-Sorunlar-ve-z-mleri-6ff1d94959ae4ad4aea356075f4a2bc5?pvs=4" target="_blank">Hata Çözümleri ve Yeni Öğrenilenler</a>

## Kullanılan Teknolojiler
<p align="center"> 
  <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> 
  <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> 
</a>
   <a href="https://developer.android.com/" target="_blank" rel="noreferrer"> 
  <img src="https://www.vectorlogo.zone/logos/android/android-official.svg" alt="android" width="40" height="40"/> 
</a>
<a href="https://firebase.google.com/" target="_blank" rel="noreferrer">
  <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> 
</a> 
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> 
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> 
</a> 
</p>

## Kullanılan Yapılar
 <table  align="center" style="margin: 0px auto; text-align:center;">

  <tr>
    <td>MVVM</td>
    <td>Retrofit</td>
    <td>Okhttp</td>
    <td>Glide</td>
  </tr>
  <tr>
    <td>LiveData</td>
    <td>Flow</td>
    <td>Navigation</td>
    <td>Dagger Hilt</td>
  </tr>
  <tr>
    <td>Shared Preferences</td>
    <td>Coroutines</td>
    <td>Data Binding</td>
    <td></td>
  </tr>
</table> 

## Ekranlar Ve İşlevleri

### Karşılama Ekranı

* Daha önce giriş yapıldıysa doğrudan anasayfaya, yapılmadıysa giriş ekranına yönlendirme yapılır.


<p align="center">
  <img src="https://user-images.githubusercontent.com/63983517/233830601-d274a577-3d77-4624-bff6-547d64371841.png" style="width:250px"/>
</p>

### Giriş ve Kayıt Ekranı

* Kullanıcının hesabı varsa giriş ekranında gerekli bilgiler ile hesabına giriş yapar
* Daha önce kayıtlı olmayan kullanıcı eğer yönetici ise apartmanına ait isim belirler ve rol seçimini Yönetici yaparak kayıt olduğunda hem kendisi hem de apartmanı için yeni hesap açmış olur.
* Açılmış olan apartmana kayıt olmak için diğer kullanıcıların Apartman Sakini ya da Kapıcı rolüyle üye olmalı


<p align="center">
   <img src="https://user-images.githubusercontent.com/63983517/233830622-503d734e-caa8-4874-8190-5675f05e97f6.png" style="width:250px"/>
   <img src="https://user-images.githubusercontent.com/63983517/233830624-541027f2-8384-4e42-b387-a5f3604ea704.png" style="width:250px"/>
 </p>

### Anasayfa

* Anasayfada apartman hesabının genel bilgileri yer almaktadır.Kullanıcılar burada yönetici duyurularına,kapıcı duyurularına,apartman sakini isteklerine ve anketlere ulaşabilir.
* Anketler sayfasında dileyen kullanıcı anket sonucunu pdf olarak kaydedip telefonunda saklayabilir.

https://user-images.githubusercontent.com/63983517/233830631-10a0434e-7a07-4516-9317-89c7b9b51a42.mp4

* Kullanıcılar dilerse anket sonuçlarını telefonlarına PDF dosyası olarak kaydedebilir.

https://user-images.githubusercontent.com/63983517/233830637-13e7800f-1a08-49d8-91b1-16da192b23f9.mp4

### Kullanıcı Profil Sayfası

<b>1- Yönetici Profili</b>

* Yöneticiler profil sayfasından Kapıcı görevi,gelir gider ,duyuru,anket paylaşımı yapabilir.Aidat ücretini güncelleyebilir ve mevcut verileri silebilir.

https://user-images.githubusercontent.com/63983517/233830653-72ca4554-5f93-4cfc-b4cf-3aa0fc1e47a8.mp4

<b> 2-Apartman Sakin Profili</b>

* Normal kullanıcılar istek paylaşabilir ve kapıcıya görev verebilir.Aidat ödemesi yaptıklarını belirtebilirler.

<p align="center">
  <img src="https://user-images.githubusercontent.com/63983517/233830665-7ff2a311-c642-45c2-9cdc-4da834727d7a.png" style="width:250px"/>
</p>

<b>3- Kapıcı Profili </b>

* Kapıcı rolüne sahip kullanıcı bu ekrandan yeni duyuru paylaşabilir.

<p align="center">
  <img src="https://user-images.githubusercontent.com/63983517/233830674-2437e957-d5d5-46de-a019-fc3a05501610.png" style="width:250px"/>
</p>

* Aidat Ödeme

https://user-images.githubusercontent.com/63983517/233830692-c23f22e8-e3bd-4d0a-abce-07f7111f9ab7.mp4

### Kapıcı Sayfası

<b>1- Kapıcı rolüne sahip kullanıcı için kapıcı sayfası</b>

* Kapıcılar bu ekranda mevcut görevleri yapıldı olarak işaretleyebilir

https://user-images.githubusercontent.com/63983517/233830708-89f299da-3c5e-4113-8223-43ca296a37d2.mp4

<b>2- Diğer Kullanıcılar İçin Kapıcı Sayfası</b>


* Diğer kullanıcılar kapıcının yaptığı ve yapacağı görevleri inceleyebilir

<p align="center">
  <img src="https://user-images.githubusercontent.com/63983517/233830727-597c0b57-9718-439a-8c3c-5b9d00963bbb.png" style="width:250px"/>
</p>

### Apartman Sakinleri Ve Sakin Detay Sayfası

* Bu ekranda apartmanda bulunan kullanıcılar listelenir ve plaka,isim ya da telefon numarasına göre kullanıcılar filtrelenebilir.
* Sohbet ekranına geçiş yapılabilir
* Kullanıcı detay sayfasında kullacının detayları incelenebilir ve kayıtlı numara varsa arama yapılabilir

https://user-images.githubusercontent.com/63983517/233830737-465eda6d-072b-4752-a1b0-41f38d53c44e.mp4

### Sohbet Ekranı

* Bu ekranda apartmana kayıtlı kullanıcılar canlı olarak sohbet edebilir.
  * (Görsel hata mevcut düzeltme yapılacak)

<p align="center">
  <img src="https://user-images.githubusercontent.com/63983517/233830750-fac602f0-44bc-48a8-a8a8-1235372e994e.png" style="width:250px"/>
</p>

### Cüzdan Sayfası

* Bu ekranda kapıcının giriş yaptığı gelir ve giderler ve apartmanın sahip olduğu bütçe gözlemlenebilir
* Sakinlerin aidat ödeme durumu incelenebilir
* Dileyen kullanıcı gelir ve giderleri excel dosyası olarak telefonuna kaydedebilir

https://user-images.githubusercontent.com/63983517/233830753-f61d6345-579a-4075-a572-337d1947f2df.mp4


* Gelir Gider Durumunu Excel Dosyasına Dönüştürme

https://user-images.githubusercontent.com/63983517/233832998-a284d9a4-36f9-41b9-b3ce-e130762537de.mp4

* Veritabanı

https://user-images.githubusercontent.com/63983517/233834873-68bbcde3-6d0f-4da2-a43b-64a4aa23f32c.mp4








