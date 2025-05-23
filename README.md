# README
ECZANE YÖNETİM SİSTEMİ – PROJE ÇALIŞTIRMA TALİMATLARI

Bu uygulama Java dili ile geliştirilmiştir. Kullanıcı arayüzü JavaFX kullanılarak yapılmıştır. Veritabanı işlemleri için SQLite tercih edilmiştir.

GEREKENLER:
- Java JDK 17 veya üzeri (biz JDK 24 kullandık)
- JavaFX SDK 24.0.1
- Eclipse IDE
- sqlite-jdbc kütüphanesi

KURULUM ADIMLARI:

1. Eysis.zip dosyasını çıkarın.
2. Eclipse'te yeni bir Java projesi oluşturun.
3. ZIP içindeki .java dosyalarını src klasörüne aktarın.
4. application.css ve eczane.db dosyalarını proje klasörüne koyun.
5. JavaFX kütüphanelerini module path olarak ekleyin.
6. sqlite-jdbc.jar dosyasını classpath olarak ekleyin.

VM ARGÜMANLARI:

Aşağıdaki satırı Run Configurations → VM arguments kısmına yapıştırın:

--module-path "C:\javafx-sdk-24.0.1\lib" --add-modules javafx.controls,javafx.fxml --enable-native-access=ALL-UNNAMED

Veritabanı Yolu:
Veritabani.java dosyasında veritabanı yolu şu şekilde ayarlanmıştır:

C:/Users/İsmail PC/Desktop/eczane.db

Bu dosya masaüstünde bulunmalıdır. Yoksa uygulama ilk açıldığında otomatik oluşturulur.

ÇALIŞTIRMA:

Main.java dosyasına sağ tıklayıp "Run As → Java Application" seçildiğinde uygulama açılır.

Özellikler:

- Veritabani.java → Veritabanına bağlanır
- DatabaseInitializer.java → Tabloları oluşturur
- IlacIslemleri.java → İlaç işlemlerini yapar
- MusteriIslemleri.java → Müşteri işlemlerini yapar
- SatisIslemleri.java → Satış kaydeder
- Main.java → Uygulamayı başlatır
- AnaMenu.java → Ana ekranı açar

Hazırlayanlar: (Adınızı buraya yazabilirsiniz)
