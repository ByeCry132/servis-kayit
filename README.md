  Servis Kayıt

Oto servisler için basit araç kayıt sistemi. Telefondan veya bilgisayardan tarayıcıyla çalışır, kurulum gerektirmez.

  Ne yapar?
Kullanıcı adı ve şifre ile giriş
Araç kaydı ekleme: elle veya plaka fotoğrafı ile
Plaka okuma (Türkiye plaka biçimine göre düzeltme yapar)
Marka, model ve jenerasyon seçimi (Opel, Chevrolet, Peugeot, Citroën, DS)
Plaka veya nota göre kayıt arama, CSV olarak indirme
Yönetici paneli: kullanıcı ekleme/silme, araç ekleme/silme
Kayıtlar ortak veritabanında durur, tüm çalışanlar aynı kayıtları görür

  Nasıl çalışır?

Tek dosyalık bir web sayfasıdır (index.html). Veriler Supabase üzerinde saklanır. Giriş ve yetki kontrolü sunucu tarafında yapılır, sayfanın kodunda şifre bulunmaz.

  Kurulum
Supabase'de ücretsiz bir proje aç ve gerekli tabloları/fonksiyonları SQL Editor'den çalıştır.
index.html içindeki SB satırına Supabase proje adresini ve herkese açık (anon/publishable) anahtarı yaz.
Dosyayı GitHub Pages veya Netlify ile yayınla.

Gizli (service_role / secret) anahtarı asla koda yazma veya depoya yükleme.

  Kullanım
Adresi telefonda aç, kullanıcı adı ve şifre ile giriş yap.
Elle gir veya Fotoğraf çek seç.
Plakayı kontrol et, marka, model ve jenerasyonu seç, isteğe bağlı not yaz, Kaydet'e bas.
Kayıtlı araçlar bölümünden geçmiş kayıtlara bak.
Plaka okuma için ipuçları
Plakayı çerçevenin içine tam sığdır, karşıdan çek.
Yansıma ve gölge olmasın.
Okunan plakayı kaydetmeden önce kontrol et.
  
  Teknik not

Plaka okuma Tesseract.js ile tarayıcıda yapılır ve ilk kullanımda internet gerektirir.
