# ArtBook - Android Art Gallery App

Bu proje, Android platformu için geliştirilmiş bir sanat galerisi uygulamasıdır. Kullanıcılar sanat eserlerini kaydedebilir, görüntüleyebilir ve yönetebilir.

## Özellikler

- 📱 Modern Android UI/UX tasarımı
- 🖼️ Galeriden resim seçme ve kaydetme
- 💾 SQLite veritabanı ile yerel depolama
- 📋 RecyclerView ile sanat eseri listesi
- 🔍 Sanat eseri detaylarını görüntüleme
- 📝 Sanat eseri bilgilerini düzenleme (isim, sanatçı, yıl)
- 🎨 Resim boyutlandırma ve optimizasyon

## Teknolojiler

- **Platform:** Android
- **Dil:** Java
- **Minimum SDK:** 28 (Android 9.0)
- **Target SDK:** 34 (Android 14)
- **Veritabanı:** SQLite
- **UI Framework:** AndroidX, Material Design
- **Build System:** Gradle

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/furblood0/ArtBook.git
```

2. Android Studio'yu açın ve projeyi import edin

3. Gradle sync işlemini tamamlayın

4. Uygulamayı bir Android cihazda veya emülatörde çalıştırın

## Kullanım

### Sanat Eseri Ekleme
1. Ana ekranda sağ üst köşedeki "+" butonuna tıklayın
2. Sanat eseri adını, sanatçı adını ve yılını girin
3. "Select Image" butonuna tıklayarak galeriden resim seçin
4. "Save" butonuna tıklayarak kaydedin

### Sanat Eseri Görüntüleme
1. Ana ekrandaki listeden bir sanat eserine tıklayın
2. Detay sayfasında tüm bilgileri ve resmi görüntüleyin

## İzinler

Uygulama aşağıdaki izinleri gerektirir:
- `READ_EXTERNAL_STORAGE` (Android 12 ve altı)
- `READ_MEDIA_IMAGES` (Android 13 ve üstü)

## Proje Yapısı

```
app/src/main/java/com/furkan/artbook/
├── MainActivity.java          # Ana aktivite
├── ArtActivity.java           # Sanat eseri detay/ekleme aktivitesi
├── Art.java                   # Sanat eseri model sınıfı
└── ArtAdapter.java            # RecyclerView adapter

app/src/main/res/
├── layout/                    # UI layout dosyaları
├── values/                    # String, color, theme tanımları
└── drawable/                  # Resim ve drawable kaynakları
```

## Katkıda Bulunma

1. Bu repository'yi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakın.

## İletişim

Proje Linki: [https://github.com/furblood0/ArtBook](https://github.com/furblood0/ArtBook) 