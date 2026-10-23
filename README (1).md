# FinTrack - Kişisel Finans Yönetim ve Analiz Sistemi

Python dersi için 2 kişilik grup olarak geliştirdiğimiz bir kişisel finans takip uygulaması. Kullanıcılar gelirlerini ve giderlerini kaydedip kategorilere ayırabiliyor, bütçe limiti belirleyebiliyor ve harcamalarını grafiklerle takip edebiliyor.

## Özellikler

- Kullanıcı kayıt ve giriş sistemi (şifreler hash'lenerek saklanır)
- Gelir ve gider ekleme, silme, güncelleme
- Harcamaları kategorilere ayırma
- Aylık ve yıllık harcama raporları
- Gelir-gider grafikleri
- Bütçe limiti belirleme ve limit aşılınca uyarı verme
- En çok harcama yapılan kategoriyi belirleme
- Geçmiş işlemleri filtreleme
- Raporları Excel veya PDF olarak dışa aktarma

## Kullanılan Teknolojiler

| Teknoloji | Ne için kullanıyoruz |
|---|---|
| Python | Ana dil |
| CustomTkinter | Arayüz |
| SQLite3 | Veritabanı |
| pandas | Veri gruplama ve filtreleme |
| matplotlib | Grafikler |
| openpyxl | Excel çıktısı |
| reportlab | PDF çıktısı |
| hashlib | Şifre hash'leme |


## Proje Yapısı

> Proje ilerledikçe burası güncellenecek.

```
fintrack-kisisel-finans/
├── main.py
├── database.py
├── requirements.txt
└── README.md
```

## Ekip

- Ayşe Ak
- Ezgi Hanife Erzurum

## Yapılacaklar

- [ ] Veritabanı tablolarını oluşturmak
- [ ] Kayıt ve giriş ekranı
- [ ] Gelir/gider ekleme, silme, güncelleme
- [ ] Kategori ve bütçe limiti sistemi
- [ ] Raporlar ve grafikler
- [ ] Excel ve PDF dışa aktarma
- [ ] Test ve son düzenlemeler

## Ders Bilgisi

Bu proje Python dersi dönem projesi olarak hazırlanmaktadır.
