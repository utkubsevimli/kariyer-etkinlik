# Kampüs Etkinlikleri - Sprint 6 ve Vize Teslimi
## 1. Canlı Yayın (Vercel)
**Canlı Adres:** [https://utkuburaksevimli-frontend.vercel.app](https://utkuburaksevimli-frontend.vercel.app/)

## 2. Kurulum ve Çalıştırma

Projeyi yerel ortamda çalıştırmak için aşağıdaki adımları izleyin:

# Bağımlılıkları yükleyin
npm install

# Geliştirme sunucusunu başlatın
npm run dev

Route Listesi
Uygulamada yer alan tüm rotalar ve açıklamaları:

/ : Ana Sayfa (Öne çıkan ve yaklaşan etkinlikler)

/events : Tüm Etkinlikler (Kategori filtreleme ve dinamik arama)

/events/:id : Etkinlik Detay Sayfası

/admin : Yönetim Paneli (Etkinlik listesi, silme ve düzenleme yönlendirmesi)

/admin/new : Yeni Etkinlik Ekleme Formu

/admin/:id/edit : Etkinlik Düzenleme Formu

/login : Giriş Sayfası (Form doğrulama ile)

/register : Kayıt Ol Sayfası (Şifre eşleşme kontrolü ile)

/forgot-password : Şifre Sıfırlama Sayfası

* : 404 Sayfa Bulunamadı (Geçersiz URL yakalayıcı)
