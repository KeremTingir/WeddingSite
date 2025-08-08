# 💒 Beyza & Sercan - Düğün Fotoğraf Paylaşım Sitesi

Romantik ve şık bir düğün fotoğraf paylaşım web sitesi. Misafirler düğün fotoğraflarını kolayca Google Drive'a yükleyebilir.

## ✨ Özellikler

- 🎨 **Romantik Tasarım**: Beyza & Sercan'a özel düğün teması
- 🌸 **Yumuşak Gradient**: Pembe, altın sarısı, beyaz tonlarında geçişli arka plan
- ✨ **Animasyonlu Partiküller**: Altın toz efektleri ve yumuşak hareket eden kalpler
- 📱 **Mobil Uyumlu**: Telefon ve tabletlerde mükemmel çalışır
- 🎯 **Tek Tıkla Erişim**: Google Drive'a direkt yönlendirme
- 💝 **Great Vibes Fontu**: Romantik başlık yazı tipi

## 🚀 Hızlı Başlangıç

### 1. Google Drive Klasörü Hazırlayın
1. Google Drive'da yeni bir klasör oluşturun
2. Klasörü herkese açık hale getirin:
   - Klasöre sağ tıklayın
   - "Share" seçin
   - "Anyone with the link" seçin
   - "Editor" izni verin
   - "Done" tıklayın

### 2. Drive Linkini Güncelleyin
`index.html` dosyasında şu satırı bulun ve kendi Drive linkinizi yazın:
```javascript
const GOOGLE_DRIVE_LINK = 'https://drive.google.com/drive/folders/YOUR_FOLDER_ID_HERE';
```

### 3. Deploy Edin
```bash
# Vercel CLI ile
vercel --prod

# Veya GitHub'a push edip Vercel'de import edin
```

## 🎨 Tasarım Özellikleri

### Renk Paleti
- **Pembe Tonları**: #FFB6C1, #FFE4E1
- **Altın Tonları**: #FFD700, #FFF8DC
- **Kahverengi Metin**: #8B4513 (romantik ve okunaklı)

### Animasyonlar
- **Partikül Efektleri**: 10 adet altın parçacık yukarı süzülüyor
- **Kalp Dekorasyonları**: 4 adet kalp emoji yumuşak hareket ediyor
- **Gradient Shift**: Arka plan renkleri 15 saniyede bir değişiyor
- **Fade-in Animasyonları**: Başlık, buton ve metin yumuşak beliriyor

### Fontlar
- **Great Vibes**: Romantik başlık yazı tipi
- **Poppins**: Modern ve okunaklı metin

## 📱 Kullanım

1. **Site Açılır**: Güzel düğün teması ve animasyonlar
2. **Butona Tıklanır**: "📸 Fotoğraf Yükle" butonuna tıklayın
3. **Google Drive Açılır**: Yeni sekmede Drive klasörü açılır
4. **Fotoğraf Yüklenir**: Misafirler fotoğraflarını manuel olarak yükler

## 🔧 Teknik Detaylar

### Teknolojiler
- **HTML5**: Semantic markup
- **CSS3**: Modern styling ve animasyonlar
- **Vanilla JavaScript**: Hafif ve hızlı
- **Vercel**: Hosting platform

### Güvenlik
- HTTPS zorunlu
- XSS koruması
- Clickjacking koruması
- MIME type sniffing koruması

## 📁 Proje Yapısı

```
WeddingSite/
├── index.html          # Ana sayfa
├── vercel.json         # Vercel konfigürasyonu
├── .gitignore          # Git ignore dosyası
└── README.md           # Bu dosya
```

## 🚀 Deploy

### Vercel (Önerilen)
1. GitHub'a push edin
2. Vercel'de projeyi import edin
3. Otomatik deploy

### Manuel Deploy
```bash
vercel --prod
```

## 🔧 Özelleştirme

### Google Drive Linkini Değiştirme
```javascript
// index.html dosyasında bu satırı bulun
const GOOGLE_DRIVE_LINK = 'https://drive.google.com/drive/folders/YOUR_FOLDER_ID_HERE';
```

### Renkleri Değiştirme
```css
/* Ana gradient renkleri */
background: linear-gradient(135deg, 
    #FFE4E1 0%,    /* Pembe */
    #FFF8DC 25%,   /* Krem */
    #FFD700 50%,   /* Altın */
    #FFB6C1 75%,   /* Pembe */
    #FFF8DC 100%   /* Krem */
);
```

### Animasyon Hızını Değiştirme
```css
/* Partikül animasyon süresi */
animation: float 6s ease-in-out infinite;

/* Gradient değişim süresi */
animation: gradientShift 15s ease infinite;
```

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 🙏 Teşekkürler

- [Google Fonts](https://fonts.google.com/) - Great Vibes ve Poppins fontları
- [Vercel](https://vercel.com/) - Hosting platform
- [Google Drive](https://drive.google.com/) - File storage

---

**💝 Beyza & Sercan'ın düğününde güzel anılar biriktirmeniz dileğiyle! 💝**

---

*Bu proje düğün fotoğraf paylaşımı için özel olarak tasarlanmıştır. Romantik ve kullanıcı dostu bir deneyim sunar.*
