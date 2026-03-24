# 🚆 Başkentray PWA — Kurulum Rehberi

## Dosyalar
```
baskentray-pwa/
├── index.html      ← Ana uygulama
├── manifest.json   ← PWA ayarları
├── sw.js           ← Çevrimdışı destek
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## 🌐 Adım 1: Netlify'a Yükle (Ücretsiz)

1. **https://netlify.com** adresine git
2. Sağ üstten **"Sign up"** → Google ile giriş yap
3. Ana sayfada **"Add new site"** → **"Deploy manually"** tıkla
4. Bu klasörü (`baskentray-pwa`) sürükle-bırak yap
5. 30 saniye bekle → sana bir link verecek:
   `https://baskentray-xxxxx.netlify.app`

### Özel domain (opsiyonel)
- Netlify'da **"Domain settings"** → **"Add custom domain"**
- `baskentray.netlify.app` gibi ücretsiz subdomain alabilirsin

---

## 📱 Adım 2: Telefona Yükle

### Android (Chrome):
1. Chrome ile linki aç
2. Sağ üst **⋮** menü → **"Ana ekrana ekle"**
3. Uygulamanın adını gir → **"Ekle"**
4. Artık ikon olarak görünür! 🎉

### iPhone (Safari):
1. Safari ile linki aç (Chrome değil!)
2. Alt ortadaki **paylaş** butonuna bas (□↑)
3. **"Ana Ekrana Ekle"** seç
4. **"Ekle"** bas

---

## ✅ Özellikler
- ✅ İnternetsiz çalışır (çevrimdışı mod)
- ✅ Gerçek TCDD tarifesi (Sincan ↔ Kayaş)
- ✅ Hafta içi / hafta sonu ayrımı
- ✅ Favori duraklar (kaydedilir)
- ✅ Yaklaşan tren bildirimi
- ✅ Canlı saat & geri sayım

---

## 🔄 Güncelleme
Tarifeyi değiştirmek istersen `index.html` içindeki
`TRAINS_D0` ve `TRAINS_D1` dizilerini düzenle.

---

*Resmi TCDD tarifesi baz alınmıştır. Bağımsız uygulama.*
