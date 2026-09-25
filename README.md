# Savaş Türkoğlu — CV

Senior Full-Stack & AI Automation Engineer · Antalya, Türkiye

Kişisel özgeçmişimin kaynak deposu: tek sayfalık statik HTML sürüm + orijinal PDF.

## İçerik

| Dosya | Açıklama |
|---|---|
| `index.html` | Tek sayfalık HTML özgeçmiş (build adımı yok) |
| `assets/styles.css` | Tüm stiller — açık/koyu tema + yazdırma stilleri |
| `assets/savas-turkoglu-cv.pdf` | Orijinal PDF sürüm |
| `assets/savas-turkoglu-2026.jpg` | Portre görsel |

## Çalıştırma

Bağımlılık yok, derleme yok. Dosyayı doğrudan açmak yeterli:

```bash
open index.html
```

Yerel sunucu tercih edilirse:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Notlar

- Tipografi Google Fonts üzerinden yükleniyor (Instrument Serif, IBM Plex Sans/Mono).
- `prefers-color-scheme` ile açık ve koyu tema desteği var.
- `@media print` kuralları sayesinde tarayıcıdan doğrudan PDF olarak yazdırılabilir.
- `prefers-reduced-motion` desteklenir.

## İletişim

- E-posta: savasturkoglu.dev@gmail.com
- Web: [savasturkoglu.com](https://savasturkoglu.com)
- LinkedIn: [/in/savas-dev](https://linkedin.com/in/savas-dev)

## Yayın

Canlı sürüm: **https://savasturkoglu1.github.io/resume/**

GitHub Pages, `main` dalının kökünden yayınlanır. `main`'e yapılan her push
otomatik olarak siteye yansır.
