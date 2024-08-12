Bu proje, dijital ürün satışı yapan bir platform geliştirmek amacıyla oluşturulmuştur. Kullanıcılar, platform üzerinden dijital ürünler satın alabilir, puan kazanabilir ve kupon kullanabilirler. Proje, hem mobil (Android, iOS) hem de web platformlarına hizmet verecek bir API içerir. 
Özellikler
Kullanıcı Kayıt ve Giriş:
Kullanıcılar, platforma kayıt olabilir ve giriş yapabilir.
JWT tabanlı kimlik doğrulama sistemi kullanılmaktadır.
Dijital Ürünler:
Kullanıcılar, çeşitli dijital ürünleri inceleyebilir ve satın alabilir.
Puan Sistemi:
Kullanıcılar, yaptıkları her alışverişten puan kazanır.
Kupon Yönetimi:
Kazanılan veya satın alınan kuponlar, indirimlerde kullanılabilir.
Rol Tabanlı Erişim:
Admin ve kullanıcı rolleri tanımlıdır ve her rolün farklı yetkileri bulunmaktadır.
Swagger Desteği:
API'lerin test edilmesi ve dökümantasyonu için Swagger desteği sunulmaktadır.

Kullanım
Kullanıcı Kayıt:
Kullanıcılar, /Account/Register endpoint'ini kullanarak kayıt olabilir.
Kullanıcı Girişi:
Giriş yapmak için /Account/Login endpoint'ini kullanın.
Başarılı giriş sonrası JWT token alınır.
Ürün Listeleme:
Dijital ürünleri listelemek için /Products endpoint'i kullanılabilir.
Proje Yapısı
Controllers: API isteklerini işleyen denetleyiciler.
Models: Veri modelleri.
Services: İş mantığı ve servis katmanı.
Data: Veritabanı bağlamı ve veri yönetimi.
Views: Razor sayfaları ve Blazor bileşenleri.
Geliştirme Süreci
Kullanıcı Yönetimi: İlk olarak, kullanıcı kayıt ve giriş işlemleri JWT ile güvence altına alındı.
Dijital Ürün İşlemleri: Ürün listeleme, satın alma ve puan sistemi entegre edildi.
Kupon Yönetimi: Kupon oluşturma ve kullanma özellikleri eklendi.
Swagger: API'lerin dökümantasyonu için Swagger yapılandırıldı.
