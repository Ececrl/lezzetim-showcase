# 🍽️ Lezzetim

**Damak zevkine göre restoran öneren yapay zekâ destekli web uygulaması.**

> 🚧 Proje geliştirme aşamasında. Kaynak kodu özel (private) bir repoda tutuluyor; bu repo projenin tanıtım sayfasıdır.

## Ne yapıyor?

Lezzetim, kullanıcının yemek tercihlerinden ayrıntılı bir "damak zevki profili" çıkarır ve restoran önerilerini bu profile göre kişiselleştirir.

- **6 adımlı damak zevki onboarding'i:** mutfak türleri (fotoğraflı seçim), et/sebze tercihleri, acı seviyesi, bütçe, ortam tercihi, diyet kısıtları ve serbest notlar
- **Şef AI asistanı:** sohbet ederek restoran önerisi alınır. Asistan yalnızca Google Places'ten gelen **gerçek** restoranları önerir (iki aşamalı akış: önce arama terimi çıkarılır, sonra sadece gerçek sonuçlar arasından öneri yapılır)
- **Konum desteği:** öneriler kullanıcının bulunduğu yere göre yapılır
- **Profil sayfası:** tercihler emojili kartlar halinde gösterilir
- **Güvenli kullanıcı verisi:** Supabase Auth ve satır düzeyinde güvenlik (RLS) politikaları

## Teknolojiler

| Katman | Teknoloji |
|---|---|
| Ön yüz | Next.js, React, Tailwind CSS |
| Veritabanı & kimlik doğrulama | Supabase |
| Yapay zekâ | Groq (Llama) |
| Mekân verisi | Google Places API |

## Ekran görüntüleri

_Yakında eklenecek._

---

👩‍💻 Geliştiren: [@Ececrl](https://github.com/Ececrl)
