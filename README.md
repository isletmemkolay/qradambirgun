# adambirgün · QR Studio

Minimal, ücretsiz ve tam özellikli QR kod üreticisi. Antalya merkezli web geliştirici **adambirgun** tarafından yapılmıştır.

## 🚀 Canlı Demo

GitHub Pages üzerinden yayınlamak için:
1. Repoyu fork veya clone et
2. `qr-studio.html` → `index.html` olarak yeniden adlandır
3. GitHub Pages'ı `main` branch / `root` olarak ayarla

## ✨ Özellikler

- **8 QR türü**: URL, Text, Wi-Fi, Email, Telefon, SMS, vCard, Geo
- **Statik & Dinamik mod**
- **4 modül stili**: Soft, Sharp, Dots, Classy
- **Tam renk kontrolü**: QR, Fon, Köşe, Köşe-iç renkleri ayrı ayrı
- **6 renk paleti preseti** — tek tıkla tema değiştir
- **QR merkez logosu** yükleme + boyut kontrolü
- **Site / marka logosu** yükleme (sayfada floating header olarak görünür)
- **Transparan arka planlı PNG** indirme (mockup & ürün görseli için)
- **PNG + SVG** export
- **Slider tabanlı boyut kontrolü** (180px – 900px)
- **Kenar boşluğu kontrolü**
- **Mobil uyumlu** responsive tasarım (375px+)
- **SEO & Geo meta etiketleri** (Antalya / TR)

## 📁 Dosya Yapısı

```
adambirgun-qr-studio/
├── index.html          ← Ana uygulama (qr-studio.html'i yeniden adlandır)
├── README.md
├── LICENSE
└── assets/
    └── og-preview.png  ← (isteğe bağlı) Open Graph görseli
```

## 🛠 Kurulum

Herhangi bir build aracı gerekmez. Tamamen statik HTML.

```bash
git clone https://github.com/adambirgun/qr-studio.git
cd qr-studio
# index.html'i tarayıcıda aç
```

## 🎨 Özelleştirme

`index.html` içinde şu değerleri değiştir:

| Değer | Satır | Açıklama |
|---|---|---|
| `isletmemkolay@gmil.com` | ~footer | İletişim e-postası |
| `36.8969 / 30.7133` | meta + geo default | Varsayılan konum |
| `https://example.com` | url default | Varsayılan URL |
| `adambirgün · QR Studio` | `<title>` | Site başlığı |
| `--fg:#0e0e0e` | CSS :root | Ana renk (dark mode için de güncelle) |
| `--bg:#f9f8f6` | CSS :root | Arka plan rengi |

## 📦 Kullanılan Kütüphaneler

- [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) v1.9.2 — QR üretimi (MIT)
- [DM Sans + DM Mono](https://fonts.google.com) — Google Fonts (OFL)

## 📄 Lisans

MIT © adambirgun
